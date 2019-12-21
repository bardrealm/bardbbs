---
layout: page
title: Web Client
permalink: /webclient/
---


# Web Client

## Press the Connect button below to connect to BardBBS!

<div id="fTelnetContainer_bardbbs_belthesar_com_25080" class="fTelnetContainer"></div>
<script>document.write('<script src="//embed-v2.ftelnet.ca/js/ftelnet-loader.norip.noxfer.js?v=' + (new Date()).getTime() + '"><\/script>');</script>
<script>
    var Options_bardbbs_belthesar_com_25080 = new fTelnetOptions();
    Options_bardbbs_belthesar_com_25080.BareLFtoCRLF = false;
    Options_bardbbs_belthesar_com_25080.BitsPerSecond = 57600;
    Options_bardbbs_belthesar_com_25080.ConnectionType = 'telnet';
    Options_bardbbs_belthesar_com_25080.Emulation = 'ansi-bbs';
    Options_bardbbs_belthesar_com_25080.Enter = '\r';
    Options_bardbbs_belthesar_com_25080.Font = 'CP437';
    Options_bardbbs_belthesar_com_25080.ForceWss = false;
    Options_bardbbs_belthesar_com_25080.Hostname = 'bardbbs.belthesar.com';
    Options_bardbbs_belthesar_com_25080.LocalEcho = false;
    Options_bardbbs_belthesar_com_25080.NegotiateLocalEcho = true;
    Options_bardbbs_belthesar_com_25080.Port = 25080;
    Options_bardbbs_belthesar_com_25080.ScreenColumns = 80;
    Options_bardbbs_belthesar_com_25080.ScreenRows = 25;
    Options_bardbbs_belthesar_com_25080.SendLocation = true;
    var fTelnet_bardbbs_belthesar_com_25080 = new fTelnetClient('fTelnetContainer_bardbbs_belthesar_com_25080', Options_bardbbs_belthesar_com_25080);
</script>
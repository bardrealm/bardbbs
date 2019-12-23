---
title: Web Client
permalink: /webclient/
layout: page
---


# Web Client

## Press the Connect button below to connect to BardBBS!

<div id="fTelnetContainer" class="fTelnetContainer"></div>
<script>document.write('<script src="//embed-v2.ftelnet.ca/js/ftelnet-loader.norip.noxfer.js?v=' + (new Date()).getTime() + '"><\/script>');</script>
<script>
    var Options = new fTelnetOptions();
    Options.BareLFtoCRLF = false;
    Options.BitsPerSecond = 115200;
    Options.ConnectionType = 'telnet';
    Options.Emulation = 'ansi-bbs';
    Options.Enter = '\r';
    Options.Font = 'CP437';
    Options.ForceWss = false;
    Options.Hostname = 'bardbbs.belthesar.com';
    Options.LocalEcho = false;
    Options.NegotiateLocalEcho = true;
    Options.Port = 25023;
    Options.ProxyHostname = 'proxy-us-ga.ftelnet.ca';
    Options.ProxyPort = 80;
    Options.ProxyPort = 443;
    Options.ScreenColumns = 80;
    Options.ScreenRows = 25;
    Options.SendLocation = true;
    var fTelnet = new fTelnetClient('fTelnetContainer', Options);
</script>

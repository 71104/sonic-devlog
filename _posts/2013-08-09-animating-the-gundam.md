---
layout: post
title: "Animating the Gundam"
description: "COLLADA esperiments"
category: 
tags: [gundam, webgl, oogl.js, collada, xml, xpath, dom]
---
{% include JB/setup %}

[Giorgio](http://www.giorgiopomettini.eu/) had a rigged and animated Gundam mesh ready to use, so he exported it to COLLADA and I'm trying to load it from JavaScript and feed it to WebGL through [oogl.js](http://oogljs.com/), our WebGL engine.

First of all I would like to really thank XPath: I didn't know it, just learned for the occasion in a couple of hours. Fucking cool way to query XML and general DOM data, but it needs some work to simplify some tasks. I don't care about the namespace resolving crap, I just remove the `xmlns` attribute from the COLLADA files Giorgio sends me and set the XPath namespace resolver to `null`.

![XPath](/images/xpath.gif)

That Gundam mesh wouldn't have made it to my browser if it weren't for XPath, although it was only the subsequent day when I found out that I can also use CSS selectors on generic DOM nodes, not only HTML elements (the `querySelector/All` APIs are defined by the `Node` interface). Oh well.

What do you think about it?

[http://71104.github.io/sonic/](http://71104.github.io/sonic/) (it might take some seconds to load)

Controls:
- left click and drag to rotate,
- right click and drag to move.

![Gundam](/images/gundam.png)

BTW, looks like even IE users will (someday) be able to play the game:
[http://techcrunch.com/2013/06/26/microsoft-confirms-webgl-support-for-internet-explorer-11/](http://techcrunch.com/2013/06/26/microsoft-confirms-webgl-support-for-internet-explorer-11/)
[http://msdn.microsoft.com/en-us/library/ie/bg182648(v=vs.85).aspx](http://msdn.microsoft.com/en-us/library/ie/bg182648%28v=vs.85%29.aspx)

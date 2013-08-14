---
layout: post
title: "Third Person Sonic the Hedgehog"
description: "sketching"
tags: [sonic, audio, third person, youtube, oogl.js, collada]
---
{% include JB/setup %}

There are obvious, manifest, evident insights suggesting that a Sonic game should be third person, not first: the best thing of such a game is the reknown as well as beloved character, if you remove that the game is nonsensical crap.

Getting a working 3D animated Sonic with his vortex-shaped running legs into a webpage is not a trivial task. We need the following:
- a great 3D artist that believes he can create and animate Sonic the Hedgehog ([check](http://www.giorgiopomettini.eu/)),
- 3D modeling software ([check](http://www.autodesk.com/products/autodesk-maya/)),
- a 3D export format *supporting animations* ([check](https://collada.org/)),
- a WebGL engine ([check](http://oogljs.com/)),
- COLLADA importing code.

First challenge: we don't have the COLLADA importing code, as the WebGL engine of our choice sucks. Coming up COLLADA importing experiments including animation.

Trailing video featuring the full soundtrack of Sonic the Hedgehog, one of the most beautiful soundtracks ever made. It will also be our main source of audio assets.

<iframe
	width="420"
	height="315"
	src="//www.youtube.com/embed/WklPJsbnDTc"
	frameborder="0"
	allowfullscreen="allowfullscreen">
</iframe>

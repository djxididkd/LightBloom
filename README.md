LightBloom
========
Bloom is an image effect for MikuMikuDance, it can help to hint the relative brightness of objects or add beauty and atmospheric.

Requirements:
-----------
* MikuMikuDance (Only tested on 926 version x64)
* MikuMikuEffect (Only tested on 037 version x64)
* Direct3D 9 With Shader Model 3.0 (ps_3_0)

Install:
-----------
* Download a zip archive from the github page.
* Un-zip the archive.
* Put the the `LightBloom.x` and `LightBloomController.pmx` to the MMD window.
* Drag the `BloomThreshold` to 0.5 in the morph panel

Effect Params:
-----------
* BloomThreshold - Fetch out pixels higher than this level of brightness.
* BloomRadius - Controls the size of veiling effects in percent of the screen width.
* BloomColorAllHSV - Scales the color of the whole bloom effect (linear color-space with HSV color)
* Bloom1st~5st HSV - Modifies the brightness and color of the bloom in the each layer, if you need a larger bloom, use high layer instead

[License (MIT)](https://raw.githubusercontent.com/MikuMikuShaders/LightBloom/master/LICENSE.txt)
-------------------------------------------------------------------------------
	Copyright (C) 2016-2017 Rui. All rights reserved.

	https://github.com/MikuMikuShaders

	Permission is hereby granted, free of charge, to any person obtaining a
	copy of this software and associated documentation files (the "Software"),
	to deal in the Software without restriction, including without limitation
	the rights to use, copy, modify, merge, publish, distribute, sublicense,
	and/or sell copies of the Software, and to permit persons to whom the
	Software is furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included
	in all copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
	OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL
	BRIAN PAUL BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
	AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
	CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
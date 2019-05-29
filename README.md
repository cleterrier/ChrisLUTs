# ChrisLUTs

Due to popular request (well at least [@AbAttacks](https://twitter.com/AbAttacks/status/941068029433180160)), here are the LUTs I've generated for ImageJ. Right now there are three sets of LUTs. You can also check the great [DavLUTs](https://github.com/quokka79/DavLUT) and the [Fiji LUTs repository](https://github.com/fiji/fiji/tree/master/luts).

## 3color
3color are three-color LUTs that are made to be complementary (BMR/RMB vs YGC/CGY have non crossing paths along the RGB cube). I use them for "two-channels rainbow images" when I want to encode two channels with two distinct "half-rainbow" LUTs.

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_3-color.tif)

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_3color_Image.jpg)

## BOP
BOP is a set of 3 complementary LUTs (their overlay is white) that have blue (B), orange (O) and purple (P)  as base colors.

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_BOP.png)

It also looks nice inverted, with a muted RGB result:

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_BOP_rev.png)

## I for Inverted
Inverted LUTs are made to generate black-on-white images aka [#invertedLUTs](https://twitter.com/search?q=%23invertedLUT&src=typd). It allow to directly see the image rather than using "Invert" at the end of the procedure in ImageJ. However, the ImageJ overlay visualization for multi-channel stacks isn't adapted to inverted LUTs, so you won't see the resulting overlay straight away. You should convert the multi-channel stack to a multi-slice RGB stack and then project the channels using "Sum Slices" to get a propet RGB overlay.

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_Inverted.tif)

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_Inverted_Image.png)

## OPF LUTs
OPF LUTs are a set of 3 complementary LUTs (their overlay is white) that have orange (O), purple (P) and "fresh" green (F) as base colors.

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_OPF.tif)

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_OPF_Image.png)

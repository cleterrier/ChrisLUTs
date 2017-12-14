# ChrisLUTs

Due to popular request (well at least [@AbAttacks](https://twitter.com/AbAttacks/status/941068029433180160)), here are the LUTs I've generated for ImageJ.

Right now there are three sets of LUTs:
* 3color are three-color LUTs that are made to be complementary (ie BMR/RMB vs YGC/CGY have non crossing paths along the RGB cube). I use them for "two-channels rainbow images", i.e. encode two channels each with a distinct "half-rainbow" map.

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_3-color.tif)

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_3-color_Image.jpg)


* Inverted LUTs are made to generate black-on-white images aka [#invertedLUTs](https://twitter.com/search?q=%23invertedLUT&src=typd). It allow to directly see the results rather than using "Invert" at the end in ImageJ. However, the overly visualization in ImageJ mutli-channel stacks is not adapted to inverted LUTs so you won't see the resulting overlay straight away for multi-channel images. You should convert the stack to a multi-slice RGB stack and then project the channels usinng "Sum Slices" to get a propet RGB overlay.

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_Inverted.tif)

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_Inverted_Image.png)

* OPF LUTs are a set of 3 complementary LUTs (i.e. their overlay is white) that have orange (O), purple (P) and "fresh" green (F) as base colors.

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_OPF.tif)

![3-color](http://www.neurocytolab.org/up/Github/ChrisLUTs_OPF_Image.png)


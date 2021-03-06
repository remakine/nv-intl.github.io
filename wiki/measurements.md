---
title: Measurements
---

Every night vision tube comes with a set of measurements.

These can be used to determine the quality and how suitable it is for different uses.

## Demo

This demo attempts to convey the effect of different measurements a tube can have.

It is still very much work in progress and should not be seen as any comparison to real world devices.

{% include demo.html %}

## Signal-To-Noise ratio (SNR or S/N)
Unit: unitless

A dimensionless value that is determined by dividing the perceived strength of the intensified image by the perceived noise.
The image below gives a visual representation of a high- and low values of SNR.

{% include image.html image="signal_large.webp" description="Exemplaric signal to noise ratio graph" %}

Low SNR tubes are generally cheaper, but still produce clear results when there is enough light left.

High SNR tubes become expensive quickly, but will produce a clear image even in much darker conditions.

According to Photonis, the SNR is measured using a 0.2 mm spot of light flickering at 10 Hz with a brightness of 108 µlx. [<sup>[1](4.6.11)</sup>][1]

## Resolution
Unit: lp / mm

Determined by the number of light points on the phosphor screen across a line of one millimeter.

The effect is the same as with the resolution of a camera sensor or a smartphone - the higher the resolution the more details can be recognized.


## Figure Of Merit (FOM)
Unit: unitless

The figure of merit is a dimensionless number used to benchmark tubes without requiring to look at different
measurements.

The formula is

```
FOM = SNR x Resolution (lp/mm)
```

The range of FOM currently available to the civilian market is between 0 and 3000.

The price of a tube is often directly proportional to the FOM.

## Gain
Unit: fL/fc, cd/m²/lx

The gain of a tube is typically measured using one of two units.

The most common unit is cd/m²/lx, i.e. candelas per meter squared per lux.

The older convention is Fl/Fc (foot-lamberts per foot-candle).

The gain is measured as a value of output intensity over input intensity.
A gain of 10000 cd/m²/lx is the same as 31415 Fl/Fc. 

## Photocathode Sensitivity
Unit: uA/lm

The photocathode sensitivity determines how many microampere are produced relative to the illumination level measured in lumen.

The higher the sensitivity, the easier incoming photons can dislodge an electron from the photocathode,
resulting in more electrons hitting the phosphor screen for a given illumination level.

Photocathode sensitivity is directly related to the gain of a system.

## Equivalent Background Input (EBI)
Unit: lx

A tube that has no light input still lights up slightly - referred to as background illumination.
It is measured by comparing it to how much light input would be required to achieve an equivalent level of illumination of the tube,
if the tube would not have any background illumination in the first place.

## Modulation transfer function (MTF)
Unit: Function of spatial frequency (lp / mm)

The MTF is the major characteristic how well a tube can reproduce the contrast of an observed scene.[<sup>[2]</sup>][2]
Tubes with a bad MTF will make the observed scene look blurry, even if the tube has high resolution.
A good MTF is usually connected to the perceived "crisp" of the image.


[1]: https://drive.google.com/file/d/1AVyxBbefFo_3oL5uleMdIk21kWuWc272/view?usp=sharing
[2]: https://www.photonis.com/system/files/2019-03/Modulation-Transfer-Function.pdf
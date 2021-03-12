# LUTs-Linear-to-Blender-s-Filmic-sRGB

## Content

Includes LUTs tranform Linear intput into Blender's Filmic sRGB with the following looks:

 - Very Low Contrast.3dl
 - Low Contrast.3dl
 - Medium Low Contrast.3dl
 - Medium Contrast.3dl
 - Medium High Contrast.3dl
 - High Contrast.3dl
 - Very High Contrast.3dl

Each look is in a separated file. If none was selected in Blender, use "Medium Contrast".

The lut files were created using [DuME's OCIO LUT Converter by Rainbox Dev](https://github.com/Rainbox-dev/DuME) with the following settings:
- input color space: Linear
- Output color space: Filmic sRGB
- shader color space or role: <blank>
- Looks: see file names after the number

## Testing

Tests were done using the EXR file `Test_original_Linear.exr` and comparing the LUTed conversions to Blender's own sRGB png version in `Test_original_sRGB.png`:

![test original sRGB](https://github.com/L0Lock/LUTs-Linear-to-Blender-s-Filmic-sRGB/blob/main/Test_original_sRGB.png)

All test files are available here.

To do your own tests:  
Put the `Test_original_Linear.exr` file (you can create your own test file, but keep the same name) and the luts in the same folder as the `lutizer.bat` file, then select and drag'n'drop the luts you want to test on the bat file. It will automatically create test one PNG for each lut you sent.

## Download

 - If interested in creating your own LUTs or testing: Download [the repository as zip](https://github.com/L0Lock/LUTs-Linear-to-Blender-s-Filmic-sRGB/archive/main.zip)
 - If you just want to use the LUTs: Download the [Latest Release](https://github.com/L0Lock/LUTs-Linear-to-Blender-s-Filmic-sRGB/releases/latest)

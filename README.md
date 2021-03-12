# LUTs-Linear-to-Blender-s-Filmic-sRGB

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

Tests were done using the EXR file `Test_original_Linear.exr` looking like this in Blender:

![test original sRGB](https://github.com/L0Lock/LUTs-Linear-to-Blender-s-Filmic-sRGB/blob/main/Test_original_sRGB.png)

All test files are available here. You can also use the [lutizer.bat](https://raw.githubusercontent.com/L0Lock/LUTs-Linear-to-Blender-s-Filmic-sRGB/main/lutizer.bat) batch file to create your own luts and tests. Put the `Test_original_Linear.exr` file (you can create your own test file, but keep the same name) and the luts in the same folder as the bat file, then select and drag'n'drop the luts you want to test on the bat file. It will automatically create test PNGs for each lut.

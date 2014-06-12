# Android image resizer

Have you ever tried creating all needed drawables for an android project? It sucks, and updating them sucks even more. So I decided to do a simple script converting SVG files into all the drawables you need.

### Basic usage

`android-image-resizer width input.svg output.png`

Where
- `width` is the desired width for the mdpi resource.
- `input.svg` is the SVG to convert
- `output.png` is the desired name of the output file

This will create all folders needed and place a scaled `output.png` in each


Annotation-Kit
==============

Annotation Kit is a collection of useful tools and plugins for [Sketch App](http://bohemiancoding.com/sketch/) that help with adding annotations to your designs. Currently this package contains just a few tools, but pretty soon it will grow to a full fledged solution.

I will be posting updates in my twitter. Follow me [@turbobabr](https://twitter.com/turbobabr) to stay tuned.

## Installation

1. [Download Annotation-Kit.zip archive file](https://github.com/turbobabr/Annotation-Kit/archive/master.zip).
2. Reveal plugins folder in finder ('Sketch App Menu' -> 'Plugins' -> 'Reveal Plugins Folder...').
3. Copy downloaded zip file to the revealed folder and un-zip it.
4. You are ready to go! :)

**Note: All the plugins in this package work only in Sketch 3.2 Beta**

## Change Log

##### v0.2.0: December 4, 2014

- Added Magnifying Glass Tool
- Fixed aspect ratio bug in Shadow Remover

##### v0.1.0: December 2, 2014

- Initial release with only `Shadow Remover` and `Icon Extractor` tools

# Magnifying Glass Tool

This tool is essential when you need to get a detailed picture of a small area of your design. It looks exactly like the standard Sketch color picker and can be configured to suite your needs.

#### Magnify Area

1. Hit `Command-S` and put a slice on the area you want to magnify. Be sure that slice size is small enough, otherwise you'll get gazillion pixels magnifying glass. By default selected slice is magnified 8x times:
<img src="./docs/magnify_area_create_placeholder.png" width="696" height="324">
2. Select the slice and hit `Control-A` to magnify the area:
<img src="./docs/magnify_area_add_glass.png" width="696" height="324">

#### Magnify Area with Custom Settings

1. Hit `Command-S` and add a new slice:
<img src="./docs/magnify_area_with_custom_settings_initial.png" width="696" height="324">
2. Select the slice, hit `Control-Shift-A`, and setup magnifying glass properties:
<img src="./docs/magnify_area_with_custom_settings.png" width="696" height="529">
3. Click `OK` button or hit `Enter` to add the glass:
<img src="./docs/magnify_area_with_custom_settings_result.png" width="696" height="354">

# Shadow Remover Tool

Shadow Remover is a handy tool to quickly remove shadow from a window screenshot. It’s a great companion for anyone who is making documentation, writing articles or preparing presentations. By removing a shadow from your screenshot, it becomes more clear and less cluttered.

With this tool you could easily achieve the following result:

<img src="https://raw.githubusercontent.com/turbobabr/Annotation-Kit/master/docs/shadow_remover_result.png" width="728" height="286">

### Usage

1. Make a Window Screenshot using standard `Ctrl+Shift+Cmd+4`, hover over a window and hit `Space`.
2. Paste it into the page.
3. Select resulting image layer.
4. Hit `Ctrl+A` to remove the shadow.

### Caution

Shadow remover works only with window screenshots that have a certain pattern of bitmap data. It tests several pixels for transparency and color components to be sure that the reference bitmap layer is actually a window screenshot.

The following pixel probes are used during screenshot validation:

<img src="./docs/shadow_remover_pixel_probes.png" width="728" height="446">

This means that Shadow Remover works only with window screenshots that have standard shape and shadow. Popover windows, menus and windows with custom shape are not supported.

# Icon Extractor Tool

Icon Extractor Tool allows to extract contents of icons associated with application bundle or any file system object. It also allows to extract all or specific size representations from Apple `.icns` files or Windows `.ico` file.

<img src="./docs/icon_extractor_tool_hero.png" width="728" height="339">

This tool has nothing to do with annotations, but anyway I decided to include it in the package, since it's a real helper for designing graphics for documentation, articles or presentation. It's also might be used to quickly grab an icon of desired size and use it as a reference during graphics design process.

### Usage

1. Launch plugin `Annotation-Kit - > Extract Icon`.
2. Choose application, icon file or any other object you want extract icon from.
3. Hit `Grab Icon!` button.
4. You've just got some icons on your page! :)

> IMPORTANT NOTE: Don't forget that all the icons are belong to their respective owners! :)

## Feedback

If you discover any issue or have any suggestions, please [open an issue](https://github.com/turbobabr/annotation-kit/issues) or find me on twitter [@turbobabr](http://twitter.com/turbobabr).

## License

The MIT License (MIT)

Copyright (c) 2014 Andrey Shakhmin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
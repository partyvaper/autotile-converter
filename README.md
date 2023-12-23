# RPG Maker to Godot autotile converter

## Direct link

[partyvaper.github.io/autotile-converter](https://partyvaper.github.io/autotile-converter "partyvaper.github.io/autotile-converter")

## Preview

![https://i.imgur.com/wkMlSl7.png](https://i.imgur.com/wkMlSl7.png "preview")

## Known issues

If you have combined lots of different tile modes (usually copy modes) in one sprite-sheet, it can have weird layout issues. For most use cases it should work fine.

<details>
<summary>See a possible solution for layout issues that can happen</summary>
  
See the example below, if you look at the right side, tiles on right side shifted up (due to nothing above them), but we would like them in same height as the left one, to keep the input layout.

![https://i.imgur.com/0WiOKhS.png](https://i.imgur.com/0WiOKhS.png "example 1")


On next example you can see - if you create just empty tiles similar to left ones, but more to right, this will give us the padded space needed for tiles to match the source desired layout.

![https://i.imgur.com/se5f932.png](https://i.imgur.com/se5f932.png "example 2")

</details>

## Guide

1. Open tool,
2. Load spritesheet with RPG Maker autotiles by drag drop, choosing file or entering URL,
3. Optionally adjust tile size to match input source,
5. Switch modes if necessary (hover over mode selection for tooltip with a bit more explanation),
4. Select regions of autotiles by clicking on source image,
6. Save generated autotile sprite-sheet.

## Author

[github.com/partyvaper](https://github.com/partyvaper "github.com/partyvaper") | [partyvaper.itch.io](https://partyvaper.itch.io "partyvaper.itch.io")

## License

[MIT](https://github.com/partyvaper/autotile-converter/blob/main/LICENSE "MIT")

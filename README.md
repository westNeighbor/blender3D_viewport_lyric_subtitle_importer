# blender3D_viewport_lyric_subtitle_importer
import dynamic lyrics/subtitles to blender 3D viewport

[Blender subtitle/lyric importer Addon](https://mhstar.gumroad.com/l/kzgmm)

# installation
> Edit -> Preference -> Addon (select on the left side bar) -> Install (on the top)
select the .zip file to install, after installation, enable it by checking the checkbox.
Go the viewport, press `N` key to open side panel, you will find the addon at the bottom, now you can explore it to use.

# usage
First check the example of the effect. 

[![Addon Effect](http://img.youtube.com/vi/jEz0FAp4ui0/0.jpg)](https://www.youtube.com/watch?v=jEz0FAp4ui0)

It's pretty simple and straightforward to use. Overall all there are two parts. 

1. The subtitle/lyric text

   It imports the subtitle/lyric text and highlight the current time line, you can turn off the nonactive lines, you can fix the active line position. Since the time of dynamic subtitle/lyric based on the frame rate, you need press the `Update` button once you change the `FPS` (frame rate). Also, you can `Update` different subtitle/lyric file if you don't need to `New` one. 
   
2. Progress bar
   
   I add the progress bar option to indicate the time length and elapse for the progress. It's useful when you want to indicate the time information. 
   
# Be aware

- Generally, the perform is very good, can import hundreds or thounds characters without lagging, depending on the fonts you use. Some fonts are very heavy, it immediately lags even for not many texts, then you can go to the `Advance` setting to boost performance. 

- Don't change the modifier name.

# Tutorial
If you need more information and knowledge about my addon, you can check my tutorial on YouTube.

[![Blender subtitle/lyric addon tutorial](https://img.youtube.com/vi/M4LX6PhcU_g/hqdefault.jpg)](https://youtu.be/M4LX6PhcU_g)

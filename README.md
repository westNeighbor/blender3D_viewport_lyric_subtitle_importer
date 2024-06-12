# blender3D_viewport_lyric_subtitle_importer
import dynamic lyrics/subtitles to blender 3D viewport

# installation
> Edit -> Preference -> Addon (select on the left side bar) -> Install (on the top)
select the .zip file to install, after installation, enable it by checking the checkbox.
Go the viewport, press `N` key to open side panel, you will find the addon at the bottom, now you can explore it to use.

# usage
First check the example of the effect. 
[![effects](http://img.youtube.com/vi/vBlm_J-th1E&t=2905s/0.jpg)]([http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE](https://www.youtube.com/watch?v=vBlm_J-th1E&t=2904s))

It's pretty simple and straightforward to use. Overall all there are two parts. 

1. The subtitle/lyric text

   It imports the subtitle/lyric text and highlight the current time line, you can turn off the nonactive lines, you can fix the active line position. Since the time of dynamic subtitle/lyric based on the frame rate, you need press the `Update` button once you change the `FPS` (frame rate). 
   
2. Progress bar
   
   I add the progress bar option to indicate the time length and elapse for the progress. It's useful when you want to indicate the time information. 
   
# Be aware

For the progress bar moving object instancing part, when you choose `collection`, remember to check `Pick Instance` to separate all the objects in the collection. However, before changing back to `Object` or `Default`, you must **uncheck** `Pick Instance` first, otherwise, the object or default will not appear.

Generally, the perform is very good, can import hundreds or thounds characters without lagging, depending on the fonts you use. Some fonts are very heavy, it immediately lags even for not many texts, then you can go to the `Advance` setting to boost performance. 

# Tutorial
If you need more information and knowledge about my addon, you can check my tutorial on YouTube.

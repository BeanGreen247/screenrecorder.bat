# screenrecorder.bat
script for screencasting for windows using ffmpeg

## Stuff to change

* **-i audio="Microphone (3- USB Advanced Audio Device)"** to **-i audio="your microphone name here"**
* **-vf scale=1920x1080** to **-vf scale=output_video_widthxoutput_video_height**
* **-pixel_format yuv444p** to **-pixel_format your_preffered_pixel_format_here**
* **-crf 25** to **-crf your_number_here** , this will determine the quality of the footage
* change the **"30"** in **-g 30** , **-keyint_min 30** and **-async 30** to the fps you want your video to be in

## Video for reference

https://youtu.be/hQj3wgYQTqo

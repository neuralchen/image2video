# image2video
A python tool set for images to video, gif and so on.

# Dependencies:
- Python3
- Opencv
- tqdm
- imageio
- PIL

# Usage:
## images to video:
- To translate your images: `python images2video.py --imagePath [your images] --outputPath [your output file path]`
- To set the fps: `python images2video.py --imagePath [your images] --outputPath [your output file path] --videoFPS [FPS]`
- To set sampling scale: `python images2video.py --imagePath [your images] --outputPath [your output file path] --sampleSacle [image sampling scale]`

## images to gif:
- To make a gif from a dir: `python image2gif.py --imagePath [your images] --outputPath [output file path .gif] --duration [animation duration of gif (sencond)] --sampleScale [image sampling scale]`

## video to gif:
- To make a gif from a video file: `python video2gif.py --videoPath [your images] --outputPath [output file path .gif] --duration [animation duration of gif (sencond)] --sampleScale [image sampling scale]`

# Who do i talk to?
- CXH @ chenxuanhongzju@gmail.com

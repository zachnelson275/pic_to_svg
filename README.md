# pic_to_svg
This project converts .jpg and .png files into .svg files through a local web tool. I created 
this to help my wife, a graphic designer, to not have to spend so much time tracing out low-res 
images into workable .svg files to send to send to the manufacturers. 

To build and run this project, make sure you have docker installed on your machine. Then, run 
"docker build -t converter ." followed by "docker run -p 5000:5000 converter". You then can open 
a web browser and go to "localhost:5000" to access the converter

STILL IN PROGRESS

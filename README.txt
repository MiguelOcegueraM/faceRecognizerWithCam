##To run the face detection w/ openCV type in the terminal

$ python detect_faces.py --image nameOfImage.jpg --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel

##TO RUN THE FACE DETECTIO WITH CAM 
$ python detect_faces_video.py --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel

THIS PROGRAM WAS MADE AT APRIL 07 2020
DURING THE QUARANTINE OF CORONAVIRUS COVID-19
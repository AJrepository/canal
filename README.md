# canal
Tensorflow object detection api
https://github.com/tensorflow/models/tree/master/research/object_detection

Tensorflow object detection tutorial i followed
https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10

Image annotation tool I used
https://github.com/tzutalin/labelImg

#object detection and collision warning

Unfortunately I wasnt able to uplad my tensorflow object detection folder due to size restrictions but i will be able to guide you the with instruction from here.
You can find the tensorflow object detection files in the appendix, zipped.
The files on here are also in the zipped folder. So there is no need to copy the object detection files from here.
I have only uploaded them here to show my contribution to the project.

You can look at the tensorflow github page i have linked above for its dependencies.
Then follow the tutorial i followed which is linked up there just to install the api and other dependencies. 
because the changes he makes to the files would have been already done by me. 
All you have to do is install the api and the test your object detector on the object_detection_tutorial.ipynb
if all is good, then you can simply run the object_detection_image.py file or object_detection_video.py file to see an output,
if you want to run the object_detection_webcam.py file, follow the tutorial linked above

But if you want to follow the tutorial from scratch then you wouldnt need the files i have attached as the appendix,
You could just follow the tutorial, the test and train images I used are in the object detection folder and when you finish training 
your model and are ready to test you detector you can copy my collision warning code portion from the executable files in the same folder.
This way you will be able to replicate my results.

Also in the object detection files folder I have uploaded the output videos I got by running the testvideos using
object_detection_video.py.


#lane detectiion

The files in edge detection folder can perfom the edge detection.
You can run the canny python file noramlly but change image file inside if you want to test other images

The holistic model is included in the appendix as its a large file
To run the holistic model keep the ile stucture the same as you would need the pre trained weights in hed_model folder. 
The method to run this model is in the executable file. The executable file is also available in the edge detection folder here

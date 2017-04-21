# ComputerVision
Pedestrian Crossing by identifying and classifying the objects in an image

Info:
•	This repository consists of 4 cascade classifier files and a .cpp file.
•	The explanation of the code is done with comments.

Usage:
•	Install Visual Studio and download OpenCV 3.2 library.
•	Set up an environment for Visual Studio with OpenCV libraries to run the code.
•	Download and store all the 4 cascade files and .cpp(PedestrianCrossing) file in the same folder.
•	Give arguments in the following way:
argv[1] argv[2] argv[3] argv[4] argv[5] argv[6]
1.	Path of the first image in which pedestrians, vehicles and pedestrian traffic signal needs to detected(pedestrian.jpg).
2.	Path of the template image which is used to detect pedestrian traffic signal(temp.jpg).
3.	Path of the first cascade file(checkcas.xml).
4.	Path of the second cascade file(cas1.xml).
5.	Path of the third cascade file(cas2.xml).
6.	Path of the four cascade file(cas3.xml).
•	Compile and run the code in debug mode.

Results:
•	Two windows will be displayed:
1.	“Car-Pedestrian” window - Cars and pedestrians will be detected.
2.	“Pedestrian Signal” window – Traffic signal will be detected.
•	The results are truly based on the positive and negative images provided in the database.

Note:
•	Used Template matching method to detect the pedestrian traffic signal in the image. 



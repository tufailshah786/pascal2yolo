# pascal2yolo
Converting the pascal voc files into the yolo format

First of all you need the latest version of python installed in your pc

step 1: Download the zip file and extract the file in C:/ folder after extraction you will get this folder"pascal2yolo-master"

step 2: Open the folder "pascal2yolo-master" and create 3 folders name as it is "images" "labels" "results" and store the images in "images" folder and annotations in "labels" folder (its only for the rotated bounding box, xml file that contains the point xmin,ymin,xmax,ymax,angle)

step 3: Write the class names in the voc text file and save it 

step 4: Open the command prompt and then go to the extract folder "C:\pascal2yolo-master\Yolo_Format" by writing this command "cd C:\pascal2yolo-master\Yolo_Format"

step 5: write command "python voc.py voc.names images/ labels/ results/" and you will get yolo annotation files in "results" folder

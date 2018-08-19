# Edge Detection

To run this code we need to 
1. store the project in the local drive
2. open the project file "Hands-on1.2(Edge Detection).vcxproj" in Visual Studio 2015.
3. open the "Code.cpp" and run it by pressing Ctrl+F5.

NOTE:
The user must specify the path of the input image "bird.jpg" in the imread function. For instance, in the code the path for the input image will be mentioned as "E:\\Venkatesh Balaji\\MS Sem2 materials\\DIVPC\\Visual studio codes\\Images\\bird.jpg".
The user must change this path to the path where the input image is located.

The edge maps will be stored in the folder where the source code and the project file is present. The user can change the location where the edge map is stored by mentioning a path along with the file name and file type extension where he/she wants to store it in the imwrite function.

The input image is "bird.jpg" and the output edge maps are named as
1. CannyFinal_output.jpg
2. LaplaceFinal_output.jpg
3. SobelFinal_output.jpg
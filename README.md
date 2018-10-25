In this , I am performing two morphological operations which are Erosion and Dilation on the image cells.jpg
For this , I have used a plus window of size 3. 

The Erosion operation on the image can be performed with the command :
python Morph.py --image cells.jpg -m EROSION

On running this command, we can see the output image in the output folder where a white blob is increased in size and the
black blob has decreased. 


and the Dilation operation on the image can be performed with the command:
python Morph.py --image cells.jpg -m DILATION

On performing Dilation on the input image, we can see that the output folder has a new image where white blob has decreased and
almost reduced whereas a black blob has increased. 

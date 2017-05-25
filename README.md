# sdcwork

<h2>Project-1 Writeup</h2>

<p>
My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I did the 
gaussian blur, followed by the canny edge.  A region of interest was cordoned off and then 
lines after the hough transformation were drawn.  This process was repeated for the videos and
a rough lane line annotation was produced.
</p>
<p>
One potential shortcoming would be what would happen when there are no original lane lines
on the road.
</p>
<p>
A possible improvement would be to incorporate the calculation of the slopes of the lines
to improve accuracy of the annotation.
</p>

# OpenCV


<h2 style="color: blue"><u>PROJECTS :</u></h2>

<ol>
<li style="color: green"><b><u>Hand detection and Fingers counting</u></b></li>
<h4><b>Contents :</b></h4>
<ul>
<li><b><a href="https://github.com/Shivam06/OpenCV/blob/master/handDetection/hand.py">hand.py</a></b> - Script for hand detection and fingers counting in a video.</li>
<li><b><a href="https://github.com/Shivam06/OpenCV/blob/master/handDetection/1.png">1.png</a>, <a href="https://github.com/Shivam06/OpenCV/blob/master/handDetection/2.png">2.png</a>, <a href="https://github.com/Shivam06/OpenCV/blob/master/handDetection/3.png">3.png</a>, <a href="https://github.com/Shivam06/OpenCV/blob/master/handDetection/4.png">4.png</a>, <a href="https://github.com/Shivam06/OpenCV/blob/master/handDetection/5.png">5.png</a></b> are screenshots taken from the webcam video</li>
</ul>
<br/>
<li style="color: green"><b><u>Sudoku Solver</u></b></li>
<h4><b>Contents :</b></h4>
<ul>
<li><b><a href="https://github.com/Shivam06/OpenCV/blob/master/Sudoku/Scripts/image_processing/imageProc.py">imageProc.py</a></b> Script to segement the image of sudoku square from original image <b><a href="https://github.com/Shivam06/OpenCV/blob/master/Sudoku/Solving_sudoku_images/Original_image.jpg">"Original_image.jpg"</a></b></li>
<li><b><a href="https://github.com/Shivam06/OpenCV/blob/master/Sudoku/Scripts/data_creation/sudoku_data.py">imageToData.py</a></b> Script to prompt user mark correct labels (1-9) for numbers shown in image. (Creation of training data and test data) <b><a href="https://github.com/Shivam06/OpenCV/blob/master/Sudoku/numbers2.png">"numbers2.png"</a></b> and <b><a href="https://github.com/Shivam06/OpenCV/blob/master/Sudoku/numbers.png">"numbers.png"</a></b> and storing the feature vectors of all the numbers (feature matrix) shown in the image in 2 text files, one for training set and other for test set.</li>
<li><b><a href="https://github.com/Shivam06/OpenCV/blob/master/Sudoku/Scripts/OCR/miscellaneous_sudoku.py">miscellaneous sudoku.py</a></b> Module contains function for digit recognition which has been used in <b><a href="https://github.com/Shivam06/OpenCV/blob/master/Sudoku/Scripts/sudoku_main.py">sudoku_main.py</a></b>.
<li><b><a href="https://github.com/Shivam06/OpenCV/blob/master/Sudoku/Scripts/sudoku_main.py">sudoku_main.py</a></b> - Main Script of project to take an image of sudoku and solve it.</li>
</ul>
</ol>

<br/>
<h2 style="color: red">TODO - Sudoku Solver</h2>

<ul>
<li>Improve Accuracy for recognition either by training more and different fonts of training data or use different algorithm. Will try <b>Artificial Neural Network (ANN)</b> model trained over MNIST dataset (hand written digits).</li>
<li>Debug and complete <b>sudoku.py</b></li>
<li>Solve sudoku using <b>backtracking algorithm</b>.</li>
<li>Document all the codes.</li>
</ul>



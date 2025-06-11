# cs6476-computer-vision-problem-set-3-introduction-to-ar-solved
**TO GET THIS SOLUTION VISIT:** [CS6476: Computer Vision Problem Set 3: Introduction to AR Solved](https://mantutor.com/product/cs6476-computer-vision-problem-set-3-introduction-to-ar-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;55877&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6476: Computer Vision Problem Set 3: Introduction to AR Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<h1>Description</h1>
Problem Set 3 introduces basic concepts behind Augmented Reality, using the contents that you will learn in modules 3A-3D and 4A-4C: Projective geometry, Corner detection, Perspective imaging, and Homographies, respectively.

&nbsp;

Additionally, you will also learn how to read from a video, process each video frame by identifying important features, insert images within images, and assemble a video from a sequence of frames.

<h1>Learning Objectives</h1>
<ul>
<li>Find markers using circle and corner detection, convolution, and / or pattern recognition.</li>
<li>Learn how projective geometry can be used to transform a sample image from one plane to another.</li>
<li>Address the marker recognition problem when there is noise in the scene.</li>
<li>Implement backwards (reverse) warping</li>
<li>Understand how video can be extracted in sequences of images, and replace specific areas of each image with different content.</li>
<li>Assemble a video from a sequence of images.</li>
</ul>
<h1>Problem Overview</h1>
<strong>Methods to be used: </strong>In this assignment you are to use methods that work with Feature Correspondence and​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Corner detection. You will also apply methods that are part of Projective Geometry and Image Warping, however you will have to do these manually using linear algebra concepts.

<strong>&nbsp;</strong>

<strong>RULES:</strong> You may use image processing functions to find color channels, load images, find edges (such as with​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Canny).&nbsp; Don’t forget that those have a variety of parameters and you may need to experiment with them. There are certain functions that may not be allowed and are specified in the assignment’s autograder Piazza post. Refer to this problem set’s autograder post for a list of banned function calls.

<strong><u>Please</u> do not use absolute paths in your submission code. All paths should be relative to the submission directory. Any submissions with absolute paths are in danger of receiving a penalty! </strong>

<strong>Obtaining the Started Files</strong>

Obtain the starter code from canvas under files.

<h1>Programming instructions</h1>
Your main programming task is to complete the api described in the file <strong>ps3.py</strong>​&nbsp;&nbsp; .&nbsp; The driver program​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>experiment.py</strong> helps to illustrate the intended use and will output the files needed for the writeup.&nbsp; Additionally​ there is a file <strong>ps3_test.py</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; that you can use to test your implementation.​

<h1>Write-up instructions</h1>
Create <strong>ps3_report.pdf</strong>​&nbsp;&nbsp; – a PDF file that shows all your output for the problem set, including images labeled​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; appropriately (by filename, e.g. ps3-1-a-1.png) so it is clear which section they are for and the small number of written responses necessary to answer some of the questions (as indicated).&nbsp; For a guide as to how to showcase your results, please refer to the powerpoint template for PS3.

<strong>How to submit: </strong>

<ol>
<li>To submit your code, in the terminal window run the following command: python submit.py ps03</li>
<li>To submit the report, input images for part 5, and experiment.py, in the terminal window run the following command: python submit.py ps03_report</li>
<li>Submit your report pdf to gradescope.</li>
</ol>
&nbsp;

<strong>YOU MUST PERFORM ALL THREE STEPS. I.e. two commands in the terminal window and one upload to gradescope.&nbsp;&nbsp; </strong><strong>Only your last submission before the deadline will be counted for each of the code and the</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong> report. </strong>

&nbsp;

The following lines will appear:

GT Login required.

Username : &lt;GT username (same as T-square)&gt;

Password: &lt;GT password&gt;

Save the jwt?[y,N] &lt;either y or N if you want to save your credentials&gt;

You should see the autograder’s feedback in the terminal window. Additionally, you can look at a history of all your submissions at <a href="https://bonnie.udacity.com/">https://bonnie.udacity.com</a><u>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </u><a href="https://bonnie.udacity.com/">/</a>

<h1>Grading</h1>
The assignment will be graded out of 100 points.&nbsp; The last submission before the time limit will only be considered. The code portion (autograder) represents <strong>60</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>%</strong> of the grade and the report the remaining ​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>40</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>%</strong>.​

&nbsp;

The images included in your report must be generated using experiment.py. This file should be set to be run as is to verify your results. <strong>Your report grade will be affected if we cannot reproduce your output images.</strong>​

&nbsp;

The report grade breakdown is shown in the question heading. As for the code grade, you will be able to see it in the console message you receive when submitting.

<h1>Assignment Overview</h1>
A glass/windshield manufacturer wants to develop an interactive screen that can be used in cars and eyeglasses. They have partnered with a billboard manufacturer in order to render certain marketing products according to each customer’s preferences.

&nbsp;

Their goal is to detect four points (markers) currently present in the screen’s field-of-view and insert an image or video in the scene. To help with this task, the advertising company is installing blank billboards with four distinct markers, which determine the area’s intended four corners.&nbsp; The advertising company plans to insert a target image / video into this space.

&nbsp;

They have hired you to produce the necessary software to make this happen. They have set up their sensors so that you will receive an image / video feed and a target image / video. They expect an altered image / video that contains the target content rendered in the scene, visible in the screen.

<h1>1.&nbsp; Marker detection in a simulated scene [15 Points]</h1>
The first task is to identify the markers for this Augmented Reality exercise.&nbsp; In real practice, markers can be used (in the form of unique pictures) that stand out from the background of an image.&nbsp; Below is an image with four markers.

&nbsp;

Notice that they contain a cross section bounded by a circle.&nbsp; The cross-section is useful in that it forms a distinguished corner.&nbsp; In this section you will create a function/set of functions that can the detect these markers, as shown above.&nbsp; You will use the images provided ​ to detect the (x, y) center coordinates of each of​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; these markers in the image. The position should be represented by the center of the marker (where the cross-section is).

&nbsp;

<strong>Code:</strong> Complete ​ find_markers(image)​

&nbsp;

You will use the function mark_location(image, pt) in experiment.py to create a resulting image that highlights the center of each marker and overlays the marker coordinates in the image. Each marker should present their location similar to this:

&nbsp;

&nbsp;

Images like the one above may not be that hard to solve. However, in a real-life scene, it proves to be much more difficult.&nbsp; Make sure your methods are robust enough to also locate the markers in images like the one below, where there could be other objects in the scene:

&nbsp;

&nbsp;

Let’s now assume there is “noise” in the scene (i.e. rain, fog, etc.).

&nbsp;

&nbsp;

<strong>Report: </strong>​Find the markers and place their coordinates, as shown above. Use the following images:

<ul>
<li>Input: ​<strong>jpg</strong>​. Output: ​<strong>ps3-1-a-1.png </strong></li>
<li>Input: ​<strong>jpg. </strong>​Output: ​<strong>ps3-1-a-2.png </strong></li>
<li>Input: ​<strong>jpg. </strong>​Output: ​<strong>ps3-1-a-3.png </strong></li>
</ul>
<h1>2.&nbsp; Marker detection in a real scene [20 Points]</h1>
Now that you have a working method to detect markers in simulated scenes, you will adapt it to identify these same markers in real scenes like the image shown below.&nbsp; Use the images provided to essentially repeat the task of section 1&nbsp; above and draw a box (four 3-pixel wide lines, any color) where the box corners touch the marker centers.

&nbsp;

&nbsp;

<strong>Code: </strong>​Complete ​draw_box(image, markers)

&nbsp;

<strong>Report: </strong>​Find the markers and place their coordinates, as shown above. Use the following images:

<ul>
<li>Input: ​<strong>ps3-2-a_base.jpg</strong>​. Output: ​<strong>ps3-2-a-1.png </strong></li>
<li>Input: ​<strong>ps3-2-b_base.jpg</strong>​. Output: ​<strong>ps3-2-a-2.png</strong></li>
<li>Input: ​<strong>ps3-2-c_base.jpg</strong>​. Output: ​<strong>ps3-2-a-3.png </strong>​(90-degree rotation is intentional)</li>
<li>Input: ​<strong>ps3-2-d_base.jpg</strong>​. Output: ​<strong>ps3-2-a-4.png </strong></li>
<li>Input: ​<strong>ps3-2-e_base.jpg</strong>​. Output: ​<strong>ps3-2-a-5.png </strong></li>
</ul>
<h1>3.&nbsp; Projective Geometry [20 Points]</h1>
&nbsp;

Now that you know where the billboard markers are located in the scene, we want to add the marketing image. The advertising company requires that their client’s billboard image is visible from all possible angles since you are not just driving straight into the advertisements.&nbsp; Unphased, you know enough about computer vision to introduce projective geometry.&nbsp; The next task will use the information obtained in the previous section to compute a transformation matrix <em>H </em>. This matrix will allow you to project a set of points (x, y) to another plane represented by the points (x’, y’) in a 2D view. In other words we are looking at the following operation:

&nbsp;

In this case, the 3×3 matrix is a ​<em>homography</em>​, also known as a ​<em>perspective transform</em>​ or ​<em>projective transform</em>​.

There are eight unknowns, ​<strong>a</strong>​ through ​<strong>h</strong>, and ​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ​<strong>i</strong>​ is 1. If we had four pairs of corresponding (<em>u</em>, <em>v</em>) ↔ (<em>u</em>′, <em>v</em>′) points, we can solve for the homography.

&nbsp;

The objective here is to insert an image in the rectangular area that the markers define. This insertion should be robust enough to support cases where the markers are not in an orthogonal plane from the point of view and present rotations. Here are two examples of what you should achieve:

&nbsp;

<strong>Code: </strong>​Complete:

<ul>
<li>find_four_point_transform(src_points, dst_points)</li>
<li>project_imageA_onto_imageB(imageA, imageB, homography)</li>
</ul>
<strong>&nbsp;</strong>

<strong>Report: </strong>​Use an image of your own to project in the area delimited by the four markers. Name it ​<strong>img-3-a-1.png </strong>and place it in the “input_images” directory.

<ul>
<li>Input: ​<strong>ps3-3-a_base.jpg, img-3-a-1.png</strong>​. Output: ​<strong>ps3-3-a-1.png </strong></li>
<li>Input: ​<strong>ps3-3-b_base.jpg, img-3-a-1.png</strong>​. Output: <strong>ps3-3-a-2.png</strong>​</li>
<li>Input: ​<strong>ps3-3-c_base.jpg, img-3-a-1.png</strong>​. Output: ​<strong>ps3-3-a-3.png </strong></li>
</ul>
<h1>4.&nbsp; Finding markers in a video [20 Points]</h1>
<em>&nbsp;</em>

Static images are fine in theory, but the company wants this functional and put into practice.&nbsp; That means, finding markers in a moving scene.

&nbsp;

In this part you will work with a short video sequence of a similar scene. When processing videos, you will read the input file and obtain images (frames). Once the image is obtained, you will apply the same concept as explained in the previous sections. Unlike the static image, the input video will change in translation, rotation, and perspective. Additionally there may be cases where a few markers are partially visible.&nbsp; Finally, you will assemble this collection of modified images into a new video. Your output must render each marker position relative to the current frame coordinates.

&nbsp;

Besides making all the necessary modifications to make your code more robust, you will complete a function that outputs a video frame generator. This function is almost complete and it is placed so that you can learn how videos are read using OpenCV. Follow the instructions placed in ps3.py.

&nbsp;

<strong>Code: </strong>​Complete ​video_frame_generator(filename)

&nbsp;

<strong>Report: In order to grade your implementation, share a link to each video (Youtube, Dropbox, etc.). This video should be only visible via link sharing, not public. If we cannot open this link when grading your grade for this and remaining sections will be affected. </strong>

<strong>&nbsp;</strong>

<ol>
<li>First we will start with the following videos. Include the specified frames in your report as instructed below.</li>
</ol>
&nbsp;

Frames to record: 355, 555, and 725.

<ul>
<li>Input: ​<strong>ps3-4-a.mp4</strong>​. Output: ​<strong>ps3-4-a-1.png, ps3-4-a-2.png, ps3-4-a-3.png, link to the full video. </strong>Frames to record: 97, 407, and 435.</li>
<li>​Input: ​<strong>ps3-4-b.mp4</strong>​. Output: ​<strong>ps3-4-a-4.png, ps3-4-a-5.png, ps3-4-a-6.png, link to the full video.</strong></li>
</ul>
&nbsp;

<ol>
<li>Now work with noisy videos:</li>
</ol>
Frames to record: 47, 470, and 691.

<ul>
<li>Input: ​<strong>ps3-4-c.mp4</strong>​. Output: ​<strong>ps3-4-b-1.png, ps3-4-b-2.png, ps3-4-b-3.png, link to the full video. </strong></li>
</ul>
<strong>&nbsp;</strong>

Frames to record: 207, 367, and 737.

<ul>
<li>Input: ​<strong>ps3-4-d.mp4</strong>​. Output: ​<strong>ps3-4-b-4.png, ps3-4-b-5.png, ps3-4-b-6.png, link to the full video.</strong></li>
</ul>
<h1>5.&nbsp; Final Augmented Reality [20 Points]</h1>
&nbsp;

Now that you have all the pieces, insert your advertisement into the video provided.&nbsp; Pick an image and insert it in the provided video.

&nbsp;

<strong>Report: In order to grade your implementation, share a link to each video (Youtube, Dropbox, etc.). This video should be only visible via link sharing, not public. If we cannot open this link when grading your grade for this and remaining sections will be affected. </strong>

<strong>&nbsp;</strong>

<ol>
<li>First we will start with the following videos. Include the specified frames in your report as instructed below.</li>
</ol>
Frames to record: 355, 555, and 725.

<ul>
<li>Input: ​<strong>ps3-4-a.mp4</strong>​. Output: ​<strong>ps3-5-a-1.png, ps3-5-a-2.png, ps3-5-a-3.png, link to the full video. </strong></li>
</ul>
<strong>&nbsp;</strong>

Frames to record: 97, 407, and 435.

<ul>
<li>​Input: ​<strong>ps3-4-b.mp4</strong>​. Output: ​<strong>ps3-5-a-4.png, ps3-5-a-5.png, ps3-5-a-6.png, link to the full video.</strong></li>
</ul>
&nbsp;

<ol>
<li>Now work with noisy videos:</li>
</ol>
Frames to record: 47, 470, and 691.

<ul>
<li>Input: ​<strong>ps3-4-c.mp4</strong>​. Output: ​<strong>ps3-5-b-1.png, ps3-5-b-2.png, ps3-5-b-3.png, link to the full video. </strong></li>
</ul>
<strong>&nbsp;</strong>

Frames to record: 207, 367, and 737

<ul>
<li>Input: ​<strong>ps3-4-d.mp4</strong>​. Output: ​<strong>ps3-5-b-4.png, ps3-5-b-5.png, ps3-5-b-6.png, link to the full video. </strong></li>
</ul>
<h1>6.&nbsp; Challenge problem: Video in Video [5 points]</h1>
As a challenge, try embedding a video inside the markers video.&nbsp; You are free to select any video and modify it as necessary to make it fit both in size and number of frames. Name this video ​<strong>my-ad.mp4</strong>​, this file will not be collected as it may exceed the Bonnie submission size limit. A different file with the same name will be used when grading your assignment (which shouldn’t affect your results). The file we will use for grading is longer in

&nbsp;

&nbsp;

&nbsp;

Georgia Tech’s CS 6476: Computer Vision

duration than ps3-4-a.mp4.&nbsp; Your output should have the same size and number of frames as the original markers video.

&nbsp;

<ul>
<li>Frames to record: 355, 555, and 725.</li>
<li>Input: <strong>ps3-4-a.mp4, my-ad.mp4</strong>​ . Output: ​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>ps3-6-a-1.png, ps3-6-a-2.png, ps3-6-a-3.png, link to the full</strong>​</li>
</ul>
<strong>&nbsp;</strong>

&nbsp;

&nbsp;

&nbsp;

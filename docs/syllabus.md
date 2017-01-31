---
layout: page
title:  Syllabus
---

## Introduction to Computer Vision and Machine Learning, ARTTECH 3039

Semester, Year
:   Spring, 2017

Meeting Times
:   Tuesday 9am-4pm

Meeting Location
:   MacLean 400

Instructor
:   [Christopher Baker](https://christopherbaker.net)

Class Forum
:   [https://ats.community/c/courses/arttech-3039](https://ats.community/c/courses/arttech-3039)

Class Website
:   [http://saic-ats.github.io/ARTTECH-3039/](http://saic-ats.github.io/ARTTECH-3039/)

Public Repository (code examples, etc)
:   [https://github.com/SAIC-ATS/ARTTECH-3039/](https://github.com/SAIC-ATS/ARTTECH-3039/)

Private Repository (assignment submission, etc)
:   [https://github.com/SAIC-ATS/ARTTECH-3039-Spring-2017-Private](https://github.com/SAIC-ATS/ARTTECH-3039-Spring-2017-Private)

TA
:   N/A

--------------------------------------------------------------------------------

### Instructor Bio
[Christopher Baker](http://christopherbaker.net) is an artist whose work engages the rich collection of social, technological and ideological networks present in the urban landscape. He creates artifacts and situations that reveal and generate relationships within and between these networks. Christopher’s work has been presented worldwide and he contributes to the open source community at [http://github.com/bakercp](http://github.com/bakercp).

### TA Bio
N/A

--------------------------------------------------------------------------------

### Course Description

Computer vision allows machines to see and understand their environment. This course will equip students with the practical skills and critical theory needed to both employ and critically engage these techniques. Real-time body tracking, facial recognition and gesture analysis using RGB+D and LiDAR sensors, artificial intelligence and machine learning will be emphasized. Students will explore and critique contemporary applications ranging from automated mass surveillance to interactive installations. A final project will build on in-class workshops, technical exercises, critical readings and discussions.

### Course Goals
__Key goals include:__

- Working and applied knowledge "classical" computer vision techniques.
- Working and applied knowledge of modern computer vision techniques that leverage machine learning.

### Course Values
- Sharing / Open
    - Documentation
    - [DIWO](http://furtherfield.org/projects/diwo-do-it-others-resource)
    - Publish
    - [Cult of Done](http://www.brepettis.com/blog/2009/3/3/the-cult-of-done-manifesto.html)

### Methodology
Students will engage in individual in-lab and home assignments, class presentations, lectures, discussions, assigned readings, group and individual projects and desk critiques. Visiting artists / faculty may enhance the experience and offer additional perspectives.

### Assignments
The course may include workshops and several projects, relevant technical and theoretical reading, written online responses, technical research and outings.

### Class Text
There is no official class text, though there are several books that we'll reference on occasion.

#### openFrameworks
- [ofBook](https://github.com/openframeworks/ofBook)

#### Classical Computer Vision
- [Practical OpenCV](https://link.springer.com/book/10.1007%2F978-1-4302-6080-6)
- [Learning OpenCV : computer vision with the OpenCV library](https://vufind.carli.illinois.edu/vf-sai/Record/sai_123825)
- [Computer Vision: Algorithms and Applications](http://szeliski.org/Book/)

#### Machine Learning
- [ML4A](https://ml4a.github.io/index/) _In progress book_

### Reading and other Resources
Posted on the course website.

### Materials
Provided by the student as needed.

### Attendance
1. Students are best served by attending all classes.
2. Missing three classes will result in a class failure. This is strictly enforced.
3. Six or more unexcused late arrivals or early departures will result in class failure.

_Tip: If you are going to be absent, late to class, or need to depart early, please contact me BEFORE class starts. This is so I can make sure you have what you need to succeed!_

### Wait Lists
Students wait-listed for classes will be admitted on a space available basis determined by instructors’ discretion (in consultation with the department chair).

### Grading Procedure/Criteria
- Grades are credit / no-credit for this course. Credit is based on several factors: 30% participation (discussions, critiques, etc), 70% projects / assignments.
- Incomplete grades will not be offered.

### Writing Assistance
[Writing Center](http://www.saic.edu/webspaces/portal/advising/write\_center.html)

### Special Needs
[Disability and Learning Resource Center](http://www.saic.edu/lifeatsaic/wellnesscenter/disabilityandlearningresourcecenter/)

### Course Schedule

_(subject to change based on incoming skills and experience)_

#### Week 0
- Course Overview
  - Classic Computer Vision
  - Machine Learning
- Review
  - git / github
  - openFrameworks
    - Installation
    - Project Generator
    - Addons
      - [ofxPS3EyeGrabber](https://github.com/bakercp/ofxPS3EyeGrabber/)
        - A driver for the cheap and versatile [PS3 Eye Camera](https://en.wikipedia.org/wiki/PlayStation_Eye).
      - ofxOpenCv _(Included with openFrameworks as a core addon)_
        - Contains the [OpenCV](http://opencv.org/) library.
        - Contains some older classes to simplify interacting with OpenCV in openFrameworks.
      - [ofxCv](https://github.com/bakercp/ofxCv) (_develop branch of @bakercp's fork is up-to-date with latest openFrameworks_)
        - Contains a lot of OpenCV examples along with a modern collection of wrappers.
    - Compiling
    - Program Structure
  - Code Basics
    - Variables - data, memory, etc.
    - Arrays - collections of variables.
    - `for` loops, including ``
    - `if` / `else`
  - Image Representation
    - Single 1-dimensional array
    - Accessing individual elements
      - Nested for-loop for x and y
 - Simple Infinite Impulse Response [Low Pass Filters](https://en.wikipedia.org/wiki/Low-pass_filter#Simple_infinite_impulse_response_filter)
  > Low-pass filters provide a smoother form of a signal, removing the short-term fluctuations, and leaving the longer-term trend.

- Intro to Computer Vision
- Motion Detection
  - Frame Differencing
    - In class Example
  - Optical Flow
    - https://en.wikipedia.org/wiki/Optical_flow
- Background Subtraction
  - Fixed Background Subtraction
  - Adaptive Background Subtraction
- Brightness Thresholding
  - Fixed Threshold
  - Adaptive Threshold
- Pixel Tracking
  - Brightness Tracking
  - Color Tracking

- Color Tracking
  - [Color Distance](https://en.wikipedia.org/wiki/Color_difference)

- Resources
  - [Intro](http://openframeworks.cc/ofBook/chapters/image_processing_computer_vision.html)
  - [Introduction to Computer Vision](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6aG2RJHErXKSWFDXU4qo_ro)
  - [Computer Vision for Artists and Designers: Pedagogic Tools and Techniques for Novice Programmers](http://www.flong.com/texts/essays/essay_cvad/)
  - http://ofxaddons.com/categories/10-computer-vision
  - [Workshop](https://github.com/kylemcdonald/ofxCv/wiki/Intermediate-Computer-Vision-with-openFrameworks)

#### Week 1
- Classical Computer Vision Part 0
  - Image Filtering
    - Brightness, Contrast, etc.
    - Morphological Operators, Lines and Edges
      - Hough, Canny, Scharr, Sobel, Structured Forest, [etc](http://docs.opencv.org/3.1.0/d0/da5/tutorial_ximgproc_prediction.html)
  - Image Segmentation
  - Contours
  - Object Tracking

#### Week 2
- Classical Computer Vision Part 1
  - Homography and Rectification
  - Video Mapping / Quad Mapping
  - Detection
  - Recognition

#### Week 3
- Contemporary Sensing with RGB+D
  - Kinect
  - 3D Segmentation
  - Skeleton Tracking
- LIDAR
- Point Clouds

#### Week 4
- Machine Learning 0
  - [Introduction](https://www.youtube.com/watch?v=40riCqvRoMs&list=PLzjJ7xfFxm6nTKTfB1xwE70efksbY6jbC)
  - Resources
    - https://arxiv.org/, http://www.arxiv-sanity.com/
    - http://www.gitxiv.com/
  - [Implementations](http://www.gitxiv.com/)
  - Introduction to Machine Learning
  - Basic Training
    - MNIST
  - [t-SNE](https://lvdmaaten.github.io/tsne/), [ofxTSNE](https://github.com/genekogan/ofxTSNE)

#### Week 5
- Machine Learning 1
  - Object Recognition Darknet / Yolo
    - https://github.com/mrzl/ofxDarknet
    - https://github.com/genekogan/screengrab-caption
    - http://pjreddie.com/darknet/yolo/
    - https://github.com/TensorBox/TensorBox
  - [Multi-Person Pose Estimation](https://www.youtube.com/watch?v=pW6nZXeWlGM) and [this](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation)

#### Week 6
- Machine Learning 2
  - Image Generation with [Pix2Pix](https://github.com/phillipi/pix2pix), ([example](https://github.com/brangerbriz/docker-StackGAN))

#### Week 7
- Machine Learning 3
  - Adversarial Networks [GANs](https://github.com/brangerbriz/docker-StackGAN)

#### Week 8
- Machine Learning 3
  - Viewers Choice

#### Week 9
  - Open Studio

#### Week 10
  - Open Studio

#### Week 11
  - Open Studio

#### Week 13
  - Open Studio

#### Week 14
  - Final Critiques
# Image Interest Points for LimeSurvey 5.x
**A custom question theme that allows for dropping "positive" and "negative" markers and related comments on an image in LimeSurvey 5.x.**

Compatible with LimeSurvey version 5.x.

![Image Interest Points](/Interest-Points/survey/questions/answer/multipleshorttext/assets/images/interest_points_2.png)

**Implementation:**

1) Extract the download, compress (zip) the *Interest-Points* folder and import via the theme manager.

2) Create a multiple-short-text question, click Save.

3) Set the question type to "Interest-Points", click Save.  
![Image Select Interest-Points](/Interest-Points/survey/questions/answer/multipleshorttext/assets/images/interest_points_3.png)

4) In the question settings "Custom theme options", enter an absolute path to the image, click Save.  
![Image Enter path to image](/Interest-Points/survey/questions/answer/multipleshorttext/assets/images/interest_points_4.png)

5) Create 3 times as many subquestions as the number of markers allowed
    - Each marker will populate three sub-questions
    - The marker sign
    - The marker coordinates relative to percentages of width and height of the image
    - The marker comment

**Notes:**

1) The styles for the theme can be modified in */pathToLimeSurvey/upload/themes/question/Interest-Points/survey/questions/answer/multipleshorttext/assets/css/interestPoints.css*.

2) Demo survey in */Interest-Points/survey/questions/answer/multipleshorttext/assets/demo/*.
    
    
*Custom themes are given without any warranty, implied or otherwise.*

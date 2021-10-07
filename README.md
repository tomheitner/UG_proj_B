# Project B
Created by Yahav Sasson and Tom Heitner

This code was meant to be used on Google Collaboratory. In order to run this code you need to have a Google Drive mounted on to the code (first code cell takes care of that, click the link, log in through your browser to the relevant Google account and follow the instructions that pop-up).

The drive should be set up with a the following:
* A folder named *pretrained_models* containing *.rar - an archive of a net that would be used in the code. The code is currently set up to classify shoes into two classes, but that is interchangeable.
* A folder named videos containing the input video (optional, if in the "breaking video into frames" cell <*use_drive*> is 'True', otherwise the video should be uploaded directly into the Collab session's files).
* A folder corresponding with the one training and testing DINO, filled with images such that the training set is in <*folder_name*>/training/* and the test set - <*folder_name*>/test/*.

The usage of these elements is spread out across the "Preparations" cells. 

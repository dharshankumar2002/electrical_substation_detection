# Electrical Substation Detection using Satellite Images

This work is done for a Hackathon conducted by ICETCI 2021 and ISRO <br>
https://competitions.codalab.org/competitions/32132#learn_the_details <br><br>
### Authors:
Dharshan Kumar K S <br>
Dev Khare <br>
Shraddha Seshadri <br>
Prasanth S N
<hr style=\"border:0.5px solid gray\"> </hr>

### Objective
Extracting Electrical Substations from high resolution satellite images

<p align="left">
  <img src="https://github.com/dharshankumar2002/electrical_substation_detection/blob/main/Output%20Images/output_pic1.png" width="500" alt="Example_output_image">
</p>

### Methodology
Used SegNet architecture for this image segmentation task. SegNet has 2 subparts in it - encoder and decoder. The encoder of SegNet is replaced with encoder of VGG-19 to get better results.

<p align="left">
  <img src="https://github.com/dharshankumar2002/electrical_substation_detection/blob/main/Output%20Images/methodology_pic1.png" width="500" alt="Example_output_image">
</p>

### Results
Reached 
<ul> 
<li> 97% training accuracy </li> 
<li> 0.689956 IoU on test images </li>
</ul>
Placed within the top 10 positions of the competition leaderboard
<img src="https://github.com/dharshankumar2002/electrical_substation_detection/blob/main/Output%20Images/result_pic1.png" width="600" alt="Example_output_image">
</p>


### kiddo: A robot for child education..  <br>

This code works with the vrep model 'kiddobot_dynamixel_real_v2.ttt' <br>
<img src='kiddobot_ws.png' width=40%>


### How to start
* Clone this repository.
* Install <a href="https://www.coppeliarobotics.com/downloads" target="_blank">VREP</a> EDU version. <br>
* run the "auto_kiddobot.ipynb" file.


### autokiddobot api <br>
Variables: <br>
    * x,y  : last pen coordinate. set by the get_current_xy() function.  <br>
    * xmax, ymax  : range in x axis and y axis. Fixed value.  (300, 200)<br>
Functions: <br>
    * start(): connect with VREP and start simulation. Make sure the model is loaded in VREP beforehand.<br>
    * get_current_xy()  : read pen position. returns (x,y)<br>
    * go_to_xy(x, y)  : move pen position to (x,y) position.<br>
    * pen_down() : as it said.<br>
    * pen_up() : as it said.<br>
    * close() : close simulation in VREP.<br><br>

Dept. of CSE,North East University Bangladesh. <br>

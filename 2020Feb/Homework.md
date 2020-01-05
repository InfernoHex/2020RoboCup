Let's start working on Resue Area, here's our brainstorm notes,


1) Try to avoid robot go out side of the Rescue Area
   Code Logic: if both side of the color sensors see white, then treat it as Outside, then start to retreat.
2) Try to detect the can
   * Option 1, go forward to center then start to spin around and try to find the can
   * Option 2, go forward a little bit (not to center yet), and start to spin around to try to find the can 
   * Option 3, stop at the entry of the rescue area, spin certain angle to try to detect the object
   * Option 4, once enter the resue area , try to go to the edge and try to find the can as well as find the orange area (lift and shift the can)
 3) Try to push the can out
   * how to find the correct angle to push ? Spin around and memorize the shortest distance?
   
Other possible strategy,
   * Sweeping the area, go quickly until almost out of the area, back , change direction and then go again.
   
 
 Home work,
 
 Think about above strategies, start to draft a logic to handle it. The logic can be the code or even text description about the logic.
 Next meeting, we will do many rounds of debug of the initial idea and come to some conclusion what direction we want to go.
 
 
 
 

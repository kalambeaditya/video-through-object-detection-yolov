# video-through-object-detection-yolov4
<h1> If you want to detect all the object then you should have to replace</h1><br>
            if label == "person":<br>
&nbsp;&nbsp;&nbsp;&nbsp;cv2.rectangle(img, (x,y), (x+w, y+h), color, 2)<br>
&nbsp;&nbsp;&nbsp;&nbsp;cv2.putText(img, label + " " + confidence, (x, y+20), font, 2, (255,255,255), 2)
                
   <br>             
by<br> 
this<br> 
&nbsp;&nbsp;&nbsp;&nbsp;cv2.rectangle(img, (x,y), (x+w, y+h), color, 2)<br> 
&nbsp;&nbsp;&nbsp;&nbsp;cv2.putText(img, label + " " + confidence, (x, y+20), font, 2, (255,255,255), 2)

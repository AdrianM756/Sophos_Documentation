## Create Application Traffic Shaping Policy

Navigate to ```PROTECT> Applications```. Under the ```Traffic shaping default``` tab, click on the filter icon on the ```Category name```.

<img width="174" height="186" alt="image" src="https://github.com/user-attachments/assets/ebe083b6-9d4d-41dc-a3e0-aba6d3f79fd3" />
<br>

<img width="1155" height="361" alt="image" src="https://github.com/user-attachments/assets/53988a3d-7013-4602-b469-08b622dc17c2" />
<br>
<br>

On the ```Application``` drop-down field, select ```Contains``` then type a value of ```360```. Click ```Apply``` once done.

<img width="604" height="168" alt="image" src="https://github.com/user-attachments/assets/eb3387b5-dbb1-4c8a-8bab-b3572ebe5792" />
<br>
<br>

Click on the edit icon for the ```Articulate 360```. On the ```Traffic shaping policy``` drop-down field, click ```Add``.

<img width="1097" height="111" alt="image" src="https://github.com/user-attachments/assets/4c63b356-744d-4eb3-9d72-469e0cfbf091" />
<br>

<img width="976" height="472" alt="image" src="https://github.com/user-attachments/assets/bc1e3669-6cb2-44d3-aabe-8ac688ea6f0c" />
<br>
<br>

We will the name this policy as ```Training Traffic Shaping Rule```. Set the ```Rule type``` as ```Guarantee```, set the ```Priority``` as ```2 - [Normmal]``` and set the ```Guarantee - limit``` to ```20480KB``` ```(2.5MB)``` upto ```102400KB``` ```(12.5MB)```. Once done, click on ```Save```.

<img width="1090" height="527" alt="image" src="https://github.com/user-attachments/assets/6acdc4d8-4e08-4268-ae34-b2734c87a679" />
<br>

<img width="728" height="522" alt="image" src="https://github.com/user-attachments/assets/ec51f6d3-16ea-4f9f-8c25-aa35f5ee5653" />
<br>
<br>

Next, navigate to ```PROTECT> Rules and policies```.

<img width="177" height="184" alt="image" src="https://github.com/user-attachments/assets/dc9f01a5-f4bd-469c-8ef4-138549c29364" />
<br>
<br>

Click the ```+``` symbol on the ```Traffic to WAN``` group.

<img width="408" height="481" alt="image" src="https://github.com/user-attachments/assets/34bec8f4-10d8-496e-9f45-dee05c6a1ff3" />
<br>
<br>

Click on the ```#Default_Network_Policy``` rule to edit.

<img width="216" height="54" alt="image" src="https://github.com/user-attachments/assets/6221ebc8-b07a-48ed-a693-13e4eff8d713" />
<br>
<br>

Scroll down to the ```Identity and control applications(App control)``` then check the box ```Apply application-based traffic shaping policy```. Click ```Save``` once done.

<img width="426" height="371" alt="image" src="https://github.com/user-attachments/assets/d4d81bc8-ab21-4b4c-b8eb-03f28e9622e4" />
<br>
<br>














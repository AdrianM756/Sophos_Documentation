## Setting up Security Heartbeat

For this demo, we will install sophos central on a server, enable synchronized security on Sophos Firewall, then modify a firewall rule to restrict network access based on the heartbeat status of the source devices.
<br>

First, Let's open up a browser and go to ```central.sophos.com``` then login using your sophos central account.

<img width="361" height="313" alt="image" src="https://github.com/user-attachments/assets/9ca40d85-1c51-46a2-9078-ab486dd53142" />
<br>
<br>

On the left-side menu on the dashboard on the Sophos Central Console, click on ```Protect Devices```.

<img width="260" height="581" alt="image" src="https://github.com/user-attachments/assets/8bcc7be4-4c06-4c97-ba83-5dbac5565404" />
<br>
<br>

Next, we will download the ```Complete Windows Server Installer```.

<img width="553" height="519" alt="image" src="https://github.com/user-attachments/assets/720f38b5-d865-4d8f-92b8-056d6b371dbe" />
<br>
<br>

Click the ```SophosSetup.exe```.

<img width="177" height="48" alt="image" src="https://github.com/user-attachments/assets/8ad4133c-4c97-478e-8ab5-32121d7ce228" />
<br>
<br>

Select ```Yes```.

<img width="324" height="241" alt="image" src="https://github.com/user-attachments/assets/36be0534-ee12-4e0f-8070-9404fa88e7f5" />
<br>
<br>

Click ```Install``` then ```Finish```.

<img width="512" height="357" alt="image" src="https://github.com/user-attachments/assets/5d3cd20f-4bb7-4b41-b9fe-0acb6445fb0e" />
<br>

<img width="512" height="362" alt="image" src="https://github.com/user-attachments/assets/bc40b2e7-c8e4-4543-a91d-5c28da4eb629" />
<br>
<br>

Go to the Sophos Firewall. on the left-side menu on the dashboard, navigate to ```SYSTEM> Sophos Central``` then click on ```Register```.

<img width="150" height="115" alt="image" src="https://github.com/user-attachments/assets/c4b79b24-88e8-4fd2-814d-b17c714b86d9" />
<br>

<img width="1159" height="114" alt="image" src="https://github.com/user-attachments/assets/93a5747f-9d8e-4290-a63b-6c722bbef034" />
<br>
<br>

You can register using OTP or using email address. For this demo, we will use OTP.

<img width="494" height="440" alt="image" src="https://github.com/user-attachments/assets/81046f3b-0969-4e4b-b53e-6626aa96042a" />
<br>
<br>

Go to ```Sophos Central Console``` and navigate to ```Firewall Management```.

<img width="209" height="450" alt="image" src="https://github.com/user-attachments/assets/17113eb7-ebb5-4edb-adb9-edf25179fb76" />
<br>
<br>

Under ```Manage```, select ```Firewalls```.

<img width="227" height="450" alt="image" src="https://github.com/user-attachments/assets/16ff375f-e166-4c23-815a-b69e90dfbcc7" />
<br>
<br>

Select ```Add Firewall```.

<img width="1177" height="309" alt="image" src="https://github.com/user-attachments/assets/bc21147c-d6b9-43cb-8e5a-6bc188487c83" />
<br>
<br>

Click on ```Join a firewall that is configured  or deployed```.

<img width="802" height="246" alt="image" src="https://github.com/user-attachments/assets/55ac3d56-df56-491c-9ca7-6a2185cc182e" />
<br>
<br>

We will then need to input the serial number of the firewall. Once done, click on ```Next```.

<img width="530" height="593" alt="image" src="https://github.com/user-attachments/assets/1fe9ed7a-59e7-4daf-b7b9-d37645fd9187" />
<br>
<br>

Click on ```Copy OTP and Finish``` and paste it to our Firewall. Once done, click on ```Register```.

<img width="548" height="286" alt="image" src="https://github.com/user-attachments/assets/0812c3ae-f9d7-4ef8-98cc-bba9f6d86ace" />
<br>

<img width="500" height="423" alt="image" src="https://github.com/user-attachments/assets/09ba8af5-bbf7-4aa6-9c26-0a6cbdddb5a1" />
<br>
<br>

Under ```Security Heartbeat```, select the ```Optional configurations```.

<img width="344" height="248" alt="image" src="https://github.com/user-attachments/assets/413a7744-b76e-48c7-bfd6-824084373a48" />
<br>
<br>

On this section, you can configure which zones you want to take action where an endpoint has a missing heartbeat. Click on ```Add new item```. Select ```LAN``` then ```Apply```. Once done, click ```Save Configurations```.

<img width="476" height="329" alt="image" src="https://github.com/user-attachments/assets/fb6c34fc-7080-4f49-be28-1b767870a432" />
<br>

<img width="477" height="316" alt="image" src="https://github.com/user-attachments/assets/d3cdc4ba-db32-44f3-9e45-a61c996d438e" />
<br>
<br>

Navigate to ```PROTECT> Rules and policies```.

<img width="176" height="190" alt="image" src="https://github.com/user-attachments/assets/27b51ea0-0c8e-40d7-a191-1c8413a6fadd" />
<br>
<br>

We will then need to click in order to edit the ```LAN to App Servers```.

<img width="941" height="79" alt="image" src="https://github.com/user-attachments/assets/8915edb9-a07d-4a18-b0b6-13770ad1bed1" />
<br>
<br>

Scroll down to ```Configure Synchronized Security Heartbeat```, then select ```GREEN``` for the ```Minimum source HB permitted```. Once done, click on ```Save```.

<img width="810" height="446" alt="image" src="https://github.com/user-attachments/assets/faab679b-261e-4c3d-a2c0-42248a89640f" />
<br>
<br>

Navigate to  ```MONITOR & ANALYZE> Control center```.

<img width="168" height="129" alt="image" src="https://github.com/user-attachments/assets/45f9fd3f-543b-4a08-b724-cd38f33b6eb1" />
<br>

In the ```Security Heartbeat``` widget, we can that the servers is connected to Sophos Firewall.

<img width="261" height="79" alt="image" src="https://github.com/user-attachments/assets/701a49de-6256-4c48-8b70-541ae0cd520d" />
<br>






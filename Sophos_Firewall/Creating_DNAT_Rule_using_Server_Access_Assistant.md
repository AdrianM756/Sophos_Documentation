## Creating DNAT Rule using Server Access Assistant

For this demo, we will publish a server using the Server Access Assistant wizard.
<br>

On the left-side menu on the dashboard, navigate to ```PROTECT> Rules and policies```.

<img width="158" height="178" alt="image" src="https://github.com/user-attachments/assets/849e3713-443b-47e2-aea7-5b13773d01fd" />
<br>
<br>

The Server Access Assistant can be both started on the ```Firewall rules``` or ```NAT rules``` tab. click on the ```Add firewall rule``` and select ```Server Accesss Assistant(DNAT)```.

<img width="1052" height="102" alt="image" src="https://github.com/user-attachments/assets/03dcd70f-5373-4659-a4d7-aa81d4420e24" />
<br>

<img width="259" height="119" alt="image" src="https://github.com/user-attachments/assets/dca32d3a-7759-47ed-a8f0-aa4192419849" />
<br>
<br>

On the first section, you will select where the  traffic will be sent. For this, We will be using an existing IP host then click on ```Next```.

<img width="1006" height="264" alt="image" src="https://github.com/user-attachments/assets/53f5d0f0-13b8-4b46-8a95-183ff645bf52" />
<br>

<img width="1013" height="266" alt="image" src="https://github.com/user-attachments/assets/875ba868-4c17-4a5d-924b-7ce6103e9a8c" />
<br>
<br>

On this tab, we will be selecting where to listen for the traffic to be translated. Once done, click on ```Next```.

<img width="1008" height="265" alt="image" src="https://github.com/user-attachments/assets/33e2ccdb-ba77-4c2e-a764-30bb6e710c9e" />
<br>

<img width="1013" height="267" alt="image" src="https://github.com/user-attachments/assets/ed244556-20ad-4bc9-9aae-74b8d8d3e82f" />
<br>
<br>

On this part, we will be selecting the service or port that will be translated. in this case, it will be ```RDP```.

<img width="1007" height="266" alt="image" src="https://github.com/user-attachments/assets/05628217-e8dc-4231-a42b-20112500aa44" />
<br>

<img width="1008" height="274" alt="image" src="https://github.com/user-attachments/assets/fd09c3cc-6eeb-44dc-8c52-9b3c9615e039" />
<br>
<br>

On this section, we can limit the allowed IP addresses that can access it on the External side. Click on ```Next``` once done.

<img width="1021" height="273" alt="image" src="https://github.com/user-attachments/assets/29e664a3-d51d-4fcb-8ee8-51f2bd92abfb" />
<br>
<br>

Review the summary then click on ```Save and finish```.

<img width="990" height="623" alt="image" src="https://github.com/user-attachments/assets/5740807b-1d88-4563-8002-76a40c96f0ad" />
<br>
<br>

If we go to the ```NAT rules``` tab, we  can see the DNAT rule that we've just created.

<img width="957" height="252" alt="image" src="https://github.com/user-attachments/assets/68976e44-70c3-4fc8-b05c-8e27d39db91a" />
<br>
<br>

Let's test it out. Open Remote Desktop Connection. Input the WAN IP ```10.1.1.100``` then click ```Connect```. Enter the username and password then cick ```OK```.

<img width="373" height="225" alt="image" src="https://github.com/user-attachments/assets/0a36f1d1-df61-4e15-be99-b8fb6258d71e" />
<br>
<br>

Click ```Yes``` to accept the certificate.

<img width="358" height="334" alt="image" src="https://github.com/user-attachments/assets/1953f65f-6304-4537-b323-cbaf77c107df" />
<br>
<br>

Wait for a few seconds, and you are now connected on the remote machine.



















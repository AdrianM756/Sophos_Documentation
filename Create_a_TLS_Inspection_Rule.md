## Create a TLS Inspection Rule

For this demo, we will create a TLS inspection rule that will decrypt traffic from the LAN zone to the WAN zone.
<br>

From the left-side of the menu on the dashboard, navigate to ```PROTECT> Rules and policies```.

<img width="139" height="168" alt="image" src="https://github.com/user-attachments/assets/4210e8f1-c1fe-4e83-a01e-cf90106b9151" />
<br>
<br>

Navigate to the ```SSL/TLS inspection rules``` tab then click on ```Add```.

<img width="1062" height="126" alt="image" src="https://github.com/user-attachments/assets/6395cb0f-7005-4eae-b2fd-14492d65af9c" />
<br>
<br>

Name the rule based on your desire. Under ```Decryption profile```, select ```Block insecure SSL```.

<img width="1108" height="344" alt="image" src="https://github.com/user-attachments/assets/fd120b70-09b0-44b1-8321-3a428f45ea4f" />
<br>
<br>


For the ```Source zones```, choose the ```LAN``` zone.

<img width="1089" height="197" alt="image" src="https://github.com/user-attachments/assets/a6aec6dd-42e5-473a-aeb0-6dea2beeab61" />
<br>
<br>

For the ```Destination zones``` choose the ```WAN``` zone. Click ```Save``` once done.

<img width="1104" height="481" alt="image" src="https://github.com/user-attachments/assets/cf06b62f-d6a1-4410-9858-f6b5b113db41" />
<br>
<br>

On the left-side menu on the dashboard, navigate to ```MONITOR & ANALYZE> Control center```.

<img width="167" height="103" alt="image" src="https://github.com/user-attachments/assets/4e858138-63ee-49d8-ad8e-4da15745ff92" />
<br>
<br>

In the ```SSL/TLS Connections``` located at the bottom-right, we can see that it is now being decrypted.

<img width="936" height="397" alt="image" src="https://github.com/user-attachments/assets/0eb5ce92-2a9d-44fc-a32b-020b298d9b3f" />
<br>
<br>







## Create an IPS Policy

For this demo, we will create a custom IPS policy and apply it to the web application firewall rule for the website.
<br>

Before We create an IPS Policy, Let us first enable it. On the left-side menu on the dsahboard, navigate to ```PROTECT> Intrusion prevention>IPS Policies```.

<img width="181" height="125" alt="image" src="https://github.com/user-attachments/assets/728ef4c7-d1f9-4fd6-b0f4-434cac2eb1fc" />
<br>
<br>

Enable the ```IPS protection```. This will download the IPS signatures to the Sophos Firewall. Once downloaded, it will be kept up-to-date. If IPS is disabled via the switch, the IPS signatures will be remove after 30 days unless it is enabled again.

<img width="472" height="91" alt="image" src="https://github.com/user-attachments/assets/ed2d7cf4-3b94-4101-967d-c2d9f6312d6c" />
<br>
<br>

Click ```Add```.

<img width="1172" height="341" alt="image" src="https://github.com/user-attachments/assets/707ca934-07ba-4552-b747-2c77eaf7ccbb" />
<br>
<br>

We will name it as ```Store Website```. Click ```Save``` once done.

<img width="671" height="323" alt="image" src="https://github.com/user-attachments/assets/46f59bf7-d439-4118-bf21-86ade5cc5731" />

<br>
<br>

Scroll down and click on the ```Store Website``` to edit the policy.

<img width="1127" height="55" alt="image" src="https://github.com/user-attachments/assets/fc774d1f-687b-4739-93a3-fc08bc778c5d" />
<br>
<br>

Click ```Add``` to create a new rule for the policy.

<img width="1119" height="445" alt="image" src="https://github.com/user-attachments/assets/d0136543-b72f-4fd9-a29c-3b7a17d22984" />
<br>
<br>

we will name it as ```Apache Linux Server Minor +```.

<img width="479" height="118" alt="image" src="https://github.com/user-attachments/assets/9b5e723c-f605-4a3a-9200-202527ad05a9" />
<br>
<br>

Click on the ```Category``` and select ```server-apache``` then click ```OK```.

<img width="203" height="299" alt="image" src="https://github.com/user-attachments/assets/6d084a30-4038-426b-9dae-4bcf763e114b" />
<br>
<br>

Under the ```Severity```, select 1-4 then click ```OK```.

<img width="200" height="259" alt="image" src="https://github.com/user-attachments/assets/1ac1f687-7d8c-452e-b2fc-06ab0bb49aee" />
<br>
<br>

Under the ```Platform``` select ```Linux``` then click ```OK```.

<img width="198" height="300" alt="image" src="https://github.com/user-attachments/assets/5b1ca1d0-7e59-4bdc-aa84-bac429b77ee0" />
<br>
<br>

Under the ```Target``` select ```Server``` then click ```OK```.

<img width="194" height="171" alt="image" src="https://github.com/user-attachments/assets/2e38de9a-bfb6-4523-b29d-d34621f3d658" />
<br>
<br>

Review it then click on ```Save```.

<img width="809" height="490" alt="image" src="https://github.com/user-attachments/assets/375a0f70-20ee-47cf-a35b-715c4bc53a29" />
<br>
<br>

Click ```Save```.

<img width="1195" height="507" alt="image" src="https://github.com/user-attachments/assets/77c75986-b2f3-4785-8fde-d341fa64a3f7" />
<br>
<br>

On the left-side menu on the dashboard, go to ```PROTECT> Rules and policies``` and expand the ```Traffic to DMZ``` using the ```+``` symbol.

<img width="191" height="193" alt="image" src="https://github.com/user-attachments/assets/20f74309-21c1-432b-b9d6-96e5f8990292" />
<br>
<br>

Click the ```Store Website``` to access the firewall rule.

<img width="318" height="160" alt="image" src="https://github.com/user-attachments/assets/b1a09f82-7e1a-4f05-8c7e-01a0c30e0486" />
<br>
<br>

Scroll down and click on the Intrusion Prevention drop-down field. Select ```Store Website``` then click on ```Save```.

<img width="1138" height="308" alt="image" src="https://github.com/user-attachments/assets/e193cc24-ab0b-4735-a89e-df466035c59a" />
<br>

<img width="365" height="422" alt="image" src="https://github.com/user-attachments/assets/082b478b-537f-4b4f-989f-e72076a0f71a" />
<br>

<img width="1144" height="405" alt="image" src="https://github.com/user-attachments/assets/52ec0e31-daab-4400-a8cb-35fe33d568d4" />
<br>
<br>













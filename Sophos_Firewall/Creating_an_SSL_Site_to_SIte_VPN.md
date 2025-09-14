## Creating an SSL Site to SIte VPN

For this demo, We will create an SSL Site-To-Site VPN between the London and New York Firewall

On the London Firewall, Navigate to ```CONFIGURE > Site-to-Site VPN```. Select the ```SSL VPN``` tab and on the ```Server``` section, click on ```Add```.

<img width="153" height="139" alt="image" src="https://github.com/user-attachments/assets/23cb03ed-0b4e-4516-a29f-58e2601c5827" />
<br>

<img width="1169" height="352" alt="image" src="https://github.com/user-attachments/assets/3c681722-58a5-4886-8e24-a6b20550e42d" />
<br>
<br>

We will then name this rule as ```LondonToNewYork```.

<img width="1115" height="269" alt="image" src="https://github.com/user-attachments/assets/07d08c70-753b-46f4-b06f-79cb72efae18" />
<br>

On the ```Local networks```, we will select the ```London LAN``` network. On the ```Remote networks```, we will select the ```NewYork``` network. Click ```Save``` once done.

<img width="1081" height="610" alt="image" src="https://github.com/user-attachments/assets/1312cf9e-e0d0-45bb-bc27-3a071b6dadf8" />
<br>
<br>

Click the Download icon for the ```LondonToNewYork``` connection.

<img width="1165" height="192" alt="image" src="https://github.com/user-attachments/assets/51429371-d0ca-48d5-b5c7-0ce2e0e0b70a" />
<br>
<br>

Check the ```Encrypt configuration file``` then input the password. Once done, click on ```Download```.

<img width="633" height="313" alt="image" src="https://github.com/user-attachments/assets/425e0e56-1489-4d02-9682-56c5f315a08f" />
<br>
<br>


Next, navigate to ```SYSTEM > Administration```. Go to the ```Device Access``` tab and check the box for the ```SSL VPN``` on the ```WAN``` column. Once done, click ```Apply```.

<img width="164" height="112" alt="image" src="https://github.com/user-attachments/assets/94d180df-1fec-427a-a85d-47a8f5a87c6a" />
<br>

<img width="1139" height="293" alt="image" src="https://github.com/user-attachments/assets/9ded49ac-a96f-4c2e-ba37-dde7ac90f3ed" />
<br>

<img width="1130" height="469" alt="image" src="https://github.com/user-attachments/assets/aa482b96-3a50-4a86-9d2c-2a022889c740" />
<br>
<br>

Click ```OK```.

<img width="542" height="87" alt="image" src="https://github.com/user-attachments/assets/04d73eca-bc40-44be-a53a-3c3a2b763e31" />
<br>
<br>

We will then need to go to the New York FIrewall. Navigate to ```CONFIGURE > Site-to-Site VPN```. Select the ```SSL VPN``` tab and on the ```Client``` section, click on ```Add```.

<img width="179" height="139" alt="image" src="https://github.com/user-attachments/assets/26b0ac05-efb4-4c70-90ef-a3b961cc7293" />
<br>

<img width="1202" height="577" alt="image" src="https://github.com/user-attachments/assets/36490c8c-5d21-4531-b975-776138b09885" />
<br>
<br>

We will name this as ```NewYorkToLondon```. In the ```Configuration file``` click on ```Choose file```.

<img width="1138" height="465" alt="image" src="https://github.com/user-attachments/assets/f93d8e57-1fb1-43cd-ac1c-c638248568ca" />
<br>

We will then need to select the ```server_LondonToNewYork.epc``` then click on ```Save```.

<img width="1070" height="596" alt="image" src="https://github.com/user-attachments/assets/b916044e-f4b5-4339-ac67-a728c8d59dfc" />
<br>
<b>

Go back to the London Firewall and navigate to ```PROTECT> Rules and policies```.

<img width="163" height="184" alt="image" src="https://github.com/user-attachments/assets/205e8d5c-e987-4c2d-9b8e-6159fd1e21ab" />
<br>

We will then add a new firewall rule.

<img width="1128" height="210" alt="image" src="https://github.com/user-attachments/assets/ee8c7967-c84e-46ff-9221-e1258ba0a490" />
<br>
<br>

We will then name this rule as ```To VPN``` and click the checkbox ```Log firewall traffic```.

<img width="413" height="239" alt="image" src="https://github.com/user-attachments/assets/b01667a5-6825-43bf-ada8-b90f95ef650d" />
<br>
<br>

For the ```Source zones``` we will choose ```LAN```

<img width="404" height="234" alt="image" src="https://github.com/user-attachments/assets/549a7ed6-697a-4eb6-880b-02349e1e6992" />
<br>
<br>

On the ```Destination zones``` we will choose ```VPN```. Click on ```Save``` once done.

<img width="552" height="522" alt="image" src="https://github.com/user-attachments/assets/263a45db-1931-4ef6-a7d2-655b784cf5af" />
<br>
<br>

We will then add another firewall rule and name it as ```From VPN``` and click the checkbox ```Log firewall traffic```.

<img width="954" height="202" alt="image" src="https://github.com/user-attachments/assets/c55093e9-f0a3-4d2e-9aeb-d1706cde286d" />
<br>

<img width="423" height="230" alt="image" src="https://github.com/user-attachments/assets/638eab8e-d58a-4b7f-8ddd-7a3356d77886" />
<br>
<br>

On the ```Source zones``` we will choose ```VPN```. Click on ```Save``` once done.

<img width="389" height="232" alt="image" src="https://github.com/user-attachments/assets/e6bec392-8ebe-4686-be1f-b91f7cdce179" />
<br>

On the ```Destination zones``` we will choose ```LAN```. Click on ```Save``` once done.

<img width="412" height="593" alt="image" src="https://github.com/user-attachments/assets/dde1b8cf-6cf8-4c3c-86b1-65b7674d434f" />
<br>
<br>












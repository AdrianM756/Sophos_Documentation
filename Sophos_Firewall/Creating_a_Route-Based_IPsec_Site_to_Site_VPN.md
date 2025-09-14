<img width="1015" height="303" alt="image" src="https://github.com/user-attachments/assets/7fb35903-e396-4512-bf3b-82f52c90de1e" />## Creating a Route-Based IPsec Site to Site VPN

For this demo, we will create a Route-Based IPsec site-to-site VPN between the London ang New York Firewall.
<br>

On the London Firewall, navigate to ```CONFIFURE > Site-to-site VPN```. On the ```IPsec connections```, click on ```Add```.

<img width="193" height="146" alt="image" src="https://github.com/user-attachments/assets/71e4d93a-f4ca-44e6-bb72-b5b489eef80a" />
<br>

<img width="1437" height="244" alt="image" src="https://github.com/user-attachments/assets/0500be81-f43b-4ef7-9b5c-e067c8cdad30" />
<br>
<br>

on the ```General Settings```, We will name it as ```NewYork```. For the ```Connection type```, we will select ```Tunnel interface``` and check the box ```Activate on save```.

<img width="1264" height="304" alt="image" src="https://github.com/user-attachments/assets/19e1a134-9d1c-47c1-8f7e-989589aefb38" />
<br>
<br>

On the ```Encrryption```, set the ```Authentication type``` to ````Preshared key```` then input and take note your desired password.

<img width="1015" height="303" alt="image" src="https://github.com/user-attachments/assets/db255954-2158-4640-bef1-ae8754acb407" />
<br>
<br>

On the ```Gateway settings```, Input the following:

<img width="982" height="651" alt="image" src="https://github.com/user-attachments/assets/472fba38-542e-42e7-bec3-44ef6f3f90e5" />
<br>
<br>

Click on ```Save``` once finish.
<br>
<br>

Click ```OK```.

<img width="712" height="197" alt="image" src="https://github.com/user-attachments/assets/ab2baa61-9c8e-419d-8029-744e32aede5a" />
<br>
<br>

A message will appear at the top.

<img width="676" height="164" alt="image" src="https://github.com/user-attachments/assets/6110c5bb-8552-4ea2-8f21-ee91718e6df9" />
<br>
<br>

Navigate to ```SYSTEM > Administration```. Go to the ```Device Access``` tab then check the ```IPsec``` box on the ```WAN``` column and the ```Ping/Ping6``` box on the ```VPN``` column.

<img width="191" height="164" alt="image" src="https://github.com/user-attachments/assets/7963e81d-988b-44c5-99c4-cfdb7fc17af5" />
<br>

<img width="1416" height="627" alt="image" src="https://github.com/user-attachments/assets/802a2310-48b8-49b2-967e-3020c1d4fc05" />
<br>
<br>

Once performed, click on ```Apply``` and ```OK```.

<img width="486" height="90" alt="image" src="https://github.com/user-attachments/assets/42a82f35-be76-48ec-a85f-fcdab91e0ae6" />
<br>
<br>

Navigate to ```CONFIGURE> Network```

<img width="185" height="149" alt="image" src="https://github.com/user-attachments/assets/093e6c5f-851c-4220-a24b-6db345748631" />
<br>
<br>

Expand the ```PortB```. We can see the tunnel interface that has been created. Click ```xfrm1```.

<img width="775" height="145" alt="image" src="https://github.com/user-attachments/assets/86b2efea-cbe1-4c63-bb57-ac6e0a94e1c0" />
<br>

We will then set the IP address to ```172.16.254.1/24```. Click ```Save``` once done. A message box will appear. Click on ```Update interface```.

<img width="1070" height="643" alt="image" src="https://github.com/user-attachments/assets/1ae44add-f5ce-4335-be61-29992902fd63" />
<br>

<img width="756" height="212" alt="image" src="https://github.com/user-attachments/assets/16c8be29-9c47-45fc-9034-9841cb82bb53" />
<br>
<br>

Navigate to ```CONFIGURE> Routing``` then go to ```Gateways``` tab and click ```Add```.

<img width="192" height="144" alt="image" src="https://github.com/user-attachments/assets/ac28b357-ed35-4eb5-bffd-d7f4798a3dfe" />
<br>

<img width="1426" height="173" alt="image" src="https://github.com/user-attachments/assets/4db0d592-a421-461a-92dc-a1952f4a1df6" />
<br>
<br>

Inpit the Following:

<img width="800" height="711" alt="image" src="https://github.com/user-attachments/assets/881c1d5a-37c6-4e5d-810f-f558322446a5" />
<br>

Click ```Save``` once done.
<br>
<br>

Go to the ```SD-WAN routes``` tab. We will then create a SD WAN route for traffic going to the New York network so it uses the IPsec tunnel. To do this, click on ```Add```.

<img width="1438" height="326" alt="image" src="https://github.com/user-attachments/assets/a1442920-84c8-4925-9db5-4a572aabde0e" />
<br>
<br>

We will name this as ```NewYork via IPsec``` then input the following:

<img width="874" height="706" alt="image" src="https://github.com/user-attachments/assets/e57facb3-1c1c-487a-b8c8-da4e8cf41b83" />
<br>

Once done, click ```Save```.
<br>
<br>

Next, go to ```PROTECT> Rules and policies```. We will then need to create a firewall rule to allow the traffic to and from New York over the VPN. Click ```Add firewall rule> New firewall rule```.

<img width="183" height="182" alt="image" src="https://github.com/user-attachments/assets/1ffe35bb-b55b-4e7e-ab02-32cbc3f24a8e" />
<br>

<img width="1207" height="140" alt="image" src="https://github.com/user-attachments/assets/590118b7-1adb-4d37-b9cb-77ea3fde71a8" />
<br>
<br>

We will name this rule as ```From NewYork to VPN``` and click the check box ```Log firewall traffic```.

<img width="508" height="243" alt="image" src="https://github.com/user-attachments/assets/62522efa-eb70-47ee-8c6e-85a6dd4c4f68" />
<br>
<br>

Next, copy and input the following. Once finished, click on ```Save```.

<img width="840" height="239" alt="image" src="https://github.com/user-attachments/assets/62e2e9df-bcdc-4409-a952-82aaea229979" />
<br>

<img width="846" height="254" alt="image" src="https://github.com/user-attachments/assets/559791bc-25f0-458c-a996-afad045d35b4" />
<br>
<br>

Go to the New York Firewall, navigate to ```CONFIFURE > Site-to-site VPN```. On the ```IPsec connections```, click on ```Add```. Copy and input the following then click on ```Save``` once finished.

<img width="193" height="146" alt="image" src="https://github.com/user-attachments/assets/71e4d93a-f4ca-44e6-bb72-b5b489eef80a" />
<br>

<img width="1169" height="651" alt="image" src="https://github.com/user-attachments/assets/ac0bab5b-cf29-401d-afea-dc1bd5a33875" />
<br>

<img width="1002" height="650" alt="image" src="https://github.com/user-attachments/assets/7aa326ff-dd8b-47bc-8a48-aadfce9b9d34" />
<br>
<br>

Click ```OK```.

<img width="710" height="195" alt="image" src="https://github.com/user-attachments/assets/724da388-d819-47d8-b0ae-066b47df8cd6" />
<br>
<br>

Navigate to ```CONFIGURE> Network```

<img width="185" height="149" alt="image" src="https://github.com/user-attachments/assets/093e6c5f-851c-4220-a24b-6db345748631" />
<br>
<br>

Expand the ```PortB```. We can see the tunnel interface that has been created. Click ```xfrm1```.

<img width="775" height="145" alt="image" src="https://github.com/user-attachments/assets/86b2efea-cbe1-4c63-bb57-ac6e0a94e1c0" />
<br>

We will then set the IP address to ```172.16.254.2/24```. Click ```Save``` once done.

<img width="1098" height="640" alt="image" src="https://github.com/user-attachments/assets/c7c63fca-6a16-4661-8339-46f73d7078d6" />
<br>
<br>

Click ```Update interface```.

<img width="752" height="210" alt="image" src="https://github.com/user-attachments/assets/f3fe1dda-a516-4799-8295-717b612e40c7" />
<br>
<br>

Navigate to ```CONFIGURE> Routing``` then go to ```Gateways``` tab and click ```Add```.

<img width="192" height="144" alt="image" src="https://github.com/user-attachments/assets/ac28b357-ed35-4eb5-bffd-d7f4798a3dfe" />
<br>

<img width="1426" height="173" alt="image" src="https://github.com/user-attachments/assets/4db0d592-a421-461a-92dc-a1952f4a1df6" />
<br>
<br>

Copy and input the following then click on ```Save``` once done.

<img width="868" height="706" alt="image" src="https://github.com/user-attachments/assets/d848fbdc-8586-463f-81ff-2a166ba4c2cb" />
<br>
<br>

Go to the ```SD-WAN routes``` tab. We will then create a SD WAN route for traffic going to the London network so it uses the IPsec tunnel. To do this, click on ```Add```.

<img width="1438" height="326" alt="image" src="https://github.com/user-attachments/assets/a1442920-84c8-4925-9db5-4a572aabde0e" />
<br>
<br>

Copy and input the following then click on ```Save``` once done.

<img width="850" height="647" alt="image" src="https://github.com/user-attachments/assets/1f41fc41-a457-43eb-89ec-a43cfc6e29ff" />
<br>

<img width="830" height="711" alt="image" src="https://github.com/user-attachments/assets/c7746039-9cee-46d9-9694-65507f83d596" />
<br>
<br>

Next, go to ```PROTECT> Rules and policies```. We can see the ```From London IPsec VPN``` rule.

<img width="183" height="182" alt="image" src="https://github.com/user-attachments/assets/1ffe35bb-b55b-4e7e-ab02-32cbc3f24a8e" />
<br>




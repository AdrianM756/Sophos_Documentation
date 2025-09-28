## Configure a remote access SSL VPN
<br>

For this demo, we will configure an SSL remote accesss VPN with one time password authentication on Sophos Firewall.
<br>

Navigate to ```CONFIGURE> Remote access VPN```.


<img width="155" height="133" alt="image" src="https://github.com/user-attachments/assets/b99a2eb8-19fe-49cc-b8b3-82a2b951b7ab" />
<br>

Go to the ```SSL VPN``` tab then click on ```Add```.

<img width="1433" height="204" alt="image" src="https://github.com/user-attachments/assets/475c1b2a-8ae8-466b-9442-ce21ae3f88e7" />
<br>

Review the global settings then click on ```Next```.

<img width="802" height="401" alt="image" src="https://github.com/user-attachments/assets/f3dc71ca-aec1-4847-911a-3f68061ba713" />
<br>

We will name this connection as ```Sales``` then click on ```Next```.

<img width="800" height="373" alt="image" src="https://github.com/user-attachments/assets/1aa068c1-7da9-4b40-9ab6-8d73c7789d95" />
<br>

Under the ```Users and groups```, add the ```Sales``` then click on ```Next```.

<img width="811" height="359" alt="image" src="https://github.com/user-attachments/assets/ba2409df-c76d-4f39-b84a-25bae37d0944" />
<br>

Select ```Same as firewall``` then click on ```Next```.

<img width="806" height="633" alt="image" src="https://github.com/user-attachments/assets/4594c0a0-782e-4889-a547-4f585ddd7213" />
<br>

Under the ```Access to resources```, select and add the ```Intranet-172-25-25``` and ```SecurityHeartbeat_over_VPN``` then click on ```Next```.

<img width="803" height="361" alt="image" src="https://github.com/user-attachments/assets/118383fe-afb1-4ddf-857c-0e14faf94392" />
<br>

Select ```Use VPN for traffic to resources``` then click on ```Next```.

<img width="798" height="356" alt="image" src="https://github.com/user-attachments/assets/04252045-ea32-407c-bfe2-804606444168" />
<br>

Review the zones that the VPN portal is accessible from, then click on ```Next```.

<img width="802" height="438" alt="image" src="https://github.com/user-attachments/assets/fd42c917-0d81-4209-807a-e2d8db704fbe" />
<br>

Review the zones that the SSL VPN is accessible from, then click on ```Next```.

<img width="797" height="404" alt="image" src="https://github.com/user-attachments/assets/0b8909ba-aff1-4811-ba64-87b558df234a" />
<br>

Review the settings the click on ```Finish```.

<img width="809" height="476" alt="image" src="https://github.com/user-attachments/assets/b1499e5b-f14b-4f23-bdc2-3344eccb11aa" />
<br>

Click ```SSL VPN global settings```

<img width="542" height="222" alt="image" src="https://github.com/user-attachments/assets/3c30f903-d35c-4d23-b1fc-65d910558235" />
<br>

For the ```IPv4 DNS```, input ```172.16.16.16``` then click ```Apply```.

<img width="1082" height="463" alt="image" src="https://github.com/user-attachments/assets/f2c63353-6514-443d-a776-b2baa31b8c27" />
<br>

A message box will appear. Click on ```OK```.

<img width="525" height="141" alt="image" src="https://github.com/user-attachments/assets/16cbbf1b-c073-4191-9a21-e04991c3fd5a" />
<br>

Next, navigate to  ```SYSTEM > Administration > Device Access```, then select the ```DNS``` in the VPN zone then click on ```Apply```.

<img width="154" height="146" alt="image" src="https://github.com/user-attachments/assets/8c86de6c-afe4-4522-9129-c569649abc06" />
<br>

<img width="1402" height="612" alt="image" src="https://github.com/user-attachments/assets/2044a3be-7573-4c35-87be-4277c842925a" />
<br>

A message box will appear. Click on ```OK```.

<img width="538" height="84" alt="image" src="https://github.com/user-attachments/assets/0469dd96-be5c-47b7-9aa6-45aab9bfab53" />
<br>

Next, Go to ```CONFIGURE > Authentication > Services```, scroll down in the ```SSL VPN authentication methods```, select ```Same as firewall```, then click ```Apply```.

<img width="162" height="151" alt="image" src="https://github.com/user-attachments/assets/9c6f0899-01be-470a-a843-e87540afc6a0" />
<br>

<img width="649" height="582" alt="image" src="https://github.com/user-attachments/assets/e4a73e65-37e0-46d9-a575-d0e9730d426c" />
<br>

A message box will appear. Click on ```OK```.
<img width="523" height="85" alt="image" src="https://github.com/user-attachments/assets/714e34f2-fce6-4aa7-b90a-e3f358eee811" />

Next, navigate to the ```Multi-factor authentication``` tab. On the ```Require MFA for:``` select the ```SSL VPN remote access``` then click ```Apply```.

<img width="1076" height="605" alt="image" src="https://github.com/user-attachments/assets/f8546842-28ae-4eb8-9adf-bd6eeaa7cc59" />
<br>

Next, login to your Sophos Connect client and select ```Download for windows```.

<img width="446" height="239" alt="image" src="https://github.com/user-attachments/assets/26af3e53-2bc1-48c8-89ca-37dfb2b26960" />
<br>

After downloading, click on the top right off the browser.

<img width="347" height="50" alt="image" src="https://github.com/user-attachments/assets/aa173d77-3441-4abd-a59b-791362384e95" />
<br>

Check the terms and condition then click ```Install```.

<img width="471" height="361" alt="image" src="https://github.com/user-attachments/assets/dbc9fd12-04c0-4786-9445-1463aaf7c004" />
<br>

Click the check box then select ```Finish```.

<img width="477" height="355" alt="image" src="https://github.com/user-attachments/assets/1b7d4f4e-260c-490a-9753-1c4c0cd76029" />
<br>

Under the ```VPN Configuraion``` section, click ```Download for Windows, MacOS, Linux```.

<img width="641" height="362" alt="image" src="https://github.com/user-attachments/assets/c108f430-ab25-4120-935b-9b165143407b" />
<br>

After downloading, click on the top right off the browser.

<img width="314" height="50" alt="image" src="https://github.com/user-attachments/assets/7b0eafec-de97-48a9-9b6e-47ec258757f7" />
<br>


Click on the Sophos Connect icon located on the lower-right corner then click on ```Connect```.

<img width="589" height="619" alt="image" src="https://github.com/user-attachments/assets/f3f2a29d-7d5c-4080-b9ed-5d7cd3446ea9" />
<br>

Input your username and password including the token. Once done, we can see that it is now connected.

<img width="1032" height="427" alt="image" src="https://github.com/user-attachments/assets/b7686d30-6fa4-40eb-b5c6-536aad4ac440" />
<br>

<img width="560" height="290" alt="image" src="https://github.com/user-attachments/assets/abcf0998-aa4f-4d0b-a420-adc1c999e909" />
<br>

Let's then open cmd and ping/tracert the ```lon-intranet.ad.trainingdemo.xyz```. We can see on the image below that it is now reachable.

<img width="963" height="254" alt="image" src="https://github.com/user-attachments/assets/f6f20442-ce3c-4651-99fa-40174f057f02" />
<br>







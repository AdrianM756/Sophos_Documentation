## Sophos DNS Protection

From the ```Sophos Central Console```, under the ```My Products``` field, select ```DNS Protection> Dashboard```.

<img width="1177" height="722" alt="image" src="https://github.com/user-attachments/assets/191a55e0-351a-4331-84d1-0868b0544b36" />
<br>
<br>

Click on ```Add locations```.

<img width="1299" height="242" alt="image" src="https://github.com/user-attachments/assets/5141c6aa-7628-47b5-93b5-5c569b508e8b" />
<br>
<br>

A location is one or more IP public addresses and FQDNs that DNS requests will be made from. Click ```Add```.

<img width="1238" height="331" alt="image" src="https://github.com/user-attachments/assets/467d9191-be33-4653-a8e2-f0ef9e8364bd" />
<br>
<br>

For the ```Location name```, we will name it as ```demo```. For the ```IPv4 addresses or FQDNs```, type ```demo.trainingdemo.xyz```. Click ```Save``` once done.

<img width="487" height="617" alt="image" src="https://github.com/user-attachments/assets/b45a72cb-9113-4e4e-87a7-8906f84c5c95" />
<br>
<br>

Go to ```Dashboard``` and click on ```Set up network```.

<img width="262" height="257" alt="image" src="https://github.com/user-attachments/assets/1cf8bbae-75f7-4340-89a9-a90a3e6d9f82" />
<br>

<img width="1295" height="244" alt="image" src="https://github.com/user-attachments/assets/b80a22b3-1e15-41a7-be11-a32be10ef5cf" />
<br>
<br>

Copy the 2 IP Addresses and Paste it on the DNS server on the Windows Client/user device.

<img width="1125" height="458" alt="image" src="https://github.com/user-attachments/assets/3a9e35ec-02a0-4a4d-a7fe-ef456597013c" />
<br>

<img width="329" height="564" alt="image" src="https://github.com/user-attachments/assets/43ae64a5-a379-4338-a059-8933666a6dd2" />
<br>
<br>

On the ```File Explorer> Downloads```, You can see a file named ```certificate.pem```. Rename the file as ```certificate.cer``` then click ```Yes```.

<img width="534" height="155" alt="image" src="https://github.com/user-attachments/assets/039785c6-87fc-459a-b40e-ae787cde054c" />
<br>
<br>

Double-click on ```certificate.cer``` then click ```Install Certificates```.

<img width="343" height="438" alt="image" src="https://github.com/user-attachments/assets/b9abe67e-2a1d-4786-832c-a21a67428741" />
<br>
<br>

A pop-up wizard will appear. Select ```Local Machine``` then click on ```Next```.

<img width="457" height="422" alt="image" src="https://github.com/user-attachments/assets/a9bec57c-467a-4c26-8033-29cf7c8476b9" />
<br>
<br>

Select ```Place all certificates in the following store```. Click on ```Browse``` then look for ```Trusted Root Certification Authorities```. Once done, click on ```Next```.

<img width="454" height="419" alt="image" src="https://github.com/user-attachments/assets/e0499a48-0ae5-4d8e-af0e-89c8045d2688" />
<br>
<br>

Review the following then click on ```Finish```.

<img width="452" height="419" alt="image" src="https://github.com/user-attachments/assets/cc68c1c3-de1a-4444-a29c-9702c366e8e0" />
<br>
<br>

Open up your browser then type ```https://dns.access.sophos.com```. This domain is only resolved by Sophos DNS Protection. So if the devices are not using the Sophos DNS Protection servers, they will not be able to access this page.

<img width="1245" height="564" alt="image" src="https://github.com/user-attachments/assets/d5e4ca10-76f5-4ea8-83da-7a5761e63e14" />
<br>
<br>

Go back to the ```Sophos Central Console``` page, then click on ```Dashboard```.

<img width="275" height="300" alt="image" src="https://github.com/user-attachments/assets/b24831d3-1d6a-426e-bf95-bee25ce3e5a7" />
<br>
<br>

Next, click on ```Create policy``` then select ```Add policy```.

<img width="1300" height="266" alt="image" src="https://github.com/user-attachments/assets/643428a1-fa14-4d79-b12b-475c00d5b0d6" />
<br>

<img width="972" height="281" alt="image" src="https://github.com/user-attachments/assets/9e6e8ae4-e555-421f-a289-4db3ae5db654" />
<br>
<br>

We will name it as ```Demo policy```. We will move the location of ```Demo``` to the selected panel using the blue button.

<img width="1104" height="691" alt="image" src="https://github.com/user-attachments/assets/23238e38-a8d9-4ff9-ad42-0e51d2255357" />
<br>

<img width="1083" height="518" alt="image" src="https://github.com/user-attachments/assets/191b1ad8-5cfe-47e4-8daf-0b559d847dec" />
<br>
<br>

Next, click on the ```Settings```. On the ```Filtering by web category```, click on drop-down then select ```Business only```. Once done, click ```Save```.

<img width="1322" height="689" alt="image" src="https://github.com/user-attachments/assets/58d261de-c7d7-4baf-8d53-9600aabaf5d8" />
<br>
<br>

Go back to the ```Dashboard```. We can that we've successfully setup DNS Protection.

<img width="275" height="300" alt="image" src="https://github.com/user-attachments/assets/b24831d3-1d6a-426e-bf95-bee25ce3e5a7" />
<br>

<img width="1321" height="442" alt="image" src="https://github.com/user-attachments/assets/8e2c90c6-1489-4c6a-a929-9f527accc32b" />
<br>
<br>












<br>

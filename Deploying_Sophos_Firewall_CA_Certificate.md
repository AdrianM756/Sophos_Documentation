## Deploying Sophos Firewall CA Certificate

For this demo, we will be deploying Sophos Firewall Certificate authorities using [Active Directory Group Policy(GPO)](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/manage/group-policy/group-policy-overview).
<br>

On the left-side menu on the dashboard, navigate to ```SYSTEM> Certificates```.

<img width="171" height="128" alt="image" src="https://github.com/user-attachments/assets/0df4fcbf-1181-4f2e-b97d-d3f564358ed2" />
<br>
<br>

Go to the ```Certificate Authorities``` tab and click on ```Download icon``` for the ```Default``` certificate authority. This is used for signing certificates that is generated on the firewall. For example, for the WebAdmin.

<img width="1052" height="209" alt="image" src="https://github.com/user-attachments/assets/437c7564-3a63-46af-a4c9-f9feb798dc8f" />
<br>
<br>

Click on ```OK```.

<img width="314" height="217" alt="image" src="https://github.com/user-attachments/assets/0d728ab2-d48a-4ab7-a1ea-60207a9d06d3" />
<br>
<br>

Click the ```Download icon``` on the ```SecurityAppliance_SSL_CA```. This is use to sign certificates generated for TLS inspection.

<img width="1029" height="65" alt="image" src="https://github.com/user-attachments/assets/26a50524-90b4-47f0-b77f-d22ec710ba27" />
<br>
<br>

Click on ```OK```.

<img width="313" height="218" alt="image" src="https://github.com/user-attachments/assets/04dfb266-4a82-442d-8a04-9b99d3c0ee95" />
<br>
<br>

Open up File Explorer and navigate to the downloads. Noted that windows does not have a file association for ```.pem``` files so we need to rename to ```.cer```.
<br>
<br>

We will then need to extract the ```.tar``` for our the default CA. After extracting, rename it to ```.cer``` extension.
<br>
<br>

Next, navigate to ```Windows Administrative Tools> Group Policy Management``` and right click on ```Default Domain Policy``` and select ```Edit```.

<img width="189" height="41" alt="image" src="https://github.com/user-attachments/assets/e7f46d9c-5f50-495f-833d-be151e3c22fc" />
<br>

<img width="204" height="85" alt="image" src="https://github.com/user-attachments/assets/db545d12-757c-4ae7-8c6f-d3febe57c46f" />
<br>
<br>

Navigate to ```Computer Configuration> Policies> Windows Settings> Security Settings> Public Key Policies``` and right-click on the ```Trusted Root Certification Authorities``` and select ```import```.

<img width="171" height="199" alt="image" src="https://github.com/user-attachments/assets/28cbbe85-d910-4c05-b335-2391e103eb10" />
<br>

<img width="184" height="119" alt="image" src="https://github.com/user-attachments/assets/b7d91ae3-3d0e-412e-b055-853a33407241" />
<br>
<br>

A pop-up message will appear. click on ```Next```.

<img width="488" height="470" alt="image" src="https://github.com/user-attachments/assets/ae29e7f7-2de0-4559-a34d-acc050e16a9c" />
<br>
<br>

Click on ```Browse``` and select the ```SecurityAppliance_SSL_CA```.

<img width="491" height="472" alt="image" src="https://github.com/user-attachments/assets/ea7dca4d-e4a9-4b47-b111-0aa1d7b214bb" />
<br>

<img width="748" height="426" alt="image" src="https://github.com/user-attachments/assets/1d6496a9-3317-4154-b32c-3e5ef86903e2" />
<br>
<br>

Click on ```Next```.

<img width="492" height="471" alt="image" src="https://github.com/user-attachments/assets/b6852043-37f4-46e8-a687-8e2bfd01d740" />
<br>

<img width="492" height="470" alt="image" src="https://github.com/user-attachments/assets/dd2e1adc-87af-4d18-a0bf-11f59f919235" />
<br>
<br>

Then click on ```Finish```.

<img width="494" height="471" alt="image" src="https://github.com/user-attachments/assets/db965d02-8824-435e-8bdb-df811d4a31b9" />
<br>
<br>

When you click on the ```Trusted Root Certification Authorities```, you can see all the available certificates.

<img width="373" height="68" alt="image" src="https://github.com/user-attachments/assets/d2dd2dfe-3dbd-49fe-b590-928c8626257c" />
<br>
<br>











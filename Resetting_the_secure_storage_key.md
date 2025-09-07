The [secure storage master key](https://docs.sophos.com/nsg/sophos-firewall/20.0/Help/en-us/webhelp/onlinehelp/AdministratorHelp/BackupAndFirmware/BackupAndRestore/BackupAndRestoreSSMK/index.html) enhances the security of account data stored on the Sophos Firewall. It encrypts critical information like passwords, secrets, and cryptographic keys to safeguard against unauthorized access. Once the master key is set up, it can be reset via the CLI using the designated command.
<br>

The secure storage master key **can only be reset** using the default super administrator account.

To reset the secure storage master key, do as follows:
<br>

Enter the default admin account's password.
```
System Configuration

1.  Set Password for User Admin
2.  Set System Date
3.  Set Email ID for system notification
4.  Reset Default Web Admin Certificate
5.  Reset secure storage master key
0.  Exit

Select Menu Number [0-5]: 5
Enter the default admin account password:
```
<br>

Enter a new secure storage key.
```
Enter a new key that satisfies the following requirements:
- Minimum 12 characters
- An uppercase letter
- A lowercase letter
- A number (0-9)
- A special character (!#$%&()*+,-./:;<=>?@[]^_`{|}~)
New secure storage key:
```
<br>

Reenter the new key to confirm.
```
To confirm, reenter the new key:
```
<br>

The secure storage master key is reset.
```
Secure storage master key has been reset.
```
<br>






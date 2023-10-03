### This is a fork of Python3 password decryption tool for the McAfee **SiteList.xml** file.

The script is readjusted to work with newest python3 on Kali Linux.

Make sure you have the `pycryptodome` library installed. `pycryptodome` is a drop-in replacement for the PyCrypto library. 
You can install it using pip3:

```
pip3 install pycryptodome
```

 Original author:
- Author:  jerome.nokin@gmail.com
- Blog:  http://funoverip.net
- Date:  Feb 10 2016

### References:

- https://funoverip.net/2016/02/mcafee-sitelist-xml-password-decryption/
- https://www.reddit.com/r/netsec/comments/43mni7/mcafee_privileged_sitelistxml_leads_to_active/
- https://github.com/tfairane/HackStory/blob/master/McAfeePrivesc.md
- https://www.syss.de/fileadmin/dokumente/Publikationen/2011/SySS_2011_Deeg_Privilege_Escalation_via_Antivirus_Software.pdf

### Example usage:

```
./mcafee_sitelist_pwd_decrypt.py jWbTyS7BL1Hj7PkO5Di/QhhYmcGj5cOoZ2OkDTrFXsR/abAFPM9B3Q==
Crypted password   : jWbTyS7BL1Hj7PkO5Di/QhhYmcGj5cOoZ2OkDTrFXsR/abAFPM9B3Q==
Decrypted password : MyStrongPassword!
```


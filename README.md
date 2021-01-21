Experimental environment: win10 x64      
Software official website:https://www.jiangmin.com/PC/207.html   
Software version:16.0.13.301   
Affected Component: KVSrvXP.exe   
  
Jiangmin Technology Antivirus can be activated under ordinary users, but cannot open the trusted zone.    

However, when I copy the sample, the anti-virus software will pop up a dialog box when killing the sample. I can restore the sample from this dialog box.  

In addition to this recovery method, there is another recovery method. After the sample file is restored, select the scan file and restore it from the scan window.  

However, these recovery methods did not determine the file reparse point, nor did they use the simulation token, nor did they determine whether the target file has write permissions for the current user.  

I can revert to C:\Windows\system32 to achieve local privilege escalation  

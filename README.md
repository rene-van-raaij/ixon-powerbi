# IXON Power BI Template - Account Analysis

This is a Power BI Template to analyze your account data.

![Screenshot IXON Power BI Template Account Analysis](https://user-images.githubusercontent.com/94700064/143576062-5902f4c3-32d9-44db-bfa9-ca6f5ef8215f.png)

## Getting started
Download the file 'IXON Account analysis.pbit' and open it in Power BI Desktop.
Power BI will ask for some parameters to enter.

### Default values for the parameters
**Email address**           : Email adress which is assigned to the IXON Cloud Portal; :warning: See Warning note

**One Time Password (OTP)** : When you have 2 factor authenticaition enabled, fill in the OTP; if 2FA is disabled, leave this field blank

**Password**                : Password that belongs to the e-mail address; :warning: See warning note

**Api-Version**             : 2

**Api-Application**         :
```
hwcvO13tCdK1
```
**PageSize**                : 1000



![image](https://user-images.githubusercontent.com/94700064/143577365-f58ff15b-37d2-4464-a3c0-9b82bc8ce4e7.png)


### :warning: Warning note
Please be aware of the fact that the parameters, including Email address and Password, will be loaded/saved in the Power BI report. In case of sharing the (saved) Power BI report to others, your credentials are available for the recipients to see.

# CVE {Code} - classroombookings Cross Site Scripting (XSS) at create and edit session page via Administrator Dashboard

> CVE Description
	Insufficient validation on session add/edit page leads to cross-site-scripting at the Administrator Dashboard

**Affected Project**: classroombookings

**Official Website**:  https://www.classroombookings.com/

**Version**: 2.8.7

**Fixed Version**: 

**Affected Endpoint**:  https://site/sessions

**Affected Parameter**: N/A

## Demonstration

Step 1: Place the XSS payload at the session name field and save (Administrator)
![image](https://github.com/user-attachments/assets/0584886d-cb13-4090-8873-1fa05635d2b9)


Step 2: Trigger the XSS by visiting the booking page as a normal user or administrator
![image](https://github.com/user-attachments/assets/713c9586-d4a8-4709-a42b-06daafeb9e31)



Disclaimer: The developer or maintainer of this project has been notified of this vulnerability through this report.

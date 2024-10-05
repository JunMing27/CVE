# CVE {Code} - classroombookings Cross Site Scripting (XSS) at custom field

> CVE Description

**Affected Project**: classroombookings

**Official Website**:  https://www.classroombookings.com/

**Version**: 2.14.0.

**Affected Endpoint**:  https://site/rooms/fields

**Affected Parameter**: N/A

## Demonstration

Step 1: Place the XSS payload at the name field
![image](https://github.com/user-attachments/assets/71a6b61b-e654-48f6-b35e-606620217c6e)

Step 2: Trigger the XSS by clicking any room at https://site/rooms
![image](https://github.com/user-attachments/assets/7cb74187-763d-4e48-a8d4-334b9b30f0f9)
![image](https://github.com/user-attachments/assets/15c9e874-5a64-4c58-b6d5-0baa0180ba5d)

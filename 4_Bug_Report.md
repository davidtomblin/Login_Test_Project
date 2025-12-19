\# Bug Report: Login Button Enabled with Incomplete Fields



\## Project

Swag Labs Login Functionality



\## Reported By

David Tomblin



\## Date

12/19/2025



\## Environment

\- \*\*Browser:\*\* Chrome (latest version)  

\- \*\*OS:\*\* Windows 11  

\- \*\*URL:\*\* https://www.saucedemo.com



\## Description

The login button remains enabled if (username or password) are filled or not. The button should be disabled until both fields have input to prevent incomplete login attempts.



\## Steps to Reproduce

1\. Navigate to https://www.saucedemo.com 

2\. Observe the login button 

3\. Enter only the username: `standard\_user`  

4\. Observe the login button (it remains enabled)  

5\. Clear the username and enter only the password: `secret\_sauce`  

6\. Observe the login button (it remains enabled)



\## Expected Result

The login button should remain disabled until both the username and password fields are filled.



\## Actual Result

The login button stays enables if there are inputs in username and password or not.



\## Severity

Low — could lead to user confusion or unnecessary failed login attempts.



\##Screenshots

Bug\_Report\_TC007\_Screenshot.png



\## Notes / Recommendations

Consider disabling the login button until both fields have valid input to prevent unnecessary login attempts.




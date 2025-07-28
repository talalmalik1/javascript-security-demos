## Stored Cross Site Scripting (XSS) 

An attack where a malicious script is stored on the website's database and is executed whenever a user accesses the affected page. 

## How to check vulnerability?
1. Open the vulnerability.html file in a browser (e.g., Chrome).
2. Enter a script as a comment like: "<script>alert('XSS')</script>"
3. Upon pressing Enter, the script is saved in localStorage.
4. The script runs whenever the page is refreshed. Thus, it is persistently stored and executed whenever a user accesses this page. 

## How to fix the vulnerability?
1. Open the fixed.html file in a browser.
2. Enter a script as a comment like: "<script>alert('XSS')</script>"
3. This time, the script appears as text and does not execute.

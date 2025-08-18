## Reflected Cross Site Scripting (XSS)

An attack where malicious scripts are injected into a website through user input and then reflected back to the user's browser in the server's response.

## How to check vulnerability?
1. Open the vulnerable.html file in a browser (e.g., Chrome).
2. In the address bar, enter a query string like: "file:/path/to/vulnerable.html?name=<script>alert('XSS')</script>".
3. You would get an alert.
4. The script is reflected back into the page and executed.

## How to fix vulnerability?
1. Open the fixed.html file in a browser.
2. In the address bar, enter a query string like: "file:/path/to/fixed.html?name=<script>alert('XSS')</script>".
3. The script would appear as text and does not execute.

# chrome-optimizely-goals

## Roadmap
- [ ] load humane.js
- [ ] update permissions to only listen for logs.optimizely xhr calls
- [ ] onCompleted pop a humane.js alert in the active tab for the `n` and `r` query params 
- [ ] toggle alerts on / off via icon state similar to how Google Analytics Debugger can toggle on/off

# Original AJAX Debugger Readme
AJAX Debugger will log all AJAX (XMLHttpRequest) activity to Chrome's Developer Tools Console. This allows developers to easily see top-level request info, like the HTTP status, response time, and size. Click the URL to open the AJAX call in a new tab, including all the inputs, making debugging much easier. You can even drill down to see all the low-level request details including the HTTP header information.

Logged data includes:
* File called  
* Response Status  
* Response Time  
* Response Size  
* AJAX source link with all input params  
* Object containing all request and response details  
* Response content (optional)  
* Warning if response takes longer than set time


Logo & promo design by [Andy Merskin](http://www.AndyMerskin.com)

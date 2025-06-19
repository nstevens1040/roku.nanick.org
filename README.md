# [roku.nanick.org](https://roku.nanick.org)
A webpage that sends keyboard input to your Roku which allows for easier typing and navigation within the Roku UI.

---
My Roku's URL is hard coded in the JavaScript. If you want to use this, then you'll need to replace  
```js
var baseuri = "https://rokustick4k.nanicklocal.hopto.org"
```
with either a URL that your Roku can be reached at or your Roku's IP address. I also had to use an nginx proxy_pass in order to get this to work with a hostname.  

---
If you've ever been faced with a non-qwerty on-screen keyboard and nothing but a remote equipped with arrows and an 'OK' button, then you know that it feels like it takes 15 minutes <i>each</i> time you type your email address to authenticate into a single streaming platform.  
  
You can use this webpage to, for example, enable you to use your laptop keyboard to type your login credentials for the streaming platforms that you use. For me this made the process roughly 12 times faster.  

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

---
## Key and Function map  
  
<table id="table1">
    <tr>
        <td style="border-left: 2px solid blue; border-top-left-radius: 0.5em;" class="head">Key</td>
        <td style="border-top-right-radius: 0.5em;" class="head">Function</td>
        <td style="border-top-left-radius: 0.5em; border-left: 2px solid blue;" class="head">Key</td>
        <td class="head" style="border-top-right-radius: 0.5em;">Function</td>
    </tr>
    <tr>
        <td style="border-left: 2px solid blue;" class="cell"><kbd class="keyboard-key nowrap">&uarr;</kbd></td>
        <td class="cell">Navigate up</td>
        <td style="border-left: 2px solid blue;" class="cell"><kbd class="keyboard-key nowrap">Backspace</kbd></td>
        <td class="cell">Backspace</td>
    </tr>
    <tr>
        <td style="border-left: 2px solid blue;" class="cell"><kbd class="keyboard-key nowrap">&larr;</kbd></td>
        <td class="cell">Navigate left</td>
        <td style="border-left: 2px solid blue;" class="cell">
            <kbd class="keyboard-key nowrap">Alt</kbd> + <kbd class="keyboard-key nowrap">H</kbd>
        </td>
        <td class="cell">Home</td>
    </tr>
    <tr>
        <td style="border-left: 2px solid blue;" class="cell"><kbd class="keyboard-key nowrap">&darr;</kbd></td>
        <td class="cell">Navigate down</td>
        <td style="border-left: 2px solid blue;" class="cell">
            <kbd class="keyboard-key nowrap">Esc</kbd>
        </td>
        <td class="cell">Navigate back</td>
    </tr>
    <tr>
        <td style="border-left: 2px solid blue;" class="cell"><kbd class="keyboard-key nowrap">&rarr;</kbd></td>
        <td class="cell">Navigate right</td>
        <td style="border-left: 2px solid blue;" class="cell">
            <kbd class="keyboard-key nowrap">Cntrl</kbd> + <kbd class="keyboard-key nowrap">Space</kbd>
        </td>
        <td class="cell">Pause / Play</td>
    </tr>
    <tr>
        <td style="border-left: 2px solid blue;" class="cell">
            <kbd class="keyboard-key nowrap">Enter</kbd>
        </td>
        <td class="cell">Select</td>
        <td style="border-left: 2px solid blue;" class="cell">
            <kbd class="keyboard-key nowrap">Alt</kbd> + <kbd class="keyboard-key nowrap">&uarr;</kbd>
        </td>
        <td class="cell">Volume Up</td>
    </tr>
    <tr>
        <td style="border-bottom-left-radius: 0.5em; border-left: 2px solid blue; border-bottom: 2px solid blue;" class="cell">
            <kbd class="keyboard-key nowrap">Alt</kbd> + <kbd class="keyboard-key nowrap">&larr;</kbd>
        </td>
        <td style="border-bottom-right-radius: 0.5em; border-bottom: 2px solid blue;" class="cell">Navigate back</td>
        <td style=" border-bottom: 2px solid blue; border-bottom-left-radius: 0.5em; border-left: 2px solid blue;" class="cell"><kbd class="keyboard-key nowrap">Alt</kbd> + <kbd class="keyboard-key nowrap">&darr;</kbd></td>
        <td style="border-bottom-right-radius: 0.5em; border-bottom: 2px solid blue;" class="cell">Volume Down</td>
    </tr>
</table>

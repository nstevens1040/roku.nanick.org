**[roku.nanick.org](https://roku.nanick.org)**
---
A webpage that leverages Roku's External Control Protocol to send keyboard input to your Roku which allows for easier typing and faster navigation within the Roku UI.  

**Quick Start**
---
Once you navigate to [roku.nanick.org](https://roku.nanick.org) you'll be asked for the URL that your Roku can be reached at on your local network.  

In my case, I had to set up a DNS CNAME record as well as a nginx proxy_pass in order to use a hostname, but you can also use an IP address. Your input is checked for a valid URL, so make sure you include the URI scheme (http) as well as the port number (8060), like this
```
http://10.0.0.10:8060
```
**Use Case**  
---
The picture below basically sums up the entire use case.  
![](https://raw.githubusercontent.com/nstevens1040/roku.nanick.org/refs/heads/main/.gitignore/nonqwerty.png)  
If you've ever been faced with a non-qwerty on-screen keyboard and nothing but a remote equipped with arrows and an 'OK' button, then you know that it feels like it takes 15 minutes <i>each</i> time you type your email address to authenticate into a single streaming platform.  
  
You can use this webpage to, for example, enable you to use your laptop keyboard to type your login credentials for the streaming platforms that you use. For me this made the process roughly 12 times faster.  

**Key and Function map**  
---

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
            <kbd class="keyboard-key nowrap">Ctrl</kbd> + <kbd class="keyboard-key nowrap">Space</kbd>
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

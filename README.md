# Trees Wolf
## Preconditions
Get the latest Version of Tampermonkey/GreaseMonkey for your Browser:

**Chrome:** https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en

**Firefox:** https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/

### Script Installation
Create a new Script in your extension and paste the Content of the prefered Script.txt File

## How To Use
### Timed Attack
**Timeserver**

For the best performance change your Windows Timeserver to *pool.ntp.org*. (Control Panel -> Clock and Region -> Date and Time -> Internet Time -> Change settings..)

**Time Offset**

The Time Offset can be set on the 16th line of the script. The Time Offset is given in ms.

**Attacking**

Go to the "Vrsammligsplatz". Set the target and your troops and press "Agriffe". There is now an additional option to time the attack on attack-time. If you have set the time in the time selector, press the button and it should turn red. For additional information you can check the console (F12).

``Important``

``You need to keep the page open, aswell as in the foreground, else there will be unexpected delay! To execute multiple attacks at the same time, use multiple windows.``

``The later you start the attack timer, the more accurate it will be!``

``Attacks that will arrive exactly at midnight, might not work!``

**Procedure**

Before sending an attack you should do the following:

1. Update the time from the time server (Control Panel -> Clock and Region -> Date and Time -> Internet Time -> Change settings.. -> Update now)
2. Set the Time Offset (Send an attack subtract the time difference from the time_offset variable, repeat multiple time)
3. Enjoy ;)

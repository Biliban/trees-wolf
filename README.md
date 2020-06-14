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

**Lag**

The lag can be set on the 16th line of the script. The lag is given in ms.

**Attacking**

Go to the "Vrsammligsplatz". Set the target and your troops and press "Agriffe". There are now additional options to time the attack on attack- or return-time. The return-time will always be at 0ms. If you have set the time in the time selector, press the button and it should turn red. For additional information you can check the console (F12).

``Important``

``Currently attacks that will arrive on the next day, will not work!``

``The later you start the attack timer, the more accurate it will be!``



**Procedure**

Before sending an attack you should do the following:

1. Update the time from the time server (Control Panel -> Clock and Region -> Date and Time -> Internet Time -> Change settings.. -> Update now)
2. Set lag (Send an attack subtract the time difference from the lag variable, repeat multiple time)
3. Enjoy ;)

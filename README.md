# ssj clicker
an autoclicker dll that can be injected into any process

## installation
### [tutorial](https://www.youtube.com/watch?v=7lyi2RAchgA)
download .dll file [here](https://github.com/felossj/autoclick/releases/tag/0.1).<br />
remember that you can change the name and the extension it doesnt care

## usage

### 1st method
open a injector (system informer, process hacker or any injector), execute any program (for example, notepad) and inject .dll into the program. it will open a new window but when you close it, the program will close as well.

### 2nd method
open cmd, writes "rundll32 [path to .dll] [some random word]" and touch enter.

## real ac bypasses
- vulcan 12-16 cps ([video](https://youtu.be/UeklgYz6cAI))
- verus 14-18 cps
- hypixel 20-22 cps
- astralmc 13-18 cps

## bypass guide
- download the file in %temp% folder and name it something like "+~JF3888639446943723253.tmp" (dont download and then change name because it will appear on journaltrace)
- launch clicker with rundll32
- self destruct
- press win+r, types prefetch and press enter
- deletes all files with rundll32 name on them
- press win+r, types regedit and press enter
- go to Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\bam\State\UserSettings\ and open the folder with the longest name
- right click this folder and give administrators full permisions, deletes the file called C:\Windows\System32\rundll32, uncheck the full permisions for administrators and minimize all folders
  this lil guide probably make you bypass manual screenshares but this clickers isnt screenshare proof and most ss tools probably detects it
  
## modules
- randomization
- self destruct
- left and right click
- toggle on/off bind
- changes from white to green with on/off
- gui that tries to copy 420clicker
- new random 32 characters window title on each launch
  
## images
ssj clicker [alpha 0.1](https://imgur.com/a/PF2NRgc)

ssj clicker [alpha 0.02](https://imgur.com/a/fUiSGVg)

ssj clicker [alpha 0.01](https://imgur.com/a/WudtAKY)

### aclaration (ignore, its from when the project was open source)
if you want to use this code for your project its fine but it has to be open source

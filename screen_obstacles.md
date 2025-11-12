So when starting byobu "screen" is used in the background, a real great tool for working with a text console in a cool, modern way: but it needs a bit of practice ;)

First and foremost the most important info is, that you switch into the "screen" command mode usualy per default with Ctrl-a
In byobu this is mapped to F12 per default...So whenever you press F12 in byobu, you are actibating the "screen" command mode: 
here you can for instance paste the "screen" clipboard with Ctr-] ... which means on a german keyboard pressing AltGr-9 and is not so comfortable as you can imagine:
<img width="909" height="315" alt="image" src="https://github.com/user-attachments/assets/98d8da97-1ef7-4f2e-aa55-8ab54235b13b" />

But you can change this to the today more convenient keybinding/kemapping Ctrl-v (german keyborad Strg-v): By pressing F12 in your byobu session and then pressing Ctrl-v , the text selected in "mouse mode on" state, where selecting text with your mouse copies your selection to the "screen" buffer/clipboard. 
The "screen" buffer/clipboard isn't reachable with Ctrl-Shift-v in your byobu session.

In your console/ssh session with byobu you can copy/paste from the system clipboard with Ctrl-Shift-c/Ctrl-Shift-v in any browser.
In Google Chrome you can even use your mouse! Pasting clipboard text with the right mouse button works there also!


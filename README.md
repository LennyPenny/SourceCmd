SourceCmd - ngb's version
=========
***NOTE: I AM NOT THE ORIGINAL AUTHOR OF SOURCECMD, CREDITS TO @RANNMANN/CRYZBL/CASUAL FOR CREATING IT.***

***I will try to preserve most of the original words here.***

This tool allows you to run console commands in your favourite source engine game (without having to enter it in the console).

> For now every time you execute a command the console will yell something about not being in the main thread, ignore that.
> This works with clients in text-mode, but only grabs the first instance of the process, not all.

Consider that I am pretty new to Visual C++ I will not be able to fix it for now (if I can find any ways to do it).

Full source code included.
Released under GPLv3 http://www.gnu.org/licenses/gpl.html (As original repository)

Usage
-------

### Interactive Mode (only supports 1 instance at a time):
* Launch your favourite source engine game. 
* Open SourceCmd.exe
* Type the name of the game's executable (in the working list below) and press enter.
* Type any console command you want.


### Command line usage (will run in every process it finds):
SourceCmd.exe \<process\> \<command\>

Example:

    SourceCmd.exe "hl2.exe" "echo Hello World!"

### Confirmed working list:
* CSGO (csgo.exe)
* CS:S (hl2.exe)

### Confirmed **NOT*** working list (will try to fix):
* Garry's Mod (hl2.exe) - crashes a few seconds later after sending first command via SourceCmd

### Q&A
**Q**: Why isn't Garry's Mod, TF2, <insert any Source Engine games> in the working list?
A: Since I don't own some games/do not have them installed due to saving space + no more playing it, I can't test almost every Source Engine games available even when it's on my Steam game library.

I will appreciate it if someone can report whenever if a game is working or not via issues.

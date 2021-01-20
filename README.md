# NXT Enhanced Firmware

# HELP WANTED!

If you know where to download a copy of IAR for Lego Mindstorms, please open an issue.

THIS IS UNOFFICIAL. 

This is a mirror of the [Mindboards SVN repository on Sourceforge](https://sourceforge.net/projects/mindboards/). 
It was imported using the [GitHub Importer](https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github)

The only modification that I made was to add this readme file. If I decide to modify it, I will fork the repository.  
This way this repository servers as a record of the firmware made but the original developers. 

As of writing, this repository does not contain the 107 code. I am looking into getting that added in as a seperate branch. 


## Newest Version
The most recent release is (I believe), the branch titled `version_131`. The `version_132` only has a couple minor changes, that I do not think were released. 

## Why did I do this

I mirrored the code from SourceForge for a couple reasons. 
- Backup: If the official mirror on SourceForge ever goes down, I want a backup for myself. 
- Git: I don't know a single thing about SVN, so importing it to GitHub makes it much eaiser for me to examine the code history.

## User associations

I believe that I properly associated commits with the correct people on GitHub, but if not, please let me know, and I will try to fix it. 

## Pull Requests/Issue Reporting

As this repository is simply acting as a mirror, it is not intended to accept Pull Requests, or for issue tracking. However, that does not mean that I will not
respond to pull requests or issues, so feel free to open them if you feel the need. 

## Compiling

The offical page for software to compile this code no longer exists, as IAR took it down. There do appear to be a few possible alternatives though. 
- [IAR Embedded Workbench for ARM](https://www.iar.com/iar-embedded-workbench/#!?architecture=Arm): IAR offers an evaluation version of their software, however, I am unusure if the code size limitation is big enough to compile the firmware
- Other ARM development software: There are other options out there, but you will have to manually port the project. [Segger Embedded Studio](https://www.segger.com/products/development-tools/embedded-studio/) is 
  free for non-commercial projects, and does not have a code size limitation. 
- [NXTGCC](http://nxtgcc.sourceforge.net/): An older project, that appears to have the goal of porting firmware development to be done with GCC. 
If I have time, I will explore some alternatives and add documentation to this readme. 

## Developing with the NXT

You can still download the NXT and EV3 software for programming the NXT. However, there are many other ways to program it as well, as documented on the [Lego Mindstorms
Wikipedia Article](https://en.wikipedia.org/wiki/Lego_Mindstorms_NXT). One of the options--Brixcc--Was developed by the same person who wrote this enhanced firmware (John Hansen)

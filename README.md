# CBT863
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 863 is from Jim Callihan and contains an IKJEFF10 TSO     *   FILE 863
//*           SUBMIT exit that originally came from PRC's CBT tape  *   FILE 863
//*           File 369.  It stopped working from z/OS 1.12 to 1.13  *   FILE 863
//*           because of a change in control blocks, and Jim found  *   FILE 863
//*           a different way to obtain the information, which,     *   FILE 863
//*           by the way, also works on old systems back to OS/390  *   FILE 863
//*           1.3 (the first Y2K compliant MVS release).  So (I     *   FILE 863
//*           think) you can use this version of the exit on older  *   FILE 863
//*           systems too.                                          *   FILE 863
//*                                                                 *   FILE 863
//*           The exit inserts a comment line in the JCL source,    *   FILE 863
//*           telling you where the JCL in the job came from.       *   FILE 863
//*                                                                 *   FILE 863
//*           For example:                                          *   FILE 863
//*                                                                 *   FILE 863
//*   //*ISPF EDIT OF SBGOLOB.B.ASM(IKJEFF1$)                       *   FILE 863
//*           or                                                    *   FILE 863
//*   //*JCL: SBGOLOB SUBMIT   'SBGOLOB.CBT484.FILE863(IKJEFF1$)'   *   FILE 863
//*                                                                 *   FILE 863
//*           email:  James.R.Callihan@salliemae.com                *   FILE 863
//*                                                                 *   FILE 863
//*           email:  sbgolob@cbttape.org                           *   FILE 863
//*                                                                 *   FILE 863
```

# CBT1053
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE1053 is from Alain Barthelemy, and contains program MEMZAP *   FILE1053
//*           written by him.  Originally, all his programs were    *   FILE1053
//*           commented in French.  One program, called MEMZAP,     *   FILE1053
//*           which can display and zap memory, has been rendered   *   FILE1053
//*           in English, with English comments, and is being       *   FILE1053
//*           included here.  Other programs are following, the     *   FILE1053
//*           first one being KDSLIST.                              *   FILE1053
//*                                                                 *   FILE1053
//*           Alain has translated another of his programs, called  *   FILE1053
//*           KDSLIST, into English.  KDSLIST deals with ICSF.      *   FILE1053
//*           KDSLIST is a utility written in REXX, allowing you    *   FILE1053
//*           to list the contents of an ICSF KDS (CKDS, PKDS, or   *   FILE1053
//*           TKDS).  It has the advantage of being able to work    *   FILE1053
//*           on an "offline" file, that is to say a non-active     *   FILE1053
//*           file (for example a backup) while the ICSF browser    *   FILE1053
//*           only works on active databases.                       *   FILE1053
//*                                                                 *   FILE1053
//*      PROCRAM SUMMARY:                                           *   FILE1053
//*                                                                 *   FILE1053
//*      MEMZAP   - Change memory in either your TSO session, or    *   FILE1053
//*                 in Common Storage, or within a job's address    *   FILE1053
//*                 space.                                          *   FILE1053
//*                                                                 *   FILE1053
//*      KDSLIST  - List the contents of an ICSF KDS (CKDS, PKDS,   *   FILE1053
//*                 or TKDS) but it can also work on a backup       *   FILE1053
//*                 copy (an offline copy).                         *   FILE1053
//*                                                                 *   FILE1053
//*           email :  alain.barthelemy@baphcorp.fr                 *   FILE1053
//*                                                                 *   FILE1053
//*      Further Descriptions:                                      *   FILE1053
//*                                                                 *   FILE1053
//*           About MEMZAP:                                         *   FILE1053
//*                                                                 *   FILE1053
//*           Since MEMZAP needs to run as an authorized PROGRAM    *   FILE1053
//*           (not as a TSO command), the command AUPGM from Bill   *   FILE1053
//*           Godfrey, has also been included here, and a clist     *   FILE1053
//*           called MEMZAPC, has been written so that you can      *   FILE1053
//*           run MEMZAP in your TSO address space.                 *   FILE1053
//*                                                                 *   FILE1053
//*           MEMZAP can also be run as a batch job, see member     *   FILE1053
//*           MEMZAPJ1.  And the replies from that batch job will   *   FILE1053
//*           be made from the system console.  In this case, the   *   FILE1053
//*           address space that MEMZAP runs in, will be the        *   FILE1053
//*           address space of the batch job.                       *   FILE1053
//*                                                                 *   FILE1053
//*           MEMZAP can display and zap memory in the address      *   FILE1053
//*           space in which it is running.  From there, common     *   FILE1053
//*           storage can be displayed and changed, as well.        *   FILE1053
//*                                                                 *   FILE1053
//*           Member MEMZAPP is a started proc that will run        *   FILE1053
//*           MEMZAP from a system console.  (S MEMZAP)             *   FILE1053
//*                                                                 *   FILE1053
//*           About KDSLIST:                                        *   FILE1053
//*                                                                 *   FILE1053
//*           Documentation members KDSLIST# (PDF format), and      *   FILE1053
//*           KDSLIST@ (docx format), can be downloaded to a PC     *   FILE1053
//*           (in BINARY) so they can help you use the program.     *   FILE1053
//*                                                                 *   FILE1053
```

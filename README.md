# CBT422
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 422 IS FROM DON MARQUARDT OF MAY & SPEH OAKBROOK TERRACE  *   FILE 422
//*           ILLINOIS.  THIS FILE IS IN IEBUPDTE SYSIN FORMAT AND  *   FILE 422
//*           CONTAINS THE FOLLOWING MEMBERS:  SEE MEMBER CALLED    *   FILE 422
//*           $$INDEX FOR ADDITIONAL INFORMATION.                   *   FILE 422
//*                                                                 *   FILE 422
//*           CHEKTRAN  CONVERTS NUMERIC FIELDS TO SPELLED OUT      *   FILE 422
//*                     WORDS FOR USE ON CHECKS.  IS ABLE TO        *   FILE 422
//*                     PRINT IN BOTH ENGLISH AND FRENCH AND        *   FILE 422
//*                     SUPPORTS BOTH DOLLARS/CENTS AS WELL AS      *   FILE 422
//*                     ENGLISH POUNDS/PENCE ORIGINAL AUTHOR        *   FILE 422
//*                     UNKNOWN.  I CONVERTED ROUTINE FROM DOS      *   FILE 422
//*                     TO OS.                                      *   FILE 422
//*                                                                 *   FILE 422
//*           DI        A DISPLAY INITS FOR 1.3.4 OF JES            *   FILE 422
//*                     UPDATE OF DI IN AIR FORCE FILE 300          *   FILE 422
//*                                                                 *   FILE 422
//*                     THE NEXT THREE ENTRIES ARE MACROS THAT MAY  *   FILE 422
//*                     BE USED IN SOME OF THE PROGRAMS IN THIS     *   FILE 422
//*                     FILE                                        *   FILE 422
//*                                                                 *   FILE 422
//*           DYNAM     TO DO DYNAMIC ALLOCATION                    *   FILE 422
//*                                                                 *   FILE 422
//*           ENT13     ANOTHER STARTUP ROUTINE.  THIS ONE USES     *   FILE 422
//*                     REG 13 AS A BASE AND INCLUDES CHAINING      *   FILE 422
//*                     AND SUPPLYING A NEW SAVE AREA.  IT          *   FILE 422
//*                     ELIMINATES WASTING A REGISTER JUST TO       *   FILE 422
//*                     POINT TO A SAVE AREA.  A PARM OF NO=        *   FILE 422
//*                     ALLOWS THE SPECIFICATION OF THE NUMBER      *   FILE 422
//*                     OF BASE REGS TO USE.  DEFAULT IS 1.         *   FILE 422
//*                     ASSIGNMENT IS FROM REG 13 DOWN.             *   FILE 422
//*                                                                 *   FILE 422
//*           EQUATE    ANOTHER REGISTER EQUATE ROUTINE.  PRINTS    *   FILE 422
//*                     THE WORD EQUATE IN LARGE BLOCK LETTERS      *   FILE 422
//*                     FOR EASIER SPOTTING IN A LISTING            *   FILE 422
//*                                                                 *   FILE 422
//*           EXT13     MATCHING ROUTINE TO ENT13                   *   FILE 422
//*                                                                 *   FILE 422
//*                    END OF MACROS                                *   FILE 422
//*                                                                 *   FILE 422
//*           FAVERVA   THIS PROGRAM READS CONTROL STATEMENTS FOR   *   FILE 422
//*                     GOAL SYSTEMS' FAVER PROGRAM AND CONVERTS    *   FILE 422
//*                     THEM TO SUPPORT VSAM-ASSIST FROM SOFTWORKS  *   FILE 422
//*                                                                 *   FILE 422
//*           FCBIDR    THIS PROGRAM IS KNOWN AS LISTIDR FROM       *   FILE 422
//*                     FILE 316.  I DELETED SOME OF THE PUT'S      *   FILE 422
//*                     SO ONLY THE USER IDR INFO IS PRINTED        *   FILE 422
//*                     THIS MAKES A NICE LIST FOR REVIEWING        *   FILE 422
//*                     JUST WHAT FCB'S ARE ON THE SYSTEM, WHEN,    *   FILE 422
//*                     FOR WHAT CUSTOMER, AND WHO ADDED IT TO      *   FILE 422
//*                     THE SYSTEM.                                 *   FILE 422
//*                                                                 *   FILE 422
//*                     IT IS USED IN COMBINATION WITH THE          *   FILE 422
//*                     FOLLOWING FCB.... PROGRAMS                  *   FILE 422
//*                                                                 *   FILE 422
//*           FCBIDRJC  THE JCL AND SYSIN USED FOR THE ABOVE        *   FILE 422
//*                     PROGRAM                                     *   FILE 422
//*                                                                 *   FILE 422
//*           FCBGEN    PROGRAM WE HAVE OUR PRINT ROOM OPERATORS    *   FILE 422
//*                     USE TO CREATE FCB'S.  A CLIST IS USED TO    *   FILE 422
//*                     INVOKE AND IS FCBGENC.  THE ROUTINE ASKS    *   FILE 422
//*                     FOR LAST 4 POSITIONS OF FCB NAME,           *   FILE 422
//*                     CHANNEL/LINES, REQUESTOR, AND CUSTOMER      *   FILE 422
//*                     OR FORM NAME.  IT THEN CHECKS TO MAKE       *   FILE 422
//*                     SURE THAT THIS FCB DOES NOT ALREADY         *   FILE 422
//*                     EXIST.  IF IT DOES IT ASKS THE OPERATOR     *   FILE 422
//*                     IF IT IS OK TO REPLACE.  IF YES, ROUTINE    *   FILE 422
//*                     CONTINUES.  IF NOT ROUTINE ASKS FOR A       *   FILE 422
//*                     NEW NAME.  REQUESTOR AND CUSTOMER/FORM      *   FILE 422
//*                     AND DATE CREATED IS ENTERED AS IDR DATA     *   FILE 422
//*                     FOR AUDIT USES LATER.  THE PROGRAM THEN     *   FILE 422
//*                     EXECUTES FCBWTO AT COMPLETION TO NOTIFY     *   FILE 422
//*                     THE USER THAT THE FCB IS AVAILABLE.         *   FILE 422
//*                                                                 *   FILE 422
//*           FCBGENC   CLIST USED WITH FCBGEN                      *   FILE 422
//*                                                                 *   FILE 422
//*           FCBWTO    PROGRAM TO ADVISE USER THAT THE FCB IS      *   FILE 422
//*                     NOW AVAILABLE                               *   FILE 422
//*                                                                 *   FILE 422
//*           HEWLDFP1  THIS IS A MODIFICATION OF THE DFP           *   FILE 422
//*                     LINKAGE EDITOR AT PTF LEVEL UZ78097 TO      *   FILE 422
//*                     ADD THE SYSLMOD DATASET NAME AND VOLSER     *   FILE 422
//*                     TO THE MESSAGE INDICATING                   *   FILE 422
//*                     ADDED/REPLACED.  IT IS NOT IN SMP           *   FILE 422
//*                     FORMAT.  YOU WILL HAVE TO DO THAT           *   FILE 422
//*                     YOURSELF.                                   *   FILE 422
//*                                                                 *   FILE 422
//*           HEWLFDPX  XA VERSION OF THE ABOVE.                    *   FILE 422
//*                                                                 *   FILE 422
//*           IEFTBL    THIS IS THE TABLE OF 'GOOD GUYS' THAT       *   FILE 422
//*                     ARE NOT TIMED OUT FOR WAIT TIME DURING      *   FILE 422
//*                     THE DAY.  OUTSIDE THE HOURS OF 7AM THRU     *   FILE 422
//*                     5PM.                                        *   FILE 422
//*                                                                 *   FILE 422
//*                     NOTE***  THIS MODULE MUST BE AVAILABLE      *   FILE 422
//*                              PRIOR TO USING THE COMPANION       *   FILE 422
//*                              MODULE IEFUTL.  NO CHECK IS        *   FILE 422
//*                              MADE IN IEFUTL TO BYPASS IF NOT    *   FILE 422
//*                              AVAILABLE.  I PLAN TO FIX THIS     *   FILE 422
//*                              AS SOON AS TIME PERMITS.           *   FILE 422
//*                                                                 *   FILE 422
//*           IEFUTL    THIS IS OUR UTL EXIT THAT CANCELS           *   FILE 422
//*                     EVERYTHING EXCEPT THE 'GOOD TSO GUYS'.      *   FILE 422
//*                     SEE IEFTBL ABOVE.                           *   FILE 422
//*                                                                 *   FILE 422
//*           INITJCL   THIS IS THE JCL WE USE FOR THE FOLLOWING    *   FILE 422
//*                     TWO PROGRAMS ONLY.  THE UNIT AND PGM NAMES  *   FILE 422
//*                     ARE CHANGED BASED ON WHICH TYPE OF TAPE     *   FILE 422
//*                     WE ARE INIT-ING.                            *   FILE 422
//*                                                                 *   FILE 422
//*           INITTAPE  THIS IS OUR HOME GROWN TAPE INIT            *   FILE 422
//*                     ROUTINE.  OUR OPERATORS LIKE IT BETTER.     *   FILE 422
//*                                                                 *   FILE 422
//*           INIT3480  SAME AS INITTAPE BUT FOR USE WITH THE       *   FILE 422
//*                     3480 DRIVES AS IT USES THE MSG DISPLAYS     *   FILE 422
//*                     ON THE DRIVE.                               *   FILE 422
//*                                                                 *   FILE 422
//*           JESNSLT   ZAP TO JES PRPU TO MAKE BLOCK SEPARATOR     *   FILE 422
//*                     NOT TO SLANT.  WHILE IT CAN BE DONE WITH    *   FILE 422
//*                     SMP, IT SEEMS A LITTLE OVERKILL TO RUN      *   FILE 422
//*                     AN SMP ASSEMBLY AND LINKEDIT FOR A 1        *   FILE 422
//*                     BYTE CHANGE.                                *   FILE 422
//*                                                                 *   FILE 422
//*           JESNSLTX  XA VERSION OF ABOVE ZAP.  SAME COMMENTS     *   FILE 422
//*                     APPLY.                                      *   FILE 422
//*                                                                 *   FILE 422
//*           MAS9010   PRINTS OUT THE AUTOMATIC SCHEDULING         *   FILE 422
//*                     FACILITY FILE.  THIS FACILITY WAS WRITTEN   *   FILE 422
//*                     BY DAVE COLE AT COLE SOFTWARE IN AFTON,     *   FILE 422
//*                     VIRGINIA, AND IS ON FILE 388 OF THIS TAPE.  *   FILE 422
//*                                                                 *   FILE 422
//*              Please note that an upgraded copy of the MVS       *   FILE 422
//*              Automatic Scheduling Facility is available for     *   FILE 422
//*              direct download at Dave Cole's web site:           *   FILE 422
//*                                                                 *   FILE 422
//*                  http://www.colesoft.com                        *   FILE 422
//*                                                                 *   FILE 422
//*           PRVIPLSP  MOD TO MVS 1.3.4 TO MAKE VOLUMES NOT IN     *   FILE 422
//*                     VATLIST TO DEFAULT TO PRIVATE INSTEAD OF    *   FILE 422
//*                     PUBLIC MOUNT.                               *   FILE 422
//*                                                                 *   FILE 422
//*           PRVIPLXA  XA VERSION OF THE ABOVE                     *   FILE 422
//*                                                                 *   FILE 422
//*           TSOMAXSP  THIS ZAP ALLOWS THE "GOOD GUYS" (TSD..      *   FILE 422
//*                     IN OUR CASE) TO LOGON EVEN IF THE           *   FILE 422
//*                     MAXUSERS IS EXCEEDED.  NOTE THAT IF         *   FILE 422
//*                     MAXUSERS IS SET TO 0 EVEN US GOOD GUYS      *   FILE 422
//*                     CAN'T GET ON.  MUST BE AT LEAST 1.  THIS    *   FILE 422
//*                     ZAP THANKS TO FRANK WALSCHLAGER FROM        *   FILE 422
//*                     SPIEGEL.  IT IS FOR MVS/SP 1.3.3.           *   FILE 422
//*                                                                 *   FILE 422
//*           TSOMAXXA  XA VERSION OF THE ABOVE.  GREAT WHAT A      *   FILE 422
//*                     DISASSEMBLER AND A LITTLE HUNTING CAN DO.   *   FILE 422
//*                                                                 *   FILE 422
//*           VARLENTH  A UTILITY PROGRAM THAT READS A VARIABLE     *   FILE 422
//*                     LENGTH FILE AND REPORTS ON THE RECORD       *   FILE 422
//*                     SIZE AND NUMBER OF RECORDS OF EACH          *   FILE 422
//*                     LENGTH.                                     *   FILE 422
//*                                                                 *   FILE 422
```

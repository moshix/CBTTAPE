
## $DOC.txt
```
00010000THIS IS A SAMPLE SET OF USER WRITTEN ENTRIES FOR THE TECHINFO CLIST.
00020000
00030000THE RELATED MEMBERS ARE:
00040000
00050000  $MODEL  - CONTAINS THE MODEL FOR A TECHINFO ENTRY TO BE PROCESSED
00060000            BY THE OZPDSUNL PROGRAM.
00070000
00080000  G000002 - THE WHATS NEW ENTRY FOR TECHINFO
00081000
00090000  G000003 - FIRST ENTRY SHOWN TO THE USER WHEN TECHINFO STARTS UP.
00100000            THE D=MMMYY IS THE DATE OF THE 'RELEASE' OF TECHINFO.
00110000
00120000  U000001 - THE FIRST ENTRY SHOWN TO THE USER WHEN IN ORDINARY
00130000            INFO/MVS AND A 'SWITCH' COMMAND IS ISSUED.
00140000
00150000  U000002-U999999 USER ENTRIES - SOME SAMPLE INTEL ENTRIES ARE
00160000            INCLUDED.
00170000
00171001  U092091 - SAMPLE ENTRY DOCUMENTING OUR CURRENT ACF/VTAM NETWORK
00172001            AS PRODUCED BY THE 'NETINFO' SAS PROGRAM.  (INCLUDED
00173001            ON THIS DISTRIBUTION TAPE.
00175001
00180000 THE FOLLOWING JOBS IN TECH.INTEL.JOBS.CNTL
00190000   ARE USED TO SUPPORT THE TECHINFO SYSTEM:
00200000
00210000  TECINFOC - IS A ---CLIST--- TO RUN TECHINFO
00220000
00270000  TECINFO1 - DEFINE THE TECHINFO DATABASE USING IDCAMS
00280000
00290000  TECINFO2 - EXTRACT THE 'H' (HELP) FILE FROM THE INFO/MVS TAPE AND
00300000             PUT IN FORMAT FOR USE BY BLGOZM (MERGE).
00310000
00311000  TECHINFO - IS JOB TO RECREATE AND DOWNLOAD THE TECHINFO DATABASE
00312000             USING OZPDSUNL AND THE REGULAR BLGOZ.. PROGRAMS PROVIDED
00313000             BY THE INFO/SYSTEM.
00314000
00320000 NORMAL UPDATEING IS DONE ON THE 'UNLOADED' TECHINFO DATABASE USING
00330000    SPF OR ISPF.  THE 'TECHINFO' JOB IS THEN RUN TO RECREATE THE
00340000    TECHINFO DATABASE ON AN 'AD HOC' BASIS.
00350000
```

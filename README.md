~~~~~~~~~~~~~~~~

//***FILE 111 IS FROM MR JIM PURDY, FORMERLY OF REVLON.  JIM'S      *   FILE 111
//*           NEW ADDRESS:                                          *   FILE 111
//*                                                                 *   FILE 111
//*                JIM PURDY                                        *   FILE 111
//*                ANDERSEN CONSULTING                              *   FILE 111
//*                1345 MEADOW GLEN                                 *   FILE 111
//*                SOUTHLAKE, TX  76092                             *   FILE 111
//*                (214) 402-7511                                   *   FILE 111
//*                                                                 *   FILE 111
//*           THIS FILE CONTAINS SOME MPF EXITS, A TSO COMMAND      *   FILE 111
//*           PROCESSOR FOR GDG'S AND A TSO SUBMIT EXIT.  THIS      *   FILE 111
//*           FILE IS IN IEBUPDTE SYSIN FORMAT AND CONTAINS         *   FILE 111
//*           THE FOLLOWING MEMBERS                                 *   FILE 111
//*                                                                 *   FILE 111
//*           MEMBERS WTOETPS1 & WTOETPS2 ARE MODIFICATIONS OF ALL  *   FILE 111
//*             THE COCA-COLA WTO EXITS.  THESE EXITS WILL WRITE AN *   FILE 111
//*             SMF RECORD FOR EACH MOUNT AND DISMOUNT IN ADDITION  *   FILE 111
//*             TO THE DISPLAY OF WHERE A TAPE WAS IF IT WAS        *   FILE 111
//*             RECENTLY MOUNTED.  MODIFICATIONS HAVE ALSO BEEN     *   FILE 111
//*             MADE TO CREATE A USER CVT WHICH WAS NEEDED BY THE   *   FILE 111
//*             EXITS.                                              *   FILE 111
//*                                                                 *   FILE 111
//*           MEMBER WTOTAPMT MAY BE USED TO WRITE AN SMF RECORD    *   FILE 111
//*             FOR EACH TAPE MOUNT IF THE WTOETPS1 AND WTOETPS2    *   FILE 111
//*             MODULES ARE NOT USED.                               *   FILE 111
//*                                                                 *   FILE 111
//*           MEMBER WTOERWAT IS A MODIFICATION OF THE COCA-COLA    *   FILE 111
//*             EXIT WHICH WILL RESPOND 'WAIT' TO MESSAGE IEF238D   *   FILE 111
//*             AND WRITE AN SMF RECORD TO INDICATE THE ALLOCATION  *   FILE 111
//*             RECOVERY CONDITION.                                 *   FILE 111
//*                                                                 *   FILE 111
//*           MEMBER WTOTAPAL IS THE EXIT TO ONLY WRITE THE SMF     *   FILE 111
//*             RECORD FOR ALLOCATION RECOVERY.                     *   FILE 111
//*                                                                 *   FILE 111
//*           MEMBERS LISTGDGC AND LISTGDGP ARE A PAIR OF PROGRAMS  *   FILE 111
//*             THAT COMPRISE THE LISTGDG TSO COMMAND.  THIS        *   FILE 111
//*             COMMAND WILL LIST THE ATTRIBUTES OF A GDG AND THE   *   FILE 111
//*             MOST RECENTLY CREATED GENERATIONS.  THE NUMBER OF   *   FILE 111
//*             GENERATIONS RETAINED IN THE CATALOG MAY BE CHANGED  *   FILE 111
//*             UPON REQUEST.  NEW GDG BASE ENTRIES MAY ALSO BE     *   FILE 111
//*             CREATED. THIS COMMAND WORKS WITH ICF CATALOGS AND   *   FILE 111
//*             HAS SUPPORT FOR 3380 DISK AND 3480 CARTS. THE       *   FILE 111
//*             COMMAND IS IN TWO PARTS:  THE ALLOCATION PIECE      *   FILE 111
//*             WHICH IS WRITTEN IN ASSEMBLER; AND THE LOGIC PIECE  *   FILE 111
//*             WRITTEN IN PL1.                                     *   FILE 111
//*                                                                 *   FILE 111
//*           MEMBER IKJEFF10 IS A TSO SUBMIT EXIT THIS EXIT WILL   *   FILE 111
//*             CONDITIONALLY CHECK THE JOB CARD SUBMITTED TO       *   FILE 111
//*             VERIFY THAT THE JOBNAME STARTS WITH THE USERID OR   *   FILE 111
//*             FIRST N CHAR OF USERID.  THE EXECUTION CLASS,       *   FILE 111
//*             MSGCLASS, AND TIME PARAMETERS ARE ALSO              *   FILE 111
//*             CONDITIONALLY CHECKED AND MAY BE MANDATORY AND/OR   *   FILE 111
//*             IN THE APPROPRIATE TABLES.   A TIME PARAMETER MAY   *   FILE 111
//*             ALSO BE INSERTED BY THE EXIT.  ALL CHECKING IS      *   FILE 111
//*             BASED ON THE USERID AND THE PRIVILEGES ALLOWED THAT *   FILE 111
//*             USER IN THE UIDTABLE.  JOB CLASSES MAY HAVE FLAGS   *   FILE 111
//*             TO REQUIRE TIME PARAMETERS OR REQUIRE NOT TO HAVE   *   FILE 111
//*             THEM. ALSO, THERE MAY BE MAX TIME AND DEFAULT TIME  *   FILE 111
//*             BY CLASS.  COMMAND AND CERTAIN JES 2 CONTROL CARDS  *   FILE 111
//*             WILL NOT BE ALLOWED IN THE SUBMITTED JCL.           *   FILE 111
//*                                                                 *   FILE 111
~~~~~~~~~~~~~~~~



## $$DOC.txt
```
1
      THIS IS AN INDEX TO THE MEMBERS IN THIS LIBRARY

    $CLEAR    -    CLEAR FLAG MACRO.  USED WITH $FLAG, $DFLAG AND
                   $TEST MACROS.

    $DFLAG    -    DEFINE FLAG BYTE MACRO.  USED WITH $FLAG, $CLEAR
                   AND $TEST MACROS.

    $EPILOG   -    END AND EXIT A PROGRAM CSECT.  USED WITH $PROLOG
                   MACRO.

    $FLAG     -    SET A FLAG BIT MACRO.  USED WITH $CLEAR, $DFLAG
                   AND $TEST MACROS.

    $HEAD     -    CREATE HEADER INFO BLOCKS IN ASSEMBLY LISTINGS.

    $PROLOG   -    CREATE STANDARD ENTRY LINKAGE TO A PROGRAM CSECT.
                   USED WITH $EPILOG MACRO.

    $REGS     -    INTERNAL MARCO USED BY $PROLOG TO GENERATE REGISTER
                   EQUATES.

    $TEST     -    TEST A FLAG AND BRANCH ON CONDITION MACRO.  USED
                   WITH $FLAG, $DFLAG AND $CLEAR MACROS.

    #CONVDAT  -    CONVER JULIAN DATE TO GREGORIAN DATE MACRO.

    DATECHCK  -    DATE CHECK PROGRAM SOURCE.

    DAYC????  -    THESE ARE ISPF TUTORIAL MENUS TO EXPLAIN USEAGE OF
                   DATECHCK UTILITY.

1
    THIS UTILITY IS IN USE AT DAYCO PRODUCTS INC ON AN IBM 3090
    PROCESSOR RUNNING MVS/XA 2.1.3 AT PUT LEVEL 8606.  JES2 1.3.4
    AND JES2 2.1.5 ARE BOTH IN USE AND WE HAVE ISPF/PDF 2.2 RUNNING
    UNDER TSO/E 2.1.

    THE UTILITY WAS CREATED TO ALLOW PROGRAMMERS WHO BUILD SYSTEMS
    THAT REQUIRE DATE INPUT TO THE PARM OF A PROGRAM, TO ENSURE THAT
    IF THE DATE IS ENTERED WRONG THE OPERATOR DOES NOT GET AWAY WITH
    IT.  I TRIED TO MAKE IT AS FLEXIBLE AS POSSIBLE AND IT HAS EVEN
    SAVED ME FROM MYSELF AT TIMES.  IT BECAME INVALUBLE WHEN I PUT
    UP THE PANSPOOL SYSTEM FROM THE MODS TAPE SINCE AN ERROR IN THE
    ENTERED PARM DATE COULD MEAN CONSIDERABLE HAND WORK TO CORRECT.

    THE MACROS EXECPT THE $DFLAG, $TEST, $FLAG AND $CLEAR ARE FROM
    VARIOUS FILES IN THE MODES TAPE.  THE #CONVDAT MACRO WAS MODIFIED
    FOR REENTRANCY AND AN ATTEMPT MADE TO INCLUDE DETERMINING THE
    DAY OF THE WEEK FROM THE DATE.  SOMEHOW THIS WENT WRONG BUT DID
    NOT CAUSE PROBLEMS AS FAR AS THE DATECHCK PROGRAM SINCE IT DOES
    NOT CARE.  IF YOU CAN FIX IT THEN GREATE.
1
    THE TAPE ENCLUDED IS AN NL TAPE AT 6250 BPI.  TAPE WAS CREATED
    USING IEBCOPY UNLOAD FUNCTION AND HAS ONLY ONE FILE.
-
-
                                  JOHN D. SOSTROM
                                  DAYCO PRODUCTS INC.
                                  333 W. FIRST STREET
                                  DAYTON, OHIO   45401
                                  (513)226-5747
```

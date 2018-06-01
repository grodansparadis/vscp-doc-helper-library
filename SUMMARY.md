# Summary

## Overview

* [The VSCP helper library](README.md)
* [Language Bindings](bindings.md)

## Using the library
* [Return values and erro handling](error_handling.md)
* [Using with c](c_using.md)
* [Using with Python](python_using.md)

## Using C++ classes
* [Introduction](cpp_intro.md)
* [First project](cpp_firstprj.md)
* [Available methods](cpp_methods.md)

## The CANAL library
* [libcanal](canal_libcanal.md)
* [Using the library](canal_using.md)

## Methods

### Initialization and configuration
* [vscphlp_newSession](vscphlp_newsession.md)
* [vscphlp_closeSession](vscphlp_closesession.md)
* [vscphlp_setResponseTimeout](vscphlp_setresponsetimeout.md)
* [vscphlp_setAfterCommandSleep](vscphlp_setaftercommandsleep.md)

### Communication link methods
* [vscphlp_isConnected](vscphlp_isconnected.md)
* [vscphlp_doCommand](vscphlp_docommand.md)
* [vscphlp_checkReply](vscphlp_checkreply.md)
* [vscphlp_clearLocalInputQueue](vscphlp_clearlocalinputqueue.md)
* [vscphlp_open](vscphlp_open.md)
* [vscphlp_openInterface](vscphlp_openinterface.md)
* [vscphlp_close](vscphlp_close.md)
* [vscphlp_noop](vscphlp_noop.md)
* [vscphlp_clearDaemonEventQueue](vscphlp_cleardaemoneventqueue.md)
* [vscphlp_sendEvent](vscphlp_sendevent.md)
* [vscphlp_sendEventEx](vscphlp_sendeventex.md)
* [vscphlp_isDataAvailable](vscphlp_isdataavailable.md)
* [vscphlp_enterReceiveLoop](vscphlp_enterreceiveloop.md)
* [vscphlp_quitReceiveLoop](vscphlp_quitreceiveloop.md)
* [vscphlp_blockingReceiveEvent](vscphlp_blockingreceiveevent.md)
* [vscphlp_blockingReceiveEventEx](vscphlp_blockingreceiveeventex.md)
* [vscphlp_setFilter](vscphlp_setfilter.md)
* [vscphlp_getStatistics](vscphlp_getstatistics.md)
* [vscphlp_getStatus](vscphlp_getstatus.md)
* [vscphlp_getVersion](vscphlp_getversion.md)
* [vscphlp_getDLLVersion](vscphlp_getdllversion.md)
* [vscphlp_getVendorString](vscphlp_getvendorstring.md)
* [vscphlp_getDriverInfo](vscphlp_getdriverinfo.md)
* [vscphlp_doCmdShutDown](vscphlp_docmdshutdown.md)

### GUID handling
* 

### Filter handling
* [vscphlp_clearVSCPFilter](vscphlp_clearvscpfilter.md)
* [vscphlp_copyVSCPFilter](vscphlp_copyvscpFilter.md)
* [vscphlp_readFilterFromString](vscphlp_readfilterfromstring.md)
* [vscphlp_writeFilterToString](vscphlp_writefiltertostring.md)
* [vscphlp_readMaskFromString](vscphlp_readmaskfromstring.md)
* [vscphlp_writeMaskToString](vscphlp_writemasktostring.md)
* [vscphlp_doLevel2Filter](vscphlp_doLevel2filter.md)

### Event helpers and conversions
* [vscphlp_copyVSCPEvent](vscphlp_copyvscpevent.md)
* [vscphlp_writeVscpDataToString](vscphlp_writevscpdatatostring.md)
* [vscphlp_writeVscpDataWithSizeToString](vscphlp_writevscpdatawithsizetostring.md)
* [vscphlp_setVscpDataFromString](vscphlp_setvscpdatafromstring)
* [vscphlp_writeVscpEventToString](vscphlp_writevscpeventtostring.md)
* [vscphlp_writeVscpEventExToString](vscphlp_writevscpeventextostring.md)
* [vscphlp_setVscpEventFromString](vscphlp_setvscpeventfromstring.md)
* [vscphlp_setVscpEventExFromString](vscphlp_setvscpeventexfromstring.md)
* [vscphlp_getVscpPriority](vscphlp_getvscppriority.md)
* [vscphlp_getVscpPriorityEx](vscphlp_getvscppriorityex.md)
* [vscphlp_setVscpPriority](vscphlp_setvscppriority.md)
* [vscphlp_setVscpPriorityEx](vscphlp_setvscppriorityex.md)
* [vscphlp_convertVSCPtoEx](vscphlp_convertvscptoex.md)
* [vscphlp_convertVSCPfromEx](vscphlp_convertvscpfromex.md)
* [vscphlp_newVSCPevent](vscphlp_newvscpevent.md)
* [vscphlp_deleteVSCPevent](vscphlp_deletevscpevent.md)
* [vscphlp_deleteVSCPevent_v2](vscphlp_deletescpevent_v2.md)
* [vscphlp_convertCanalToEvent](vscphlp_convertcanaltoevent.md)
* [vscphlp_convertCanalToEventEx](vscphlp_convertcanaltoeventex.md)
* [vscphlp_convertEventToCanal](vscphlp_converteventtocanal.md)
* [vscphlp_convertEventExToCanal](vscphlp_converteventextocanal.md)
* [vscphlp_setEventDateTimeBlockToNow](vscphlp_seteventdatetimeblocktonow.md)
* [vscphlp_setEventExDateTimeBlockToNow](vscphlp_seteventexdatetimeblocktonow.md)
* [vscphlp_getDateStringFromEvent](vscphlp_getdatestringfromevent.md)
*  [vscphlp_getDateStringFromEventEx](vscphlp_getdatestringfromeventex.md)

### CANAL helpers and conversions
* [vscphlp_getVSCPheadFromCANALid](vscphlp_getvscpheadfromcanalid.md)
* [vscphlp_getVSCPclassFromCANALid](vscphlp_getvscpclassfromcanalid.md)
* [vscphlp_getVSCPtypeFromCANALid](vscphlp_getvscptypefromcanalid.md)
* [vscphlp_getVSCPnicknameFromCANALid](vscphlp_getvscpnicknamefromcanalid.md)
* [vscphlp_getCANALidFromVSCPdata](vscphlp_getcanalidfromvscpdata.md)
* [vscphlp_getCANALidFromVSCPevent](vscphlp_getcanalidfromvscpevent.md)
* [vscphlp_getCANALidFromVSCPeventEx](vscphlp_getcanalidfromvscpeventex.md)
* [vscphlp_calc_crc_Event](vscphlp_calc_crc_event.md)
* [vscphlp_calc_crc_EventEx](vscphlp_calc_crc_eventex.md)

### General helpers
This part of the library describes the many helpers that are available to handle events, GUIDs, etc, etc. 
* [vscphlp_readStringValue](vscphlp_readstringvalue.md)
* [vscphlp_replaceBackslash](vscphlp_replacebackslash.md)
* [vscphlp_getTimeString](vscphlp_gettimestring.md)
* [vscphlp_getISOTimeString](vscphlp_getisotimestring.md)
* [vscphlp_convertCanalToEvent](vscphlp_convertcanaltoevent.md)
* [vscphlp_convertCanalToEventEx](vscphlp_convertcanaltoeventex.md)
* [vscphlp_convertEventToCanal](vscphlp_converteventtocanal.md)
* [vscphlp_convertEventExToCanal](vscphlp_converteventextocanal.md)
* [vscphlp_makeTimeStamp](vscphlp_maketimestamp.md)



### Variables

### Tables



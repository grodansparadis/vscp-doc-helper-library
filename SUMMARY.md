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
* [vscphlp_getGuidFromString](vscphlp_getguidfromstring.md)
* [vscphlp_getGuidFromStringEx](vscphlp_getguidfromstringex.md)
* [vscphlp_getGuidFromStringToArray](vscphlp_getguidfromstringtoarray.md)
* [vscphlp_writeGuidToString](vscphlp_writeguidtostring.md)
* [vscphlp_writeGuidToStringEx](vscphlp_writeguidtostringex.md)
* [vscphlp_writeGuidToString4Rows](vscphlp_writeguidtostring4rows.md)
* [vscphlp_writeGuidToString4RowsEx](vscphlp_writeguidtostring4rowsex.md)
* [vscphlp_writeGuidArrayToString](vscphlp_writeguidarraytostring.md)
* [vscphlp_isGUIDEmpty](vscphlp_isguidempty.md)
* [vscphlp_isSameGUID](vscphlp_issameguid.md)
* [vscphlp_reverseGUID](vscphlp_reverseguid.md)
* [vscphlp_calcCRC4GUIDArray](vscphlp_calccrc4guidarray.md)
* [vscphlp_calcCRC4GUIDString](vscphlp_calccrc4guidstring.md)

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
*  [vscphlp_convertEventToJSON](vscphlp_converteventtojson.md)
*  [vscphlp_convertEventExToJSON](vscphlp_converteventextojson.md)
*  [vscphlp_convertEventToXML](vscphlp_converteventtoxml.md)
*  [vscphlp_convertEventExToXML](vscphlp_converteventextoxml.md)
*  [vscphlp_convertEventToHTML](vscphlp_converteventtohtml.md)
*  [vscphlp_convertEventExToHTML](vscphlp_converteventextohtml.md)

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

### Measurements
* [vscphlp_getMeasurementDataCoding](vscphlp_getmeasurementdatacoding.md)
* [vscphlp_getDataCodingBitArray](vscphlp_getdatacodingbitarray.md)
* [vscphlp_getDataCodingInteger](vscphlp_getdatacodinginteger.md)
* [vscphlp_getDataCodingNormalizedInteger](vscphlp_getdatacodingnormalizedinteger.md)
* [vscphlp_getDataCodingString](vscphlp_getdatacodingstring.md)
* [vscphlp_getVSCPMeasurementAsString](vscphlp_getvscpmeasurementasstring.md)
* [vscphlp_getVSCPMeasurementAsDouble](vscphlp_getvscpmeasurementasdouble.md)
* [vscphlp_getVSCPMeasurementFloat64AsString](vscphlp_getvscpmeasurementfloat64asstring.md)
* [vscphlp_convertFloatToNormalizedEventData](vscphlp_convertfloattonormalizedeventdata.md)
* [vscphlp_convertFloatToFloatEventData](vscphlp_convertfloattofloateventdata.md)
* [vscphlp_convertIntegerToNormalizedEventData](vscphlp_convertintegertonormalizedeventdata.md)
* [vscphlp_makeFloatMeasurementEvent](vscphlp_makefloatmeasurementevent.md)
* [vscphlp_getMeasurementAsFloat](vscphlp_getmeasurementasfloat.md)
* [vscphlp_getMeasurementUnit](vscphlp_getmeasurementunit.md)
* [vscphlp_getMeasurementSensorIndex](vscphlp_getmeasurementsensorindex.md)
* [vscphlp_getMeasurementZone](vscphlp_getmeasurementzone.md)
* [vscphlp_getMeasurementSubZone](vscphlp_getmeasurementSubzone.md)
* [vscphlp_isMeasurement](vscphlp_ismeasurement.md)
* [vscphlp_convertLevel1MeasuremenToLevel2Double](vscphlp_convertlevel1measurementolevel2double.md)
* [vscphlp_convertLevel1MeasuremenToLevel2String](vscphlp_convertlevel1measurementolevel2string.md)
* [vscphlp_makeLevel2FloatMeasurementEvent](vscphlp_makelevel2floatmeasurementevent.md)
* [vscphlp_makeLevel2StringMeasurementEvent](vscphlp_makelevel2stringmeasurementevent.md)

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



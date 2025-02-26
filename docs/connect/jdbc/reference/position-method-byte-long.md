---
title: "position Method (byte, long)"
description: "position Method (byte, long)"
author: David-Engel
ms.author: v-davidengel
ms.date: "01/19/2017"
ms.prod: sql
ms.technology: connectivity
ms.topic: reference
apilocation: "sqljdbc.jar"
apiname: "SQLServerBlob.position (byte[], long)"
apitype: "Assembly"
---
# position Method (byte, long)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Returns the position of a specified pattern in the BLOB based on the given **byte** array pattern and starting index.  
  
## Syntax  
  
```  
  
public long position(byte[] bPattern,  
                     long start)  
```  
  
#### Parameters  
 *bPattern*  
  
 The pattern to search for.  
  
 *start*  
  
 The start index to search at.  
  
## Return Value  
 A **long** value of the position where the pattern was found, or -1 if it was not found.  
  
## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
  
## Remarks  
 This position method is specified by the position method in the java.sql.Blob interface.  
  
## See Also  
 [position Method &#40;SQLServerBlob&#41;](../../../connect/jdbc/reference/position-method-sqlserverblob.md)   
 [SQLServerBlob Methods](../../../connect/jdbc/reference/sqlserverblob-methods.md)   
 [SQLServerBlob Members](../../../connect/jdbc/reference/sqlserverblob-members.md)   
 [SQLServerBlob Class](../../../connect/jdbc/reference/sqlserverblob-class.md)  
  
  

---
title: "CCatalogs, CCatalogInfo | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-data"]
ms.topic: "reference"
f1_keywords: ["CCatalogs", "m_szName", "CCatalogInfo"]
dev_langs: ["C++"]
helpviewer_keywords: ["DESCRIPTION class data member", "CCatalogInfo parameter class", "CCatalogs typedef class", "m_szName", "m_szDescription"]
ms.assetid: 8362cbbd-2f00-4272-8518-fc235c4de193
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "data-storage"]
---
# CCatalogs, CCatalogInfo
Call the typedef class **CCatalogs** to implement its parameter class **CCatalogInfo**.  
  
## Remarks  
 See [Schema Rowset Classes and Typedef Classes](../../data/oledb/schema-rowset-classes-and-typedef-classes.md) for more information on using typedef classes.  
  
 This class identifies the physical attributes associated with catalogs accessible from the DBMS.  
  
 The following table lists the class data members and their corresponding OLE DB Columns. See [CATALOGS Rowset](https://msdn.microsoft.com/en-us/library/ms721241.aspx) in the *OLE DB Programmer's Reference* for more information about the schema and columns.  
  
|Data members|OLE DB columns|  
|------------------|--------------------|  
|m_szName|CATALOG_NAME|  
|m_szDescription|DESCRIPTION|  
  
## Requirements  
 **Header:** atldbsch.h  
  
## See Also  
 [CRestrictions Class](../../data/oledb/crestrictions-class.md)
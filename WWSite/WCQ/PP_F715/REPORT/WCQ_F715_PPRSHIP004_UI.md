---
title: Shipping Dimension Report
description: 
published: true
date: 2020-08-31T03:41:35.380Z
tags: 
editor: undefined
---

# **Shipping Dimension Report - WCQ**

---

## **Version Control**

| Revise Date |      Version      | Modified By | Purpose    | Register Code |
| :--------- | :--------------- | :----------- | :---------- | :------------- |
| 2020.08.19  | [1.0](#1.0) | Weson Chan  | UI Initial | LVP19008      |

---

## **UI Path**

![PPRSHIP004_UI](/wcq/pp_f715/report/pprship004/image-pprship004_ui.png)

---

## **Reference File**

[PPRSHIP001.drawio](/wcq/pp_f715/report/pprship004/pprship001.drawio)

## **UI Introduce**

### **UI Initial**

<span id="1.0">`1.0`</span>

### **Query UI**

![image-QueryUi](/wcq/pp_f715/report/pprship004/image-queryui_1.png)

**The Shipping Dimension Report is query by below the condition(need enter at least one condition)**

1. **Plant:** It is a drop-down box option
2. **Packingno:** It is a Multiple input
3. **DN:** It is a Multiple input
4. **PN:** It is a Multiple input
5. **DnOrigin:** It is a radio button ; The order type
6. **PGI Date:** It is a date option ;The PGI data  what  you want to choose

### **Query Result**

**This is the query result**

![image-queryresult_1](/wcq/pp_f715/report/pprship004/image-queryresult_1.png)

![image-queryresult_2](/wcq/pp_f715/report/pprship004/image-queryresult_2.png)

**The Special Column**  
1. **HAWB** : House Air Waybill  
2. **PN** :  The part number of DN  
3. **PCNO** : ShipId Sequence number  
4. **DIFFERENCE** : The gap between the GROSSWEIGHT and DIMWEIGHT   
5. **WEIPERCENT** : DIMWEIGHT/GROSSWEIGHT  
6. **LTTSTATUS** : Load to truck status  
7. **PGISTATUS** : PGI status


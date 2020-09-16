---
title: Manufacture Packing
description: 
published: true
date: 2020-08-31T03:38:21.147Z
tags: 
editor: undefined
---

# **Manufacture Packing - WCQ**

---

## **Version Control**

| Revise Date | Version             | Modified By | Purpose                        | Register Code |
| :---------- | :------------------ | :---------- | :----------------------------- | :------------ |
| 2020.08.08  | [1.1](#1.1) | Jack Li     | Introduce Astro Check SSN Info | LVC20001      |
| 2020.08.06  | [1.0](#1.0) | Weson Chan  | UI Initial                     | LVP19008      |

---

## **UI Path**

![image-20200826121230952](/wcq/pp_f715/transaction/pptpack002/image-20200826121230952.png)

---

## **UI Introduce**

### **UI Initial**

<span id ="1.0">`1.0`</span>

### **1.Input or Scan DN#AO#, Input or Scan USN#**

#### **Common operations**

1. input the DN#AO# or USN#
   ![image-20200821113715075](/wcq/pp_f715/transaction/pptpack002/image-20200821113715075.png)
2. after input the DN#AO# or USN#,then will show the  DN information like below picture
   ![image-20200821115223795](/wcq/pp_f715/transaction/pptpack002/image-20200821115223795.png)
3. then scan the USN/CartonID/PalletID to pack
   ![image-20200821120459322](/wcq/pp_f715/transaction/pptpack002/image-20200821120459322.png)
   After scan USN ,then will show  packingno、ShipID、dn information that has been scaned and print [**Astro Israel Label**](http://10.37.36.18:801/LMS_Doc/WWSite/WCQ/PP_F715/BASEDATA/WCQ_F715_PPBLABEL001_UI/#2astro-israel-label)/[**Russian-label**](http://10.37.36.18:801/LMS_Doc/WWSite/WCQ/PP_F715/BASEDATA/WCQ_F715_PPBLABEL001_UI/#18russian-label)/[**Astro QVC Carton Label**](http://10.37.36.18:801/LMS_Doc/WWSite/WCQ/PP_F715/BASEDATA/WCQ_F715_PPBLABEL001_UI/#23astro-qvc-carton-label)
   ![image-20200821120743408](/wcq/pp_f715/transaction/pptpack002/image-20200821120743408.png)
4. When shipid complete  
   Warning message after Ship_ID completed:
   ![img](/wcq/pp_f715/transaction/pptpack002/clip_image002-1596695991919.jpg)
   then will maintain dimension  
   ![image-20200821121530145](/wcq/pp_f715/transaction/pptpack002/image-20200821121530145.png)
5. Print the label and confirm to SAP after the ShipID Complete
   ![image-20200821121636897](/wcq/pp_f715/transaction/pptpack002/image-20200821121636897.png)
6. Print the [**Hold Label**](http://10.37.36.18:801/LMS_Doc/WWSite/WCQ/PP_F715/BASEDATA/WCQ_F715_PPBLABEL001_UI/#1hold-label)/[**Astro BoxID attachment**](http://10.37.36.18:801/LMS_Doc/WWSite/WCQ/PP_F715/BASEDATA/WCQ_F715_PPBLABEL001_UI/#11astro-boxid-attachment)/[**Astro EMEA Scanning List**](http://10.37.36.18:801/LMS_Doc/WWSite/WCQ/PP_F715/BASEDATA/WCQ_F715_PPBLABEL001_UI/#9astro-emea-scanning-list)

### **2.Special Logic**

**QVC Check:** When user input DN# and this DN# belongs to QVC shipment then it will show error message

![img](/wcq/pp_f715/transaction/pptpack002/clip_image002.jpg)

### **Astro Check SSN Info**

<span id ="1.1">`1.1`</span>

Input USN then LMS will show the ralated data wtih USN, include packing no.、AO、P/C No.、P/C Seq、P/C size、PC Qty、Pallet Type,in order to be easy to find the pallet 

![image-20200806155611441](/wcq/pp_f715/transaction/pptpack002/image-20200806155611441.png)

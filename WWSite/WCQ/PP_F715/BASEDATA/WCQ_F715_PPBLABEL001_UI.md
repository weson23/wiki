---
title: Label Type Maintenance
description: 
published: true
date: 2020-09-01T02:15:20.922Z
tags: 
editor: undefined
---

# **Label Type Maintenance - WCQ**

---

## **Version Control**

| Revise Date | Version           | Modified By | Purpose           | Register Code |
| ----------- | ----------------- | ----------- | ----------------- | ------------- |
| 2020.08.21  | [1.1](#1.1) | Weson Chan  | Add Astro SN List | LVP19008      |
| 2020.08.19  | [1.0](#1.0) | Weson Chan  | UI Initial        | LVP19008      |

---

## **UI Path**

![LabelUI](/wcq/pp_f715/basedate/ppblabel001/image-labelui.png)

---

## **Reference File**

[PPBLABEL001.drawio](/wcq/pp_f715/basedate/ppblabel001/ppblabel001.drawio)

---

## **UI Introduce**

### **UI Initial**

<span id ="1.0">`1.0`</span>

#### **Query UI**

![image-queryui.png](/wcq/pp_f715/basedate/ppblabel001/image-queryui.png)

1. **Plant** :  which plant are you in
2. **LabelType** :  Which Labeltype do you want to choose
3. **Trigger Point** :The trigger point that print the label.
    - SN Complete : After scan one usn
    - Ship ID Complete : After scan one shipid 
    - DN Complete : after scan all the DN 
    - Packing ID Complete : after scan all the PackingNo
    - Other: not belong above options
4. **Customer Group** : Which customer

#### **Query Result**

![image-QueryResult](/wcq/pp_f715/basedate/ppblabel001/image-queryresult.png)

#### **New UI:**

There is  a new label type data UI( The column with "*" is required )

![image-NewUI_1](/wcq/pp_f715/basedate/ppblabel001/image-newui_1.png)

1. **Plant** :  Which plant are you in
2. **LabelType** :  The labeltype that you want to set
3. **Description** :  The description of labeltype
4. **Trigger Point** :The trigger point that print the label.
    - SN Complete : After scan one usn
    - Ship ID Complete : After scan one shipid
    - DN Complete : after scan all the DN
    - Packing ID Complete : after scan all the PackingNo
    - Other: not belong above options
5. **Customer Group** : Which customer
6. **Template** : The template of label
7. **Processor** : Which kind of way to print label

**if don't input anything in the field,then will show the required message**

![image-Add_required](/wcq/pp_f715/basedate/ppblabel001/image-Add_required.png)

#### **Edit UI:**

You can edit the Desccription、Trigger Point、Customer Group、Customer Group、Template、Processor columns.

![image-edit](/wcq/pp_f715/basedate/ppblabel001/image-edit.png)

#### **Delete:**

1. First click the chckbox
2. Click the delete button

![image-DeleteUI](/wcq/pp_f715/basedate/ppblabel001/image-deleteui.png)

## **Labels**

#### Below picture is the existing Label print result

## **1.Hold Label**

![image-Hold_Label](/wcq/pp_f715/basedate/ppblabel001/image-hold_label.png)

## **2.Astro Israel Label**

![image-Astro_Israel_Label](/wcq/pp_f715/basedate/ppblabel001/image-astro_israel_label.png)

## **3.Astro Shipping Mark**

![image-Astro Shipping Mark](/wcq/pp_f715/basedate/ppblabel001/image-astro_shipping_mark.png)

## **4.Astro Pallet Label Type B**

![image-Pallet Label Type B](/wcq/pp_f715/basedate/ppblabel001/image-pallet_label_type_b.png)

## **5.Astro Carton Label:**

![image-Astro Carton Label](/wcq/pp_f715/basedate/ppblabel001/image-astro_carton_label.png)

## **6.Astro General Packing List**

![image-General Packing List**](/wcq/pp_f715/basedate/ppblabel001/image-general_packing_list.png)

## **7.Astro CTO Packing List for Custom:**

![image-Packing List for Custom](/wcq/pp_f715/basedate/ppblabel001/image-packing_list_for_custom.png)

## **8.Astro CTO Packing List Attach With Goods:**

![image-Packing List Attach With Goods](/wcq/pp_f715/basedate/ppblabel001/image-packing_list_attach_with Goods.png)

## **9.Astro EMEA Scanning List:**

![image-EMEA Scanning List](/wcq/pp_f715/basedate/ppblabel001/image-emea-scanning-List.png)

## **10.Astro MRP(EDI) Carton Label:**

![image-MRP(EDI) Carton Label](/wcq/pp_f715/basedate/ppblabel001/image-mrp(edi)-carton-label.png)

## **11.Astro BoxID attachment:**

![image-Astro BoxID attachment](/wcq/pp_f715/basedate/ppblabel001/image-astro-boxid-attachment.png)

## **12.Astro DDS Pallet Label:**

![image-DDS Pallet Label](/wcq/pp_f715/basedate/ppblabel001/image-dds-pallet-label.png)

## **13.Astro DDS Extra Pallet Label(CPMO):** it is hold label

## **14.Box Ship Label_Over Pack_Wholesale(Astro EDITS):**

![image-Box Ship Label_Over Pack_Wholesale](/wcq/pp_f715/basedate/ppblabel001/image-box-ship-label-wholesale.png)

## **15.Box Ship Label_Over Pack_Gift Box(Astro EDITS):**

![image-Over Pack_Gift](/wcq/pp_f715/basedate/ppblabel001/image-over_pack_gift.png)

## **16.Astro MAWB Label:**

![image-MAWB Label](/wcq/pp_f715/basedate/ppblabel001/image-mawb_label.png)


## **17.Russian Label:**

![image-Russian Label](/wcq/pp_f715/basedate/ppblabel001/image-russian_label.png)

## **18.Astro POS:**

![image-POS](/wcq/pp_f715/basedate/ppblabel001/image-pos.png)

## **19.Astro Fedex Fil Data:**

![image-Fedex Fil Data](/wcq/pp_f715/basedate/ppblabel001/image-fedex_fil_data.png)

## **20.UPS Tran-In File:**

![image-UPS Tran-In File](/wcq/pp_f715/basedate/ppblabel001/image-ups_tran_in_file.png)

## **21.Item List Label:**

![image-Item List Label](/wcq/pp_f715/basedate/ppblabel001/image-item_list_label.png)

## **22.Wistron Packing List:**

![image-Wistron Packing List](/wcq/pp_f715/basedate/ppblabel001/image-wistron_packing_list.png)

## **23.Astro QVC Carton Label:**

![image-QVC Carton Label](/wcq/pp_f715/basedate/ppblabel001/image-qvc_carton_label.png)

---

## **Add Astro SN List**

<span id="1.1">`1.1`</span>

## **24.Astro SN List**

![image-Astro_SN_List](/wcq/pp_f715/basedate/ppblabel001/image-astro_sn_list.png)






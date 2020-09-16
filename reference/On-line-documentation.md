---
title: CIM on-line documentation
description: CIM on-line documentation reference
published: true
date: 2020-08-31T02:46:31.093Z
tags: 
editor: undefined
---

# **CIM on-line documentation**
![image](/on-line-document-assets/ref_001.png)

## **On-line documentation flow**
![image](/on-line-document-assets/ref_005.png)

## **On-line documentation flow File**
[Flow File](/on-line-document-assets/reference.drawio)

## **Environment Setup**
### 1. Documentation related tools:
Note: You can [**reference here**](http://10.41.21.91:808/sct4.0_doc/it-guide/document/).
#### - [Python](https://www.python.org/) : Before install MkDocs, need install Python first
You can check if you have these already installed from the command line:
```bash
$ python --version
Python 3.7.6
```
#### - [Pip](http://pip.readthedocs.io/en/stable/installing/) : Python package manager
You can check if you have these already installed from the command line:
```bash
$ pip --version
pip 19.2.3 from d:\python\lib\site-packages\pip (python 3.7)
```
#### - [MkDocs](https://www.mkdocs.org/) : Build CIM web documents
You can check if you have these already installed from the command line:
```bash
$ mkdocs --version
mkdocs, version 1.0.4 from d:\python\lib\site-packages\mkdocs (Python 3.7)
```
#### - [Markdown](https://markdown.tw/): Web document used language
#### - [Typora](https://www.typora.io/) (Optional): Markdown editor
#### - [draw.io](https://www.draw.io/): Draw flow, architecture
### 2. Version control tools:
You can understand "How to use git?" by as06A/as06B of [Armstron 3.0](http://10.37.37.139/apps/armstrong3/sharing.html).
 
 **1. as06A - Git/Gitlab使用教學(上)**

  - Git概念與原理
  - Git實務觀念與操作
  - Git進階使用策略與技巧
  - Gitlab 使用Ground Rules

**2. as06B - Git/Gitlab使用教學(下)**

  - Git原理復習
  - VS Code Git操作與管理
  - Gitlab運用介紹
  - Gitlab Flow

#### - [Git](https://git-scm.com/downloads) : Distributed version control system
#### - [VS Code](https://code.visualstudio.com/) (Optional): Use for git management 
### 3. Wistron Gitlab:
Before request for access, you need login Gitlab once, then apply to PIC: **Aimee Chang** join **K8SWIHCIMOKR** AD group.
#### -   [Gitlab](https://gitlab.wistron.com/) : Wistron Gitlab for source code control
#### -   [Gitlab (DEV)](https://gitlab-dev.wistron.com/) : Wistron DEV Gitlab for source code control

## **Git working flow**
![image](/on-line-document-assets/ref_002.png)

## **Getting Started**
#### **1. git clone** - Copy remote master branch.
```bash
git clone https://gitlab-dev.wistron.com/okr4-cimdoc/lms.git
```
![image](/on-line-document-assets/ref_011.png)
#### **2. git [LFS](https://git-lfs.github.com/) (Large file storage)** - Just for **initial setting**.
These file types will manage by Git LFS.

- .png
- .xlsx, .xls
- .pptx, .ppt
- .pdf
- .drawio

![image](/on-line-document-assets/ref_013.png)
#### **3. git checkout** - Copy develop branch and start with here.
```bash
git checkout --track origin/develop
```

#### **4. Writing document** - Create/edit/delete file right here.
![image](/on-line-document-assets/ref_014.png)
#### **5. git add** - Track files on git.
```bash
git add .
```
#### **6. git commit** - Submit to git.
```bash
git commit –m “first commit”
```
#### **7. git push** - Push develop branch to remote.
```bash
git push origin develop
```
![image](/on-line-document-assets/ref_006.png)
#### **8. Merge request** - Make a merge request.
![image](/on-line-document-assets/ref_007.png)
#### **9. Document review** - Reviewer will receive infrom mail, check document on DEV website.
![image](/on-line-document-assets/ref_008.png)
#### **10. Merge or not** - If ok, press merge button; If not ok, press close merge request button, and return step 4 to fix document.
![image](/on-line-document-assets/ref_009.png)

## **CIM documentation website**
| Function team | PRD website | DEV website | 
| ------------- | ----------- | ----------- |
| LMS | [http://10.37.36.18:801/LMS_Doc/](http://10.37.36.18:801/LMS_Doc/) | [http://10.37.36.18:801/Pre/LMS_Doc/](http://10.37.36.18:801/Pre/LMS_Doc/) |
| WMS | [http://10.37.36.18:801/WMS_Doc/](http://10.37.36.18:801/WMS_Doc/) | [http://10.37.36.18:801/Pre/WMS_Doc/](http://10.37.36.18:801/Pre/WMS_Doc/) |
| SBG-LMS | [http://10.37.36.18:801/SBG_Doc/](http://10.37.36.18:801/SBG_Doc/) | [http://10.37.36.18:801/Pre/SBG_Doc/](http://10.37.36.18:801/Pre/SBG_Doc/) |
| SCT | [http://10.41.21.91:808/SCT4.0_Doc/](http://10.41.21.91:808/SCT4.0_Doc/) | |
| SFCS | [http://10.41.21.91:808/SFCS_Doc/](http://10.41.21.91:808/SFCS_Doc/) | [http://10.41.21.91:808/SFCS_Doc_Review/](http://10.41.21.91:808/SFCS_Doc_Review/) |
---
title: "Drug Safety Associate"
description: "Parexel International"
dateString: December 2021 - June 2022
draft: false
tags: ["health data", "data analysis", "analysis", "healthcare"]
showToc: false
weight: 302
--- 

## Description

![](/experience/parexel/parexel.jpeg#centre)

### Parexel International is a global provider of biopharmaceutical services. It conducts clinical trials on behalf of its pharmaceutical clients to expedite the drug approval process.

I joined Parexel International in December 2021 as a **Drug Safety Associate** for their biopharmaceutical project with **Sanofi SA**

-

My work focused on using **Pix2Pix** (a **CGAN** architecture) to generate **Ultrasound (US) scans** from **MRI scans**, an **image-to-image translation** problem. However, a major challenge that I faced was the lack of structural correspondence between the MRI and US scans, arising from the sheer nature of the way this data is collected. Consequently, I wrote a custom loss function incorporating the **CGAN loss** with a **Dice Loss** between the segmentation maps obtained from the MRI scans and those from the generated US scan. This forces the generator to remove the structural deformation in the generated US scans. Additionally, I was given remote access to the TU-Munich’s cluster computers for training the model as well as an account in their Discourse forum.
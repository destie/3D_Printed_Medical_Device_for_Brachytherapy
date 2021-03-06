# 3D_Printed_Medical_Device_for_Brachytherapy
A repository of code and associated information for our 3D printed Brachytherapy device. (A procedure used for cancer treatment using radiation)

Brachytherapy seeks to treat cancer through insertion of radioactive sources aligned by needles within standardized blocking templates. However, many patients have anatomy that does not conform to standard tools. 

This project sought to create a 3D printed device to provide customized needle alignment for a patient. 

CT scan of a cervix tumor from anonymized patient data was used to develop a 3D printed brachytherapy alignment tool and phantom anatomical mold. 

Multiple materials were evaluated to match patient anatomy in density and Hounsfield Units present on CT scan, with additional considerations for toxicity, compliance, and practicality. Alignment device and molds were developed in PLA. Silicone of T20 hardness was used to create relevant anatomical organs (Uterus, Rectum, Bladder). Tumor tissue was mimicked by addition of 1CC of Iodine contrast agent to silicone. Device and needles were arranged, inserted into anatomical phantom, and scanned by CT to mimic brachytherapy procedure. 3D printed Silicone uterus of 1.08 g/cm^3 and 40 HU mimicked human uterus on CT scan. Constructed uterus dimensions of 6.5 cm x 5.5 cm x 3.3 cm were verified on imaging to be within + 1 mm of original patient scan. The 1 CC of contrast agent provided sufficient differentiation of “tumor” ring from “tissue.” CT scan and treatment plan creation verified that the alignment device provided correction insertion of needles into the phantom tumor tissue and uterus. 

The results of this pilot study provide a potential methodology to develop future anatomical phantoms and alignment devices from CT scans of patient data. Additional modifications could make this a viable training tool for future residents and medical students to learn brachytherapy.

This respository contains:


**Display_DICOM_in_3D**
Code to initially display the DICOM image in 3D in python.

**Save_DICOM_Data_as_STL**
Code to save the 3D arranged DICOM slices as an STL file.

**DICOM_Device_Overlay**
Code to combine 3D object and DICOM slices of patient to confirm alignment

See full paper here: https://www.biorxiv.org/content/10.1101/2022.07.03.498548v1.full

If you find this project helpful and would like to use this work, please cite:
Provenzano D, Aghdam H, Goyal S, Loew M, Rao Y. 3D-Printing in Radiation Oncology: Development and Validation of Custom 3D-Printed Brachytherapy Alignment Device and Phantom. bioRxiv 2022.07.03.498548; doi: https://doi.org/10.1101/2022.07.03.498548 

Provenzano D, Aghdam H, Rao Y, Cifter G, Goyal S, Loew M, Rao Y. 3D-Printing in Radiation Oncology: Development and Validation of Custom 3D-Printed Brachytherapy Alignment Device and Phantom. Speaker Presentation at ABS. June 2021. Remote.

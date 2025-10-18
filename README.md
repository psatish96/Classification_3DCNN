# Classification-3DCNN

Classification of urban material in Ahmedabad, India, using PRISMA hyperspectral satellite data. The study utilized supervised machine learning algorithms, specifically Spectral Angular Mapper (SAM) and Convolutional Neural Networks (CNN), to classify various urban and natural materials like asphalt, concrete, lake water, and vegetation.

Key aspects of the project include:

  * **Objective:** To understand hyperspectral remote sensing, gain hands-on experience in data preprocessing, select regions of interest (ROI) and extract endmembers for spectral libraries, and classify urban materials in Ahmedabad using ML and DL models.
  * **Data:** PRISMA hyperspectral data were used, with three different datasets created: PRISMA resampled data, super-resolved data, and fused data (PRISMA fused with Sentinel-2 10m data).
  * **Methodology:** The process involved bad band removal, endmember selection, and classification using SAM and 3D CNN.
   ![Workflow](https://github.com/user-attachments/assets/697501a4-d393-4fa4-93a1-f4135885d644)

  * **Results:** The study found that CNN (Convolutional Neural Networks) consistently outperformed SAM (Spectral Angular Mapper) in terms of classification accuracy, including Overall Accuracy (OA) and Kappa coefficient (K), across all three datasets. For instance, CNN achieved OA values ranging from 98.36% to 99.94%, while SAM's OA ranged from 72.91% to 78.81%.
  * **3D-CNN Results** 
    <img width="3507" height="2480" alt="Map_Fused_CNN" src="https://github.com/user-attachments/assets/991f9119-1d04-4e6f-aaa5-680d80afad7e" /> 3DCNN Fused Img
    <img width="3507" height="2480" alt="Map_RES_CNN" src="https://github.com/user-attachments/assets/c849e6d0-5646-4afc-a7dd-ae0240aaccb8" /> 3DCNN Resampled Img
    <img width="3507" height="2480" alt="Map_SR_CNN" src="https://github.com/user-attachments/assets/b2777818-f553-4f90-8996-45b2503f1593" /> 3DCNN Superresolved Img


  * **Conclusion:** The project provided both theoretical and practical knowledge in hyperspectral remote sensing and its classification methods. CNN demonstrated superior effectiveness in land cover classification compared to SAM, particularly with fused data providing more detailed information.

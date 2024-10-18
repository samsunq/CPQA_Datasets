# CPQA_Datasets V2

🔥 News
We release CPQA_Datasets V2![2024-9-15]
We release CPQA_Datasets label![2024-10-18]

🎶 Introduction

**2.0**📍We have found that military targets are widely applied in the current security domain; however, the issues of reference segmentation, detection, and evaluation effectiveness of military targets under camouflage and occlusion conditions have been rarely studied. In response, we used civilian camouflage clothing to capture images of camouflage and occlusion in real scenes within the CPQA dataset. As we further refined our work, we realised that military targets could be significantly affected by shooting pixels, smoke, and other objective conditions. Therefore, we employed web scraping technology to collect 10,000 real battlefield images from the internet, from which we extracted 2K images with moderate clarity that matched camouflage scenarios. We then merged these images with those we had previously captured to form the CPQA V2 dataset. This dataset will include comprehensive annotated data for REF segmentation, evaluation, and detection, laying the groundwork for preliminary deep learning research in the niche field of military camouflage.
Link：(https://pan.baidu.com/s/1_WVfgc1qgCqTt8cJDKxQFQ)
fetch code：zct9

🖌️ COD Test result
we conduct a comparison of the COL with three newest COD methods on this dataset, including Camodiffusion, FEDER, PRNET, note that the predicted maps from all methods are obtained from open-source codes. From Fig, we can observe that the COL model achieves excellent performance as good as these networks, and COL model accurately segments objects with small proportions, and local details of camouflage tar gets. The qualitative results demonstrate that both mainstream COD methods and our COL model can achieve excellent performance on this dataset, proving the validity and adaptability of our dataset.
![detection](https://github.com/user-attachments/assets/bb99124e-7f91-45ce-a1e9-4dd2337e7e5f)



🖌️ DEMO
The newly added battlefield data includes three main categories of targets: person, vehicle, and others. The vehicle category encompasses tanks, armoured vehicles, cars, and towed equipment found on the battlefield. The others category includes targets that are obscured or completely covered by camouflage nets, which can be regarded as camouflage net targets.
![新增](https://github.com/user-attachments/assets/a29f8f74-1852-403f-aca5-440f56f08e06)





**1.0**📍The CPQA Datasets which include all the picture data for Camouflage People in field
To support our CPQA method, we captured 4,500 images using RGB cameras. These images include 10 typical vegetation scenes and a combination of 8 different human-shaped camouflage devices in various environmental settings.
The following link provides download addresses for the original images of the dataset as well as the transformed image sizes.

Download link：https://pan.baidu.com/s/1VkrKXQfWwNxDgzsJ3W4QxA 
fetching code：3qu9 

During training and testing, we resize the images to 512x384 for processing. The dataset includes both the original images （6240x3512）and the cropped training images, making it convenient for other researchers to compare the results after training.

🖌️ DEMO
To represent the diversity of image content in each CPQA database, we display in Figure A five different attributes for image subjective/objective evaluation, namely SSIM, PSNR, RMSE, VIF, and LIPS. This data is stored in an Excel spreadsheet for users to reference.

After completing the data collection, we uniformly crop the dataset into images of size 1024*768. Then, we conduct subjective evaluations following the steps outlined in section 4.1 of the article and record the corresponding scores. The initial scoring table provided to participants is based on subjective assessments of the quality of camouflage effects. Initial scores range from 0 to 10, where 0 indicates no camouflage at all, 3 indicates that the target can still be easily identified despite the use of camouflage equipment, 5 indicates the presence of camouflage but the target can be discerned upon observation, 7 indicates that after a period of careful observation, the target can be separated from the background, and 10 indicates the camouflage target is completely unidentifiable. Other scores represent evaluations of the degree of camouflage between these defined levels.
![image](https://github.com/samsunq/CPQA_Datasets/assets/90139092/d218d90b-b460-40fb-a07b-03e27cf0d9a1)

Currently, the main camouflage techniques aim to blend the target texture seamlessly with the background texture to create confusion in detection and assessment. Common field camouflage techniques involve mimicking various plants or ground textures from the background to achieve effective camouflage. To enhance the practicality of our dataset, we have chosen several typical vegetation environments from Northeast Asia as camouflage backgrounds and various types of individual camouflage clothing as targets.
![image](https://github.com/samsunq/CPQA_Datasets/assets/90139092/39c25d74-d414-4367-8ff8-d2031802eb53)

The vegetation species collected in the dataset are classified according to the "Encyclopedia of Chinese Resources Science". The data we collected is characterized by wide distribution, diverse types, complex species, and diverse ecological adaptability. It includes both native types developed under natural environmental conditions and persistent secondary types formed by human interference. Therefore, we believe that the dataset we have created is usable and generalizable.
![伪装MOS图示例](https://github.com/samsunq/CPQA_Datasets/assets/90139092/45c82959-0ae0-45c6-88a8-09168116b13a)

Attention:
[CPQA_Datasets version 1.0 only give the MOS value for every pic. The next version version we will give the detection and segmentation ground-truth for every pic, which could support for camouflage detection works]

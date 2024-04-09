# CPQA_Datasets
The CPQA Datasets which include all the picture data for Camouflage People in field


To support our CPQA method, we captured 4,500 images using RGB cameras. These images include 10 typical vegetation scenes and a combination of 8 different human-shaped camouflage devices in various environmental settings.

The following link provides download addresses for the original images of the dataset as well as the transformed image sizes.

Download link：https://pan.baidu.com/s/1VkrKXQfWwNxDgzsJ3W4QxA 
fetching code：3qu9 

To represent the diversity of image content in each CPQA database, we display in Figure A five different attributes for image subjective/objective evaluation, namely SSIM, PSNR, RMSE, VIF, and LIPS. This data is stored in an Excel spreadsheet for users to reference.

After completing the data collection, we uniformly crop the dataset into images of size 1024*768. Then, we conduct subjective evaluations following the steps outlined in section 4.1 of the article and record the corresponding scores. The initial scoring table provided to participants is based on subjective assessments of the quality of camouflage effects. Initial scores range from 0 to 10, where 0 indicates no camouflage at all, 3 indicates that the target can still be easily identified despite the use of camouflage equipment, 5 indicates the presence of camouflage but the target can be discerned upon observation, 7 indicates that after a period of careful observation, the target can be separated from the background, and 10 indicates the camouflage target is completely unidentifiable. Other scores represent evaluations of the degree of camouflage between these defined levels.
![image](https://github.com/samsunq/CPQA_Datasets/assets/90139092/d218d90b-b460-40fb-a07b-03e27cf0d9a1)

Currently, the main camouflage techniques aim to blend the target texture seamlessly with the background texture to create confusion in detection and assessment. Common field camouflage techniques involve mimicking various plants or ground textures from the background to achieve effective camouflage. To enhance the practicality of our dataset, we have chosen several typical vegetation environments from Northeast Asia as camouflage backgrounds and various types of individual camouflage clothing as targets.
![image](https://github.com/samsunq/CPQA_Datasets/assets/90139092/39c25d74-d414-4367-8ff8-d2031802eb53)

The vegetation species collected in the dataset are classified according to the "Encyclopedia of Chinese Resources Science". The data we collected is characterized by wide distribution, diverse types, complex species, and diverse ecological adaptability. It includes both native types developed under natural environmental conditions and persistent secondary types formed by human interference. Therefore, we believe that the dataset we have created is usable and generalizable.
![Uploading image.png…]()


# Tamil-Epigraphs-data-creation-and-recognition

Hello All,

This project is an attempt to create a dataset for ancient tamil epigraphs(vattezhuthukal from 8th century to 12th centuryC.E). 
          
Here I have taken a image of tamil epigraph and I have cut segemented it into individual images using opencv. Later, I used K-means clustering to clusterthe characters and then manually reclustered the wrongly clustered images.
          
Then I have augmented those images and built a dataset which is available in the zip file. A dl model was also built to recognise those images and classify them as their modern counterparts. Here, this model can classify 28 characters of ancient tamil into modern tamil characters. TO achieve better accuracies you may try using VGG16 transfer learning, if building the model is what you're focused on.
          
I look forward to do the same in OCR.


You can find the dataset in kaggle in the below link:
https://www.kaggle.com/datasets/siddharthadevanv/8th-century-tamil-inscriptions

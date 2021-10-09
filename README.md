# GAN


See Tutorial from https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html

https://howsam.org/generative-adversarial-network/#%D8%B4%D8%A8%DA%A9%D9%87_%D8%B9%D8%B5%D8%A8%DB%8C_GAN_%DA%86%DB%8C%D8%B3%D8%AA%D8%9F


use face dataset from http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

If you have link of data set use !wget link to download data (type !wget link in the google colab)

use 
        
        from google.colab import drive
        
        drive.mount('/gdrive')
      
to mount google drive  or gdrive     
      
use linux command like 

         !cp '/gdrive/My Drive/img_align_celeba.zip' /content

to put all things in content

then unzip data by

          !unzip img_align_celeba.zip


see one batch of data using 

         real_batch = next(iter(dataloader))


use 

          netG.apply(weights_init)
       
       
to have weights in the network       




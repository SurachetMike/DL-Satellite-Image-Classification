# Satellite Image Classification using Deep Neural Network
      
Land use and land cover change are important for the management of areas, especially for developing countries such as Thailand. Remote sensing is a kind of tool that can explore objects on the surface of the Earth and makes direct observations across large areas of the land surface, thus allowing land cover patterns to be mapped and save cost (Sharma, et al., 2017). Both visual interpretation and computer-based digital classification can be used to extract information on land cover from a variety of remote sensing data (e.g., aerial photographs, satellite imagery, multi-spectral imagery, hyper-spectral imagery, etc.) which vary in spatial, spectral, radiometric, and temporal resolutions (Jensen, 2015; Sharma, et al., 2017). This data is suitable for processing and analyzing the classification of land use and land cover. Sharma, et al. (2017) has explored about the image classification for remote sensing data has come many way, such as Maximum Likelihood Classifier (MLC) (Strahler, 1980), Clustering (Huang, 2002), Decision Trees (Xu, et al., 2005), Random Forests (RF) (Pal, 2005), Neural Networks (NN) (Kavzoglu and Mather, 2003; Mas and Flores, 2008), Support Vector Machines (SVM) (Gidudu, et al., 2007; Mountrakis, et al., 2011; Pal and Mather, 2005); Included various methods of deep learning such as Convolutional Neural Networks (CNNs) (Castelluccio, et al., 2015; Romero, et al., 2016).

   Land use and Land cover classifications are constantly developed based on spectral and spatial properties of the pixels or object-based approaches (Pesaresi and Gerhardinger, 2011; Rizvi and Mohan, 2011; Castelluccio, et al., 2015). This task becomes incrementally more difficult as the level of abstraction increases because land covers characterizing a given class may present a large variability and objects may appear at different scales and orientations (Castelluccio, et al., 2015). Castelluccio, et al., (2015) has investigated image classification and retrieval of Remotely Sensing imagery (RS). In particular, when RS data are classified with neural networks, the architecture of the network is the most essential. Several past studies have proposed different neural network application to RS data: land use classification by CaffeNet and GoogLeNet architectures (Castelluccio, et al., 2015), classification of Hyperspectral image (one type of RS data) using Restricted Boltzmann machines (RBMs)—are probabilistic graphical models that can be interpreted as stochastic neural networks— (Midhun, et al., 2014), land cover classification using patch-based recurrent neural network (PB-RNN) system (Sharma, et al., 2018) 
      
   This project also focuses on the classification of land use with RS images (Landsat 8 OLI satellite image). This time, I will not treat these images as a series of time-sequential images, which is also an interesting topic, but use these images as independent. Thus, this project is one of the image classifications, and DL is to be employed and evaluate which method is more suitable particularly for RS data of Phuket, Thailand.

     
## Goal setting

Short term
-	To obtain a more accurate land use classification of the Phuket Province, Thailand
-	To implement a couple of DL-based RS image classification and evaluate them.

Long term
-	To develop the land use and land cover classification system that can be used online and available for satellite imagery from other satellites.

## References

1. Castelluccio, M., Poggi, G., Sansone, C., and Verdoliva, L. (2015). Land use classification in remote sensing images by convolutional neural networks, ArXiv Preprint arXiv:1508.00092.
2. Sharma, A., Liu, X., Yang, X., and Shi, D. (2017). A patch-based convolutional neural network for remote sensing image classification. Neural Networks,95, 19-28.
3. Romero, A., Gatta, C., and Camps-Valls, G. (2016). Unsupervised deep feature extraction for remote sensing image classification. IEEE Transactions on Geoscience and Remote Sensing, 54(3), 1349–1362.
4. Wang, S., Quan, D., Liang, X., Ning, M., Guo, Y., and Jiao, L. (2018). A deep learning framework for remote sensing image registration. ISPRS Journal of Photogrammetry and Remote Sensing.
5. Scott, G.J., England, M.R., Starms, W.A., Marcum, R.A., and Davis, C.H. (2017). Training deep convolutional neural networks for land-cover classification of highresolution imagery. IEEE Geosci. Rem. Sens. Lett. 14 (4), 549–553. https://doi.org/10.1109/LGRS.2017.2657778.
6. https://github.com/zia207/Deep-Neural-Network-with-keras-Python-Satellite-Image-Classification

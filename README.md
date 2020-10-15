#  Adaptive Hypergraph Learning with Multi-Stage Optimizations for Image and Tag Recommendation
   
  The dataset provided in this directory consists of images collected from Flickr, depicting Greek sights, which can be considered as Points of Interest (POIs). Each image is accompanied with auxiliary information,such as title, tags, geo-tags (latitude, longitude). This dataset was employed in our work *"Adaptive Hypergraph Learning with Multi-Stage Optimizations for Image and Tag Recommendation"*, which proposes a hypergraph learning scheme for hypergraph ranking. The proposed approach, called HMSO, employs a multi-stage optimization learning scheme. The proposed scheme jointly optimizes hyperedge weights, hypergraph structure by updating the incidence matrix, and ranking for delivering accurate recommendations. The dataset provided herein was tested on various state-of the-art approaches and the performance metrics indicate that the propose approach outperforms them offering accurate image and tag recommendation.
   
 **DATASET FOR IMAGE RECOMMENDATION CRAWLED FROM FLICKR**  
 
     
  The dataset consists of 99,777 geo-tagged photos. It contains both indoor and outdoor medium sized photos of popular Greek landmarks, various city scenes, and landscapes.

   The following files are included:

1) images.mat: contains the id of 99,777 images in string form.
2) geo.mat: the 1st column contains image id (as number), the 2nd column contains image latitude and the 3rd column contains image longitude.
3) text.mat contains the text associated to each image.

 Raw images could be provided upon request        
 
 Contact mail: gkarantai@csd.auth.gr
		
		
		
# Citation
if you use this dataset in your experiments please cite this work by using the following bibtex entry:
     
     @ARTICLE{adapt20, 
     author={G. Karantaidis and I. Sarridis and C. Kotropoulos}, 
     journal={IEEE Trans. Image Process.}, 
     title={Adaptive Hypergraph Learning with Multi-Stage Optimizations for Image and Tag Recommendation}, 
     year={2020, SUBMITTED}, 
     volume={}, 
     number={}, 
      pages={} 
      }
  

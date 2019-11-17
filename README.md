# Simple application k-means non-supervised algorithm 

# Introduction
This repo aimes to introduce some simple example about skilearn's class k-means for non supervised learning, on classic UCI balanced multiclass dataset 'Iris'. 


# Dataset

> This is perhaps the best known database to be found in the pattern
> recognition literature. Fisher's paper is a classic in the field and
> is referenced frequently to this day. (See Duda & Hart, for example.)
> The data set contains 3 classes of 50 instances each, where each class
> refers to a type of iris plant. One class is linearly separable from
> the other 2; the latter are NOT linearly separable from each other.   
> Predicted attribute: class of iris plant.      This is an exceedingly
> simple domain.      This data differs from the data presented in
> Fishers article (identified by Steve Chadwick, spchadwick  **'@'** 
> espeedaz.net ). The 35th sample should be:
> 4.9,3.1,1.5,0.2,"Iris-setosa" where the error is in the fourth feature. The 38th sample: 4.9,3.6,1.4,0.1,"Iris-setosa" where the
> errors are in the second and third features.

(source: [[https://archive.ics.uci.edu/ml/datasets/iris](https://archive.ics.uci.edu/ml/datasets/iris)](http://microdatos.dane.gov.co/index.php/catalog/548/study-description))

## Results

The plot compare the actual labels and the clusters built by the model, showing some good results furthermore few wrong cluster points by contiguous clusters

![enter image description here](https://i.ibb.co/yYq2K1C/descarga.png)

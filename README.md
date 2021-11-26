# Road Quality Classification
Automated evaluation of road quality can be helpful to authorities and also road users, who seek high-quality roads to 
maximize their driving pleasure. Our work [1] proposes a model which classifies 
road images into six categories based on the overall surface appearance. The proposed model is based on 
Convolutional Neural Networks (CNN) and achieves 71% accuracy on a test set.


## Road Quality Dataset (RQD)
In [1] we presented a new manually annotated dataset, collected from Google Street View. 
The dataset classes were designed for road motorcyclists, but they might also suit other road users.
The class descriptions and examples can be seen below.


| Class | Description | 
| :-----: |-----------| 
 | 1 | An excellent uniform surface without any repairs, cracks or potholes, having solid curb. Typically a new asphalt surface. The only exceptions are straight fixed longitudinal cracks in the middle of the road to (i.e. close to/instead of the centre line marking, where motorcyclist do not ride. The rider can fully enjoy the ride.| 
 | 2 | Still very good surface with minor repairs of linear cracks ("snakes") in all directions, tiny unfixed cracks, or slightly rougher surface but smooth and homogeneous. Holes, bumps and potholes of any kind are not allowed. The present damages does not affect the safety and riding pleasure.|
 | 3 | Roads have partially cracked surface, large patches, slight unevenness or bumps. An inhomogeneous surface is allowed but without potholes. Riders must pay some attention to the road.|
 | 4 | Roads have an old rough surface, severe alligator cracks, bumps, potholes. Typically also a diverse surface or multi-layer patch repairs.  Riders must pay very close attention to the road, and the fun factor is gone. 
 | 5 | Any unpaved road which is not suitable for a road motorcyclist due to little grip, i.e. cobblestone, forest or dirt road. It could also be a wooden bridge. Only plausible in an emergency with extra caution.
 | 6 | Generally pictures that do not contain roads, or only a small fraction of it not allowing to determine the quality. E.g. images with cars, trees or fields.

![Dataset examples](./media/dataset_examples.png)
### Download 
We prepared two datasets: train and test with the split ratio of 85:15. Both of them can be downloaded from the links below. Images are put into folders 1-6 by the assigned class.

 - [RQD train set](https://drive.google.com/file/d/1xchkTCyCLXhsNCUDWzaEmEzJgxPSkSSB/view?usp=sharing) - used for training and validation
 - [RQG test set](https://drive.google.com/file/d/1vcx-RVM-9xN2RixhTAHS7h0nAZU4_-HB/view?usp=sharing) - only for testing

## Citation
If you find our work helpful or use the dataset, please cite us as:

 ```
@mastersthesis{lank_2021, 
	title = {Road Quality Classification}, 
	author = {Lank, Martin}, 
	year = {2021},
	month = {5},
	school = {Czech Technical University in Prague, Faculty of Information Technology},
	type = {Bachelor's thesis},
	note = {Available also from: \url{https://github.com/lenoch0d/road-quality-classification}}
}
```

 ## References
1. LANK, Martin. Road Quality Classification. Bachelor’s thesis. Czech Technical University in Prague, Faculty of Information Technology, 2021 Available online: [https://dspace.cvut.cz/handle/10467/95571](https://dspace.cvut.cz/handle/10467/95571)

# Road Quality Classification
Automated evaluation of road quality can be helpful to authorities and also road users, who seek high-quality roads to 
maximize their driving pleasure. Our work [1] proposes a model which classifies 
road images into six categories based on the overall surface appearance. The proposed model is based on 
Convolutional Neural Networks (CNN) and achieves 71% accuracy on a test set.


## Dataset
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
 | 6 | Generally pictures that do not contain roads, or only a small fraction of it not allowing to determine the quality. E.g. images with cars, trees, fields,  buildings or [generic "no-imagery" images](https://maps.googleapis.com/maps/api/streetview?size=600x300&location=78.648401,14.194336&fov=90&heading=235&pitch=10&key=AIzaSyA3kg7YWugGl1lTXmAmaBGPNhDW9pEh5bo&signature=zqYzfBsrogHNZdVCFY7rbCPsAjw=0).

![Dataset examples](./media/dataset_examples.png)
### Download 
The datasets can be downloaded from the links below. Images are put into folders 1-6 by the assigned class.

 - [v2](https://drive.google.com/file/d/15ZiW_lPYK66Xwn0rfu-wsOXYfIVMaH_6/view?usp=sharing) - used for training and validation
 - [test set](https://drive.google.com/file/d/11AF89loT8NJuvcugQ0ASNjN41QhKgTGF/view?usp=sharing) - only for testing

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
1. LANK, Martin. Road Quality Classification. Bachelor’s thesis. Czech Technical University in Prague, Faculty of Information Technology, 2021
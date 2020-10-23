<img src="\logo_con_scritta.png"/>
A syntethic Dataset containing 19440 depth maps divided in 54 categories, with one representative 3D mesh model in .OBJ format for each category.
## **Why depthOBJ**
While hundreds of thousand of datasets for coloured RGB images are available on the web, very few and small datasets dedicated to depth maps are actually available for researchers and amateurs. 
Even if the capabilities of RGB images are astounding, the need to explore depth maps, images describing the depth of a scene or an object, is absolutely trivial. Moreover for the fact that this kind of images can be compressed into a single channel, being able to pair them with their corresponding RGB counterparts, opening up to RGB-D images, a powerful yet not-that-much explored tool. 
`depthOBJ` is also engineered to be very easily implementable in Deep Learning applications, thanks to it's easy-to-read taxonomy, studied to be ready to load with Keras' `DataGenerators`.

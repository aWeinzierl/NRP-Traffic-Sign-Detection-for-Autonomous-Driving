* put images to be inserted on backgrounds in directory "to_augment"
* put backgrounds (coco dataset) to directory "coco dataset"
* in python notebook specify classes labels In 20 (var object_names)
* in In91 change the desired number of output images for each class     (images_aug = [img] * 1000)
* run the python notebook
* generated images will be in directory "images"
* generated annotations will be in directory "annotations"
* you can twick the size of inserted images in this line of code ("part = random.uniform(0.08, 0.3)") where 0.08 is min and 0.3 is max
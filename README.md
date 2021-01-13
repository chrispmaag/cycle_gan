# CycleGAN to generate nighttime images from daytime images

CycleGAN allows us to use two distinct piles of images, say daytime and nighttime, and learn a mapping to transform images of one type into the other without needing paired images (like you do in pix2pix). 


## Built With
- TensorFlow


## Results

Converting images from one set of lighting conditions to the other.

[day to night][images/day_to_night]
[night to day][images/night_to_day]

We can also look at the cycle consistency, where we take an input image, pass it to the generator, say from day to night, to get a fake version of the lighting condition. Then we pass that fake image back into the other generator that goes the opposite direction, say from night to day. Ideally after this transformation from day to night and back to day, we are left with an image that looks very similar or consistent to the original image.

[day to day cycle][images/day_to_day_cycle]
[day to day cycle 2][images/day_to_day_cycle_2]
[night to night cycle][images/night_to_night_cycle]


## Contact

- Chris Pontarolo-Maag - [@chrispmaag](https://twitter.com/chrispmaag) - chrispmaag@gmail.com

## License
[MIT](https://choosealicense.com/licenses/mit/)

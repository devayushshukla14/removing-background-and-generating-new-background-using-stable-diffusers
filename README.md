# removing-background-and-generating-new-background-using-stable-diffusers

Input image that I started working with was:

![product1](https://github.com/devayushshukla14/removing-background-and-generating-new-background-using-stable-diffusers/assets/118262157/8a890ebb-decf-45ce-9d46-38244d91f510)

I started by trying to generate 5 different images using GANs. The pretrained stable diffusion model I used was 'dreamlike-art/dreamlike-photoreal-2.0'.
For the first input image, I used the prompt "Generate a background with orange and black background with white foam around on a table" and this generated 5 images that I would be using as background.
![test4](https://github.com/devayushshukla14/removing-background-and-generating-new-background-using-stable-diffusers/assets/118262157/21fecd72-19ce-45ff-bfbc-98de703965b1)

![test3](https://github.com/devayushshukla14/removing-background-and-generating-new-background-using-stable-diffusers/assets/118262157/7ade7b34-5261-4dc2-832d-7560b4f83808)
![test2](https://github.com/devayushshukla14/removing-background-and-generating-new-background-using-stable-diffusers/assets/118262157/8b06297e-a2af-4404-97fc-dbc7fdbc9956)
![test1](https://github.com/devayushshukla14/removing-background-and-generating-new-background-using-stable-diffusers/assets/118262157/285aaddb-1c4c-4db2-ab82-d7a19aa1bbc2)
![test5](https://github.com/devayushshukla14/removing-background-and-generating-new-background-using-stable-diffusers/assets/118262157/33631a99-cff2-4adb-b3c2-97a11ff5e3cb)


# Removing the background part and overlaying it on top of generated background

I used open source model 'rembg' to make a mask and remove the background
I used PIL framework and more specifically the paste() function to achieve the desired result
One of the finished product is:

![final result](https://github.com/devayushshukla14/removing-background-and-generating-new-background-using-stable-diffusers/assets/118262157/4fb20065-e349-4db8-b7da-eb1b6a9ce13d)


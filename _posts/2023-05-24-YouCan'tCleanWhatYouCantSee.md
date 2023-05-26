# You Can't Clean What You Can't See

Deep learning uses a lot of data. Fastai attempts to reduce this requirement, however, my model is still training and testing with roughly 200 images for each animal.
It would take too long to acquire these images manually, and thus we use an internet search feature instead. This doesn't filter the images though, we just assume they 
are the desired content. So what do we do, manually look at each image and delete ones that don't fit? That's going to take a while and fastai has a better idea.

In the second video on the Practical Deep Learning Course, Jeremy explains that its easier to clean the data after training the model. This is because you can sort the
images based on their loss function. So the images which stand out the most to the model will show first. fastai even has a neat GUI to recategorise or remove images,
which is illustrated in the figure below.

![fastai cleaner GUI](/images/cleaner_GUI)

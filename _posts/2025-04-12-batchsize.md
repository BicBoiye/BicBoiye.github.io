# Adjusting the batchsize for the dataloader model

It is not explicitly stated in the fastai course (not that I could find anyways) but to change the batch size to train your model, you need to include the argument "bs" where you load data. This includes the method .dataloader() and the function ImageLoader()
# CNNs_Pytorch_Middle_project
Project Scope: Build a CNN classifier from scratch, on your own data that works on your live stream.

Acquire dataset (Train and Validation):

Grab frames from your camera for 3 classes (your own selection). The amount of data to collect, is decided by you to reach good live performance.

Define pytorch dataset and data loader: Define train and validation datasets and dataloader using dset.ImageFolder(...) with proper transforms. Also plot a few training and validation batches.

Define your CNN network (must use pytorch, and build your own network)

Train your network:

Train the network, print training accuracy and loss per epoch, and also for the validation. Save the best model to disk, and download it. Plot a few validation batches, with their labels and their predictions.

Live model inference: Connect to your laptop camera, grab frame by frame, and plot on the image the classification of the frame. If you did everything right, your model should work quite well.

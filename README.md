# Image-regression practicing
Looking for the center of the person's face in each image.

Using Biwi Kinect Head Pose dataset which was published by  {Fanelli, Gabriele and Dantone, Matthias and Gall, Juergen and Fossati, Andrea and Van Gool, Luc}.

First step download data for creating datablock and dataloader.

Second in Datablock defined find_x for Imageblock and find_y for pointblock which is the center of the person's face.

Third using resnet18 and sigmoid_fun which y range is [-1~1] to train modle.

Fourth find learning rate then see the result.

Finally using new example which was created from OpenCV to verify the modle's result.

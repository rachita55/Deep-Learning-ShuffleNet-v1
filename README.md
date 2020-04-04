# ShuffleNet-v1
Experiments performed on CIFAR-10 dataset using ShuffleNet v1 architecture 


Following Data augmentation techniques were experimented on :
1. Rotation of image (15 degrees)
2. Color jitter (brightness = 1)
3. Crop (32)
4. Horizontal Flip
5. Grayscale (p = 0.1)

We experimented with :
1. With and without normalization
2. Learning rate - 0.1, 0.01, 0.001
3. No. of epochs - 50,60,100 
4. Optimization technique - SGD with momentum (0.9) & decay, Adam
5. No. of groups in ShuffleNet (g=2,g=3)




Assignment participants : 
D19001 Abhilasha Chourasia

D19004 Ankit Das

D19017 Kusum Sharma

D19023 Pradip Sen

D19025 Rachita Pateria

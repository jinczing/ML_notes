# Attribute-Guided Face Generation Using Conditional CycleGAN

### Architecture

![](images\conditional cycleGAN.PNG)

### Algorithm

![](images\cCycleGAN algorithm.PNG)

### Some Note

* If the conditional feature vector always receives the correct attributes,
  the generator network would learn to skip the information in the conditional
  feature vector, since some of the attributes can be found in the low-res face
  image
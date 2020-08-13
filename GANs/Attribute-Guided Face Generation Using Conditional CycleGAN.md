# Attribute-Guided Face Generation Using Conditional CycleGAN

### Architecture

![conditional_cycleGAN](images/conditional_cycleGAN.PNG)

### Algorithm

![cCycleGAN_algorithm](images/cCycleGAN_algorithm.PNG)

### Some Note

* If the conditional feature vector always receives the correct attributes,
  the generator network would learn to skip the information in the conditional
  feature vector, since some of the attributes can be found in the low-res face
  image
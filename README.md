# Art-Generation
This project was built to generate 1 single piece of art(picture) by merging components from 2 input images.
It makes use of Neural Style Transfer.

Neural Style Transfer (NST) uses a previously trained convolutional network, and builds on top of that. The idea of using a network trained on a different task and applying it to a new task is called transfer learning.

NST uses a previously trained convolutional network, and builds on top of that.
Transfer learning is an idea, in which we use a network trained on a different task and apply it to a new task.

#### Computing the Cost function for content image **J<sub>content</sub>(C,G)**
<img src="Images/NST_LOSS.png" style="width:800px;height:400px;">

**Gram Matrix: Also called the 'style matrix'. It compares how similar two vectors are, using np.dot()**

<img src="Images/NST_GM.png" style="width:900px;height:300px;">

**Content Image Used by me:**

<img src="Images/koifish.jpg" style="width:400px;height:400px;">



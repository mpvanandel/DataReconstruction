# Exploring the Security Boundary of Data Reconstruction via Neuron Exclusivity Analysis
In this repository we provide an attempt to reconstruction of two figures in the paper: "Exploring the Security Boundary of Data Reconstruction via Neuron Exclusivity Analysis". In the paper, the method they provide is compared to two other methods, namely "Deep leakage from gradients" and "Inverting gradients". These two methods have a git repository, which we made submodules of our repository. These two repositories can also be found here.

[Deep leakage from gradients](https://github.com/mit-han-lab/dlg)

[Inverting gradients](https://github.com/JonasGeiping/invertinggradientsz)

Our code can be found in ```DataReconstruction.ipynb``` There we provide a way to load data from Retina MNIST, we give a full implementation of the first 2 parts of the algorithm and we give some outline for the last part. But due to some things that were not mentioned clear enough in the paper, there is no full implementation of the algorithm and the algorithm is made following some assumptions, which are all further explained in the blog post.



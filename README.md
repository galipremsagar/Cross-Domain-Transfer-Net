# Cross-Domain-Transfer-Net


Generative Adversarial Networks have been successful in generating novel (but convincing) images for a dataset. We wanted to experiment with different applications of GANs. We explored unsupervised domain transfer from an image of domain S to an image of domain T without any mapping data. We extended the approach presented in this paper for four set of domains, analysing the adaptation of the architecture on different distributions and evaluated the models. We achieved similar results for digits datasets but not faces, finding that compute resources and training strategies play a vital role in successful implementation. We tried to extend the work done for evaluation by the authors in the original work quantitatively and qualitatively.


# Experiments

Digit Transfer : SVHN to MNIST

Face Transfer: CelebA to Emoji/Simpson/Cartoons


To Run the server, Run app.py: `python app.py`

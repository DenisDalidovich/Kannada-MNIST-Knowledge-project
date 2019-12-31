# Kannada-MNIST-Knowledge-project

The purpose of this Kaggle Knowledge competition is  to practice training convolutional neural networks (CNN) using dataset other than famous MNIST dataset. The dataset used in the competition is the recently-released dataset of Kannada digits. Kannada is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers and is written using the Kannada script. Extensive information about the language and its speakers can be found at

https://en.wikipedia.org/wiki/Kannada

Tha dataset consists of 10 distinct digits that have no resemblance to the usual arabic numerals.
One can see how the Kannada digits look like as well as download the original datasets by visiting the Kaggle webpage

https://www.kaggle.com/c/Kannada-MNIST


The code provided below was used in the aforementioned competition. This competition was Knowlege-type one, and its purpose is to practice rather than to find hyperparameters leading to a perfect score. The competition was kernel-based meaning that one had to commit and run the whole code first on the Kaggle provided GPU before generating a submission file. The submission was scored on both the public test set, as well as a private (unseen) test set. Since it takes enormous amount of time 
to run it on CPU, it is feasible to run it only if one has access to GPU.

The CNN architecture provided here allowed to achieve the accuracies 0.99851 and 0.99430 on the custom made training and evaluation sets, and 0.98820 on both public and private test sets. 

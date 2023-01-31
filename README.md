# Microsoft-Rice-Disease-Classification-Challenge


Identifing disease types in images of rice grown in Egypt.

I used two different approaches for this challange.

Fastai
Pythorch Lightning
Fastai approach ~ 0.042 9th place in private LB

The file fastai.ipynb has this approach and It goes though all the processes starting from loading the data. I used different pretrained models from Vision transformer, Convnext and Swin-Transformer. all the models are found in here. For all the models a size of 224x224 and only the RGB images are used.

Lightning approach ~0.056 in private LB

The file lightning.ipynb has this approach. In this approach in addition to the fastai approach I tried to use the RGN images also but it didn't go well. here a single model with different folds prediction method is used. I haven't yet finshed the experment yet.

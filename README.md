### Butterfly Segmentation In Wild 🦋
___
<div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="doc/1.png" height="185" width="185" style="border-radius:3px;border:solid 1px #666" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="doc/2.png" height="185" width="185" style="border-radius:3px;border:solid 1px #666" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="doc/3.png" height="185" width="185" style="border-radius:3px;border:solid 1px #666" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="doc/4.png" height="185" width="185" style="border-radius:3px;border:solid 1px #666" />
</div>

___

> Dataset Link : [Kaggle](https://www.kaggle.com/veeralakrishna/butterfly-dataset)

> Results

#### Convolutional AutoEncoder 

<img src="doc/conv_auto_encoder.png" style="background:whitesmoke;padding:10px 20px;"/>

* pretty much overfitting but i'll cross validate it later.

> Epoch Results 

![](doc/conv_epochs.gif)

> Loss Over Epochs 
<p align="center">
<img height="300" src="doc/conv_auto_encoder_loss.png" />
</p>

___

#### U-Net

<img src="doc/unet_output.png" style="background:whitesmoke;padding:10px 20px;"/>

* pretty much overfitting but i'll cross validate it later.

> Epoch Results 

![](doc/unet_epochs.gif)

> Loss Over Epochs 
<p align="center">
<img height="300" src="doc/unet_loss.png" />
</p>

> And Finally The Architecture Used.

<p align="center">
<img src="doc/unet.png" width="100%" height="70%" />
</p>
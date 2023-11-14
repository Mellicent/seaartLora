# Creating LORA

In this article, I will guide you on how to create your own LORA. Since my computer is not very powerful, I will be using the Seaart.ai website.

## Getting Started

Firstly, we need to determine what we want to train LORA on. You can train it on a specific character or a particular artistic style. In my case, I will be training LORA on my own art pieces to later generate them as references. After all, it's not theft if you steal from yourself :-)

For example, here's one of my works:


<p align="center">
  <img src="https://i.ibb.co/3mTxWGw/78-LLFZs5-Ec-I.jpg" alt="Artwork Example">
</p>


# Selecting and Refining Artworks

For this step, follow these instructions:

1. Choose up to 100 drawings.
2. Download all the drawings into a single folder on your computer.
3. Adjust their resolution to a square format compatible with the neural network, such as 512 x 512, 780 x 780, or 1024 x 1024.
   
You can quickly accomplish this using the following website: [BIRME](https://www.birme.net/).

<p align="center">
  <img src="https://i.ibb.co/XkHHT4S/BTGDA2y-UWIU.jpg" alt="Choosing images">
</p>
<p align="center"><i>Choosing images</i></p>



# Handling Artwork Size

If an artwork cannot fit into a square, I sometimes divide it into two parts. The key in framing is to focus on the correct composition rather than fitting the entire figure into the frame.

Avoid doing it like this:

<p align="center">
  <img src="https://i.ibb.co/BGpS6vt/4o-Vsid0-Jm-E.jpg" alt="One figure in the midst of emptiness, but it's a full-body shot">
</p>
<p align="center"><i>One figure in the midst of emptiness, but it's a full-body shot</i></p>


In this case, it's much better to crop it. Yes, it will become a portrait, but LORA won't be adding figures of people in the middle of a gray background:

<p align="center">
  <img src="https://i.ibb.co/WxtmvRp/dmx-Y9-Gj-DFes.jpg" alt="Portrait, on the other hand, maintains proper composition.">
</p>

<p align="center"><i>Portrait, on the other hand, maintains proper composition</i></p>


Furthermore, LORA can retrain if there are too many artworks, so it's better to keep only high-quality ones; otherwise, you may end up with something like this:

<p align="center">
  <img src="https://i.ibb.co/2tXzdSh/BHFW0qw2-Zy-Q.jpg" alt="Overtrained Mellicent_digital LORA">
</p>

<p align="center"><i>Overtrained Mellicent_digital LORA</i></p>


# Uploading Dataset

To upload the dataset:

1. Register on Seaart, then go to AI Model.
2. In the AI Model section, LORAs are trained.
3. Click on "Create Dataset."

<p align="center">
  <img src="https://i.ibb.co/pvyqTRw/zcy-YD-u-Ubnk.jpg">
</p> 


Name your dataset (a set of images) and choose a category

<p align="center">
  <img src="https://i.ibb.co/gmTKLg4/5e-Azo85-TF3-U.jpg">
</p> 


Next, upload all the images into the dataset

<p align="center">
  <img src="https://i.ibb.co/wh9NMKD/zv-K-Xi-XXv-VI.jpg">
</p> 


*MAKE SURE TO SAVE THE DATASET.*


# Training LORA

Press "Train LORA."

<p align="center">
  <img src="https://i.ibb.co/jZqYmnk/5ke-N-w-Rs8-Ek.jpg">
</p> 


Here you need to decide which model you will use to train your LORA. Since my drawings always have a bold black outline, I will choose the HICCUP model.

<p align="center">
  <img src="https://i.ibb.co/31SD1TQ/Df-DId2-c1-Ic.jpg">
</p> 


# A comparison between a generic DCGAN and a artificially generated DCGAN with ChatGPT

This project contains two different DCGANs. One is been generated manually according to pytorch documentation and the other one is been built with the response of ChatGPT engine. The goal is to see if an AI can generate another AI that generates images. 

In this case, the AIs have been trained with bird images, so the generated images correspond to birds. The algorithms have been built using pytorch engine.

## ChatGPT AI

The prompt used for ChatGPT is: Generate a DCGAN algorithm that generates 3 color channel images using pytorch

The resultant DCGAN looks like the following image. The discriminator neural network has been edited to correclty correspond to the image sizes.

![chatGPT_DCGAN_Model](https://user-images.githubusercontent.com/39961776/216306676-2776cfe0-670a-4067-a6c5-660f00c37667.png)


![chatgpt_bird_generation](https://user-images.githubusercontent.com/39961776/216306063-db99295f-5ec4-4c20-9ab1-73029bdbbb8b.gif)


## Manually generated DCGAN

The manual DCGAN algorithm is simpler and smaller

![DCGANModel](https://user-images.githubusercontent.com/39961776/216307671-3443622c-1fc5-44f6-bff6-f9c8c9a83351.png)
![bird_generation](https://user-images.githubusercontent.com/39961776/216307724-82877f1f-d819-49a6-aeca-e008a33bd9fd.gif)

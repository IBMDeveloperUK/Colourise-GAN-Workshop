# Intro to Generative Adversarial Networks (GANs)

In this workshop you will learn what a Generative Adversarial Networks (GAN) is and have a play with compling
an running your own one in IBM Watson Studio.

The GAN in this case is written using the PyTorch library and will be used to add colour to black and white images.

## Recording

A recording of this workshop being presented on 20th August 2020 is available at: https://www.cinnamon.video/watch?v=390993078330066941

## Getting Started with Jupyter Notebooks

Jupyter notebooks are an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text.

In this workshop we will use IBM Watson Studio to run a notebook. For this you will need an IBM Cloud account. The following steps will show you how sign up and get started. When you have the notebook up and running we will go through the notebook.
IBM Cloud

- [Sign up](http://ibm.biz/introgans_matt) for an IBM Cloud account

- When you are signed up click Create Resource at the top of the Resources page. You can find the resources under the hamburger menu at the top left:

 ![](https://github.com/IBMDeveloperUK/Colourise-GAN-Workshop/blob/master/images/Create_resource.png)
 
- Search for Watson Studio and click on the tile:

![](https://github.com/IBMDeveloperUK/Colourise-GAN-Workshop/blob/master/images/studio.png)

- Select the Lite plan and click `Create`.
- Go back to the Resources list and click on your Watson Studio service and then click `Get Started`. 

![](https://github.com/IBMDeveloperUK/Colourise-GAN-Workshop/blob/master/images/launch.png)

## IBM Watson Studio

### 1. Create a new Project

![](https://github.com/IBMDeveloperUK/Colourise-GAN-Workshop/blob/master/images/watson_get_started.png)

- You should now be in Watson Studio.
- Create a new project by clicking on `Create Project` under `Start working`
- Select `Create and Empty Project`
- Give your Project a name.
- Select an Object Storage from the drop-down menu or create a new one for free. This is used to store the notebooks and data. **Do not forget to click refresh when returning to the Project page.**
- click `Create`.

## 4. Load and run a notebook

-  Add a new notebook. Click `Add to project` and choose `Notebook`:

![](https://github.com/IBMDeveloperUK/Colourise-GAN-Workshop/blob/master/images/notebook.png)

- Choose new notebook `From URL`. Give your notebook a name and copy the URL `https://github.com/IBMDeveloperUK/Colourise-GAN-Workshop/raw/master/Colourise_GAN_64.ipynb`
- Select the custom runtime enviroment that you created and click `Create Notebook`. 
- The notebook will load. 
 
You are now ready to follow along with the workshop in the notebook!

## Credits

Code for the GAN in this workshop is based upon code in the following two other repositories:

- https://github.com/zeruniverse/neural-colorization
- https://github.com/15101538237ren/Colorizing-with-GANs-PyTorch
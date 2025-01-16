=========================================================================================================
 - AAFAQ AHMED
 - iffiafaq123@gmail.com


# PROJECT TITLE: 
           "Text to Image Machine Learning Project" 
        

## FEATURES: 
        -This project is basically convert text to images using machine learning.
        -It is using pre-trained models.
        -It is easy to use.
        -Easy to customize.

## REQUIREMENTS:
         Python 3.12
         Libraries:
                 -diffusers
                 -torch 
                 -matplotlib

 

# Step by step requirement process in Jupyter Notebook explained:

Step 1: Open Anaconda Prompt

Step 2: Create and Activate Your Environment using code:  

              "conda create --name text2pic python=3.9 -y
              "conda activate text2pic"

Step 3: Install Jupyter Notebook in "text2pic" environment code:

           "conda install notebook -y" 

Step 4(a): Install PyTorch with CUDA support (for GPU) code:

      "conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia"

Step 4(b): Install PyTorch if you don't have a GPU (for CPU) code:
      
             "conda install pytorch torchvision torchaudio cpuonly -c pytorch"

Step 5: Install the diffusers library using pip:

              "pip install diffusers"

Step 6: Install other required libraries using pip:

              "pip install transformers accelerate scipy"

Step 7: Install "diffusers" using "pip" while the "text2pic" environment is active:

               "pip install diffusers"

[NOTE] If current installation "sympy" version is 1.13.3 and "torch" explicitly requires
         "sympy" is version 1.13.1, then you should downgrade your sympy version to match
         the requirements.

Step 8: Now OPEN Jupyter Notebook inside "text2pic" environment.


## IMPORTANT:
        If you want to generate image.
        STEP-1.
         Prompt: Type "text" inside string, what kind of image you want to generate.
         Example: Prompt="make a picture of sleeping cat"
        
        STEP-2.
         Negative Prompt: Type "text" inside string, what you dont want in the scene.
         Example: Negative Prompt= "avoid including any other animal in the scene."

        STEP-3.
         Run the code. It will generate the image.

        Step-4.
         to preview the image, run this code in the cell.
          
          plt.imshow(images)
          plt.axis("off")
          plt.show

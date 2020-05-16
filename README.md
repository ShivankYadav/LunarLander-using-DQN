# Deep Q-Learning on LunarLander-v2
We apply DQN algorithm to make and artificial agent learn how to land space-craft on moon. The code is explained in the [Deep_Q_network.ipynb](https://github.com/ShivankYadav/LunarLander-using-DQN/blob/master/Deep_Q_Network.ipynb). You guys are welcome to imporve the hyperparameters or even the algorithm for better performance(check step 5:Explore of the notebook). I have also provided a [PDF_research_paper](https://github.com/ShivankYadav/Q-Learning-on-Blackjack/blob/master/MinorProject.pptx) to explain **Deep Q-Networks**. This project is based on this research [paper](https://www.nature.com/articles/nature14236).

## Environment Description
https://gym.openai.com/envs/LunarLander-v2/

## Install requirements
Simply execute this on your shell: ```$pip install -r ```[requirements.txt](https://github.com/ShivankYadav/LunarLander-using-DQN/blob/master/requirements.txt)

**Note**: The user must install pytorch according to the specifications on his/her workspace. I used 
torch                     1.4.0 and 
torchvision               0.4.2.

You can skip running the dqn method to avoid train and just run the code using pretrained weights in [checkpoint.pth](https://github.com/ShivankYadav/LunarLander-using-DQN/blob/master/checkpoint.pth) i have provided.


## Algorithm used:
!["Algorithm_image"](https://github.com/ShivankYadav/LunarLander-using-DQN/blob/master/images/dqn_algo.png)

## Before training
!["Gif"](https://github.com/ShivankYadav/LunarLander-using-DQN/blob/master/images/learning.gif)

## After training
!["Gif"](https://github.com/ShivankYadav/LunarLander-using-DQN/blob/master/images/trained.gif)

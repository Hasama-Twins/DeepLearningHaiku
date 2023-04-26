# Haiku Generator from Photo
by Summer and Evelyn Hasama

**Link to [Google Colab](https://colab.research.google.com/drive/10c8s3OMpfmYegwXHPN35EXQsFH6s_AsS?usp=sharing)**

## Abstract

Generate a haiku (a Japanese 5-7-5 syllable poem often relating to nature) using deep learning. To make things a bit more interesting, take a photo as input and use an existing object detection model to determine keywords. We would then put these keywords in our haiku text generating model based on GPT2. Evaluate the generated haikus using BERTScore.

## How to run the code

1. Open the [Google Colab](https://colab.research.google.com/drive/10c8s3OMpfmYegwXHPN35EXQsFH6s_AsS?usp=sharing)
2. Run all cells 

## How to view the notebook with outputs

If the Python notebook is not rendering in GitHub, you can view it by pasting the github link (https://github.com/Hasama-Twins/DeepLearningHaiku/blob/main/DeepLearningHaiku.ipynb) into [NBViewer](https://nbviewer.org/)

## Planning

### Previous solutions: 
- [Generating Haiku with Deep Learning (Part 1)](https://towardsdatascience.com/generating-haiku-with-deep-learning-dbf5d18b4246)
- [Deep Haiku: Teaching GPT-J to Compose with Syllable Patterns](https://towardsdatascience.com/deep-haiku-teaching-gpt-j-to-compose-with-syllable-patterns-5234bca9701)
- [Generating and Evaluating Japanese Haiku Poems with Deep Language Models](https://www.nvidia.com/en-us/on-demand/session/gtcspring21-p31430/)   

### Related databases:
- [Haiku Dataset - bfbarry](https://www.kaggle.com/datasets/bfbarry/haiku-dataset)

### Expected result:
- Generate a haiku (5-7-5) relating to an input photo
- Example Input:  
  ![morning_coffee](https://user-images.githubusercontent.com/69527370/224106895-9572690e-fa20-4df9-b1cf-5193c6be7ad7.jpeg)
- Example Output:  
  ![haiku_coffee](https://user-images.githubusercontent.com/69527370/224106832-2998b638-ad8c-4595-a5a6-56b64c8c16e9.png)

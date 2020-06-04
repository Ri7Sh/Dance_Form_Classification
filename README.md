# Dance_Form_Classification

## Hackerearth Deep Learning Challenge - Identify the dance form



### Problem statement
This International Dance Day, an event management company organized an evening of Indian classical dance performances to celebrate the rich, eloquent, and elegant art of dance. After the event, the company plans to create a microsite to promote and raise awareness among people about these dance forms. However, identifying them from images is a difficult task.

You are appointed as a Machine Learning Engineer for this project. Your task is to build a deep learning model that can help the company classify these images into eight categories of Indian classical dance.

### Note

The eight categories of Indian classical dance are as follows:

- Manipuri

- Bharatanatyam

- Odissi

- Kathakali

- Kathak

- Sattriya

- Kuchipudi

- Mohiniyattam



### Data description
This data set consists of the following two columns:

| Column Name | Description |
| ----------- | ----------- |
| Image | Name of Image |
| target | Category of Image ['manipuri','bharatanatyam','odissi','kathakali','kathak','sattriya','kuchipudi','mohiniyattam'] |

- The data folder consists of two folders and two .csv files. The details are as follows:

**train**: Contains 364 images for 8 classes ['manipuri','bharatanatyam','odissi','kathakali','kathak','sattriya','kuchipudi','mohiniyattam']

**test**: Contains 156 images

**train.csv**: 364 x 2

**test.csv**: 156 x 1


### Model Accuracies

**Simple CNN model** 20 epochs validation accuracy - 50% accuracy score(100* f1_score) on test set - **43.97087**

**CNN model with data augumentation** 20 epochs validation accuracy - 46.64% accuracy score(100*f1_score) on test set - **45.08884**

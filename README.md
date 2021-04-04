# GooglePlayStore

## Source of the dataset
The dataset is obtained fom [Kaggle Website](https://www.kaggle.com/#). The specific download link is [here](https://www.kaggle.com/lava18/google-play-store-apps#).

This is a web scrapped data of around 10K PlayStore Apps for analysing the Android market.

# Inspiration

Android is dominating this market of smartphone operating system and the apps for the same are hosted by Google Play Store.In this era of digital marketing,we felt that this data on PlayStore Apps can be used and actionable insights can be drawn for developers to work on.

## Structure of the data

The dataset contains the following variables with the corresponding descriptions:

1. App: Application Name
2. Category: Category the app belongs to
3. Rating: Overall rating of the app, as when screpped.
4. Reviews: Number of User Reviews of the app, as and when scrapped.
5. Size: Size of the app
6. Installs: Number of user-Downloads/Installs for the app.
7. Type: Paid or free
8. Price: Price of the apps
9. Content Rating: Age group the app is targeted at- Children/ Mature 21+? Adult etc
10. Genres: An app can belong to different Genres (Apart from its main Category) For ex: A Game app which belong to "Games" Category might have "Arcade", "Action and Adventure", "Puzzle" etc as Genres
11. Last Updated: Date of last updation of the App
12. Current Version: Current Version of the app
13. Android version: The Android version in which the app is supposed to work

## Aim of the study

The primary aim of our analysis is to analyse the apps that are paid so that the app developer who creates an a paid app, may have a understanding on the price segment that they should target for better revenue generation and higher installation by the end users.


## Installing / Getting started

The analysis was conducted using Python 3.7.4 in the Jupyter Notebook.

Minimal setup required:

1. Python -- 3.7.4
2. Jupyter Notebook

Also apart from the Python core packages, Numpy  and Pandas are used for numerical computations and Data analysis respectively. For graphical analysis, we have used Seaborn as well as Plotly. Note that all the packages (except Plotly) are included in the Anaconda Distribution itself and can be used directly. For Plotly, separate installations are requiered.
To install Plotly, following codes can be run in the Bash Prompt.

```shell
pip install plotly
```
or using conda

```shell
conda install plotly
```
Once the libraries are set up, kindly clone the repository with the following command

```shell
git clone https://github.com/satarupa5/GooglePlayStore
```
Then you can run the [Notebook](/EDA_Final.ipynb)  containing all the  analysis

## Flow of the project
The data is a real world data and hence first the data is cleaned, missing data treated, duplicate apps removed and made sure the data is ready for numerical treatment.Each column has its own challenges that needed to be taken care of.

Next we explore interesting patterns in the data using EDA (Exploratory Data Analysis) techniques.This includes answering interesting questions like how is rating distributed over all apps, which category apps are most downloaded, and which category apps are less downloaded etc.

In the third stage, we move on to our primary objective of analysing the paid apps vis-a-vis their Installations and revenue generation. Finally basis our findings, we try to make recommendations to the App developers regarding the pricing of the Apps which might bring greater revenue.


## Status
The Project is still in progress.

## Road Ahead
Text Analysis (Sentiment Analysis) can be done on the basis of the textual data of reviews for the apps for understanding the consumer sentiments, as the rating varibale may not be sufficient to understand the people's sentiments.

## Development

 Want to contribute? Great!

 To enhance the existing analysis, follow these steps:

 - Fork the repo
 - Create a new branch (`git checkout -b improve-feature`)
 - Make the appropriate changes in the files
 - Add changes to reflect the changes made
 - Commit your changes (`git commit -am 'Improve feature'`)
 - Push to the branch (`git push origin improve-feature`)
 - Create a Pull Request

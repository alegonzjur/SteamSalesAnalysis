
# Steam Sales Historical Dashboard

## [Dataset](https://www.kaggle.com/datasets/benjaminlundkvist/steam-sales-historical-dataset)

## Introduction

Steam, for those who don't know, is a digital video game distribution platform developed by Valve Corporation. It's the most popular video game platform on computers by far. Steam provides the user plenty of functions that makes playing games much easier, such as game installation & automatic updates, video transmission, cloud save, social media (friend list, matching servers, chat...)  It is used by both small developers and large industry teams for the distribution of video games and related multimedia material.

This dataset provides a detailed historical record of Steam game sales, capturing discounts, prices, and availability across Windows, Linux, and macOS platforms. Updated weekly, it allows tracking of game prices and discount trends over time.

## Column Names

Each entry of the dataset includes the following columns:

| Column Name          | Description                                      |
| -------------------- | ------------------------------------------------ |
| `Game Name`          | Title of the game on Steam.                      |
| `Rating`             | Average Steam user rating (out of 100).          |
| `# Reviews`          | Total number of reviews submitted by users.      |
| `Discount %`         | Current discount percentage applied to the game. |
| `Price (€)`          | Current discounted price in €.                   |
| `Original Price (€)` | Original price in € before discount.             |
| `Release Date`       | Official release date of the game.               |
| `Windows`            | 1 if available on Windows, 0 otherwise.          |
| `Linux`              | 1 if available on Linux, 0 otherwise.            |
| `MacOS`              | 1 if available on macOS, 0 otherwise.            |
| `Fetched At`         | Timestamp of when the data was collected.        |

## Dashboard

<image src="images\Summary.gif" alt="Summary">

## Pages


<image src="images\d_p1.png" alt="Page1">

<image src="images\d_p2.png" alt="Page2">

<image src="images\d_p3.png" alt="Page3">

<image src="images\d_p4.png" alt="Page4">

## Conclusions

Lots of conclusions can be obtained from this dataset. It should be made clear that there are many more games in the Steam database, as anyone can create a game and upload it. This dataset only includes games that have ever had offers. The dataset is composed by 736 games. 

I have classified some columns in categories to show important information about them. Two examples are "Price Range" and "Ratings Category". The first one divides the game original price into "Economic Game" (less than €10), "Medium Game" (between €10 & €30), "Premium Game" (between €30 & €60) and AAA (€60 or more).  On the other hand, ratings category divides game rating into "Negative Reviews" (less than 50), "Mid Reviews" (between 50 & 70), "Good Reviews" (between 70 & 85) and "Excellent Reviews" (85 or more). From this categories, the predominant games are medium games and well reviewed games.

The amount of games released goes up every year, which makes sense due to the fact that games can be made easier than before, and more people know how to develop games. Windows is the platform that supports the most games.

The biggest discounts usually come older games. August is the month with most releases, followed by September, October and March.

To wrap up, this dataset gives us really good insights about games and trends from developers. Different information about individual games, game sagas, reviews, releases, etc. Fun dataset to work with.




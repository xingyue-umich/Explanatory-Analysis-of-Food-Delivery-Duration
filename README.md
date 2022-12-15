# :ramen: SI 618 Final project - Why is my food delivery taking so long?

## An Explanatory Analysis of Food Delivery Using Doordash Data

Whenever I place an order on DoorDash, I will receive an estimated delivery time. The food I
order usually arrives within the given time range, but sometimes when the weather is poor or
during rush hour, it takes forever for it to reach me. \
As a customer who does not wish to wait forever for my food delivery, I
would like to use data analysis skills to examine what influences delivery duration and how well
we can predict it. Meanwhile, for a company like Doordash, a reasonable delivery time estimate
is very important, since it has a significant impact on customer satisfaction.

## Data Source

The dataset I will be using in the project is from the take-home assignment in the recruitment
process for the data science positions at DoorDash. It is publicly available on the [stratascratch](https://platform.stratascratch.com/data-projects/delivery-duration-prediction)
website. The data contains a subset of DoorDash deliveries received in early 2015 in a subset of
cities. Each row in this file represents a unique delivery. There has been noise added to the
dataset by DoorDash in an attempt to obscure certain details of the business. \
This dataset contains 197428 orders and 15 features including city/region id, restaurant type,
food price, number of available dashers, and other critical features to explore these orders. A
detailed description of features will be found on the stratascratch website.

## Research Questions

There are three major questions I want to explore for this dataset:
<ol>
<li> How does time affect the delivery time? </li>
    <ul>
    <li> Does delivery time vary with the day of the week? </li>
    <li> Will the order take longer to arrive during rush hour? </li>
    </ul>
<li> Is there a difference in delivery time between different prices and types of food? </li>
    <ul>
    <li> Does the expensive food take longer to arrive? </li>
    <li> Does restaurant type have some impact? </li>
    </ul>
<li> How well we can predict the delivery time? </li>
    <ul>
    <li> What features are important and what are not? </li>
        <ul>
        <li> Can we use PCA to reduce the dataset dimensions while still preserving
the most of information? </li>
        </ul>
    <li> Which model gives us the most accurate prediction and how accurate is it? </li>
    </ul>
</ol>

## Please check the report for details on methods and results

## Installing

In order to configure this project, please clone the repository to your local system.

    ``` git
    git clone https://github.com/xingyue-umich/Explanatory-Analysis-of-Food-Delivery-Duration.git
    ```

## Build With

- Python3

- Packages:
    - pandas, numpy have been used for data manipulation
    - seaborn, matplotlib have been usd for data visualization

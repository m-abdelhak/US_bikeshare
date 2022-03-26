# US_bikeshare [^Note]

Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.

It is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, We will use data provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. You will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

## The Datasets
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

- Start Time (e.g., 2017-01-01 00:07:57)
- End Time (e.g., 2017-01-01 00:20:53)
- Trip Duration (in seconds - e.g., 776)
- Start Station (e.g., Broadway & Barry Ave)
- End Station (e.g., Sedgwick St & North Ave)
- User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:

- Gender
- Birth Year

The original files are much larger and messier, and we don't need to download them.

## Statistics Computed

We will learn about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, the code is to provide the following information:

#### 1. Popular times of travel (i.e., occurs most often in the start time)

> most common month
>
> most common day of week
>
> most common hour of day

#### 2. Popular stations and trip

> most common start station
>
> most common end station
>
> most common trip from start to end (i.e., most frequent combination of start station and end station)

#### 3. Trip duration

> total travel time
>
> average travel time

#### 4. User info

> counts of each user type
>
> counts of each gender (only available for NYC and Chicago)
>
> earliest, most recent, most common year of birth (only available for NYC and Chicago)

## The Files

To answer these questions using Python, we will need to write a Python script. we can find files in the repository

- chicago.csv.zip
- new_york_city.csv.zip
- washington.csv.zip

All of these files are zipped, and to run the project in your machine you need to unzip them, and save them in the same project file directory.

[^Note]: Udacity Data Analysis Professional Nanodegree Program Graduation Project #1

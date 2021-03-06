# cyclistic_divvy
Case study 1 for Google Data Analytics class.

![A logo of Cyclistic company](cyclistic_logo.png)

In this case study, I am working as a junior data analyst for a fictional company, Cyclistic Divvy, which is a bike-share company in Chicago. In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.

# Ask

The director of marketing, Lily Moreno, set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to
do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why
casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are
interested in analyzing the Cyclistic historical bike trip data to identify trends.

# Prepare and Process

- Data: trip data from this [link](https://divvy-tripdata.s3.amazonaws.com/index.html).
- Analytics tool: R programming for 2 main reasons:
    - The data is big (more than 1 million rows per file) so working with a spreadsheet is slowly and lagging
    - Easy to reproduce the code and findings

# Analyze

- Code: in the `code` folder, we have an [Rmd code file](code/01_Cyclistic.Rmd).

- Some key findings are:

1. Member and casual rides very differently in both the number of rides and ride length

![Fig 1. Member vs. casual rides](fig/fig1_casual_member.png)

2. Casual rides more often on weekend

![Fig 2. Rides by day of week](fig/fig2_by_weekdays.png)

3. Member rides more frequently out of working hours

![Fig 3. Rides in and out of working hours](fig/fig3_by_working_hours.png)

# Share 

- Presentation of the results: [Google slide](https://docs.google.com/presentation/d/1b1iyuXeipWlrtTCtgPX3YKdnJyvH0zPJM-VqOaRT40E/edit?usp=sharing)

# Act

I make a slide with three recommendations in the slide:

- Price policy regardings to balance the number of trips and ride length
    - E.g., cheaper unit price for long ride length for member
- Should have price-difference policy for weekend
    - E.g., cheaper unit price for member on weekend to encourage membership from casual
- Should have price-difference policy for working hours
    - E.g., higher unit price for working hours when high demand

# Contact

- Dien Giau Bui (Richard)
- Email: buidiengiau@gmail.com

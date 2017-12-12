# Summary
In this project I will take face value ticket prices from TicketMaster for concerts in the largest US markets, as well as prices for tickets on resale markets (TicketMaster resale, SeatGeek), along with data on artist and genre popularity to predict markups on secondhand concert tickets.

## 1. Question
What determines the price of a concert ticket in the secondary market? Understanding this question can help artists and tour promoters more accurately price tickets and gage demand for tickets.
Consumers may also find such a tool helpful in determining when ahd how to buy and sell tickets

## 2. Data Gathering
I gather data from 4 sources:
    1. Ticketmaster API (Face value price information)
    2. SeatGeek API (Resale value price information)
    3. Stubhub API (Resale value price information)
    4. Spotify (Popularity information on artists)

The concerts data is matched between sources based on datetime and venue name, under the assumption that a venue only has a single event at a given time. I include a few notes on how the venues were matched in the 'Venue Matching Notes' notebook.

## 3. Data Exploration and Feature Engineering
## 4. Machine Learning
## 5. Final Analysis
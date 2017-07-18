# test

# RECOMMENDATIONS TO IMPROVE THE SERVICE
I found different types of problems related either to streams, ISPs or browsers. I’ll write the general conclusion here, the details of my approach can be found in the notebook. In what follows, we will refer to connected to the backend as ON and not connected to the backend as OFF. A good rate will refer to a p2p/cdn rate superior to 60%, a bad rate will refer to a p2p/cdn rate inferior to 60% and a zero rate will refer to a p2p/cdn rate exactly equal to 0:

### STREAMS:
- there is a problem with streams 4 and 8: most people downloading these streams have a bad p2p/cdn rate (close to 0% for al ISP except BTP that has a 50% rate). If we solve this problem we will be highly improving our service to our customers as these streams represent at least 90% of their downloads (close to 99% for Fro, Arange and BTP).
- there is a problem of connection or sharing for streams 3 and 6: most people on these streams are ON with a zero rate. What does that zero rate means? It could mean for instance that people actually are OFF but they appear as ON.

### ISP
- Olga seems to have a general problem of bad p2p/cdn rate.
- Datch Telecam seems to have a general problem of connection to the backend: 80% of its viewers are OFF and they represent 80% of the total amount of downloads of Datch Telecam

### BROWSERS
- Vectrice has a problem of connection: almost 100% of its users have a zero rate.
- Swamp seems to have a similar problem: 50% of its downloads are from users that have a zero rate.  

### VIEWERS
If ISPs are focused on end-consumer experience quality, we should then focus on improving the streams that most customers are downloading. Maybe ISPs do not want a majority of their customers to experience lags due to bad rates or zero rates …In this sense we can recommend to focus on the most important streams in terms of customers where a lot of customers are more likely to be experiencing lags:
- Arange: 
    - stream 3 (27% of total customers) where 25% customers have a zero rate
    - stream 4 (15% of total customers) where around 14% have a bad rate
- BTP:
    - stream 8 (27% of total customers) where around 25% customers have a bad rate
    - stream 3 (17% of total customers) where around 15% have a zero rate
- Fro:
    - stream 3 (22% of total customers) where 18% customers have a zero rate
    - stream 4 (12% of total customers) where around 11% have a bad rate
- Datch Telecam :
    - stream 7 represents 80% of Datch Telecam customers and 75% of them are OFF
- Olga:
    - stream 5 represents 75% of Olga customers where 60% customers have a bad rate, 10% have a zero rate and 5% are OFF.

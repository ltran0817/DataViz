# Final Project
### Team Member(s):
- Lam Tran
### Task(s) picked:
- Task 2: For those trips that could not be served, do they follow a spatial or temporal pattern? For example, are most of those trips originated in particular regions, and of certain times?
### Link to visualization:
- [Source Code](https://bl.ocks.org/ltran0817/06399328bb12155b8cd80481ee00a73d)
## Reproduce
1. Extract data from `request.csv`and store as object with `hour` and `request_count`
    1. `requested` : `{"hour": ... , "request_count": ...}` - Number of request per hour from the data set.
    2. `unserved` : `{"hour": ... , "unserve_count": ...}` - Number of unserve request per hour from the data set.
    3. `countByHour` - An array of servered, unserved, served ratio
    4. `rateByHour` - Trip requested but unable to serve
2. Construct a bar plot

3. Plot "fail to serve" points to Manhattan map

## Conclusion
1. The serve rate is at highest at "very early" in the morning (1-6am) and lowest in the afternoon (7pm-11:59pm):
    - ![DVfinal1](https://user-images.githubusercontent.com/47982551/71223101-dad93080-22a0-11ea-8837-2359e2f77b80.gif)
2. The serving rate decreased significantly after(5pm) may because of **the increasing of traffic at that time**:
    - ![DVFinal2](https://user-images.githubusercontent.com/47982551/71223240-533ff180-22a1-11ea-9bf6-b40fd4efca13.gif)
3. The area with lowest serving rate is **34th street** which always have the highest number of unserved trip:
    - ![DVFinal3](https://user-images.githubusercontent.com/47982551/71223317-926e4280-22a1-11ea-9036-f74f45332fce.gif)


    

# Uber_Case_Study


### Buisness Problem: ### 

While booking cab to and from airpot, many users have experienced the problem of cancellation by the driver or non-availability of cars?

Well, if these are the problems faced by customers, these very issues also impact the business of Uber. If drivers cancel the request of riders or if cars are unavailable, Uber loses out on its revenue.

### Aim of the Analysis: ###
The aim of the analysis is to identify the root cause of the problem (i.e. cancellation and non-availability of cars), finding the peak time periods when these problems are happening.

### Data description ###
There are six attributes associated with each request made by a customer:

* Request id: A unique identifier of the request.
* Time of request: The date and time at which the customer made the trip request.
* Drop-off time: The drop-off date and time, in case the trip was completed.
* Pick-up point: The point from which the request was made.
* Driver id: The unique identification number of the driver.
* Status of the request: The final status of the trip, that can be either completed, cancelled by the driver or no cars available.

The data contains information about all the trips from the airport to city and vice-versa.

Total number of rows and columns : (6745,6)

### Analysis on data ###

* When pick-up point is city

![](https://github.com/Noopuragr/Uber_Case_Study/blob/master/img1.png).

![](https://github.com/Noopuragr/Uber_Case_Study/blob/master/img2.png).

![](https://github.com/Noopuragr/Uber_Case_Study/blob/master/img3.png).

* When pick-up point is Airpot

![](https://github.com/Noopuragr/Uber_Case_Study/blob/master/img4.png).

![](https://github.com/Noopuragr/Uber_Case_Study/blob/master/img5.png).

![](https://github.com/Noopuragr/Uber_Case_Study/blob/master/img6.png).

* Number of ride request in each time slot

![](https://github.com/Noopuragr/Uber_Case_Study/blob/master/img8.png).

* Status of trips in each time slot

![](https://github.com/Noopuragr/Uber_Case_Study/blob/master/img7.png).

### Conclusion ###

1. Most number of request are obtained in morning as well as in the evening hours across all days.
2. When pick-up point is city, most number of request are observed in morning. 
3. When pickup-point is airpot, most number of ride request is observed in evening.
4. Most number of request is coming in the evening at time slot 5 pm - 10 pm.
5. In the evening there is problem of unavailability of cars.
6. In the morning most number of trips are cancelled.


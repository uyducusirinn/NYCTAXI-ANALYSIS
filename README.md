# NYCTAXI-ANALYSIS
Bu proje New York Taksi verilerinin 2017 yılındaki kapsamlı analizini ele almaktadır.


In this document, I will walk through the analysis of New York City Taxi Data (with download link shown in Section II) using Python. 6 months of “Yellow” label data will be loaded and analyzed.

#GROUP MEMBERS

### 1-MELİH ALTAY  </br>
### 2-OĞUZHAN KANSU  </br>
### 3-HAMDİ SERDAR KARAGÖZLER  </br>
### 4-OĞUZHAN TAÇTAN  </br>
### 5-FEVZİ ÖZGÜR ORHON  </br>


## Furthermore, to deal with the large scale of data (4GB for 6 months in this case), a database is needed. 
## Here I will use SQLAlchemy, which is a Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.


![location](https://user-images.githubusercontent.com/44877995/120295466-d1465b80-c2cf-11eb-8e67-d2f5f6ba2d47.JPG)



# Q1: Which regions have most pickups and drop-offs?

![popular_zones](https://user-images.githubusercontent.com/44877995/120296520-e1ab0600-c2d0-11eb-80d8-d4ffc6f9758d.JPG)
![brgh](https://user-images.githubusercontent.com/44877995/120296609-f7203000-c2d0-11eb-91fb-a35e55de4d30.JPG)


# Q2: When are the peak hours and off-peak hours for taking taxi?

![graphics](https://user-images.githubusercontent.com/44877995/120296741-17e88580-c2d1-11eb-802e-9f1e9ff8d87c.JPG)

As you can see, according to the NYC Taxi records from 2017 January to 2017 June, it is found that

The peak hours are around 6PM ~ 7PM.
The off-peak hours are around 5AM.


# Q3: What are the differences between short and long distance trips of taking taxi?


![trips_analysis_graphic](https://user-images.githubusercontent.com/44877995/120296859-38184480-c2d1-11eb-874a-b8d58540b90d.JPG)



![zones](https://user-images.githubusercontent.com/44877995/120296964-52522280-c2d1-11eb-9490-5fc9d3057ce8.JPG)


# Payment Types Analysis

![payment_type](https://user-images.githubusercontent.com/44877995/121420669-09a40480-c976-11eb-851d-cd5f800bd1ae.JPG)

Payment_type is a numeric code signifying how the passenger paid for the trip:

1=Credit card
2=Cash
3=No charge
4=Dispute
Passengers of long trips paid a little more frequent in credit card and a little less frequent in cash comparing to that of short trips.




# Distance Trip Graphics

![dist_trip](https://user-images.githubusercontent.com/44877995/121420970-58519e80-c976-11eb-9e62-026ad7f00292.JPG)


# 3 Longest Trips

## When we list the 3 longest trips, we conclude that the longer trips are towards the airport.

![long_trips](https://user-images.githubusercontent.com/44877995/121421197-90f17800-c976-11eb-8a6e-89d22320aa14.JPG)





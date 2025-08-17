# sql-trips
The sql code consists of several ctes:
flight_counts - calculates the total number of flights for every passenger
max_flights - maximal number of flights from flight_counts cte (1 record only)
ordered - displays the name of the passenger, the name of the previous (by id) passenger, the name of the next(by id) passenger. For the first passenger(by id) the previous is considered the last(by id) passenger. For the last passenger(by id) the next is considered the first (by id) passenger
final result displays these three names for the passengers with the most flights. The output result consists of 2 rows

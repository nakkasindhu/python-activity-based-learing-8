# python-activity-based-learing-8
Algorithm
1.Start.
2.Set bus capacity and initial passengers.
3.Enter boarding and alighting counts at each stop.
4.Calculate current passengers.
5.Check whether capacity is exceeded.
6.Display passenger count and warnings.
7.Stop.
Start
Enter capacity and passenger data
Update passenger count
Check capacity limit
Display count and warnings
Stop
capacity = 40
passengers = 10

boarding = [15, 20, 5]
alighting = [5, 10, 3]

for i in range(3):
    passengers = passengers - alighting[i] + boarding[i]

    print("Stop", i + 1, "Passengers:", passengers)

    if passengers > capacity:
        print("Capacity exceeded!")
Stop 1 Passengers: 20
Stop 2 Passengers: 30
Stop 3 Passengers: 32

        

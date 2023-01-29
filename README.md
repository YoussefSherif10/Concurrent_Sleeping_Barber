# Concurrent_Sleeping_Barber

Consider that in a barber shop we have only one chair where the barber can operate on. The other task are in the waiting room which can be a queue. Two issues can arise from that situation. 
* One is over utilization or livelock where tasks overflow the queue. 
* Under utilization where there are no tasks in the queue. 

This solution is a part of "Introduction to Concurrent programming with GPUs" course. 
There are 3 barbers and 15 seats available for customers (tasks). The chairs are filled to capacity by customers. Customers are divided into four groups: adults, seniors, students, and children. Each group has a different tariff (payment). 
Barbers first make sure there are no more customers in line before beginning to trim. The barbershop's total payout is calculated by the program.

Note that the program will not complete as currently written, you will need to perform a keyboard interrupt, such as CTRL-C.

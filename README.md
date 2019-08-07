# Hall-Banquet-Algorithm
## Scenario


‘XYZ’ hotel chain has 100 banquet halls islandwide. Any hotel has minimum one banquet hall to maximum 5 halls. It provides online hotel banquet hall reservation facilities to their customers. The reservation system uses a waiting list of the selected banquet halls.

Each banquet hall has a unique id, name, location, maximum number guests, reservation date and the three menu prices. Customer can search a banquet hall with the location, reservation date and the number of guests. According to the hotel chain rules and regulations, when a possible match between reservation and the banquet hall is found the customer is contacted via email or SMS and informed. If a customer is not responding within a day, he or she is placed back in the waiting list and must wait again for another hall.

If a customer requested a date change or a location change or a change in the number of guests, he or she is placed back in the waiting list and must wait again for another reservation. We will assume that each banquet hall, once accepted, will be occupied by a reservation ID. Insert banquet hall details, reservation details, and customer details through the keyboard. The reservation process should remove a banquet hall on a given date from the queue if the customer “accepts” the reservation. If the customer rejects or changes the reservation delete the customer reservation, insert it to the back of the queue and compare next customer reservation and repeat. This process repeats until all customers complete their reservations.

## Note
Which data structure can be used and What are the valid operations that can be carried out on this data structure for the system? Implement the system using the selected data structure and its valid operations for the design specification. Use suitable error handling where appropriate. Test the application using suitable test cases.


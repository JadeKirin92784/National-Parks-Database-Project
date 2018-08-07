# National-Parks-Database-Project
This simulates a program to see descriptions of national parks and to make reservations at certain sites within the park campgrounds.
List of functionality:
1. Users of the system can view a list of available parks int he system, sorted alphabetically by name
  
  a. A park includes an id, name, location, established date, area, annual visitor count, and description.

2. Users have the ability to select a park that my customer is visiting and see a list of all campgrounds for that available park.
  
  a.A campground includes an id, name, open month, closing month, and a daily fee.
  
3. Users have the ability to select a campground and search for date availability so that they can make a reservation.
  
  a. A reservation search only requires the desired campground, a start date, and an end date.
  
  b. A campsite is unavailable if any part of their preferred date range overlaps with an existing reservation.
  
  c. If no campsites are available, indicate to the user that there are no available sites and ask them if they would like to enter in an alternate date range.
  
  d. The TOP 5 available campsites should be displayed along with the cost for the total stay.
  
4. User can find a campsite that is open during the time window, and have the ability to book a reservation at a selected campsite.
  
  a. A reservation requires a name to reserve under, a start date, and an end date.
  
  b. A confirmation id is presented to the user once the reservation has been submitted.

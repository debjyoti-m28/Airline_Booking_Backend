# Welcome to Micro-Service Based Airline Booking Backend Project

- ## Architecture Design
![Architecture Design](https://user-images.githubusercontent.com/91774344/211161135-b4682f74-4ddf-4432-940f-317780a9f760.png)
 
 
- ## The followings are the different microservices which are inter-communicating through http requests:

  - ### [Auth Service](https://github.com/debjyoti-m28/Auth_Service)
      - Responsible for user authentication and authorisation.
  - ### [Flight and Search Service](https://github.com/debjyoti-m28/FlightsAndSearchService)
      - Responsible for CRUD operations on flights and filtering flights based on different criteria.
  - ### [Ticket Booking Service](https://github.com/debjyoti-m28/AirlineTicketBookingService)
      - Responsible for Booking, Updating and Cancelling flight tickets.
  - ### [Reminder Service](https://github.com/debjyoti-m28/ReminderService)
      - Responsible for sending emails for confirmed ticket bookings and sending reminders or updates about booked flight.


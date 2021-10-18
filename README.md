# TE42122-BookingApplication
## General Booking system for all types of Bookings
- Book a table
- Book an appointment at the barber shop
- Book a laundry time
- Book a conference room
- etc

### Capabilities
- [ ] PoC: Login management, secure (using Google API) TEAM OAK
- [ ] PoC: Calendar management (using Google API) TEAM ICE
- [ ] PoC: Efficent UI/UX (using Bootstrap) TEAM SSD
- [ ] Business Logic and Domain Model
- [ ] Data management (Backing store based on JSON using Google Cloud Storage)

#### Links for reference
1. https://developers.google.com/identity/sign-in/web/sign-in
2. https://developers.google.com/calendar
3. https://getbootstrap.com/docs/5.1/getting-started/introduction/
4. https://cloud.google.com/storage/docs/json_api

#### Use Cases
"As a X, I want to Y, so that Z"

1. As a visitor to the web application, I want to sign-in using my Google Account, so that I can identify myself and access my bookings
2. As a logged in user, I want to add a new Booking, so that can keep track of my bookings
3. As a logged in user, I want to see all my upcoming Bookings, so that I can plan my time ahead
4. As a logged in user, I want to remove an existing Booking, so that irrelevant bookings are not shown in the calendar
5. As a logged in user, I want to edit an existing Booking, so that I can keep the Booking updated and relevant
6. As a logged in user, I want to see all my profile data, so that I can make sure my contact details are correct
7. As a logged in user, I want to update my existing profile data, so that I can keep my contact details updated
8. As a service provider, I want to see all future bookings made for my Booking Objects, so that I can provide the service

#### Objects
1. Visitor (anonymous visitor to the web application)
2. User (logged in and verified as a user)
3. Service Provider (the provider of the service that is bookable)
4. Booking Object (a service owned by a Service Provider, offered for booking)
5. Booking (a specific booking)
6. Bookings (list of future bookings)
7. User Profile (all contact information for a user)

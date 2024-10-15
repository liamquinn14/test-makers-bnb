# MakersBnB

## Challenge
- Do an initial read through of the provided resources (project specification and the associated mockups/wireframes)
- Work through the project specification and wireframes, analysing their functional requirements, thinking about what you can test
- Make notes on anything you think is important, as you go:
  - Potential test areas
  - Risks
  - Assumptions and/or questions
- Draw diagrams (state, mind map, etc.) where you think they will help your understanding and/or planning
- Draw up a list of parts of the project you would focus on in, say, a first 90 minute long exploratory testing session - you may want to work out what's important to cover first, for example
- Write down how you might test those parts of the project - include test cases, steps test data and anything else that you think is needed
- Commit your resources (any notes, ideas, diagrams, what and how to test, and the planned 90 minute exploratory testing session) to GitHub and submit your challenge

## Headline specifications
- Any signed-up user can list a new space.
- Users can list multiple spaces.
- Users should be able to name their space, provide a short description of the space, and a price per night.
- Users should be able to offer a range of dates where their space is available.
- Any signed-up user can request to hire any space for one night, and this should be approved by the user that owns that space.
- Nights for which a space has already been booked should not be available for users to book that space.
- Until a user has confirmed a booking request, that space can still be booked for that night.

## Nice-to-haves
Users should receive an email whenever one of the following happens:
- They sign up
- They create a space
- They update a space
- A user requests to book their space
- They confirm a request
- They request to book a space
- Their request to book a space is confirmed
- Their request to book a space is denied
Users should receive a text message to a provided number whenever one of the following happens:
- A user requests to book their space
- Their request to book a space is confirmed
- Their request to book a space is denied
- A ‘chat’ functionality once a space has been booked, allowing users whose space-booking request has been confirmed to chat with the user that owns that space
- Basic payment implementation though Stripe.

## Functionalities
- MBNB-01: User can enter email address, password and password confirmation to create an account
- MBNB-02: User can enter email address and passwrod to log in to existing account
- MBNB-03: User can input two dates and find all rooms available between those dates
- MBNB-04: User can list a space, providing a name, description, price and available dates
- MBNB-05: User can request to book a space between two chosen dates
- MBNB-06: User can view requests they've made for spaces, and requests made for their own spaces
- MBNB-07: If a user has requested one of your spaces, you can view, confirm and deny the request
- MBNB-08: If a request is confirmed or denied, the 'requests' page is automatically updated 

## Plan
- Breakdown each individual functionality, make notes, draw diagrams etc
- Draw up a list of parts of the project you would focus on in, say, a first 90 minute long exploratory testing session - you may want to work out what's important to cover first, for example
- Write down how you might test those parts of the project - include test cases, steps test data and anything else that you think is needed



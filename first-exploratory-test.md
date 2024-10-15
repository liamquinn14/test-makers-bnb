# First Exploratory Test for MakersBnB
- 90 minutes

## Assumptions
- For the purpose of this test we are assuming that after signing up you are redirected to the Login page

## Purpose of Test

Test the overall infrastructure of the application with a happy path in order to cover as many states as possible in 90 minutes. This test requires two users, User One and User Two. The tester can control both users. 

See if:
- User One can sign up and list a space
- User Two can sign up and request the newly-listed space
- User One can see the request and confirm the booking
- User Two can log in and see the request updated as 'confirmed'

Guide for the test:
- Test a happy path with regards to registration. Don't want to waste time typing fake emails.
- Make notes of possible areas to test in the future, and any ideas for edge cases
- Make notes of any experiences with the application that contradict our prior assumptions from the wireframe. E.g. specific page routing

## Step 1: User One signs up and lists a space
- Not signed up, Sign up screen => Enter valid email and password to sign up => Signed up, on Login screen
- Signed up, on Login screen => Re-enter details to Log in => Logged in, on 'Book a Space' screen
- Book a space screen => Click 'list a space' button => 'List a space' screen
- List a space screen => Enter valid details and list a space => Confirmation message? => Book a space screen
- Check if all confirmation emails were received

## Step 2: User Two signs up and requests User One's space
- Repeat Step 1's authentication steps until reaching 'Book a Space' screen
- Book a space screen => Search for dates where User One's space is available and click 'List spaces' => User One's space appears
- Book a space screen => Click on User One's space => view screen to book User One's space
- Book User One's space => Select dates where space is available and press request to book => Confirmation message? => Requests screen
- Requests screen => Can view recent request
- Requests screen => Click on recent request => See details for the recent request
- Check if all confirmation emails were received

## Step 3: User One logs in and accepts User Two's request
- Sign up screen => Press 'Login' => Login screen
- Login screen => Enter correct details to log in => Book a space screen
- Book a space screen => Press 'Requests' => Requests screen
- Requests screen => Can view User Two's recent request
- Requests screen => Click on User Two's recent request => See details for User Two's request
- Details for User Two's request => Click confirm request => Confirmation message? => Request screen
- Check if request has updated from 'Not confirmed' to 'Confirmation'
- Check if all confirmation emails were received

## Step 4: User Two logs in and sees confirmation
- Repeat Step 3's Login steps until reaching 'Book a Space' screen
- Book a space screen => Press 'Requests' => Requests screen
- Check if request has updated from 'Not confirmed' to 'Confirmation'
- Check if all confirmation emails were received

## Expected outcome
- Unsure of particular click-by-click details. The application may not behave exactly like the wireframe. These details can be clarified throughout the test.
- Overall we expect there two be a confirmed booking between User One and User Two at the end of the test. We can make notes if things do not go to plan.

## Potential issues and ideas for future tests
- If you sign up, are you automatically logged in, or do you need to re-enter details in Login page?
- Is there a limit to the number of requests that a user can make/receive?
- Can a user book multiple places for the same date?
- There is no delete account feature. Can we list a space then delete our account? What would happen to the space?
- Accessibility tests
- Check if styling is responsive to screen size
- Test the date pickers. See if you can type in invalid dates
- Test if there are multiple requests for a space, but then one of them gets confirmed. See if requests are denied for other users
- Do you stay logged in when you return to the page in the future
- Can you book a space that you have listed?
- Is there a limit for how long can it take for a Space owner to confirm or deny a booking? 
- Do input fields have certain restrictions or character limits?
- Does the currency for 'price' change for users in different locations?
- It says in the wireframe that once you list a space, you automatically go back to the Book a Space page. Is there a confirmation message?


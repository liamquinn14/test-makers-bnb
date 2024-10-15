# MBNB-02: User can enter email address and passwrod to log in to existing account
- User should see an email address and password fields, and be able to input text into them
- User should be able to press 'Login', to log in to account with same details
- Inputs should have a maximum length, to avoid typing unnecessarily long incorrect details
- If either field is empty, there should be an error message, without making an attempt to actually login somewhere
- Users shouldn't be able to bypass Login screen, and see accounts, without logging in
- Successfully logging in will change the page
- Users should get an error message if they input incorrect details, and stay on the same page
- Assumptions: user details are stored securely in a database/server. Assuming also that passwords and emails have been validated before registration, with restrictions e.g. special chars
- Questions: Was there any email verification at all? Is there 2 Factor Authentication? 
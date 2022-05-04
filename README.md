# Moodle find user profiles | userscript
A userscript for Moodle that allows you to go directly to a user's profile, by searching all users of Moodle

# How to install 
- **Chrome**: download Tampermonkey or Violentmonkey
- **Firefox**: download Greasemonkey, Tampermonkey, or Violentmonkey
- **Safari**: downloadTampermonkey or Userscripts
Then upload my script directly to this extension.

# Before using 
If your moodle instance doesn't match the *://*moodle*/ or *://ena*/ wildcards, make sure to add your own wildcard to the @match selector at the very top of the file. Don't forget to add the `/message/*`path after the wildcard.


# How to use :
This userscript uses the already existing functionality of user research in the message section of moodle.
1) Navigate to 'Profile'(top right) > 'Personal messages' 
2) Use the search button to search for users (accent sensitive for french users)
3) Select the user you want, the same way you would start a chat.
4) Select the user profile image, top-left of the conversation panel
5) There should be 2 buttons : 'block user' and 'add contact'. Wait for 3 seconds and a new button 'Profile' should appear.
6) Select the 'Profile' button > it should open a new page, directly to the user's profile.

You can now see if a colleague has already taken a course or find his contact informations, without sending a contact request.

# It doesn't work
Not all moodle instances are made the same, yours might not be the same as mine, but you can try to make it work on your side !
You can also open an issue, i'll see what I can do.

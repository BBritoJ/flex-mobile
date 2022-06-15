in progress.... for now, [click here to see it in action](https://www.loom.com/share/91e174973bee4cf1bf873f46b8334a0c)!

# Where I am working on?

### Tech Debt

    - [ ] Update README: Add how to install/run locally
    - [ ] Update README: Add how to install and run the .apk
    - [ ] Update README: Add screenshots (or an animated gif?)
    - [ ] When a Premise fails, show a Toast
    - [ ] When clicking in a Push Notification, fetch the payload of it and show the exact Chat of it

### Bugs

    Aweeee fixed all the known bugs at the moment.

### Features

# Future release will come with

    - [x] Feature - Add Push
    - [x] Feature - Add a button to start an outbound call
    - [x] Feature - Add a screen to print out the task.attributes (similary as we have in the INFO tab on Desktop)
    - [x] Feature - Show badge with the number of unread msgs in the Tasks.tsx
    - [x] Feature - Change icons and splashscreen (/assets folder + app.json)
    - [x] Feature - Token Re-usage: save token on localStorage and use it in case token is still valid
    - [x] Feature - Long-term Token: save an longTerm access-token on localStorage for days to avoid having to verify the Agent in every each hour
    - [x] Feature - Add "Availale on Mobile" activity and avoid sending Pushes when Agent is not on this Activity.
    - [x] Feature - Show the version of the App and the Bundle.
    - [x] Feature - Voice Calls: receive the call via PSTN (contact_url: +49123123) when Activity is "Available on Mobile"
    - [x] Bug - When a task is accept on Mobile, it cant be complete in the Desktop.
    - [x] Bug - When a task is complete on Mobile, the customer cannot send another SMS to start a new task.
    - [x] Bug - When a task is already in task.complete (or conversation status=closed), hide input field to not allow the user to send a new message
    - [x] Tech Debt - Refactoring the Store to use the lovely @risingstack/react-easy-state (Part 1 of 2)
    - [x] Tech Debt - Remove the last piece of Recoil in favor of @risingstack/react-easy-state (Part 2 of 2)
    - [x] Tech Debt - Add scripts to do the initial install of this whole Flex Mobile setup

# WitchesMap
An application that allows people to log in with their Mastodon account and put themselves on a map.

## Use case

- Someone displays the web app on their browser. They see a map of the world (from an openstreetmap tile provider) with a login button in a modal.
- When clicking on the login button they can log in using their Mastodon account.
- If their Mastodon account meets a set of requirement (from a particular instance, account is x months old, it has x followers, it has x toots, it has x followers from a particular instance, etc.) they can see the other users pins and they can pin their location too.
- If their Mastodon account doesn't meet the requirement, they see a « sorry » modal.

The front-end should obviously be in javascript (Using React or Vue.js perhaps) and I'd prefer if the backend were in PHP (if using an other language, please dockerize it.)

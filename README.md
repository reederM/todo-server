
**JWT documentation**
https://gist.github.com/thebigredgeek/230368bd92aa19e3f6638b659edf5cef

didn't use import syntax bc i didn't wnat to bring in any more external code than nessisary

instructions on setting up and running

unit tests for model class interfaces

**Instructions**
manually add an admin user by using `yarn adduser`


**Tests**
didn't do some sad paths


didn't add any user 'roles' so all users can edit todos, however new users do need to be created manually


Could have implemented by "soft-deleting" todos to allow user to see all completed tasks


**Design**

easy to add new routes by just adding a new route config to the module.exports
# Ignite quest 2

## Requests

* Find an user by username
* Create new to-do for an user when is in free plan and have less than ten to-do
* Create a new to-do for an user when is in pro plan
* Update user and to-do
* Find an user by id

## Business rules

* Not find user when he not exist
* Not create a new to-do for an user when he is in free plan and already have ten to-do
* Not update user and to-do when user doesn't exist
* Not update user and to-do when to-do's id isn't uuid
* Not update user and to-do when to-do doesn't exist
* Not find an user when he doesn't exist
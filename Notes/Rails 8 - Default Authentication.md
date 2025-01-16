Tags: [[Developer]]
Time: 18-12-2024-12:53

#### *Abstract*
___


___

# Rails 8 - Default Authentication

`rails g authentication`
`rails db:migrate`

- Creates a new Session and User model
	- Uses BCrypts with :has_secure_password
	- User has_many sessions
- Session Model:
	- Ip Address
	- User ID
- Application_controller
	- New class called Authentication (Concern)
	- :require_authentication as a before_action

## Allow unauthenticated access
`allow_unauthenticated_access [:index]`

## Current model
Special kind of model, singleton

Default session attribute, which is delegated to user
Can type `Current.user` to get the current user model based on the session



___

# CRM-Model-Laravel-API-

This application is based on CRM Model. In which we have multple users with multiple permission. any one can perform their tasks based on their permissions. in which we have users belongs to some business, then we have department and department have some teams and teams are managed by teamlead and in team we have some team members. Teamlead assign some tasks to team members and we also have a chat feaature in this project which is only based on teams, so that's why only team members can only chat within the team not outside the team.

Packages Include in this Project:
1. Sanctum (for user authentcations)
2. Spatie (for assigning permission to the users)
3. Pusher (for chat feature)

Other Techniques:
1. Use request sepeartely for validation inputs requests
2. Use services for seperately handle interaction with the database
3. Create events listener for send message
4. create different channels for different teams
5. use paginates

Installation:
1. Clone this code
2. Run command: composer install
3. create or copy env file from existing project and configure your database (also add/configure your pusher account in .env file)
4. Run command: php artisan migrate
5. Run command: php artisan db:seed
6. Run command: php artisan serve

And Enjoy !!!!


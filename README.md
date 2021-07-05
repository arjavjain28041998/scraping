# README
The setups steps expect following tools installed on the system.

    • Ruby 2.4.2
    • Rails 5.7.0

Create database.yml file
Copy the sample database.yml file and edit the database configuration as required.
cp config/database.yml  or  config/database.yml

Create the database
Run the following commands to create the database.
    • Bundle exec rake db:create




Migrate the database
Run the following commands to migrate the database.
bundle exec rake db:migrate

 Start the Rails server
You can start the rails server using the command given below.
bundle exec rails s
And now you can visit the site with the URL  http://localhost:3000

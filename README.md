# README
The setups steps expect following tools installed on the system.

    • Ruby 2.4.2
    • Rails 5.7.0

Create database.yml file
Copy the sample database.yml file and edit the database configuration as required.
cp config/database.yml  or  config/database.yml

Create the database
Run the following commands to create the database.
    • bundle exec rake db:create
    • rails db:migrate



Migrate the database
Run the following commands to migrate the database.
bundle exec rake db:migrate

 Start the Rails server
You can start the rails server using the command given below.
bundle exec rails s
And now you can visit the site with the URL  http://localhost:3000

Home Page
![image](https://user-images.githubusercontent.com/81669250/124554870-0fe1af80-de54-11eb-82e8-5edb3dbe9991.png)

Product List 

![image](https://user-images.githubusercontent.com/81669250/124554935-2556d980-de54-11eb-81f4-9c15b66ea10d.png)


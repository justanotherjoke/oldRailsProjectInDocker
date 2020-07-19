Tutorial:
https://guides.rubyonrails.org/v3.2/getting_started.html

Creating a Resource

These files (except abstract_mysql2.adapter.rb) created after running the command:
rails generate scaffold Post name:string title:string content:text

The following command doesn't work until creating the abstract_mysql2_adapter.rb and change the environment.rb as you can see in the commit
docker-compose run blog rake db:migrate
(source: https://stackoverflow.com/questions/40758226/mysql2error-all-parts-of-a-primary-key-must-be-not-null-if-you-need-null-in)


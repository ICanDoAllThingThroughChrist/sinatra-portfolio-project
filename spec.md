1.create new files from fwitter for	
	environments
	config.ru

2.create new director 	
	app

3.refer to sw3p for	
	DOM

4.AR Setup in Sinatra	
	https://learn.co/tracks/full-stack-web-dev-with-react/sinatra/activerecord/activerecord-setup-in-sinatra

5.AR associations	
	https://learn.co/tracks/full-stack-web-dev-with-react/sinatra/activerecord/activerecord-associations-in-sinatra

6.tux	does not work without table structure first

7.copy models files from sw3p to sw3p2	
	https://alvinalexander.com/mac-os-x/mac-copy-files-mac-finder-copy-files

8.start from scratch	
	https://github.com/thebrianemory/corneal

9.how to drop tables with rake	
	rake create migration DropInstalls
	class DropInstalls < ActiveRecord::Migration
	  def change
	    drop_table :installs
	  end
	end
	Then run rake db:migrate in the command line which should remove the Installs table

10. create objects in tux

11. create file directories of view, controller, model

12. create migrations for work orders domains: orders, sites, tasks, clients, comments, 

13. create AR associations in models

14. create a counter for each order created to auto-increment order

15. ran into problem of failure of auto-increment in orders' join table: provide counter field string data type. increment succeded.
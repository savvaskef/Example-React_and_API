#React and .Net Api and Data stored MS-SQL server
Example Project on how to develop and Build React App with DOTNET Web API
<br>
To run the Project on the backend(API) you need to navigate to the WebAPI
directory and run the solution .sln file .Then run the server ie by hitting F5
Remember to attach the .mdf database file to sql server and change the connection
string according to your configuration
<hr>
 
Open it in Code and again run the client that reads React code into functionality(-ies)
You do that By typing :
  npm run serve <br>
  
If there are any incmobatibilities remove node_modules folder and readd them via the following lines
cd my-app <br>
  npm install <br>
  ...to transfer all the environment you need fot the client side to run on a browser<br>
typing again: 
  npm run serve <br>
    
  You will get the address you need to witness the small yet all-encompassing Dept-Employee app functionality.
  The departments and Employess are now synced to the database using WEB-Api automation
  <hr>
  
For my case, specifically i had to also set a parameter.Namely:<br>
set  NODE_OPTIONS=--openssl-legacy-provider <br>
berfore npm start<br>
I have a hunch that this lowers security however.It would be best to 
'set' and 'unset' the parameter after installing and using the client respectively.

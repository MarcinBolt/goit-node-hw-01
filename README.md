#goit-node-hw-01

#node, #nodemon, #console, #bash, #commander, #nanoid #async-await

# ! Screenshots are available in folder screenshots !

# Instructions:
#To get and display the entire list of contacts in the form of a table (console.table)

node index.js --action list 

(screenshots/action list.jpg)

#To get contact by id = 05olLMgyVQdWRwgKfg5J6

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6

(screenshots/action get.jpg)

#To add the contact name = Mango email = mango@gmail.com phone = 322-22-22

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

(screenshots/action add.jpg)
#To delete the contact with id = qdggE76Jtbfd9eWJHrssH

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH

(screenshots/action remove.jpg)

# P.S. 

For importing files I used import instead require methods.

Here is how to fix the "\_\_dirname is not defined in ES module scope" error:
https://flaviocopes.com/fix-dirname-not-defined-es-module-scope/

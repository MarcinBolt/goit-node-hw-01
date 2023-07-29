# goit-node-hw-01

#node, #nodemon, #console, #bash, #commander, #nanoid #async-await

# ! Screenshots are available in folder screenshots !
action list: https://raw.githubusercontent.com/MarcinBolt/goit-node-hw-01/main/screenshots/action%20list.jpg
action get: https://raw.githubusercontent.com/MarcinBolt/goit-node-hw-01/main/screenshots/action%20get.jpg
action add: https://raw.githubusercontent.com/MarcinBolt/goit-node-hw-01/main/screenshots/action%20add.jpg
action remove: https://raw.githubusercontent.com/MarcinBolt/goit-node-hw-01/main/screenshots/action%20remove.jpg


# Instructions:
# To get and display the entire list of contacts in the form of a table (console.table)

node index.js --action list 

# To get contact by id = 05olLMgyVQdWRwgKfg5J6

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6

# To add the contact name = Mango email = mango@gmail.com phone = 322-22-22

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

# To delete the contact with id = qdggE76Jtbfd9eWJHrssH

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH

# P.S. 

For importing files I used import instead require methods.


Here is how to fix the "\_\_dirname is not defined in ES module scope" error:

https://flaviocopes.com/fix-dirname-not-defined-es-module-scope/

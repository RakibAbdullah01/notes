# Connect with MongoDB steps
one time:
1. nodemon globally install
2. mongodb atlas account ready
3. Network Access(IP Allow- atlas)

Every Project:
1. npm init -y
2. npm i express cors mongodb dotenv 
(MongoDB)
3. import(require) mongoDB
4. connect uri(connection string)
5. create client(copy code from mongo)
6. create or get database access credentials(username,password)
7. create .env file and add DB_USER and DB_PASS as environment variable
8. import .env import
9. add DB_USER and DB_PASS at URI String
10. create async function run and call it using run().catch(console.dir)
11. add try{} and finally{} inside of run()
12. inside finally, comment out 'await client.close()'
13. inside try write await client.connect() 

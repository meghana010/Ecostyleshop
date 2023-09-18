Steps to execute :
1. After downloading the folder , donot forgot to install all the packages used .
If the root directory is Sustainable Brands , use  "npm install"
2. change the directory to backendapp , and install the packages 
  cmd:         cd backendapp
               npm install
3. Go back to root directory 
  cmd:           cd ../
4. Change directory to myapp (front-end react code) and install packages
 cmd:           cd myapp
                npm install
5. Go back to root directory  
  cmd:          cd ../
6. Make sure that You are connected to database (mongoDB)  
connection URL ---  mongodb://0.0.0.0:27017/react  ............
    Donot forget to run mongod in windows Powershell.
7. Run the command 
 cmd:       concurrently "npm run start-frontend" "npm run start-backend"
8. Both front-end and back-end will run on different ports 3000 and 5000 make sure theya re not engaged.


Register before you login
Once you login it will display --- welcome , mailID.
You can filter the images based on categories specified and can also have dynamic user specific Cart ,purchase history .



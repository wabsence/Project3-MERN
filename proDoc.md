# PROJECT DOCUMENTATION

## Step 1: BACKEND CONFIGURATION


#### Command: sudo apt update (update ubuntu packages)
#### Output:

![Update](images/update.png "packages update process")

#### Command: sudo apt upgrade (upgrade ubuntu)
#### Output:

![Upgrade](images/upgrade.png "ubuntu upgrade process")

#### Command: curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - (getting node.js location from ubuntu)
#### Output:

![nodeLocation](images/node.png "node location")

#### Command: sudo apt-get install -y nodejs (installing node and npm and confirming version installed)
#### Output:

![nodeVersion](images/nodeVersion.png "Installed Version")

#### Command: npm init (Todo App project initialization and creation of packages.json file)
#### Output:
![todoAppInit](images/todoAppInit.png "Todo App Initialization")

## EXPRESSJS INSTALLATION

#### Command: npm install express

#### Output:

![expressJS](images/express.png "Expressjs Installation")

#### Command: npm install dotenv

#### Output:

![dotENV](images/dotenv.png "dotENV Installation")

![config](images/indexjs.png "configuration to listing to port 5000")

#### Command: node index.js

#### Output:

![startServer](images/serverRunning.png "startServer")

![inboundRule](images/inboundRule.png "Add Securuty Group Rule")

#### Command: http://54.84.63.43:5000/

#### Output:
![serverIP](images/serverIP.png "Access via IP in port 5000")

#### Command: mkdir routes and touch api.js (create routes directory and api.js file)

#### Output:
![Routes](images/routes.png "Routes Directory")

![API](images/apijs.png "API")

## MODELS

#### Command: npm install mongoose and mkdir models (install mongoose and create models directory)

#### Output:
![Mongoose](images/mongoose.png "Mongoose Installation")

![Model Config](images/modelTodo.png "Model Config")

![API](images/apijs2.png "API")

## MONGODB DATABASE

#### Command: create a mongoDB Database and collection

#### Output:
![mongoDB](images/mongoDB.png "MongoDB and Collection")

![DB_User_Access](images/dbAccess.png "Database User Access")

![Network_Access](images/networkAccess.png "Network Access")


![Connections_String](images/connectionString.png "Connection String")

### Create .env file
![env_File](images/env.png "env_File")

### Update index.js file

![IndexJS](images/indexjs2.png "indexjs Update")

### Start Server

![startServer](images/serverRunning2.png "startServer")

### POSTMAN (consuming all endpoint API)

#### POST REQUEST
![postRequest](images/postRequest.png "postRequest")

#### GET REQUEST
![getRequest](images/getRequest.png "postRequest")


#### BROWSER OUTPUT
![Browser](images/browserOutput.png "Browser")

#### DELETE REQUEST
![deleteRequest](images/deleteRequest.png "deleteRequest")

#### BROWSER OUTPUT AFTER DELETE REQUEST
![Browser](images/browserOutput2.png "Browser")

## STEP 2: FRONT END CREATION

#### SCARFFOLDING REACT APP
![reactAPP](images/reactApp.png "reactAPP")

#### Installing dependencies such as concurrently and nodemon 

![concurrentlyNodemon](images/concurrentlyNodemon.png "concurrentlyNodemon")

#### Update Package.json

![packageJSON_UPDATE](images/packageJSON_UPDATE.png "packageJSON_UPDATE")

#### Update Package.json in Client
#### Add "proxy": "http://localhost:5000" for react port.

![reactPort](images/reactPort.png "reactPort")

#### Run and Start the REACT App

#### Command npm run dev

![npmRunDev](images/npmRunDev.png "npmRunDev")

#### Checking The REACT APP on BROWSER via IP in port 3000
![Browser](images/browserOutput3.png "Browser")

## REACT COMPONENT

![reactComponent](images/reactComponent1.png "reactComponent")

## Axios Installation

![AXIOS INSTALLATION](images/axios.png "Axios Installation")

#### Second COMPONENT

![reactComponent](images/reactComponent2.png "reactComponent")

#### Third COMPONENT

![reactComponent](images/reactComponent3.png "reactComponent")

#### Updating files in the SRC directory
![appJS](images/appJS.png "appJS")

![appCSS](images/appCSS.png "appCSS")

![indexCSS](images/indexCSS.png "indexCSS")

## TO-DO APP OUTPUT

#### VIEWING ALL TASKS

![viewTASK](images/viewTASK.png "viewTASK")

#### NEW TASKS CREATED

![createTASK](images/createTASK.png "createTASK")

#### A TASK DELETED

![deleteTASK](images/taskDELETED.png "deleteTASK")








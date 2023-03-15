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


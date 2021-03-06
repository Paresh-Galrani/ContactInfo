# Contact Info Management

Basically this project demonstrates use of angularjs along with typescript, webpack and indexedDB

### Prerequisites

Make sure you have latest version of node installed on your machine. <br />
This project was implemented using v8.9.4. <br />
You can check node version by running following on command prompt
```
node -v
```

### Installing

Download the entire code from this Github repository.

Then do the following steps:

Step 1
```
Open command prompt and navigate to the folder where this code has been downloaded
```
Here you should be able to see package.json file

Step 2 <br />
Run the following command 
```
npm install
```
This command will create a folder named node modules and downloaded all the dependencies. <br />
This will take quite some time, till then sit back and relax.



## Running the application

To run this application. Execute following command
```
npm run serve
```
This will open your browser and run the application on 3002 port. <br />
To change the port you can navigate to webpack.config.js and change the port as follows
```
devServer: {
        host: 'localhost',
        port: 3002
    }
```
## Creating a distributable package
To create a distributable package. <br />
Execute the following command:

```
npm run build
```
This will create dist folder which will consist of all the file required for deployment.

## Authors

* **Paresh Galrani** - *Initial work* - [PareshGalrani](https://github.com/Paresh-Galrani)


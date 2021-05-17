# Sales-Inventory-Website
A sales management web application that tracks sales, inventory, profit, and growth. Incorporated with different visualization for easy view and analyses. 
## Requirements

For development, you will need Node.js and a node global package and NPM installed in your environement.

### Node 
- #### Node installation on Windows (npm installed with node)

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###
## Modules Used:
```
    "alert-node": "^1.2.5",
    "async": "^3.1.0",
    "bcryptjs": "^2.4.3",
    "body-parser": "^1.19.0",
    "connect-flash": "^0.1.1",
    "cookie-parser": "~1.4.4",
    "debug": "~2.6.9",
    "ejs": "~2.6.1",
    "express": "~4.16.1",
    "express-ejs-layouts": "^2.5.0",
    "express-session": "^1.16.2",
    "express-validator": "^6.1.1",
    "http-errors": "~1.6.3",
    "moment": "^2.24.0",
    "morgan": "~1.9.1",
    "multer": "^1.4.1",
    "mysql": "^2.17.1",
    "nodemailer": "^6.3.0",
    "nodemon": "^1.19.1",
    "passport": "^0.4.0",
    "passport-local": "^1.0.0",
    "pm2": "^4.2.3",
    "popups": "^1.1.3",
    "promisify": "0.0.3",
    "qrcode": "^1.4.4",
    "typeahead": "^0.2.2"
  ```


## Install

    $ git clone https://github.com/YOUR_USERNAME/PROJECT_TITLE
    $ cd PROJECT_TITLE
    $ npm install

## Configure app

Open `a/nice/path/to/a.file` then edit it with your settings. You will need:

- A setting;
- Another setting;
- One more setting;

## Running the project
Puroject runned using nodemon. to install nodemon:
```
npm install -g nodemon
```
    
Starting Application:
```
$ npx nodemon
```

## PM2 is used to build production. To install PM2 and other pm2 functionalities:
    $ npm install pm2 -g
    $ pm2 start app.js

## Visualizations
Visualizations are done with Chartjs module
```
npm install chart.js
```

# QUICK ES6 SETUP



#### Setting up Babel and nodemon

  - Create new FOLDER and cd FOLDER
  - Run command npm init and continue ENTER untill package.json is created in your FOLDER
  - Run command below on your terminal 
    > npm install --save-dev babel-cli babel-preset-env nodemon request
  - create file .babelrc and put code given below:
	> {
		"presets": ["env"]
	}
 - Open package.json file and put command given below to scripts like it is already given in file package.json "test": "echo \"Error: no test specified\" && exit 1":
    
	> "start": "nodemon --exec babel-node app.js"
 - To test ES6 code is working create app.js file and write code
    > import request from 'request';
    > let world = `World`;
	> console.log(`Hello ${world}`);


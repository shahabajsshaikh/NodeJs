# NodeJs
Nodejs_classes

Install nodejs 

```sh
apt-get install -y nodejs 
```

Install npm

```sh
apt-get install -y npm
```

Install yarn

```sh
npm install -g yarn
```

############################### Yarn Steps ############################### 

Step 1: mkdir src 

Step 2: cd src && vim index.js

Step 3: yarn install

Step 4: yarn init <== To create package.json

```sh
	yarn init v1.22.15
	question name (test): 
	question version (1.0.0): 
	question description: 
	question entry point (index.js): 
	question repository url: 
	question author: 
	question license (MIT): 
	question private: 
	success Saved package.json
	Done in 10.51s.
```
Step 5:

Add below steps as which scripts need to execute. 
  
```sh
  "scripts": {
      "test": "echo \"Error: no test specified\" && exit 1",
      "start": "node src/index.js",
      "build": "npm build"
    }
 ```
  
After add it should looks like.

```sh
	{
	  "name": "paas",
	  "version": "1.0.0",
	  "description": "this is for test ",
	  "main": "index.js",
	  "scripts": {
	    "test": "echo \"Error: no test specified\" && exit 1",
	    "start": "node src/index.js",
	    "build": "npm build"
	  },
	  "license": "MIT"
	}
```
	
Step 6: Execute command accoring to scripts declared under scripts. 
```     
        # yarn start
```
Or
```
       # yarn build
```

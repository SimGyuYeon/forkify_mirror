### 0. Node.js 설치
  https://nodejs.org/ko/

### 1. npm init
'''
  package name: (forkify)
  version: (1.0.0)
  description: Recipe application
  entry point: (index.js)
  test command:
  git repository:
  keywords:
  author: sim
  license: (ISC)
  About to write to C:\Users\SIM\Documents\dev_work\vs_work\forkify\package.json:
'''
  {
    "name": "forkify",
    "version": "1.0.0",
    "description": "Recipe application",
    "main": "index.js",
    "scripts": {
      "test": "echo \"Error: no test specified\" && exit 1"
    },
    "author": "sim",
    "license": "ISC"
  }

### 2. package.json created
  delete "main" property (parcel v2)

### 3. change "scripts"
  "scripts": {
    "start": "parcel index.html",
    "build": "parcel build index.html"
  },
  
### 4. install parcel
  npm i parcel@2

### 5. install core-js
  npm i core-js regenerator-runtime

### 6. npm start


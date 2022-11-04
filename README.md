# React-Deploy-Tutorial

## Adding React-App on github

### Step 1
**Go inside your react forder**

### Step 2
**Under your react forder open git bash here**

### Step 3
**Use cd command to go under your react main folder**

```
cd
```

### Step 4
**After you go to your main folder** 
**Use git init command to initilize your directory**
```
git init
```

### Step 5
**After initilizing react directory check git status using comman git status**
```
git status
```

### Step 6 
**You have to add some file using git add . command**
```
git add .
```

### Step 7
**Then commit your diectory using command git commit -m 'my commit' command**
```
git commit -m 'my commit'
```

### Step 8
**After all this process above**
**Go to your github account and create an repository**
**After creation of your github repository you will see push an existing repository from the command line**
**Under tihs copy each line under code section and pase it in your git bash one by one
**After downloading all the dependency you will see your react file copy under your github repository**

## Deployment of React-App

### Step 1
**Add homepage to package.json**
```
  "homepage": "https://myusername.github.io/my-app",
```
Where in the myusername you have to write you github username
           &
In the my-app you have to write your repository name

### Step 2
**In your terminal choose your main directory and run this command**
```
npm install --save gh-pages
```

### Step 3
**Add the following scripts in your package.json:**
```
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```
Under Script in package.json

### Step 4
**Now run this command to deploy your site**
```
npm run deploy
```

### Step 5

      





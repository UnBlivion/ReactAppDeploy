# React Deploy Test - FIREBASE

### https://kaloraat.com/articles/how-to-deploy-create-react-app-to-firebase
###### ^ This Helped a LOT ^

- Create REACT APP
> npm create-react-app folder

- Install FIREBASE and initialize it
> npm install firebase-tools and firebase init

### FIREBASE Database Setup
- Select DATABASE and HOSTING options
- Choose or create an existing Firebase Project
- "what file should be used for **Database Rules ?**", just press **Enter**

### FIREBASE Hosting Setup
- You'll be asked **What do you want do use as your public directory?(public)**, STOP right Here, We'll be using the **build** folder
- so let's create our build folder
###### run this everytime u want to push something new (i recomend to run this thing in a different terminal)
> npm run build
- Now we can Type **build**, instead of public

### Configure as SPA ?
- Firebase will ask you if u want the app to be an **SPA**. Type *y* and presse **enter**
- later on, it will say something like **File Build/index.html already exist. Overwrite?** Press *N*
#### By now we have 3 files created by firebase in our root directory.
- *.firebaserc* – Consists of the project information that you selected.
- *database.rules.json* – Consists of the database rules for Firebase.
- *firebase.json* – The min configuration file.

### Finally, Deploy REACT APP to Firebase
Just Type
>firebase deploy
AND... Ready


###### It may work ;)
# Stray-Animals-Website
This is SIT CS546 team project repo.
**Since the previous CS546 library is locked, a new repo is created to update further changes.**

## Instruction
{Project Name: Stray Animal Information Application}

## Demo
### Home Page
![image](./Demo/Home_Page.png)

### Login Page
![image](./Demo/Login_Page.png)

### Login Successful Page
![image](./Demo/Login_Successful.png)

### User Center Page
![image](./Demo/User_Center.png)

### Upload New Animal Page
![image](./Demo/Upload_New_Animal_Page.png)

### Upload New Volunteer Page
![image](./Demo/Upload_New_Volunteer_Page.png)

### Volunteer Info Page
![image](./Demo/Volunteer_Info_Page.png)

### Display Stray Animals on Map Page
![image](./Demo/Display_Map_Page.png)


## Group members：

- Youlin Chen
- Chunzhi Li
- Yetong Chen
- Wei Guo
- Siyan Liu

NOTION: seed.js may take about ten seconds to run, please be patient

## Installation/How To Run

### Dependencies

Before downloading this program, you'll need to install the following items to your computer:

- [git](https://git-scm.com/downloads "Git Installation")
- [MongoDB](https://www.mongodb.com/docs/manual/installation/ "MongoDB Install/Run Tutorial")
- [Node.js](https://nodejs.org/en/ "Node.js Installation")

### Downloading/Running the Program

#### Download

1. _git clone_ this repo to your computer.
2. On the command line, go to the repo folder and run _npm i._

#### Run

1. If MongoDB is not running, turn it on.(**_MongoDB must be running on your machine before you can use the website._** If you installed MongoDB as a service, it will always run in the background, but otherwise, you need to run cmd using **net start MongoDB** and using **net stop MongoDB** to stop)
2. Run _npm start_ to start the web server on your computer.
3. Follow the output instructions to see the website.



Tech Stack：
handlebar, Express, mongoDB, axios, expresshandlebar, openstreetmap, leaflet, leaflet geosearch, Multer, 

File Structure：

App.js - start project

Seed.js - fake data

helpers.js - public methods

Config - 
 - mongoCommection.js
 - mongoCollection.js
 - settings.json

Data - @Chunzhi Li
Index.js
animalPost.js
user.js
location.js
volunteers.js
comments.js

Routes - @yetong
index.js
animalPost - get, post, delete, patch
userCenter …
userLogin …
volunteer …get, post, delete, patch

Public - 
Main-style.css

Static
homepage.html

Views @ULIN
Error.handlebar
allPost (No auth req)
postDetail （need auth）
Login (No auth req)
Sign in (No auth req)
userCenter （need auth）
allVolunteer （No auth req）
volunteerDetail （need auth）

Map - @Wei Guo
display.js
mapSearch.js
singlelocation.js
locationData.js
test.handlebars(map)
postDetails.handlebarS(map)

publicMethods(function convertLocation())

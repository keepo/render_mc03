# ***WUUP *DLSU edition***


### AUTHORS:
- *Michael Robert Geronimo*
- *Julianne Fundales*
- *Evan Lorenz Fernandez*

### ABOUT
>Based on the popular Facebook group what's your ulam pare. This website features the core of the group
>which is to post delicious food and share it to others DLSU edition. 
>

---

## NPM PACKAGES
    1.) dotenv
    2.) express
    3.) express-handlebars
    4.) mongodb
    5.) mongoose
    6.) nodemon
    7.) bcrypt
    8.) body-parser
    9.) express-flash
    10.) express-session
    11.) passport
    12.) passport-local
    
# Read me:
---


## SECTION 1: References and Instructions
### References
    For Login and Logout (Passport): 
        1.) https://youtu.be/W5Tb1MIeg-I
        2.) https://youtu.be/-RCnNyD0L-s


### Installation Instructions
    1.) delete current package.json and package-lock.json files 
    2.) delete current node_modules folder
    3.) run the terminal and npm init
    4.) set main as app.js
    4.) install all necessary modules (list below)
    5.) add necessary lines to new package.json (instructions below)

### Instructions for Populating the Database
    Running the code for the first time will populate the database to avoid duplicate users/posts do the following
    1.) open app.js 
    2.) comment out line 44 to 55  

---

## SECTION 2: Modules to install (for step 4 of installtion instructions)

### Base  
    dotenv
    express
    express-handlebars
    mongodb
    mongoose
    nodemon
**(npm i dotenv express express-handlebars mongodb mongoose nodemon)** 

### For Login 
    bcrypt
    body-parser
    express-flash
    express-session
    passport
    passport-local
**(npm i bcrypt body-parser express-flash express-session passport passport-local)** 

### For Image Uplaod 
    multer 
**(npm i multer)** 
.
--- 

## SECTION 3: Other Important Information 

### Inside package.json That Needs to Be Added (For Step 5 in Installation Instructions)
    INSIDE SCRIPTS 
        "start":"nodemon app.js"
        (Note: use "npm start" to run it)
    ABOVE DEPENDENCIES 
        "type": "module", 

### Account and Passwords Already in Database
    1.) Username: Foodlover112 
        Password: password1 
    2.) Username: nancyVegan
        Password: password2 
    3.) Username: raymund2 
        Password: password3 
    4.) Username: pastalover012
        Password: password4 
    5.) Useranme: Tifanny24 
        Password: password5 
        
### Note
    1) Profile pictures with spaces in their filenames produces an error

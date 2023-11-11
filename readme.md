# Gorcery Store using Flask
As part of my Data Science and Programming degree at IIT Madras, I'm working on an important project called Modern Application Development 1. This project is helping me learn how to create both backend and basic frontend parts of applications.

Through this project, I'm getting hands-on experience in building the "engine" of apps (backend) and also in making the parts that users see and interact with (frontend). A special thing I'm using is Flask, a strong tool in the Python language, which is helping me make apps that can do different things when people use them.

In short, Modern Application Development 1 is like a journey that's teaching me valuable skills. It's like learning the theory and then practicing it to become better at using technology for creating useful things.

### How to use this app

------------

There are certain steps to be followed to run this app in your machine, there are three commands to be run on your machine
```bash
python -m venv mad
mad/Scripts/activate
pip install -r requirements.txt
```

After this you need to run the app be in the root directory and run the command 
```bash
python app.py
```
Now you are ready to go, the above command will make this app start listening at localhost of your desktop


### Some Important files and folders in the app
----------------------------
- **app.py**: This File is the central file of the whole app which maintains the whole app
- **requirements.txt**: This mentions the required packages python uses along with their versions.
- **routes.py**: This file contains the takes the userRoute and managerRoutes  to the central app.py file
- **config.py**: Configure the app and default running settings
- **templates/ **: This is a folder that includes all the pages that will be shown on the app
- **static/ **: This filder contains all the static images of the app 
- **allroutes/ **: The userRouting and managerRouting are the two python files into it that manages the routing of the app
- **database/configdb.py**: This file contains the configure of sqlalchemy in the app and session engine
- **database/db_controller.py**: This file contains all the database related operations happening in the app 
- **database/models.py**: This file contains the schema models of the tables that are in the app



> Thanks to use this app
> App Created by **Rohit Gupta** [Github Link](http://github.com/ri-2020)
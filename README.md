Reason for choosing React : 
1) Wanted to explore React after doing quite a few projects on Angular
2) Got a tutorial on youtube which also uses React which made life easy
3) However, I felt Angular to be easier to work with, which maybe because I am used to it

STEPS TO RUN THE SOFTWARE ON WINDOWS : 

    1) Getting the Code : 
    
        Go to the gitlab project link
        
        Click on clone and copy the link under clone with https section
        
        Open command prompt
        
        Navigate to the folder where you want the project to be present
        
        Run the command : git clone the_copied_link
    
    
    2) Setting up Redis Server : 
    
        Open this link : https://github.com/microsoftarchive/redis/releases/download/win-3.2.100/Redis-x64-3.2.100.msi
        
        Run the .msi file BUT MAKE SURE TO CHECK THE “Add the Redis installation folder to the Path environment variable” checkbox and walk through the Setup Wizard instructions
        
        Go to the Redis directory created at the location where you installed redis
        
        Click on the redis-server file and you have your redis server running
    
    
    3) Setting up the Backend : 
    
        Navigate to the project directory and run : pip install -r requirements.txt
        
        Then navigate into the justchat directory inside the project directory and run : py manage.py runserver
    
    
    4) Setting up the Frontend : 
    
        Open another command prompt
    
        Navigate to frontend directory inside the project directory
        
        Then run : npm install @babel/core @babel/plugin-proposal-class-properties @babel/preset-react react react-dom react-router-dom antd axios redux redux-thunk socket.io-client
        
        Then run : npm start
    
    
    5) Execution : 
    
        We have 2 users : admina and adminb
        
        
        Open a browser window at the link obtained after running npm start (localhost:1234)
        
        Login with username = admina and password = passworda
        
        Click on first 'Harvey Spector' option in the sidepanel
        
        
        Open another incognito window at the same link
        
        Login with username = adminb and password = passwordb
        
        Click on first 'Harvey Spector' option in the sidepanel
        
        
        THAT'S IT!!
        Send message from any one window and you will see the same message in the other window immediately
# Welcome to our project

This is a flutter based application, which is a 2d gameplay and also an educational resource to learn about exoplanets

You need to run the fastend API inorder to access predict_planet model
You can access all other pages without running server, you just need server for MYPLANET i.e predictive model of planet

Steps to clone the app:
1. git clone https://github.com/yourusername/cosmic_quest.git

Steps to run server:

First run test.py to download rag models

ml.py for ml models
main .py for rag models




Note: Before running it , change the paths in main.py to your laptop path where the files are there for data.txt, planets_faiss.index, id_to_planet.pkl and run it

after running it , run the server in this way 
Start the FastAPI server:
   ```bash
   uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
   ```

   host should be your IP address and run it 

after you run the server, go to myplanetintro.dart and change the backendUrl: 'http://YOUR_IP_ADDRESS:8000 in navigation part of code

Note: this app is accessible only in landscape mode
                






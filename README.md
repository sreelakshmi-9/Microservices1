# ## Sree's_week11_Assignment
Week 11 Graded Assignment for IIITH Software Engineering DataScience
# # 
Install Virtual box
1. Create VM as name  Ubuntu 
2. Install VS code in Ubuntu 
3. 

## Steps for model training
1. Go the application folder   
2.  activate virtual environment  
3.  python3 code_model_training/train.py  
4.  trained model will be saved in model directory  

## Steps for model testing via flask application
1. Go the application folder 
2.  activate virtual environment 
3.  python3 app.py

5. ubuntu curl -X GET http://localhost:5000/info



## Steps to create and run container 
1. Go the application folder 
2.  docker build -t \<image ID\> .  
3. docker run -d -p 5000:5000 \<image ID\>



Steps to run Featurepreneur Chat Bot :
------------------------------------
pip install rasa

rasa init ( in a separate directory)

rasa run --credentials ./credentials.yml  --enable-api --auth-token XYZ123 --model ./models --endpoints ./endpoints.yml --cors "*"

View it in live server

----------------------------------------------------------
Install rasa :

pip install rasa

To create trained model :
rasa init

Train the model :
rasa train

Run in terminal :
rasa shell

Install rasa-x :

pip install --upgrade pip==20.2

pip install SQLAlchemy==1.3.22

pip3 install rasa-x --extra-index-url https://pypi.rasa.com/simple

Rasa Bot directory - run UI :

rasa run --credentials ./credentials.yml  --enable-api --auth-token XYZ123 --model ./models --endpoints ./endpoints.yml --cors "*"

---------------------------------------------------------------
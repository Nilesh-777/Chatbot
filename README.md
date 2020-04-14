# Chatbot
A chatbot application in python

# required versions
python version 3.6.0
pip version >= 19.0.3

# required packages
pip install flask
pip install flask_bootstrap
pip install nltk
pip install numpy
pip install tflearn
pip install tensorflow

#Actiavate virtual environment
virtualenv --system-site-packages -p python ./venv
.\venv\Scripts\activate

#Check installation of tensorflow
pip install --upgrade tensorflow
python -c "import tensorflow as tf;print(tf.reduce_sum(tf.random.normal([1000, 1000])))"
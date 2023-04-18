## End to End Machine Learning Project
This is a ML project that predicts the score of a student based on some inputs provided.
The project reflects an industry standard project structure with an interactive flask app.


## Run from terminal:

docker build -t testdockerkrish.azurecr.io/mltest:latest .

docker login testdockerkrish.azurecr.io

docker push testdockerkrish.azurecr.io/mltest:latest

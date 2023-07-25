# Final exam
The aim of this exercise is to dock the Python application present in this repo, and automate its build via a pipeline on github actions. The application should be tested locally on your workstation before starting the exercise. This is a photo-based Blur detection application, with a WEB interface that can easily be tested with python on your PC.

## Exercise steps.

### Create a repository
Fork this repo on your personal account and add the user @skhedim as a read-only user for correction.

### Write the Dockerfile
Add a Dockerfile to the root of the repo. The application is based on the python 3.8 runtime. You need to run the app.py file to launch the application.

### Write the pipeline
Using GH actions, write a pipeline to automatically build the image and push it to your registry or to Github's integrated registry. (Versioning is not to be taken into account for this exercise.

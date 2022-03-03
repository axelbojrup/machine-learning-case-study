# How to query the model 

The following credentials and commands will give you access to a git repository hosted on aws codecommit. 

`username: ml-case-study-reader-at-655669646549`

`password: ca9z3VTq0Em0xVBiD/TQmTI2GV26NSeUlqWqjMuLKLs=`

Now you should be able to clone the repository:

`git clone https://git-codecommit.eu-west-1.amazonaws.com/v1/repos/machine-learning-case-study`

Jump inside the project and start the application with

`flask run`

query the application with

`curl -H "Content-Type: application/json" -X POST -d @test_request.json http://127.0.0.1:5000/default`

where the *test_request.json* can be found at the root of this project.

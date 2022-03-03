# How to query the model 

The following credentials and commands will give you access to a git repository hosted on aws codecommit. Start by executing:

`aws configure`

Provide the following as prompted.

`AWS Access Key ID: AKIAZRKHU2TKXW4DQ7WL`

`AWS Secret Key ID: 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`

`Default region name: eu-west-1`

Now you should be able to clone the repository:

`git clone https://git-codecommit.eu-west-1.amazonaws.com/v1/repos/machine-learning-case-study`

Jump inside the project and start the application with

`flask run`

query the application with

`curl -H "Content-Type: application/json" -X POST -d @test_request.json http://127.0.0.1:5000/default`

where the *test_request.json* can be found at the root of this project.

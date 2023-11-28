Plus W IT training class 5.
Task 3

AWS instance is launched. 


![Picture1](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/c1b10086-ef0c-459a-8679-583914c04550)


Connecting to instance using git


![Picture2](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/46b158f2-1a9e-43bf-a662-0e10837b70b4)


The to do list repository is cloned on my local instance 

![Picture3](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/f7ae61e2-87da-496e-91e3-547f561d9506)



Manual Steps for deploying the Django application



After installing all the necessary components such as pip and Django, using migration command to manage database schema


	![Picture4](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/37fbdb65-b037-4ab2-b65e-dc8672b55cc6)



Before running the server on 8001 port, going to settings.py file to make changes so that our web server runs 

	
![Picture5](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/14a11dbd-3665-4fb9-a8fd-80c9ffc3dbcb)




Next going to security in AWS instance security section and adding our port to security group and setting it so that it can be accessed from anywhere publicly



![Picture6](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/4b6fadde-ea43-4eba-b71c-be29ecafeeb1)



Finally running the server on 0.0.0.0:8001 IP so that it is available publicly. As you can see our web server is running successfully.
	
	







![Picture7](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/a530a7c3-5c65-4e0a-8be4-713475974d94)











Using docker to deploying the Django web server



After installing docker, creating a docker file which will automate the steps to deploy the django server 


	![Picture8](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/3e28a821-acf5-43a5-b856-9f6b60f7c2a2)



Docker file is successfully built 

![Picture9](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/89bc9351-e18a-4df3-9e50-8b3892789285)


	

Finally through docker our django web application is also deployed 


![Picture10](https://github.com/mooorey/plusw-class-5-task3/assets/59121431/893d3ede-205c-4b09-964d-9a01a24ff4a8)

	

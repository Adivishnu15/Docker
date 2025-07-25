










INSTALLATION Docker installation steps 
$ sudo apt-get update 
$ sudo apt-get install docker.io
 $ docker –version
For all java python web steps are same just run code  will be changed just change it 
	git clone https://github.com/Adivishnu15/Docker.git
	try to change image names & cntr+c for web code when it pause in a state after run

	create a new folder and add required file and Dockerfile 
	 
	 $ docker build –t javaimage . 
	 $ docker run -it javaimage  

	 $ docker login -u username   (enter actual password ,no need of tokens)

	 $ docker tag image username/image 

	  $ docker push username/image 

	 $ docker pull username/ image 

	$ docker run -it username/ image
(remember  changes made below everything is same steps for all)

  Experiment 5. Explore Docker commands for calculating sum and average of first ten numbers using Java.
Experiment 6. Explore Docker commands for perform arithmetic operations on two integers using Java
	docker build -t arithjava .
	docker run arithjava 10 20
Experiment 7. Explore Docker commands to display student details (Name, Rollno, Dept) using Java
8. Explore Docker commands for calculating sum and average of first ten numbers using Python.
9. Explore Docker commands for perform arithmetic operations on two integers using Python
	docker build -t arithpy . 
	docker run arithpy 10 20
10.Explore Docker commands for display student details (Name, Rollno, Dept) using Python
11.Explore Docker commands for change of background color of webpage.
	docker build -t bgcolor-demo .
	docker run -d -p 8080:80 bgcolor-demo
12.Explore Docker commands for Login form validation
	 docker build -t bgcolor-demo .
	docker run -d -p 8080:80 bgcolor-demo



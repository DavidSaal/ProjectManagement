### Yummly Project

Yummly is recipes website, that allow you t
our features in the project are : 
	1.give us the champion team for each leagues (premier league,La liga,primeria liga,Eredivisie,champion league,bundesliga,ligue1).  
	2.give us the best scorer for each league and sort it by amount of goals.  

### Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Python interperter
* pip
* IDE - Development envenvironment

### How to install

__1)__ Clone this repo to your computer:  `https://github.com/DavidSaal/ProjectManagement`

__2)__ Open command line.

__3)__ Enter the following commands in the CL:
      ```
      1.  pip install requests
      2.  pip install pycodestyle
      ```

__4)__ Open the project in your IDE.

## API's used

The web uses [Recipes Data- API](https://yummly.com) in order to get the recipes.  

The project is synchronized with:
* SemaphoreCi - An API used to implement CI/CD (Continuous Integration & Continuous Deployment).
* Heroku - A virtual production environment.

## Running the tests

In order to run the test, use command line to enter the following command:
(open command line in project's directory)
```
python MyTest.py
```
If all tests passed, you should see this output:

![image](https://github.com/DavidSaal/ProjectManagement/blob/master/images/TestsPass.jpg)


## Using the application
Run the program with the command (you can on  CL inside the directed file) 
```
python Yummly.py
```
and the following output will be : 

![image](https://github.com/DavidSaal/ProjectManagement/blob/master/images/ShowFeatures.jpg)

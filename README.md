The DevOps repository consists automated CICD pipleline. The pipeline is maninly designed to understand the various features of jenkins.

![image](https://user-images.githubusercontent.com/95271479/210200602-e2d6a8c3-58db-4bc7-a2a7-4ab20c00d402.png)

     
   
___________________________________________________________________________________________________________________________________________________________________
PREREQUISITES

1) Jenkins instance
2) Sonarqube
3) ASoD instance

_____________________________________________________________________________________________________________________________________________________________________
     FEATURES IN JENKINS
 
1) Modular pipeline
2) Variablization
3) Parameterization


 _____________________________________________________________________________________________________________________________________________________________________
     MODULAR PIPELINE
     
* Modular Pipeline is basically the combibation of Parameterization and Variablization. 
* Modularization helps the user to be more precise in writing and segregating the code. 
* We can segregate the stages according to the requirement.
* Modular Pipeline yaml file consists of two stages i.e "Sonarqube Code Analysis" and "Static Scan with ASoD"

![image](https://user-images.githubusercontent.com/95271479/210199013-7fd44d42-febf-46c7-b5a6-d84b1cc7ec11.png)



______________________________________________________________________________________________________________________________________________________________________
      PARAMETERIZATION
      Parameterization help to control the portion of the test to be executed. Here, in this modular pipeline we are using boolean paramter.
      Hence by defining Boolean Parameter inside a jenkins pipeline we can trigger the "Build with Paramaters" option.
      
  ![image](https://user-images.githubusercontent.com/95271479/210200791-df5192a7-ab55-4bd1-a9c0-7d9769782561.png)


      
___________________________________________________________________________________________________________________________________________________________________

      VARIABLIZATION
      Pipeline Variablization helps to separate configuration values from the core and inject during the runtime. Variablization is done for ASoD and sonarqube.
      Keep the groovy file which contains variables, and load the variables from the github into the pipeline during the runtime.
      
  ![image](https://user-images.githubusercontent.com/95271479/210199470-67df54cd-e7a7-4614-8a70-e9f0e8a6f5b8.png)
  
  
  


      


     

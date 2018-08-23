# Jenkins_demo
  **A declarative pipeline demonstration.**


### How to do ?

   1. Start jenkins in your machine.
   2. Select **New Item** from left side menu
   3. Enter project name (e.g., Declarative_Pipeline)
   4. Choose pipeline project
   5. Click on **Ok**
   6. Select **Configure** option from left side menu
   7. Select **Advanced Project Options** , it will scroll to down
   8. Select **Pipeline -> Definition -> Pipeline script from SCM** 
   9. Select Your SCM (Source Controll Managment) (e.g., Git)
   10. Enter your **Repositories info** 
      e.g., 
           -  URL : https://github.com/uds214125/jenkins_demo.git
           -  Add creds : github username  and github password
   11. Enter your script file name **Script Path** 
      e.g., pipeline-stage
   12. Apply -> Save
   13. Select **Build Now** option from left side menu
   
   
   ### How to do scripted pipeline in jenkins instance shell ?
   
   0. Follow above step from 1 to 7 
   8. Select **Pipeline -> Definition -> Pipeline script ** 
   9. Write your scirpt or copy and paste code from scripted_pipeline file.
   10. Apply -> Save
   11. Select **Build Now** option from left side menu.

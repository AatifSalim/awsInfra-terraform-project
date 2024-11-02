In this project I have deployed an infrastructure on aws using terraform.
I have used two ec2 instances which has its own user data with html code that will be executed when instance run.
![Screenshot 2024-11-02 195031](https://github.com/user-attachments/assets/c31333c6-0d04-47df-af1d-0d0c9b4ad951)
![Screenshot 2024-11-02 195307](https://github.com/user-attachments/assets/7ed53ca1-2975-4e6a-98c8-dcd5df9c614d)
Along with this i have used elastic load balancer for balancing the load on both the instances.
Various other resources such as vpc subnets , target groups will be created.

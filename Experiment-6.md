Experiment-6
Create the operator1 user and confirm that it exists in the system. Set the 
password for operator1. Create the additional operator2 and operator3 users. 
 
Set their passwords as well. Run the usermod -c command to update the 
comments of the operator1 user account. Remove the operator3 user from the 
system.

Approach-
Create the `operator1`, `operator2`, and `operator3` users, set their passwords, and confirm their existence. Update `operator1`’s comment using `usermod -c`, then remove `operator3` from the system.

![image](https://github.com/user-attachments/assets/75104073-7b97-456b-9a4b-1611f5e15fe4)
![image](https://github.com/user-attachments/assets/68f58ae6-ebed-4355-96f4-2c33de25f7f5)
![image](https://github.com/user-attachments/assets/9f0cd6ca-7263-4004-a8b2-ced4ef037af9)
![image](https://github.com/user-attachments/assets/e549a324-497c-4018-a51d-baf14bd56a23)
![image](https://github.com/user-attachments/assets/7beb2caf-f209-430d-b01d-55437c6e24ec)


Commands used-
useradd operator1, passwd operator1, useradd operator2, passwd operator2, useradd operator3, passwd operator3, usermod -c "<comment>" operator1, userdel operator3

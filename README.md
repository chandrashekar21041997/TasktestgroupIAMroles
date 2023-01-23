1) * Create an IAM user named 'testuser' * Create an IAM group named 'testgroup' The 'testuser' must have the following permissions attached directly to user: -> EC2 ReadOnlyAccess ' -> S3 ReadOnly Access -> RDS ReadOnlyAccess The 'testuser' must have the following permissions attached from usergroup named 'testgroup': -> EC2 FullAccess -> S3 FullAccess -> RDS FullAccess



Creating New User name: "testuser"
![Screenshot (371)](https://user-images.githubusercontent.com/119240540/214099146-eb76b597-87ea-4ff4-9c7c-f18cf1949051.png)

Adding to User Group


![Screenshot (373)](https://user-images.githubusercontent.com/119240540/214100109-60ac0134-e521-4b74-9448-96bb360ebb0b.png)



EC2 ReadOnlyAccess giving permision for testusergrop


![Screenshot (374)](https://user-images.githubusercontent.com/119240540/214100162-0ff34202-0eca-4add-b5ba-abb832d7afc4.png)

Creating User and Groups



![Screenshot (375)](https://user-images.githubusercontent.com/119240540/214101237-82f0af3a-0b04-488e-944d-d893c134ee31.png)

Created UserGroup

![Screenshot (376)](https://user-images.githubusercontent.com/119240540/214101524-2c821e90-f708-4aad-adf1-604c65bb042b.png)


Set permissions boundary on testuser
Login to test user and created Ec2 i can't create a new instance does not permision am only given read only access

![Screenshot (377)](https://user-images.githubusercontent.com/119240540/214102665-66eeacd0-c8cf-42c3-9f8a-184cbe6ac4ef.png)

now am giving full access to testuser for 3 things
1)EC2 FullAccess
2)S3 FullAccess
3)RDS FullAccess

![Screenshot (378)](https://user-images.githubusercontent.com/119240540/214103757-5eb622b6-2e98-4b00-81ba-44a235770735.png)

![Screenshot (379)](https://user-images.githubusercontent.com/119240540/214103852-15610b70-e5bd-4267-888b-16ed065b0a29.png)


![Screenshot (380)](https://user-images.githubusercontent.com/119240540/214103927-b92ad74c-9faa-4e16-90ab-da75377d8b44.png)


finally created EC2

![Screenshot (381)](https://user-images.githubusercontent.com/119240540/214104106-bacb872d-e0d4-40d6-8413-a66947721fb1.png)


# Students Details API using Postman & Newman
## How to run this project

- Clone this project
- Open with Postman / Command Shell
- Run Command:
   ```bash
  newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
- Run Command for Report:
  
 ```bash
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
 ```
## Technology used:
- Postman
- Newman
## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library
## Newman and Report Installation Process:
- Newman Install Command:
 ```
npm install -g newman-reporter-htmlextra
 ```
- Newman Html Report Install Command:
 ```
npm install -g newman-reporter-htmlextra
 ```
## API Documentation:
- https://documenter.getpostman.com/view/40715992/2sAYJ9BJkg
## Test case list:
 ### Create Student
   > i.Create Data Sets Using the Dynamic Random Variables.

  > ii.Response time below 500

### Verify Crated Student Details
In the test case you need to validate the following field values:

  > i.First Name

  > ii.Middle Name

  > iii.Last Name

  > iv.Date of Birth

  > v.Response time below 300

### Update Student
In the test case you need to validate the following field values:

  > i.Successful Message

  > ii.Response time below 1000

### Verify Verify Updated Student Details
In the test case you need to validate the following field values:

  > i.First Name

  > ii.Middle Name

  > iii.Last Name

  > iv.Date of Birth

  > v.Response time below 300

###Create Technical skills Create Student Address
In the test case you need to validate the following field values:

  > i.Successful Message

  > ii.Response time below 300

### Create a Student Address
In the test case you need to validate the following field values:

  > i.Successful Message

  > ii.Response time below 300

### Get the Student's Full Details
In the test case you need to validate the following field values:

  > i.First Name

  > ii.Middle Name

  > iii.Last Name

  > iv.Date of Birth

  > v.Language

  > vi.Year Of Experience

  > vii.Last Used Date

  > viii.House Number

  > ix.City

  > x.State

  > xi.Country

  > xii.Std Code

  > xiii.Home Address

  > xiv.Mobile

  > xv.Response time below 300

### Delete Specific Student
In the test case you need to validate the following field values:
   > i.Successful Message

  > ii.Response time below 300


## Newman Report Summary:
![1](https://github.com/user-attachments/assets/37dfbdc7-3a3c-48fb-b9dc-cc7bbacdc38f)
![2](https://github.com/user-attachments/assets/d49e58f8-2ec3-4902-80cd-dfc6cdd24b03)
![3](https://github.com/user-attachments/assets/59c53d15-a166-4107-986b-60bc5bed4227)



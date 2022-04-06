# vagrant_multi_vm
### Cloud Security Lecture

### GOALS:
- Based on Multi-server vagrant environment.
- 3 Virtual Machine -> build Web-service environment
- 2 VM = Web Server / 1 VM = DB Server
- 2 web server reference one DB server's database table and manage data. each web server's reference table is different.
  - web server1 -> response1 table
  - web server2 -> response2 table
  - The web server you are accessing decides which tables to modify.

### Results:
1. vagrant up: 2 web servers, 1 DB
<img width="412" alt="image" src="https://user-images.githubusercontent.com/74848401/161999353-b9997b00-76f6-4056-a687-4969c933a668.png">
2. Check created VMs
<img width="283" alt="image" src="https://user-images.githubusercontent.com/74848401/161999533-8ecf8e77-69bb-43e3-aa24-4f50402d9e16.png">
3. Accessing Website
<img width="1048" alt="image" src="https://user-images.githubusercontent.com/74848401/161999808-9c8d4d55-a744-4222-bcbe-6db41c7b51c7.png">
<img width="1046" alt="image" src="https://user-images.githubusercontent.com/74848401/162000071-bbb8cce7-e5e9-4b63-8337-225b1cbdf54e.png">
4. View the data
<img width="1041" alt="image" src="https://user-images.githubusercontent.com/74848401/162000187-da4b8c09-19bc-4693-9a00-49d020f59c5e.png">

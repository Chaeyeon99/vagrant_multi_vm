# vagrant_multi_vm
Cloud Security Lecture

GOALS:
- Based on Multi-server vagrant environment.
- 3 Virtual Machine -> build Web-service environment
- 2 VM = Web Server / 1 VM = DB Server
- 2 web server reference one DB server's database table and manage data. each web server's reference table is different.
 -- web server1 -> response1 table
 -- web server2 -> response2 table
 -> The web server you are accessing decides which tables to modify.

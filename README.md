# Configuration-Files that were modified and documentation created during the project

In this repository, there will be a copy of the main apache configuration file that exists on the server which is used to provide security
for users that browse and navigate the website as well as additional files that have been modified. The changes the group has made can be
found within this repository as well as information regarding the issues discovered and how they were resolved.

Important files within the repository.
  1) 'apache2.conf' is the file where the most changes were made. In the file is the entire apache configuration file and changes were 
  made in here to resolve security flaws. The code in the file enables the website to be as secure as possible.
  2) One change was made in the 'login.html' file to prevent password autocomplete in browser occuring enabling this issue from happening.
  3) The file 'Security-Issues' discuss the errors that were discovered through testing using an application called OWASP ZAP Zed Attack 
  Proxy which is a pentesting application.
  4) The file 'Implementation-To-Resolve-Security-Issues' shows the configuration code to fix each error that existed.

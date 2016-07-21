# CodeWorkshop-2016-08-04

Bluemix, NodeRed and Watson course

Set up development environment for Coding Workshop

(i) Sign up for Bluemix at www.bluemix.net with IBM email address.
(ii) Request services

Increase your Bluemix services and memory.

 Open a ticket through one of the following methods.

1- Fill out the form at https://ibm.biz/bluemixsupport
2- Submit a new ticket through the Client Success Portal at https://support.ibmcloud.com/ics/support/mylogin.asp?login=bluemix

Request 4 GB of memory and 15 services, plus 6 month access to Bluemix.

2.      Sign up for GitHub

https://github.com/

3.      Set up terminal and editor.

If you have a Macbook, download Atom text editor.

https://atom.io/

If you have a Thinkpad sign up for C9, which has full IDE needed and it is free. This isn’t an IBM product, however for the purposes of learning it is great for the workshop without having to install text editor and Ubuntu.

https://c9.io/

4.      Install Cloud Foundry in terminal.

In C9, log in and open a workspace and click “node.js” for template.

Open command line and copy and paste the following:

 curl -L "https://cli.run.pivotal.io/stable?release=linux64-binary&source=github" | tar -zx
Verify the version:

./cf --version
 

Mac OS:

curl -L "https://cli.run.pivotal.io/stable?release=macosx64-binary&source=github" | tar -zx
 Verify the version:

./cf --version
Reference: https://github.com/cloudfoundry/cli#downloads

5.      Install Homebrew and NPM if you are using your Macbook, c9 does require installation of NPM.

(i)                 Type in this command in your terminal for Homebrew:

curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install

(ii)               Type in:

Brew install node

Verify installed by typing in “npm –v” and should say version number.

References:

https://docs.npmjs.com/getting-started/installing-node

Prep material

Modern Programming Fundamentals

1)      JavaScript

http://eloquentjavascript.net/

https://www.codecademy.com/learn/javascript

Node.js, https://nodejs.org/en/

2)      Git tutorial

https://www.codecademy.com/learn/learn-git


Extra FYI

3)      Microservices Architecture

https://www.nginx.com/blog/introduction-to-microservices/

http://searchitoperations.techtarget.com/definition/microservices

12 factor app

http://12factor.net/

4)      Pair Programming

http://www.extremeprogramming.org/rules/pair.html

 

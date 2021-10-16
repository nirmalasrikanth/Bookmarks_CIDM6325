#1 My first road block is trying to figure where the base.html file is located in order to incorporate the changes to reflect the addition of checcking for authenticated users. I was searching for the file in the wrong place.

#2 Did not restart  the server after making changes to codes and was getting errors on the browser.

#3 The Django book did not explicitly ask to import os in settings.py but without that makemigration was throwing error for os.path.join.

#4 Visual Studion threw error when tried to install Social authentication app of Django. 

#5 The nightmare started when I tried to install the packages for a secure server login and things started spiraling down. First Google chrome and Microsoft Edge did not accept the certificate created in the code, then tried creating the certificate in Google Chrome and added it to Trusted Certificates, that did not work. Next I tried to create one using OpenSSL and I messed up the Environment Variable Path that even the command prompt was not opening and Python stopped working. I had to take a backup and rest the computer but there was still an issue with the user settings that I had to create a new user in my laptop, install the softwares, and do the codes all over. This time I have decided not to even try to install the packages and struggle with https issue. I have decided to skip that part of the code in Chapter 4.

#6 I could not use all the feature that comes with bookmark since my server runs on http and it was trying to access https content. "code 400, message Bad HTTP/0.9 request type". I could not bookmark images on other websites due to this reason.

#7 Did not follow the instruction in the code properly and added the user_follow after user_detail path in urls.py and ended up with error when the "FOLLOW" button was clicked.

#8 Had created the "action/detail.html" folder under the "Account" instead of "action/templates". The server threw an error that action/detail.html is not available. 






ECHO is on.
------------------------------------------------------------------
project admin:
name->ojas gupta
email->ojasgupta25@gmail.com
contact->+1 310347 6097------------------------------------------------------------------
project-description
project ondemandservices is web application which provides couples of tools
like resume maker, free ebook , image resizer,
bulk emails senderk etc.

_________________________________________________________________
current running enviroment-
dbugmode=on [setting.py]
localhost

_________________________________________________________________
project status--- under development
                          project start date-2019
_________________________________________________________________
Project global configuration:
1-install requirements.txt first 
2-add you google login api secrete key and id in settings.py
3-for create admin username and password for admin login -- use command->>>python manage.py createsuperuser



__________________________________________________________________
Application detail and local configuration:

Bulk_email_sender->

1-set you gmail password in views.py 
2-change the email and username according to your gmail account  :
@ location -->if request.user.email == 'geekydirect@gmail.com' and request.user.username == 'geekydirect':
in view.py
___________________________

free-books->
1-all uploaded images and ebooks would be saved in media folder

___________________________
Resume maker->
1-Still under development
______________________________________
email-recorder->
1-no configuration required
_______________________________________
image resizer->
1- work with jpeg only
no other configuration required

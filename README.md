# devops-mailhog
A simple mailhog stack with auth in file 


## auth setting

- Users are define in `auth_file.txt`

- the Default user is `test:test`

   `test:$2a$04$qxRo.ftFoNep7ld/5jfKtuBTnGqff/fZVyj53mUC5sVf9dtDLAi/S`



Edit `auth_file.txt`  for set users

mailhog doc about auth 

https://github.com/mailhog/MailHog/blob/master/docs/Auth.md



## launch the stack

  `docker-compose up -d` 

  or
 
  `dc up -d`

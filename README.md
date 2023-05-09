# Aws_Test_Deploy
This is for testing purpose how to deploy your django app on aws
article used here:https://www.codewithmuh.com/blog/deploy-django-application-on-ec2-with-postgresql-s3-domain-and-ssl-setup
structure--------------------
root(repository) name->requirements.txt,manage.py,root folder,app folder,media folder,readme file
password--------------------
localhost(sqlite)->username:pinaki
                   password:1234
EC2 details------------------
name:backendcourse
keypairname:backendcourse

commands---------------------
sudo rm -f {folder_name}

RDS details-----------------
name:backendcourse
master_usernme:mysuperuser
master_password:mysuperuser
security_name:backend
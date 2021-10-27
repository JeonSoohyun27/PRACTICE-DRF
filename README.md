Build a Backend REST API with Python & Django
---
Git
---
Use the below Git commands in the Windows Command Prompt or macOS Terminal.

<b>Configure default email and name</b>
```
git config --global user.email "your@email.com"
git config --global user.name "Your Name"
```
<b>Initialise a new Git repository</b>
```
git init
```
<b>Commit changes to Git</b>
```
git add .
git commit -am "Commit message"
```
<b>Set Git remote</b>
```
git remote add origin <URL TO PROJECT>
git push -u origin master
```
<b>Push changes to GitHub</b>
```
git push origin
```

SSH Key Management
---
The below commands are used to manage SSH keys on your local development machine.

<b>Checking for existing SSH key</b>
```
ls ~/.ssh/
```
<b>Print contents of public key</b>
```
cat ~/.ssh/id_rsa.pub
```
<b>Generate new SSH key on your local machine</b>
```
ssh-keygen -t rsa -b 4096 -C "EMAIL ADDRESS"
```

Django Management Commands
---
<b>Create new Django project</b>
```
django-admin.py startproject profiles_project  .
```
<b>Create new Django app</b>
```
python manage.py startapp profiles_api
```
<b>Start Django development server</b>
```
python manage.py runserver 0.0.0.0:8000
```
<b>Create database migrations file</b>
```
python manage.py makemigrations
```
<b>Run migrations</b>
```
python manage.py migrate
```
<b>Create new superuser</b>
```
python manage.py createsuperuser
```

AWS Public IPv4 DNS
---
ec2-3-38-151-241.ap-northeast-2.compute.amazonaws.com/api




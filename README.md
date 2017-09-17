# Linux Server Configuration

---

### IP Address
54.218.78.111

### URL
http://54.218.78.111/

### SSH PORT
2200

---

The user _grader_ was created with the password of "grader".

To connect remotely, _grader_ must use ssh key based authentication.

Firewall was configured in OS to block all incoming connection requests except 
on ports 80 (http), 2200 (ssh), and 123 (ntp).  All outgoing connection requests 
are allowed.

Packages were updated as well as any security updates.

In order to setup and have a running wsgi website, Apache and Postgresql 
were install along with the wsgi module for Apache.

I had to install _pip_ to install all the required Python modules (e.g. Flask, 
psycopg2, etc.) for the web site to run properly.

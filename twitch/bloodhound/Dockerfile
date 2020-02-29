FROM kalilinux/kali-rolling:latest 

RUN apt update && apt install python python-pip -y

RUN pip install ldap3==2.5.1
RUN pip install bloodhound

CMD bloodhound-python
FROM kalilinux/kali-rolling:latest 

RUN apt update && apt install python python-pip git -y

RUN git clone https://github.com/rxwx/impacket.git

WORKDIR /impacket

RUN pip install -r requirements.txt
RUN pip install .


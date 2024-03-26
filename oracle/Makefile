profile: /etc/profile
	source $^
	source ~/.bashrc
start: 
	source ~/.bashrc
	lsnrctl start
	netstat -ntlp
stop:
	lsnrctl stop
	netstat -ntlp
status:
	lsnrctl status
	netstat -ntlp

# ATW (AWS Tool Web)

Required
========
	Python + Flask + Boto3

Install
=======
	# yum install python-pip -y
	# pip install flask
	# pip install boto3
	# git clone https://github.com/nopp/atw.git
	# cd atw
	-> configure the application
	# python atw.py

Configure
=========

	Create a file /etc/atw/config.cfg with:

	[conf]
	accessKey = yourAccessKeyWithEC2ReadOnly
	secretKey = yourPrivateKeyWithEC2ReadOnly
	ip = ipOfYourATWServer
	port = portOfYourATWServer

Screenshot
==========
![Image Alt](http://i68.tinypic.com/1568wp1.png)

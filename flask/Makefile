run:
	#export FLASK_ENV=development
	#flask --app server run -h 0.0.0.0 -p 8083
	python3 server.py
install-dependencies:
	pip install -r requirements.txt
background:
	nohup python3 server.py > server.out &
ps:
	 ps -fea | grep python3
monitor:
	tail -f server.out

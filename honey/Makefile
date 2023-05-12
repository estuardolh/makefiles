today:
	mkdir -p /tmp/cowrie/ && docker cp honey:/cowrie/cowrie-git/var/log/cowrie/ /tmp/cowrie/ && egrep -Hr "cowrie\.login|cowrie\.command" /tmp/cowrie/cowrie/cowrie.json | head -n 25 | egrep --color "login|success|username|password|input"
all:
	mkdir -p /tmp/cowrie/ && docker cp honey:/cowrie/cowrie-git/var/log/cowrie/ /tmp/cowrie/ && cat /tmp/cowrie/cowrie/*json* | less

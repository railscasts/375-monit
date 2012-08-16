# RailsCasts Episode #375: Monit

http://railscasts.com/episodes/375-monit

Requires Ruby 1.9.2 or higher.


### Commands used on server

```
sudo apt-get update
sudo apt-get install monit
sudo vim /etc/monit/monitrc
sudo killall nginx
sudo tail /var/log/monit.log
```

### Commands used on local

```
cap monit:setup
cap unicorn:setup unicorn:restart monit:setup
```

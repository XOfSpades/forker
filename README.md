# Usage

* Assuming you have a file which can be executed with `foo ./bar`. You can use forker with `./forker.sh "foo ./bar"`. The script will create 5 forks and monitor each pid. If an instance crashes it is restarted after a short sleep.

* You can also send out an email if the process fails to restart, with, `./forker.sh "foo ./bar" "email1.com"` or to multiple recipients using  `./forker.sh "foo ./bar" "email1.com email2.com"`

* To send an email install mailutils: `sudo apt-get install mailutils`

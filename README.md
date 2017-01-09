# Usage

Assuming you have a file which can be executed with `foo ./bar`. You can use forker with `./forker.sh "foo ./bar"`. The script will create 5 forks and monitor each pid. If an instance crashes it is restarted after a short sleep.

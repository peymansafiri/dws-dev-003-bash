# dws-dev-003-bash
This Bash script creating command retry intervals with this format :# try -i Interval -n Number COMMAND

in this script we have default number for variable.when the Command exit with code 0 , it means script run successful and if code is not 0 the process continues till successful execution.

for example : #try -i 15 -n 10 flask app test

[@dwsclass](https://github.com/dwsclass) dws-dev-003-bash

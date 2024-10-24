# restart_quil_node

Nadajesz mu prawa do wykonania:


chmod +x $HOME/check-for-frames.sh

Edycja crontab
Otwórz edytor crontab dla bieżącego użytkownika za pomocą polecenia:

crontab -e


Dodaj następującą linię, aby skrypt uruchamiał się co 10 minut:

*/10 * * * * ${HOME}/check-for-frames.sh >> ${HOME}/check-for-frames.log 2>&1

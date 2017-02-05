Witajcie! Dziś poradnik – serwer LEMP na systemie CentOS 6 / RHEL 6 – dlaczego dla tak “starego” systemu ?
Wbrew pozorom, z CentOSa korzysta bardzo wiele użytkowników, system ten pracuje jeszcze na Kernelu 2.6.32.x i jest wspierany (security).
Popularnośc systemu można zawdzięczyć zapewne jogo “ojcu” czyli Red Hatowi, ale odpowiedź na pytanie pozostawie dla was.

Przygotowana konfiguracja opiera się na:

NGINX – jako główny serwer WWW, wszelkie konfiguracje v-hostów znajdują się w /etc/nginx/conf.d/ (przykładowy plik w katalogu)
MariaDB w wersjach 5/10/10.1 – jako alternatywna baza danych (odpowiednik MySQL)
PHP-FPM wersja 5.6 interpreter skryptów PHP wraz z Opcache oraz IonCube’m
vSFTPd – jako serwer FTP
PHPMyAdmin – jako graficzny interfejs do zarządzania bazami danych i użytkownikami bazy danych
..oraz dodatki ode mnie..
 

Dostęp do PHPMyAdmina: http://IP:9977
NGINX port : http://IP:80
Pliki konfiguracyjne:

vhost NGINX – /etc/nginx/conf.d/default.conf
php.ini – /etc/php.ini
konfiguracja NGINX – /etc/nginx/

###########################################################################################################################################

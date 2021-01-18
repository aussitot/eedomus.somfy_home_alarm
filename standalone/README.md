# eedomus.somfy_home_alarm
plugin eedomus pour somfy home alarm
Initial script : https://github.com/Mystikal57/Somfy_Home_ALARM_API


appeler la page control.php avec l'argument action= armed, disarmed, partial, weekend, notif_off ou notif_on
ex: control.php?action=armed

Pour connaite l'état de l'alarme il faut appeler la page state.php

Description des commandes:
- armed : activer l'alarme
- disarmed : desactiver l'alarme
- partial: mode nuit : 3 etapes: desactivation de la notification sonore de la sirene, activation du mode nuit, réactivation de la notification sonore (après le délais d'activation)
- weekend: mode nuit sans réactivation des notifications sonores (évite d'être reveillé par la notification)
- notif_off: desactivation des notifications sonores de la sirene
- notif_on: activation des notifications sonores de la sirene


Changelog:

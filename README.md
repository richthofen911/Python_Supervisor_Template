# Python_Supervisor_Template

url_reference: https://serversforhackers.com/monitoring-processes-with-supervisord
url_offical: http://supervisord.org/configuration.html

default conf file path: /etc/supervisord.conf

To take effect for the conf changes:
   supervisorctl reread
   supervisorctl update
   supervisorctl start 'program_name'
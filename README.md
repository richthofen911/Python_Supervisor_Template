# Python_Supervisor_Template<br />

url_reference: https://serversforhackers.com/monitoring-processes-with-supervisord<br />
url_offical: http://supervisord.org/configuration.html<br /><br />

default conf file path: /etc/supervisord.conf<br /><br />

To take effect for the conf changes:<br />
   supervisorctl reread<br />
   supervisorctl update<br />
   supervisorctl start 'program_name‘

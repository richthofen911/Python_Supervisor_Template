# Python_Supervisor_Template<br />

http://www.restran.net/2015/10/04/supervisord-tutorial/

url_reference: https://serversforhackers.com/monitoring-processes-with-supervisord<br />
url_offical: http://supervisord.org/configuration.html<br /><br />

default conf file path: /etc/supervisord.conf<br /><br />

To take effect for the conf changes:<br /><br />
   supervisorctl reread<br />
   supervisorctl update<br />
   supervisorctl start 'program_name‘

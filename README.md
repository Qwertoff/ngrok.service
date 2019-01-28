# ngrok.service
Ngrok service for systemd

1. Download ngrok from http://ngrok.io

2. Put ngrok to /opt/ngrok

3. Put ngrok.yml to /opt/ngrok/conf
  * Auth is enabled only with Basic billing subscribtion or higher
  * Examples of config file look at https://ngrok.com/docs#config-examples

4. Put ngrok.service to /etc/systemd/system

5. Autostart ngrok with systemctl enable ngrok.service

6. Start ngrok with systemctl start ngrok.service

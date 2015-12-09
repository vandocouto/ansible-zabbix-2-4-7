# Orquestração do Zabb

Necessário a instalação do módulo: blockinfile

Para instalar, execute o comando abaixo:

$ sudo ansible-galaxy install yaegashi.blockinfile

Altera os valores das variáveis conforme sua necessidade:

zabbix_agent/vars/main.yml

---
# vars file for zabbix_agent
zabbix_server: 'zabbix.tgl.com'
url: 'http://downloads.sourceforge.net/project/zabbix/ZABBIX%20Latest%20Stable/2.4.7/zabbix-2.4.7.tar.gz'
tar_zabbix: 'zabbix-2.4.7.tar.gz'
dir_dest: '/opt'
dir_zabbix: 'zabbix-2.4.7'

Mais informações visite o blog:
http://tutoriaisgnulinux.com


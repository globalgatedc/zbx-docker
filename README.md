# zbx-docker
O plugin no grafana já está sendo instalado pelo ENV de plugins, precisa ser habilitado
as envs que precisam ser setadas para rodar estão com placeholder no .env
a url a ser configurada no grafana com a configuração atual é a: http://zabbix-web-nginx-mysql:8080/api_jsonrpc.php
é preciso setar o user (atualmente o padrão) pensar na criação de um usuário separado para o grafana a fim de dar a possibilidade pro usuário alterar a senha padrão

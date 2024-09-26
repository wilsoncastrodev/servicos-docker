
# Serviços Docker

![adminer](https://img.shields.io/badge/adminer-blue?style=for-the-badge) ![filebrowser](https://img.shields.io/badge/filebrowser-green?style=for-the-badge) ![elasticsearch](https://img.shields.io/badge/elasticsearch-yellow?style=for-the-badge) ![registry](https://img.shields.io/badge/registry-lightgrey?style=for-the-badge) ![zabbix](https://img.shields.io/badge/zabbix-red?style=for-the-badge) ![rclone](https://img.shields.io/badge/rclone-purple?style=for-the-badge) ![duplicati](https://img.shields.io/badge/duplicati-orange?style=for-the-badge) ![graylog](https://img.shields.io/badge/graylog-black?style=for-the-badge) ![yacht](https://img.shields.io/badge/yacht-cyan?style=for-the-badge) ![ntfy](https://img.shields.io/badge/ntfy-lightblue?style=for-the-badge) ![elastic-agent](https://img.shields.io/badge/elastic--agent-yellowgreen?style=for-the-badge) ![glances](https://img.shields.io/badge/glances-darkblue?style=for-the-badge) ![portainer](https://img.shields.io/badge/portainer-brightgreen?style=for-the-badge) ![yourls](https://img.shields.io/badge/yourls-lightcoral?style=for-the-badge) ![authelia](https://img.shields.io/badge/authelia-9cf?style=for-the-badge) ![syslog](https://img.shields.io/badge/syslog-blueviolet?style=for-the-badge) ![keycloak](https://img.shields.io/badge/keycloak-darkred?style=for-the-badge) ![gitea](https://img.shields.io/badge/gitea-darkgreen?style=for-the-badge) ![it-tools](https://img.shields.io/badge/it--tools-mediumorchid?style=for-the-badge) ![wiseguard](https://img.shields.io/badge/wiseguard-teal?style=for-the-badge) ![dozzle](https://img.shields.io/badge/dozzle-crimson?style=for-the-badge) ![traefik](https://img.shields.io/badge/traefik-pink?style=for-the-badge) ![mailhog](https://img.shields.io/badge/mailhog-maroon?style=for-the-badge) ![tailscale](https://img.shields.io/badge/tailscale-deepskyblue?style=for-the-badge) ![swarmpit](https://img.shields.io/badge/swarmpit-darkcyan?style=for-the-badge) ![kibana](https://img.shields.io/badge/kibana-palevioletred?style=for-the-badge) ![uptime-kuma](https://img.shields.io/badge/uptime--kuma-darkorange?style=for-the-badge) ![netdata](https://img.shields.io/badge/netdata-midnightblue?style=for-the-badge) ![homer](https://img.shields.io/badge/homer-tomato?style=for-the-badge) ![vault](https://img.shields.io/badge/vault-slategray?style=for-the-badge) ![fluentbit](https://img.shields.io/badge/fluentbit-dodgerblue?style=for-the-badge) ![grafana](https://img.shields.io/badge/grafana-darkorange?style=for-the-badge) ![vaultwarden](https://img.shields.io/badge/vaultwarden-lightslategray?style=for-the-badge) 

## Objetivo
O objetivo é estudar serviços Docker que facilitem o desenvolvimento, manutenção, monitoramento e segurança das aplicações. A ideia é melhorar o fluxo de trabalho, encontrando soluções que tornem tarefas complexas mais simples, aumentando assim a produtividade e a qualidade em todas as fases do ciclo de vida do desenvolvimento.

<br>

> Nota: A maioria destes serviços já se encontram pré-configurados para funcionar no ambiente de testes. No entanto, para o ambiente de produção, é necessário fazer configurações adicionais de segurança. Essas configurações são cruciais para garantir que os serviços funcionem de forma segura e confiável.

<br>

## Índice
- [Mapa Mental](#mapa-mental)
- [Lista de Serviços](#lista-de-serviços)
- [Instalação e Execução da Aplicação](#instalação-e-execução-da-aplicação)
- [Screenshots dos Serviços](#screenshots-dos-serviços)
- [Créditos](#créditos)
- [Agradecimentos](#agradecimentos)
- [Autores](#autores)
- [Licença](#licença)

## Mapa Mental
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/services-mind-map.png) 

## Lista de Serviços
#### Adminer
- Interface simples para gerenciar bancos de dados (MySQL, PostgreSQL, SQLite, etc.) via web. Alternativa ao phpMyAdmin.
#### Authelia
- Solução de autenticação multifator (MFA) e single sign-on (SSO) para proteger aplicativos.
#### Dozzle
- Visualizador simples e em tempo real de logs Docker via navegador.
#### Duplicati
- Software de backup que criptografa e envia dados para serviços de nuvem ou servidores remotos.
#### Elastic-agent
- Agente para coletar métricas e logs de servidores, redes e aplicações, integrando-se com Elasticsearch e Kibana.
#### Elasticsearch
- Motor de busca e análise distribuído, projetado para indexar grandes volumes de dados em tempo real.
#### Filebrowser
- Gerenciador de arquivos via navegador, que permite visualizar, editar, excluir e fazer upload de arquivos remotamente.
#### Fluentbit
- Coletor de logs leve e de alto desempenho para monitoramento de sistemas e agregação de logs.
#### Gitea
- Plataforma leve de controle de versão e colaboração de código, similar ao GitHub, auto-hospedada.
#### Glances
- Monitor de sistema em tempo real que exibe métricas de uso de CPU, memória, rede e processos.
#### Grafana
- Plataforma de visualização e monitoramento de dados, com suporte a gráficos interativos e alertas.
#### Graylog
- Plataforma de gerenciamento de logs centralizada com suporte a pesquisa e análise de logs em tempo real.
#### Homer
- Interface de dashboard simples e personalizável para exibir links e informações sobre serviços e ferramentas.
#### IT-Tools
- Conjunto de ferramentas online para realizar tarefas comuns de TI, como conversões e diagnósticos.
#### Keycloak
- Ferramenta de gerenciamento de identidade e acesso, com suporte a autenticação e autorização via SSO.
#### Kibana
- Interface de visualização e exploração de dados para Elasticsearch, usada para criar dashboards e relatórios.
#### Mailhog
- Ferramenta para capturar e inspecionar emails enviados durante testes de desenvolvimento.
#### Netdata
- Ferramenta de monitoramento de performance em tempo real, exibindo gráficos de métricas do sistema.
#### Ntfy
- Sistema de notificação via push, permitindo enviar alertas ou mensagens para dispositivos móveis e desktops.
#### Portainer
- Interface de gerenciamento para ambientes Docker e Kubernetes, simplificando o gerenciamento de contêineres e stacks.
#### Rclone
- Ferramenta de linha de comando para gerenciar e sincronizar arquivos entre armazenamento local e serviços em nuvem.
#### Registry
- Repositório Docker para armazenar e distribuir imagens de contêineres.
#### Swarmpit
- Interface web para gerenciar e monitorar clusters Docker Swarm.
#### Syslog
- Protocolo para envio de logs de eventos do sistema ou de dispositivos de rede para um servidor central.
#### Traefik
- Proxy reverso e balanceador de carga, integrado com Docker, Kubernetes e Let's Encrypt para gerenciamento de certificados.
#### Uptime-Kuma
- Monitoramento de uptime de sites e serviços com notificações de falhas e relatórios de disponibilidade.
#### Vault
- Ferramenta de gerenciamento de segredos e controle de acesso para proteger dados confidenciais como senhas e tokens.
#### Vaultwarden
- Implementação leve do Bitwarden, um gerenciador de senhas, para uso auto-hospedado.
#### WiseGuard
- Solução de segurança para proteger aplicativos e redes, provavelmente relacionada a firewall ou monitoramento.
#### Yacht
- Interface web para gerenciar contêineres Docker, simplificando a administração de stacks.
#### YOURLS
- Sistema de encurtamento de URLs auto-hospedado, que permite criar e gerenciar links curtos.
#### Zabbix
- Plataforma de monitoramento para redes, servidores e aplicações, com suporte a alertas e dashboards.

## Instalação e Execução da Aplicação

#### Pré-requisitos
São necessários os seguintes requisitos instalados e configurados no ambiente de testes para executar os serviços:
- Docker instalado
- Docker Compose instalado
- Docker Swarm inicializado
- Rede Overlay "web" configurada
- Traefik configurado
- Firewall e Portas configuradas 

#### Configurando e Executando os Serviços com Docker
- A configuração dos serviços deve ser ajustadas de acordo com as necessidades específicas de cada serviço individualmente. E em cada arquivo docker-compose se encontram comandos documentados para implantar os serviços docker no ambiente de testes.

## Screenshots dos Serviços
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/homer.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/yatch.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/it-tools.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/dozzle.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/duplicati.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/filebrowser.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/gitea.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/glances.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/grafana.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/authelia.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/portainer.png)
![Service Screenshot](https://github.com/wilsoncastrodev/servicos-docker/blob/master/%23docs/images/vault.png)


## Créditos
Seguem os créditos das ferramentas e dos serviços Docker:
- **[Adminer](https://hub.docker.com/_/adminer)** desenvolvido por [Adminer](https://www.adminer.org/)
- **[Dozzle](https://hub.docker.com/r/amir20/dozzle)** desenvolvido por [Amir20](https://github.com/amir20)
- **[Authelia](https://hub.docker.com/r/authelia/authelia)** desenvolvido por [Authelia](https://www.authelia.com/)
- **[Homer](https://hub.docker.com/r/b4bz/homer)** desenvolvido por [B4bz](https://github.com/b4bz)
- **[Syslog-ng](https://hub.docker.com/r/balabit/syslog-ng)** desenvolvido por [Balabit](https://syslog-ng.com/)
- **[Ntfy](https://hub.docker.com/r/binwiederhier/ntfy)** desenvolvido por [Binwiederhier](https://github.com/binwiederhier)
- **[Watchtower](https://hub.docker.com/r/containrrr/watchtower)** desenvolvido por [Containrrr](https://containrrr.dev/)
- **[IT Tools](https://hub.docker.com/r/corentinth/it-tools)** desenvolvido por [Corentinth](https://github.com/CorentinTh)
- **[Elastic Agent](https://hub.docker.com/r/elastic/elastic-agent)** desenvolvido por [Elastic](https://www.elastic.co/)
- **[Elasticsearch](https://hub.docker.com/_/elasticsearch)** desenvolvido por [Elastic](https://www.elastic.co/)
- **[Kibana](https://hub.docker.com/_/kibana)** desenvolvido por [Elastic](https://www.elastic.co/)
- **[Filebrowser](https://hub.docker.com/r/filebrowser/filebrowser)** desenvolvido por [Filebrowser](https://filebrowser.org/)
- **[Fluent-bit](https://hub.docker.com/r/fluent/fluent-bit)** desenvolvido por [Fluent](https://fluentbit.io/)
- **[Gitea](https://hub.docker.com/r/gitea/gitea)** desenvolvido por [Gitea](https://gitea.io/en-us/)
- **[Grafana](https://hub.docker.com/r/grafana/grafana)** desenvolvido por [Grafana Labs](https://grafana.com/)
- **[Loki](https://hub.docker.com/r/grafana/loki)** desenvolvido por [Grafana Labs](https://grafana.com/)
- **[Promtail](https://hub.docker.com/r/grafana/promtail)** desenvolvido por [Grafana Labs](https://grafana.com/)
- **[Graylog](https://hub.docker.com/r/graylog/graylog)** desenvolvido por [Graylog](https://www.graylog.org/)
- **[Consul](https://hub.docker.com/r/hashicorp/consul)** desenvolvido por [Hashi Corp, Inc.](https://www.hashicorp.com/)
- **[Vault](https://hub.docker.com/r/hashicorp/vault)** desenvolvido por [Hashi Corp, Inc.](https://www.hashicorp.com/)
- **[InfluxDB](https://hub.docker.com/r/influxdb/influxdb)** desenvolvido por [InfluxData](https://www.influxdata.com/)
- **[Jenkins](https://hub.docker.com/r/jenkins/jenkins)** desenvolvido por [Jenkins](https://www.jenkins.io/)
- **[Docker Registry UI](https://hub.docker.com/r/joxit/docker-registry-ui)** desenvolvido por [Joxit](https://github.com/Joxit)
- **[Duplicati](https://hub.docker.com/r/linuxserver/duplicati)** desenvolvido por [Linuxserver.io](https://www.linuxserver.io/)
- **[Wireguard](https://hub.docker.com/r/linuxserver/wireguard)** desenvolvido por [Linuxserver.io](https://www.linuxserver.io/)
- **[Uptime Kuma](https://hub.docker.com/r/louislam/uptime-kuma)** desenvolvido por [Louislam](https://github.com/louislam/uptime-kuma)
- **[Mailhog](https://hub.docker.com/r/mailhog/mailhog)** desenvolvido por [Mailhog](https://github.com/mailhog/MailHog)
- **[Netdata](https://hub.docker.com/r/netdata/netdata)** desenvolvido por [Netdata](https://www.netdata.cloud/)
- **[Glances](https://hub.docker.com/r/nicolargo/glances)** desenvolvido por [Nicolargo](https://nicolargo.github.io/)
- **[Portainer](https://hub.docker.com/r/portainer/portainer-ce)** desenvolvido por [Portainer.io](https://www.portainer.io/)
- **[Keycloak](https://hub.docker.com/r/keycloak/keycloak)** desenvolvido por [Keycloak](https://www.keycloak.org/)
- **[Rclone](https://hub.docker.com/r/rclone/rclone)** desenvolvido por [Rclone](https://rclone.org/)
- **[Registry](https://hub.docker.com/_/registry)** desenvolvido por [Docker](https://www.docker.com/)
- **[Yacht](https://hub.docker.com/r/selfhostedpro/yacht)** desenvolvido por [Selfhostedpro](https://github.com/SelfhostedPro)
- **[Swarmpit Agent](https://hub.docker.com/r/swarmpit/agent)** desenvolvido por [Swarmpit](https://swarmpit.io/)
- **[Swarmpit](https://hub.docker.com/r/swarmpit/swarmpit)** desenvolvido por [Swarmpit](https://swarmpit.io/)
- **[Traefik Forward Auth](https://hub.docker.com/r/thomseddon/traefik-forward-auth)** desenvolvido por [Thomseddon](https://github.com/thomseddon/traefik-forward-auth)
- **[Traefik](https://hub.docker.com/r/traefik/traefik)** desenvolvido por [Traefik Labs](https://traefik.io/)
- **[Vaultwarden](https://hub.docker.com/r/vaultwarden/server)** desenvolvido por [Vaultwarden](https://github.com/dani-garcia/vaultwarden)
- **[Yourls](https://hub.docker.com/r/yourls/yourls)** desenvolvido por [Yourls](https://yourls.org/)
- **[Zabbix Agent](https://hub.docker.com/r/zabbix/zabbix-agent2)** desenvolvido por [Zabbix](https://www.zabbix.com/)
- **[Zabbix Server (PostgreSQL)](https://hub.docker.com/r/zabbix/zabbix-server-pgsql)** desenvolvido por [Zabbix](https://www.zabbix.com/)
- **[Zabbix Web (Nginx/PostgreSQL)](https://hub.docker.com/r/zabbix/zabbix-web-nginx-pgsql)** desenvolvido por [Zabbix](https://www.zabbix.com/)

## Agradecimentos
Agradecimentos especiais às comunidades de código aberto por compartilharem estes serviços. Vocês fazem a diferença no mundo, inspirando outros a contribuir e a colaborar. Que Deus abençoe vocês todos. Vocês são incríveis!

> Esta documentação foi parcialmente elaborada com o auxílio do ChatGPT, que é a inteligência artificial desenvolvida pela OpenAI.

## Autores
- [@wcastro](https://github.com/wilsoncastrodev) 

## Licença
![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)


# 1 DOCKER instalado

# 2 Executar o compose com o seguinte comando
docker-compose -f "Manuais/Ambientes/Dev/docker-compose.yml" up -d

# pode ser acessado o consul pelo link:
http://localhost:8500

# Banco postgres
http://localhost:5432

# Servidor de Autenticação KEYCLOAK rodando
http://localhost:8082

# Servidor de mensageria RabbitMQ
http://localhost:8083


# AMBIENTE CONFIGURADO


# Comparativo dos serviços de mensageria ActiveMQ e RabbitMQ
https://www.openlogic.com/blog/activemq-vs-rabbitmq


# INFRA  DEV
 - Keycloak : Autenticação
 - Postgres : Banco para o keycloak
 - RabbitMQ : Mensageria
 - Stork : Service discovery com consul 
 - Consul : Service discovery e Proxy com CONSUL DNS <Futura implementação>
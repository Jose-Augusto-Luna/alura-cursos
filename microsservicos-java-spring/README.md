Para praticar o design e projeto de uma arquitetura de microsserviços, vamos implementar os seguintes componentes:

Serviço de registro e descoberta: uso do Eureka Server, utilizado amplamente no ecossistema Spring Cloud.
API Gateway: componente que vai atuar como ponto de entrada único para todas as requisições feitas pelos clientes (como frontend, mobile ou terceiros)
Microsserviços de pedidos, pagamentos e usuários: todas essas aplicações serão independentes, com seu próprio banco de dados, e irão comunicar-se entre si.
Config Server: um serviço do Spring Cloud que permite centralizar e gerenciar configurações de múltiplos microsserviços.
Utilizaemos estratégias de comunicação, tanto síncrona quanto assíncrona, utilizando message brokers para garantir eficiência e escalabilidade.

Além disso, exploramos mecanismos de resiliência, como circuit breaker e fallback, essenciais para manter a estabilidade dos serviços diante de falhas.

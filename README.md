# AzureDevOps-Pipelines-Kafka-Bash-kcat-LoadTests
Pipeline do Azure DevOps para execução automatizada de testes de carga baseados na ferramenta kafkacat/kcat a partir do virtual environment ubuntu-latest (Linux), com execução de instruções em paralelo via Bash e envio de mensagens para um tópico do Apache Kafka no Azure Event Hubs.

Deployment da aplicação testada, incluindo configurações do **KEDA (Kubernetes Event-driven Autoscaling)**:

**https://github.com/renatogroffe/Kubernetes-KEDA-Kafka-DotNet7-Sql-AppInsights_ContagemAcessos**

Para saber mais sobre o **kafkacat/kcat** acesse este [**link**](https://github.com/edenhill/kcat).
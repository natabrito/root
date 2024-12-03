```
root/
├── api-gateway/
│   ├── README.md
│   ├── pom.xml
│   └── src/
├── ingestion-service/
│   ├── README.md
│   ├── pom.xml
│   └── src/
├── enrichment-service/
│   ├── README.md
│   ├── pom.xml
│   └── src/
├── risk-calculation-service/
│   ├── README.md
│   ├── pom.xml
│   └── src/
├── anomaly-detection-service/
│   ├── README.md
│   ├── Pipfile
│   └── src/
├── action-orchestration-service/
│   ├── README.md
│   ├── serverless.yml
│   └── src/
├── common-libraries/
│   ├── README.md
│   └── utils/
├── infrastructure/
│   ├── README.md
│   ├── terraform/
│   └── ansible/
├── docs/
│   ├── README.md
│   ├── architecture-diagram.png
│   └── requirements.md
├── tests/
│   ├── README.md
│   └── integration/
├── scripts/
│   ├── build.sh
│   ├── test.sh
│   └── deploy.sh
├── docker-compose.yml
├── .gitignore
├── README.md
└── glossary.md

```
# Ingestion Service

## Descrição

O Serviço de Ingestão recebe transações financeiras através do API Gateway, valida os dados e os publica no sistema de mensageria para processamento posterior.

## Tecnologias Utilizadas

- Java 11
- Spring Boot
- Maven

## Como Executar

### Pré-requisitos

- Java 11 instalado
- Maven instalado
- Docker (opcional, para executar com Docker)

### Passos

1. Clonar o repositório:

   ```bash
   git clone https://github.com/empresa/anomaly-detection-system.git

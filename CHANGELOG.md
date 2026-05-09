# Changelog - Abstergo AWS Cost Savings

Todas as alterações notáveis neste projeto serão documentadas neste arquivo.

## [1.0.0] - 2026-05-08

### Adicionado
- Estrutura inicial do repositório focada em otimização de custos para a Abstergo Industries.
- Relatório técnico completo em Markdown (`docs/relatorio_aws.md`) detalhando a implementação estratégica.
- Caso de uso para **AWS CloudFormation** como ferramenta de Infraestrutura como Código (IaC) para automação de ambientes.
- Caso de uso para **AWS Fargate** visando a eliminação de ociosidade de servidores através de computação serverless.
- Caso de uso para **Amazon S3 Intelligent-Tiering** para gestão automática de custos de armazenamento de dados clínicos.
- Diagrama de arquitetura lógica (`docs/modelo_logico_farm_aws.PNG`) representando o fluxo da solução.
- Arquivo `README.md` com a documentação do projeto e guia de navegação.

### Corrigido
- Ajuste no relatório para substituição do Amazon CloudFront pelo **AWS CloudFormation**, alinhando a estratégia para foco em automação e padronização.
- Correção de conflitos de histórico no Git (reconciliation de branches divergentes) durante o push inicial.
- Atualização do arquivo de imagem do diagrama de arquitetura para refletir os serviços selecionados.

---
*Este changelog segue os princípios de [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/).*
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 08/05/2026

Empresa: Abstergo Industries

Responsável: <strong>Paulo Carlos</strong>

Introdução
Este relatório apresenta o processo de seleção e sugestão de implementação de ferramentas na empresa Abstergo Industries, realizado por Paulo Carlos. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar a diminuição de custos imediatos e otimização de infraestrutura.

Descrição do Projeto
O projeto de implementação estratégica foi dividido em 3 etapas, focando em serviços gerenciados que reduzem o custo operacional e de transferência. A seguir, as etapas descritas:

<strong>Etapa 1:</strong>
Ferramenta: AWS CloudFormation

Foco: Infraestrutura como Código (IaC)

Caso de uso: Utilizado para automatizar o provisionamento dos recursos da farmacêutica de forma padronizada e replicável. Através de templates, o CloudFormation garante que toda a infraestrutura seja criada sem erros manuais, permitindo a rápida destruição ou recriação de ambientes para testes de novas fórmulas, otimizando custos ao evitar recursos esquecidos ativos.

<strong>Etapa 2:</strong>
Ferramenta: AWS Fargate

Foco: Computação Serverless para Containers

Caso de uso: Execução de APIs de inventário e consulta. Ao migrar para o Fargate, a empresa elimina o custo de instâncias EC2 ligadas sem necessidade, pagando apenas pelo processamento utilizado durante as janelas de operação.

<strong>Etapa 3:</strong>
Ferramenta: AWS S3 Intelligent-Tiering

Foco: Otimização automática de custo de storage

Caso de uso: Armazenamento de dados históricos de ensaios clínicos. O serviço move automaticamente arquivos pouco acessados para camadas de menor custo, garantindo economia sem necessidade de intervenção manual da equipe de TI.

Conclusão
A implementação das ferramentas na empresa Abstergo Industries tem como esperado a redução da fatura mensal de nuvem e o aumento da eficiência no gerenciamento de recursos. A transição para serviços gerenciados e serverless permitirá que a equipe foque no desenvolvimento de novos produtos, deixando a gestão da infraestrutura para a AWS. Recomenda-se a continuidade da utilização das ferramentas sugeridas para garantir a produtividade e escalabilidade da empresa.

<strong>Anexos:</strong>
Diagrama lógico de arquitetura sugerida.

Assinatura do Responsável pelo Projeto: <strong>Paulo Carlos</strong>

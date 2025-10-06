
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 06/10/2025

Empresa: Abstergo Industries

Responsável: Caio Bukvar Fernandes

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries. O objetivo do projeto foi *elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos*.

## Descrição do Projeto
O projeto de implementação de ferramentas foi *dividido em 03 etapas, cada uma com seus objetivos específicos*. A seguir, serão descritas as etapas do projeto:

### Etapa 01:
- **Amazon EC2 Auto Scaling**
- Otimização automática de capacidade computacional
- Implementação de dimensionamento automático dos servidores baseado na demanda real. O sistema ajusta automaticamente o número de instâncias EC2 ativas conforme o volume de acessos e processamento, eliminando desperdício com servidores ociosos em horários de baixa demanda (noites, finais de semana). Redução estimada de 30-40% nos custos de infraestrutura computacional nos primeiros 3 meses.

### Etapa 02:
- **Amazon S3 com Intelligent-Tiering**
- Armazenamento inteligente e econômico de dados
- Migração dos arquivos e backups da empresa para o S3 com classificação automática de dados. Arquivos frequentemente acessados permanecem em camadas de acesso rápido, enquanto dados raramente utilizados são movidos automaticamente para camadas mais econômicas (S3 Glacier, por exemplo). Substituição de servidores de arquivos físicos, eliminando custos com hardware, manutenção e energia elétrica.

### Etapa 03:
- **AWS Cost Explorer com AWS Budgets**
- Monitoramento e controle de gastos em nuvem
- Implementação de sistema de análise e alertas de custos AWS. Configuração de orçamentos departamentais com notificações automáticas quando limites são atingidos. Identificação de recursos subutilizados, análise de tendências de gastos e geração de relatórios mensais para tomada de decisão. Permite controle proativo dos custos e identificação de oportunidades adicionais de economia.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a **redução de 35-50% nos custos de infraestrutura de TI** através da otimização inteligente de recursos. O **Amazon EC2 Auto Scaling** eliminará desperdícios com servidores ociosos, o **Amazon S3 com Intelligent-Tiering** reduzirá custos de armazenamento e hardware, e o **AWS Cost Explorer com AWS Budgets** garantirá controle proativo dos gastos.

Esses benefícios combinados aumentarão significativamente a eficiência e produtividade da empresa, proporcionando **maior escalabilidade automática, disponibilidade dos sistemas e visibilidade sobre custos**, liberando recursos financeiros para investimentos estratégicos.

Recomenda-se a continuidade da utilização das ferramentas implementadas, o monitoramento mensal através do Cost Explorer, e a busca por novas tecnologias AWS que possam melhorar ainda mais os processos da empresa.


## Assinatura do Responsável pelo Projeto:

Caio Bukvar Fernandes

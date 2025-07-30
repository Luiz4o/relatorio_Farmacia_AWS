Este é um relatório demonstrando 3 serviçõs da AWS que poderiam ser implementados pensando em otimização de custos em um local onde não há uso de Cloud em geral.

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOES AWS

Data : 30/07/2025
Empresa : Abstergo Insdustries
Responsável : Luiz Henrique

## Introdução
 Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Insdustries, realizado por Luiz Henrique. 
 O objetivo do projeto é elencar 3 serviços AWS, com a finalidade de redução de custos imediatos.

 ## Descrição do Projeto
  O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: Otimização e Visibilidade de Custos
   
 - Nome da ferramenta: AWS Cost Explorer e AWS Budgets

 - Foco da ferramenta: Visibilidade e Controle de Custos

 - Descrição de caso de uso:
 O primeiro passo para a otimização de custos é entender para onde os recursos estão sendo direcionados. Atualmente, com uma infraestrutura local, muitos custos são fixos e difíceis de rastrear em relação ao uso real. Ao iniciar a jornada para a nuvem, mesmo que de forma gradual, o AWS Cost Explorer fornecerá uma visão detalhada e gráfica dos gastos com os serviços da AWS. Será possível identificar quais aplicações ou processos consomem mais recursos e onde estão as principais oportunidades de economia.

Complementarmente, com o AWS Budgets, a Abstergo Industries poderá definir orçamentos personalizados para os custos e o uso dos serviços. Alertas automáticos serão configurados para notificar a equipe responsável sempre que os gastos se aproximarem ou excederem os limites predefinidos. Essa abordagem proativa evita surpresas na fatura e garante que a migração para a nuvem se mantenha dentro do planejado, gerando uma economia imediata através da gestão consciente dos recursos desde o primeiro dia. A implementação desta etapa não requer uma migração completa, podendo ser iniciada com cargas de trabalho pequenas, como um ambiente de desenvolvimento ou um backup secundário, já trazendo o benefício da previsibilidade financeira.

 Etapa 2: Armazenamento Escalável e Seguro de Dados
 
 - Nome da ferramenta: Amazon S3 (Simple Storage Service)

 - Foco da ferramenta: Redução de Custos com Armazenamento e Aumento da Durabilidade dos Dados

 - Descrição de caso de uso:
 Com a visibilidade de custos estabelecida, a próxima etapa foca em um dos maiores custos de infraestrutura: o armazenamento de dados. A Abstergo Industries, por atuar como farmácia e distribuidora, lida com um volume crescente de dados, como registros de vendas, informações de clientes, dados de inventário e documentos fiscais. Manter e garantir a segurança desses dados em servidores locais gera um custo elevado com hardware, energia e manutenção.

 O Amazon S3 oferece uma solução de armazenamento de objetos altamente durável, escalável e de baixo custo. Nesta fase, a empresa poderá começar a mover dados de backup, arquivos e documentos para o S3. Por exemplo, os backups diários do sistema de gestão da farmácia, que hoje ocupam um espaço significativo em discos locais, podem ser automatizados para serem enviados ao S3. Isso não apenas libera capacidade de armazenamento local, mas também aumenta a segurança e a durabilidade desses backups, que estarão replicados em múltiplas localizações físicas.

 A economia é gerada pela substituição de investimentos caros em hardware de armazenamento por um modelo de pagamento conforme o uso, onde a empresa paga apenas pelo espaço que realmente utiliza. Além disso, o S3 possui diferentes classes de armazenamento, permitindo mover dados acessados com menos frequência para camadas de custo ainda menor, otimizando continuamente os gastos. Esta etapa garante que dados críticos, como o histórico de pedidos online, nunca sejam perdidos por falhas de hardware local.

 Etapa 3: Alta Disponibilidade para Aplicações Críticas
 - Nome da ferramenta: Amazon EC2 (Elastic Compute Cloud) com Auto Scaling

 - Foco da ferramenta: Garantir a Disponibilidade do Sistema e Otimizar Custos de Computação

 - Descrição de caso de uso:
 Após otimizar o armazenamento, o foco se volta para a disponibilidade das aplicações que sustentam as operações da farmácia e da distribuidora, como o sistema de ponto de venda (PDV) e a plataforma de e-commerce. Quedas nesses sistemas resultam em perda de vendas e danos à reputação da empresa. Atualmente, a capacidade computacional é limitada aos servidores físicos existentes.

 Com o Amazon EC2, a Abstergo Industries pode começar a migrar suas aplicações para instâncias de computação na nuvem. O grande diferencial desta etapa é o uso do Auto Scaling. Essa funcionalidade ajusta automaticamente a quantidade de instâncias EC2 de acordo com a demanda. Por exemplo, durante os horários de pico de vendas na farmácia ou em períodos de grande volume de pedidos online, o Auto Scaling pode adicionar mais instâncias para garantir que o sistema permaneça rápido e responsivo. Quando a demanda diminui, ele desliga as instâncias desnecessárias, e a empresa deixa de pagar por elas.

 Essa elasticidade garante dois benefícios principais:

 - Alta Disponibilidade: O sistema nunca ficará sobrecarregado, evitando quedas e lentidão que poderiam impedir os clientes de finalizar uma compra na loja ou online.

 - Otimização de Custos: A empresa paga apenas pela capacidade computacional que realmente utiliza, eliminando o desperdício de manter servidores superdimensionados para picos de demanda que ocorrem apenas esporadicamente.

## Conclusão

A implementação destas etapas consolida o ciclo de otimização, garantindo que a Abstergo Industries tenha uma infraestrutura robusta, resiliente e com custos controlados, pronta para suportar o crescimento do negócio.

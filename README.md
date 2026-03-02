# Relatório de Implementação de Serviços AWS

**Data:** 01 de março de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Vitória Correia  

---

##  Introdução
Este relatório apresenta o processo de implementação de ferramentas e serviços em nuvem na empresa **Abstergo Industries**, realizado por **[Seu Nome]**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos e otimizar a infraestrutura existente, garantindo a saúde financeira e a escalabilidade do ambiente.

##  Descrição do Projeto
O projeto de otimização e implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos voltados para a eficiência operacional. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Otimização Computacional
- **Nome da ferramenta:** Amazon EC2 (Spot Instances e Compute Savings Plans)
- **Foco da ferramenta:** Otimização e redução de custos computacionais.
- **Descrição de caso de uso:** Substituição de instâncias provisionadas sob demanda por instâncias *Spot* em ambientes de desenvolvimento, testes e cargas de trabalho tolerantes a falhas. Para os servidores de produção com uso contínuo, foi aplicado o *Compute Savings Plans*, garantindo descontos significativos em troca do compromisso de uso, reduzindo os custos de computação em até 70%.

### Etapa 2: Armazenamento Inteligente
- **Nome da ferramenta:** Amazon S3 (Intelligent-Tiering)
- **Foco da ferramenta:** Otimização inteligente de custos de armazenamento de dados.
- **Descrição de caso de uso:** Habilitação da classe de armazenamento *S3 Intelligent-Tiering* para os *buckets* de dados da empresa. A ferramenta passou a monitorar os padrões de acesso e a mover automaticamente os arquivos não acessados para camadas de armazenamento mais baratas (*Infrequent Access* ou *Archive*), cortando custos de armazenamento ocioso sem afetar a performance da aplicação.

### Etapa 3: Governança e Monitoramento
- **Nome da ferramenta:** AWS Budgets e AWS Cost Explorer
- **Foco da ferramenta:** Governança financeira, monitoramento e criação de alertas.
- **Descrição de caso de uso:** Configuração de painéis no *Cost Explorer* para identificar os serviços que mais geram gastos diários. Em conjunto, o *AWS Budgets* foi configurado para enviar alertas automáticos por e-mail e SMS aos administradores caso os custos reais ou previstos ultrapassem o limite do orçamento mensal estipulado, evitando surpresas na fatura.

##  Conclusão
A implementação dessas ferramentas na empresa **Abstergo Industries** tem como esperado a **redução drástica do desperdício de recursos em nuvem, maior previsibilidade financeira e a otimização da infraestrutura**, o que aumentará a eficiência e a produtividade da empresa, liberando capital para novos investimentos em tecnologia. Recomenda-se a continuidade do monitoramento contínuo das métricas geradas e a busca por novas arquiteturas (como a adoção de *serverless*) que possam melhorar ainda mais os processos da empresa a longo prazo.

##  Anexos
*  `Planilha_Estimativa_de_Economia_AWS_Pricing_Calculator.xlsx`
*  `Relatorio_de_Utilizacao_EC2_CloudWatch.pdf`
*  `Diagrama_de_Arquitetura_Otimizada.png`
(exemplos)
---

**Assinatura do Responsável pelo Projeto:**

> Vitória Correia

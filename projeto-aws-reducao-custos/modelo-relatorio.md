# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 15/01/2026  
Empresa: Abstergo Industries  
Responsável: Iann Oliveira  

## Introdução

Este relatório apresenta o processo de implementação de serviços AWS na empresa Abstergo Industries, realizado por Iann Oliveira. O objetivo do projeto foi selecionar e aplicar três serviços da AWS com foco na redução imediata de custos operacionais, mantendo a eficiência, a segurança e a escalabilidade da infraestrutura em nuvem.

## Descrição do Projeto

O projeto de implementação foi dividido em três etapas, cada uma abordando um serviço específico da AWS, conforme descrito a seguir:

### Etapa 1: Amazon EC2 com Auto Scaling

- **Nome da ferramenta:** Amazon EC2 + Auto Scaling  
- **Foco da ferramenta:** Redução de custos com computação sob demanda  
- **Descrição do caso de uso:**  
Foi implementado o Auto Scaling para ajustar automaticamente a quantidade de instâncias EC2 conforme a demanda do sistema. Dessa forma, a empresa evita custos com servidores ociosos em períodos de baixa utilização, pagando apenas pelos recursos necessários.

---

### Etapa 2: Amazon S3 com Storage Classes Inteligentes

- **Nome da ferramenta:** Amazon S3 (Intelligent-Tiering)  
- **Foco da ferramenta:** Otimização de custos de armazenamento  
- **Descrição do caso de uso:**  
Os dados armazenados no Amazon S3 passaram a utilizar classes de armazenamento inteligentes, permitindo que arquivos pouco acessados sejam movidos automaticamente para camadas mais baratas. Isso reduziu custos sem impactar a disponibilidade ou a segurança das informações.

---

### Etapa 3: AWS Cost Explorer e Budgets

- **Nome da ferramenta:** AWS Cost Explorer + AWS Budgets  
- **Foco da ferramenta:** Monitoramento e controle financeiro  
- **Descrição do caso de uso:**  
Foi configurado o AWS Cost Explorer para análise detalhada dos gastos, juntamente com o AWS Budgets para criação de alertas financeiros. Essa abordagem permite identificar desperdícios, prever custos futuros e agir rapidamente em caso de desvios orçamentários.

---

## Conclusão

A implementação dos serviços AWS na empresa Abstergo Industries tem como resultado esperado a redução significativa de custos operacionais, maior controle financeiro e melhor aproveitamento dos recursos em nuvem. As soluções adotadas aumentam a eficiência da infraestrutura, mantendo escalabilidade e confiabilidade. Recomenda-se a continuidade do uso das ferramentas implementadas e a avaliação constante de novas soluções AWS para otimização contínua.

## Anexos

- Documentação oficial dos serviços AWS  
- Prints do AWS Cost Explorer  
- Diagrama simples da arquitetura utilizada  

---

Assinatura do Responsável pelo Projeto:

**Iann Oliveira**

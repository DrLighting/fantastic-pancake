# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 27/07/2025  
Empresa: Abstergo Industries  
Responsável: Daniel R. Nakano  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Daniel R. Nakano. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de promover redução de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1:**  
- **Amazon EC2 Auto Scaling**  
- Redução de custo com servidores, ajustando recursos conforme a demanda.  
- Em vez de manter servidores ativos 24/7, é possível configurar o Auto Scaling para aumentar ou reduzir automaticamente o número de instâncias EC2 com base no uso real (como aumento de pedidos ou horários de pico de vendas). Isso evita pagar por capacidade ociosa.

**Etapa 2:**  
- **Amazon S3**  
- Armazenamento econômico e seguro de documentos, dados logísticos e arquivos de clientes ou parceiros.  
- Armazene faturas, relatórios, etiquetas, bulas, documentos regulatórios e arquivos de integração com parceiros no Amazon S3.  
Ao usar a classe "Intelligent-Tiering", o próprio S3 move os arquivos automaticamente entre camadas mais baratas com base na frequência de acesso — sem necessidade de ação manual, gerando economia imediata.

**Etapa 3:**  
- **AWS Lambda**  
- Execução de código sob demanda sem necessidade de servidores, com cobrança apenas pelo uso.  
- Você pode usar o AWS Lambda para processar pedidos, atualizar estoques ou enviar notificações de entrega sem manter servidores ligados o tempo todo. Por exemplo, ao receber um pedido de uma empresa parceira, um evento pode disparar uma função Lambda que atualiza seu sistema, envia e-mails ou faz integração com outros sistemas.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries visa permitir o pagamento por servidores com base no uso real, evitando custos em momentos ociosos; armazenamento inteligente que move automaticamente os arquivos para camadas mais baratas com base nos acessos; e execução de código sob demanda com cobrança apenas por uso, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
Gráfico com base nos benefícios típicos observados por empresas que adotam serviços AWS gerenciados e com escalabilidade automática para reduzir custos operacionais imediatos:  
[Link para o gráfico](https://drive.google.com/file/d/1WDYvebQ0D7kr3qu38I1Of6upYpQEjVdR/view?usp=drive_link)

**Assinatura do responsável pelo projeto:**  
Daniel Ryouhei Nakano


















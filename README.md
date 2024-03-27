RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 26/03/2024 Empresa: Abstergo Industries Responsável: Kelvin Felipe Motter

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Kelvin Felipe Motter. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

AWS S3 Intelligent-Tiering
Redução de custos com armazenamento.
O S3 Intelligent-Tiering monitora os padrões de acesso e move automaticamente os objetos que não foram acessados para níveis de acesso de custo inferior.
Etapa 2:

EC2 Auto Scaling
Permite adicionar ou remover automaticamente instâncias do EC2 de acordo com as condições definidas.
Com auto scaling em momentos de menos acessos e requisições a aplicação poderemos manter o minimo possível de capacidade computacional assim diminuindo os custos. Se possível podemos até configurar o Instance Scheduler para interromper a EC2 nos horários que não tenha uso. Caso a aplicação tenha uso somente em horário comercial poderíamos ter ganhos significativos, exemplo: 10 horas/dia * 22 dias = 220 horas. (Redução de 69% aproximadamente).
Etapa 2:

AWS Trusted Advisor
Ajuda a otimizar custos, aumentar o desempenho, melhorar a segurança e a resiliência e operar em grande escala na nuvem.
O serviço fará algumas verificações e recomendará possíveis melhorias na otimização de custo, desempenho, segurança, etc. Podemos começar pelas ações recomendadas, que inicialmente seriam aquelas com maior impacto em desperdício e consequentemente maior custo.
Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado reduzir os custos com armazenamento, escalonar instâncias EC2 e monitorar o uso das ferramentas, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Anexos
Documentação AWS S3 intelligent-Tiering: https://aws.amazon.com/pt/s3/storage-classes/intelligent-tiering/ Documentação AWS EC2 Auto Scaling: https://aws.amazon.com/pt/autoscaling/ Documentação AWS Trusted Advisor: https://aws.amazon.com/pt/premiumsupport/technology/trusted-advisor/

Assinatura do Responsável pelo Projeto:

Kelvin Felipe Motter

# AWS-Expert

# DIA 1 - Treinamento

# Provedores - CSP

**1. AWS Amazon Web Services** 33%: Lidernça nas Plataformas em nuvens

**2. Microsoft Azure** 18%: 

**3. Google Cloud Platform - GCP** 9%


Outros...

**4. Alibaba Cloud**

**5. Oracle Cloud**

**6. IBM Cloud**

# What is Cloud (O que é Cloud)?

Rodar nossos serviços ou produtos em algum lugar e oferecer com plataforma para alguem, que seja possivel escalar de uma forma legal, ter uma certa elasticidade porem alguns muita dúvida sobre esse conceito, existe algumas caracteristica que considera ser cloud computing ex: Amazon AWS o EC2 (Maquina Virtual). E outras empresa como microsoft co o Azure, e a Google Cloud.

Computação em nuvem é o forncecimento de serviçs de computação, incluindo servidores, armazenamento, banco de dados, rede, software, analise e inteligencia, pela internet para oferecer recursos felxeiveis e economia de escala.

Oferecer um datacenter e pagar conforme o uso...

**E a contratacao?**

Normalmente se paga apenas pelos serviços de nuvem em uso, ajudando a reduzir os custos operacionais conforme as necessidades da empresa.

# Characteristics and Advantages

**1.Agility (Agilidade):** Os times sempre foram ageis com ferramentas, Time Dev: Entregar codigo, porem com tempo foi exigido mais velocidade na entrega de produto mais agil e melhor (Qualidade e Entrega), speedy to markenting e etc.... Time Operação: Cuida da parte fisica, com o tempo o conceito de DevOps comecou a integrar o time de operacoes com o Cloud, agilidade em entrega de maquina EC2 com cloud Público. Principal agilidade do Cloud está ligado com o time DevOps, o Cloud te dá agilidade, você não precisa lidar com aspecto fisico infraestrtura (Datacenter local - custo alto).

**2.Maintenace:** Manter a Manutenção do Ambiente cloud, a vantagem redução de custos dependo do ambiente do projeto.

**3.Reliability:** Cloud aumenta a confiabilidade por que agora existe especialista fazendo a manutenção.

**4.Security:** Importante e preocupar!!!. Dentro da AWS existe muitas ferramentas para prever falhas fisicas, assim voce pode focar em outras falhas mais especifica. Impedir vazamento de informação. A segurança aumentou nas provas em certificações. Alguns ambiente a segurança é primordial. Chamada de API, 

**5.Perfomance:** É possivel ter um nivel de performance porem tem um custo desse uso sobe demanda, porem voce tem as ultimas tecnologias do mercado dentro do cloud, porem precisa ser pago para usar isso. Cloud não é para todo mundo.

**6.Scalability:** É uma vantagem do cloud escalar de uma forma simples, se sua aplicação não foi desenvolvida para rodar levando em conta os pontos anterior a sua aplicação não é para cloud e voce pode ter problemas. É possivel escalar seu serviço sobre demanda (Ex: Serviço para rodar durante Black Friday), e pagar apenas pelos recursos que voce usar, exemplo se voce precisar 2,3 ,4, 5 ou mais servidores é muito rápido dentro do cloud. Porem sua aplicação precisa ter se sido desenhada (desenvolvida) para esse tipo de ambiente.

Exemplo 1: Uma tarefa de Agente de Backup - Agendado!. Como que sua aplicação vai entender que voce tem 3, 4 ou 5 servidor disparando tarefas ao mesmo tempo.

Exemplo 2: Elastico ou Infinito? O Elastico se esticar muito ele para e se continuar esticando ele quebra!

A elasticidade tem um limite, algumas vezes poder ser um limite por um 'software limite' (Ex: EC2 voce pode rodar 30 durante um mes) se voce precisar de mais voce solicita (ticket) para a AWS e eles pode aumentar isso para sua empresa, isso é controle de segurança, que poder ser alterado.

Exemplo 3: Mas existe um outro limite que é o 'Hardware Limite' que isso não pode ser aumentado ou alterado para sua empresa, não se pode mexer, quando chegar no limite do datacenter da AWS não pode ser alterado. O serviço nem sempre vai estar disponivel para se ele atingir o limite de hardware.

Ex: Voce vai em uma loja e não encontra um produto. Não tem que ser feito.

Por isso é importante o planejamento. 

**7.Cost and Elasticity:** Gerenciar melhor isso no cloud pagar pelo que uso sobre demanda. So pago se a maquina estiver ativa.

Muitos clientes por não sabe usar o cloud e não entender a sua necessidade, achando que o Cloud é mais barato e ele não é mais barato.

Single Intancias. (Monolito) .

Se voce fizer direito de acordo com cloud.

# The National Intitute of Standard and Technology

**.On demanda seft-service:** 

Voce provisicona quando precisa e usa quando precisa isso é uma vantagen.

**.Broad network access:** 

Acesso a uma rede distribuida de cosias.

**.Resource pooling:** 

Pooling de recursos que voce usa, quando precisar, existe um catalogo de recursos.

**.Rapid elasticity:** 

Velocidade rapida para crescer é verdade é possivel.

**.Measured service:** 

O serviço precisa ser medido para saber o estado de saúde, saber onde houve falhas dos serviços eu preciso coletar metricas e ter opçõess de ferramentas endpoint para obter essas informações.

# Service Models

Cloud não é so publicar uma maquina na Internet (Cloud) existe varios modelos vendido no mercado:

**IaaS (Infraestrtura como Serviço)**: Quando saiu o conceito de cloud, EC2 (AWS Amazon) é um exemplo, usar uma computador, banco de dados sendo disponibilizada como serviço.

A categora mais básica de serviços de computacao em nuvem. Com o IaaS, voce aluga a infraestrtua de TI, (que inclui servidores e maquinas virtuais, armazenamento (VMs), rede e sistemas operacionais), de um provedor de nuvem, com pagamento conforme o uso.

**PaaS (Plataforma como serviço)**: A nuvem configura para voce (Servidor, Rede e Banco de Dados) não precisando se envolver com a Infraestrutura.

Oferece serviços de computacao em nuvem sob demanda para desenvolvimento, teste e gerenciamento de aplicativos de software. 
Cuida de toda a configuracao e gerencia da infraestrutura dos servidores , armazenamento, rede e bancos de dados necessarios para desenvolvimento.

**SaaS (Software como serviço)**: Voce pode usar um produto sem precisar se preocupar com a Infraestrutura alguns exemplos (Google Drive, Office 365, Hotmail e etc...). 

É um metodo para distribuição de aplicativos de software pela Internet sob demanda normalmente baseado em assinaturas. O SaaS permite que os usuarios conectem o aplicativo pela internet, normalmente com um navegador da Web em seu telefone,tablet ou PC.

**FaaS (Funções como Serviço**): É adeia de um produto mais granular, fazer um micro serviço como função, exemplo preciso enviar um e-mail de forma automatica atraves de um simples script (um codigo). 

# Deployment models

Esse são ass principais que todas especialista de cloud precisa conhecer

**1. Private Cloud**: Cloud Privado implantado dentro da empresa (Open Stack, VMware, Zen) é o cloud que é seu não permite acesso de outras pessoas e outras empresas a seu cloud. On-Premise (VMs)

**2. Public Cloud**: Qualquer um pode usar, voce contrata e usa (AWS, Google Cloud, Azure). Isso não significa que elas vão ter acesso a sua infraestrtura.

**3. Hybrid Cloud**: On-Premise´e Public dentro da sua empresa, uma parte na AWS e outra dentro de sua empresa.


**Multicloud**: Roda todos seus serviços em todos os Clouds (AWS, Google Cloud, Azure), existe varias confusões sobre o uso do termo, Business Continue porem não é uma solução muito utilizado, alguns usam com Desaster Recovery. Não chega a ser considerado Multicloud pois não está enviando requisições para os dois ao mesmo tempo.

**Community**: Empresa se reuniem para usar o mesmo Cloud usando um pouco das duas On-Premise´e Public e convidam outras empresas a utilizar a mesma infraestrutura.

# DIA 2 - Treinamento

**Foundation**: Fundação para gerenciar suas contas dentro da AWS para administrar seus recursos na nuvem.

**Root Accounts, part 1**: É a primeira conta que criamos na AWS a nossa conta principal e por ela que adicionamos nosso cartão de credito para que a AWS cobre os serviços usado na nunvem.

**Root Accounts, part 2**: E atraves dela criamos as sub-accounts para dividir meu ambiente da AWS, e gerenciamos outras contas, quando dividimos nosso ambiente com sub-accounts fica mais organizado, e mais seguro usar sempre as sub-accounts para acessar nosso ambiente, e deixar a Root Accounts apenas para fazer os pagamentos.

**Organization Unit (OU)**: As Organization Unit (OU) serve para organizar e criar politicas e criars regras organizacional. (Dev, Producao e etc...), assim podemos limitar usos dos recursos (Por Zonas, Uso de ECS e etc...) atraves de politicas. Poucas pessoas usam e isso é uma boa prática para segurança.
.
**AWS Accounts, part 1:** Se tiver sub-accounts então será necessário usar uma 'Organization Unit (OU)'. Caracterias de Root Account voce precisa de um e-mail único.

**AWS Accounts, part 2:** Necessário ter uma conta (Nome e e-mail), use o email do time (ex: financeiro@empresa.com). Crie um e-mail valido que uma pessoas vai ler. Cada conta vai ter um gerenciador de identidade.  Os resources (são os recursos que voce usa na nuvem para cada conta).

**Create Account, parte 1**: Será necessário um cartão de crédito.

**Free Tier**: 

750hs de EC2 - T2.MICRO
S3 - 5gb
etc...

**Creating Account, part 3**: ...

**Creating Account, part 4**: criou uma máquina EC2

**My Security Credentials**: Ativar o MFA na conta Root.
** As ORganizatiobs:* li


# Live ao Vivo

## Conceito da Nuvem: Visão geral

CloudFormation: Implante programatcamente a infraestrutura repetivel...

Eastic Beanstalk: Implante sua aplicação da forma mais simples possivel (Php, Node etc...)

Direct Connect: Forneça uma conexão de rede dedicada a paerti de seu local á AWS...

Route 53: Execute Serviço DNS...

Lambda: Execute o codigo sem gerenciar os servidores.

CloudFront CDN: Entregue seu conteudo por uma rede com alta escala globalmente disposnivel.

# Orientações:

- No final tera um quiz 85% de desconto para concorrer ao voucher da AWS.

- https://www.aws.training/Certification : Processo de sua certificação, será associado um ID da sua conta voce faz uma marcação (Online), 'Register for an exam', tera acesso ao Painel de Certificações. 

## Dominio 2: Descrição do Exame

2.1 Defina o modelo de responsabilidade shared da AWS
2.2 Defina os conceitos de segurança e conformidade da nuvem AWS
2.3 Identifique os recursos de gerenciamento de acesso da AWS
2.4 


# Segurança e nossa maior prioridade

- Projetado para segurança:
- Monitora constantemente: 
- Altamente automatizado:
- Altamente disponivel: Mesmo que tenha uma sobrecarga de recursos...
- Altamente em conformidade: Regulamentações e Certificações 

# Modelo de responsabilidade compartilhada da AWS

Cliente: Na nuvem
- Dados de cliente
- Plataforma, aplicações, Identify and Acess Management: Acesso, permissionamento..
- Confguraçẽs de sistema operacionais, rede e firewall: Security Group 
- Criptografia de dados no lado Cliente
- Criptografia de dados no lCriptografia de dados no lado clienteado Servidor
- Proteção do trafefo de rede

AWS: Da Nuvem
- Software
- Computação, Armazenamento, Banco de Dados, Rede
- Hadware, Infraestrutura global da AWS
- Regiões, Zonas de disponibilidade, Locais de borda (Edge Locations)


# AWS Identfy and Acess Management (IAM)

IAM Permite permite gerenciar o aceso a serviços e recursos AWS: Usuarios, Role, Grupo de Usuarios, Politica do IAM, Autenticação multifator (MFA).

Usuarios precisa acessar um determinado ambiente precisa ter um conjunto de permissões, **mas e sua equipe grupo de usario precisa ter acesso ao mesmo conteudo?** Existe um recurso chamado 'Grupo' onde voce adicionar todos esses usuarios herda as permissões. As preciso ter um acesso temporario para um determinado ambiente ou a um serviços para realizar ações porem não quero criar um usuario fixo? Voce pode criar uma 'Role' para um pessoa acessar as permissão dessa 'role e acessar temporariamente.

Politica: É um documento que esta associado a um usuario, grupo ou role. O que não estiver dentro da politica não esta autorizado a acessar. Quando o DENY explicito substituir qualquerregra ALLOW.

# Autenticação: quem é voce?

AWS CLI, SDKs da AWS, AWS Managemete Console: IAM (Usuarios, Grupo).

login (usuario e senha)...

# Autorização: O que pode fazer?

Usuarios, grupo ou role do IAM --> (Politica IAM) Acesso Total, Somente Leitura,  --> AWS CLI, Bucket do Amazon S3

# O que é o Amazon Inspector?

Avaliação de Segurança automazada como um serviço

- Avalia vulnerabilidades das aplicações

- Produz uma lista detalhada de descobertas de segurança
 
- Utiliza práticas recomendadas de segurança

Dica: Usamos esse recursos para saber se meu ambiente está exposto de alguma maneira ou vulneravel, isso permite criar um agrupamento de recursos e formar uma analise para gerar relatorios e decidir de acordo com o resultado que medidas iremos tomar. É como se uma mae orientar um filho sobre os obstaculos que vamos encontrar.

# O que é DDos?

DDos -> Aplicação < x Usuario Legitimo

Aplicação sofrendo um ataque distribuido visando a indisponibilidade do meu ambiente, existe ataques diferente de acordo com o modelo OSI, com o objetivo de derrubar um serviço, um servidor e etc...

A AWS tem alguns serviço para proteger 

# O que é o AWS Shilde?

- Um serviço gerenciado de Protecao de DDosS
- Detecção sempre ativa e mitgações
- Integracao e implatacao continuas
- Proteção economica e customizavel

Standard ativo em todas contas por padrão.

Advanced protege contra ataquer mais comus e mais na cama app

# Dominio 3 Tecnologia









































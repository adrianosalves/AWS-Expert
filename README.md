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

Responabilidade sua: A segurança e configuração e sua....

AWS: Da Nuvem
- Software
- Computação, Armazenamento, Banco de Dados, Rede
- Hadware, Infraestrutura global da AWS
- Regiões, Zonas de disponibilidade, Locais de borda (Edge Locations)

Responabilidade sua:

# AWS Identfy and Acess Management (IAM)

IAM Permite permite gerenciar o aceso a serviços e recursos AWS: Usuarios, Role, Grupo de Usuarios, Politica do IAM, Autenticação multifator (MFA).

Usuarios precisa acessar um determinado ambiente precisa ter um conjunto de permissões, **mas e sua equipe grupo de usario precisa ter acesso ao mesmo conteudo?** Existe um recurso chamado 'Grupo' onde voce adicionar todos esses usuarios herda as permissões. As preciso ter um acesso temporario para um determinado ambiente ou a um serviços para realizar ações porem não quero criar um usuario fixo? Voce pode criar uma 'Role' para um pessoa acessar as permissão dessa 'role e acessar temporariamente.

Politica: É um documento que esta associado a um usuario, grupo ou role. O que não estiver dentro da politica não esta autorizado a acessar. Quando o DENY explicito substituir qualquerregra ALLOW.

Role: Regra temporaria desde 15 min ou mais, não sendo necessário criar um usuario fixo, mais uma politica temporaria e atribui para outro usuario.

Lambda: Executar um codigo sem um servidor.

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

Advanced protege contra ataquer mais comus e mais na camada da aplicação.

# Dominio 3: Tecnologia

Perguntas?

Diferenca entre Security Group (Firewall nivel de placa de rede) e Network Next Firewall Lista (Nivel de Sub-net).

# Regiões

Um area geografica de nosso planeta isola com um conjunto de zona de disponibilidade (2 ou mais zonas de disponibilidade). 

Cada região:

- É completamente independente.

- Usa a infraestrtura de rede AWS

- Tem duas ou mais Zonas de disponibilidade

# Zonas de disponibilidade

As são Organizalidade por:

- Data Centers e uma Região (um ou mais em cada AZ)

- Projetadas para isolamento de falhas

- Interconectadas usando links privados de alta disponibilidade

- Usadas para alcançar alta disponibilidade

Dicas: 

# Locais de Bordas (Edge Location)

Locais de borda

- Executadas nas principais cidades do mundo.
- Suporte a serviços da AWS como Route S3 e CloudFront.

# O que é o Amazon EC2?

Poder computacional na nuvem um servidor para minha apliação, banco de dados ou web e etc... Podemos pensar em usar o EC2.

No EC2 podemos escolher o recurso que queremos provisionar.

- Usar a capacidade comutacional segura e dimensionavel. (Memoria, Processador e HD)
- Inicialize as instancias em minutos. (De acordo com usa necessidades, e escalar horizontal ou verticalmente).
- Pague apenas pelo o que utilizar.

# Amazon Elastic Block Store (EBS)

- Armazenamento de bloco persistente para instancias
- Protegendo por replicação
- Diferentes tios de unidade
- Aumentar ou diminuir em minutos
- Pague apenas pela provisão
- Funcionalidade de snapshot
- Critptografia

Nuvem AWS

EC2  <-> EC2, EC2 EC2 (Volumes de Amazon EBS): Podemos ter mais de um volume associado a uma instancia EC2. 

Solid State Driver (SSD)
- Volumes de SSD de IOPS provisionado (io1, io2): Maior performance, compare com um carro de formula 1, porem apenas 1 piloto no carro
- Volumes de SSD de uso geral (gp2, gp3): 
 
Hard Disk Driver (HDD)
- VOlumes de HDD com throughput otimizados (st1): Menor perfomance, comparamos o HD comparado a um onibus mas um volume maior de dados.
- VOlumes de HDD Cold (sc1): 

Lancar um instancia -> Conecte-se a instancia -> Usar a instancia...

# Por que a escalabilidade é importante

Vantagesns da nuvem é a capacidade elastica e escalar nossa infraestrutura.

Como fazer isso?

Necessário analisar sua aplicação em uso durante o uso na semana e analisar a capacidade não usada!

Se eu provisiono os recursos pode ser que não consigo atender a demanda.

Demanda + Capacidade?

O Amazon **EC2 Auto Saling** ajusta a capacidade conforme necessário.

- Aumente a escala para picos.
- Reduza a escala horizontal em horario fora de pico
- Substituir instancias com problemas.
- Pague somente pelo que usar.

Dica: Ele vai ter uma receita ou uma programacao (templat) minimo e o maximo de recursos.

# Elasic Load Balancing: Ele força uma alta disponibilidade entre zonas  (AZs) de disponibilidade

Distribuia automaticamente o tráfego entre arios destinos

- Alta disponibilidade
- verificações de integridade
- Terminação SSL/TLS
- Monitoramento operacional

Elastic Load Balancing -> Instancia, Instancia, Instancia, Instancia, Instancia

Dicas: EC2 Auto Scaling provisiona recursos dentro de um grupo de escalibidade, que vai enviar a comunicação para o ELB estarão integrados.

# O que é o Amazon CloudWatch?

Monitora
- Recursos da AWS
- Aplicações em execução na AWS

Coleta e rastreia:
- Metricas padrão
- Metricas personalizadas

Alarmes:
- Enviar notificações
- Fazer alterações automaticamente com base nas regiões que voce define

Dica: CloudWatch se comunica com EC2 Auto Scalin e o EBL atraves de alarmes.

# O que é o Amazon S3?

- Os dados são armazenados como objetos em buckets
- Armazenamento ilimitado
  * Objeto único limitado a **5 TB**

- 99,999999999% durável
- Acesso granular a buckets e objetos: Forma customizada que pode controlar o acesso aos recursos no seu armazenamento.

Dica: Armazenar fotos, centralizar logs e etc... É um serviço que primeito voce **define uma região** (Ele fica no minimo em 3 zonas de alta disponibilidade), e fica ate o momento que quiser retirar, depois voce escolhe um *local para armazenar* seus dados e local e chamado **'Buckets' (Balde)**. 

# Classe de arqazenamento  / Recurso

S3 Standard: 
* 3 Zonas de disponibilidade

S3 Standard - Infrequent Access (IA) : 
* Taxa de recuperacao associada a objetos
* Mas adequada para dados acessados com menos frequencia

S3 Intelligent - Tiering: 
* Move objetos automaticamente entre camadas com base nos padrães de acesso
* 3 Zonas de disponibilidade

One Zone -IA:
* 1 Zonas de disponibilidade
* Custo 20% menores que o S3...

Como criar um bucket S3...


# Faca voce mesmo X Servicos de Bacno de Dados Gerenciados

Banco de dados no Amazon EC2
- Acesso ao Sistema Operacional
- Precisa de recursos de aplicações especificos


Serviço de Banc de Dados AWS
- Facil de configurar , gerenciar e manter
- Alta disponibilidade com alguns cliques
- Foco no desempleho



# Amazon Relation Databse Services (RDS)

opere escale um banco de dados relacional a nuvel AWS -> Automatiza tarefas administrativas 

Mecanismo de banco de Dados RDS: Amazon Aurora, PostgreeSQl, MySQL, MariaDB, Oracle Databse, Microsoft SQL Server


# Amazon Autora (Replicado 6x)

Armazena dadso em um banco de dados ralcional corporativo 

# Amazon DynamoDB - Serveless não relacional

# Amazon Virtual Priate Cloud (Amazon VPC)

Nuvem AWS -> Regiao -> VPC -> Intervalo de IPs da VPC -> 
Zona de Disponibidalde A

Sub-rede publica 
Instancias
. Internet Publica: Portao de entrada ao acessar (Internet Gateway). NACL controle de acesso. das sub-rede

Sub-rede privada
Instancias
. DataCenter Corporativo: Não tem Uma rota direta para intenet publica. Imagine que voce tem um **porta para pessoas autorizadas (Instatess)** e para manter uma segurança coloquei um **Security Group** (Statefull).

Dica: Latencia é importante por isso (Edge Location), cloudFront

# Faturamento e Preço:

RESUMO DO CONTEÚDO – AWS CERTIFIED CLOUD PRACTITIONER (PARTE I)
June 18, 2020
Esse é um resumo do conteúdo para o exame AWS Certified Cloud Practitioner. Não é nenhum conteúdo oficial, apenas uma orientação dos principais conceitos de Cloud concepts, Security and compliance, Technology e Billing and Pricing.

Antes de seguir adiante nessa leitura, sugiro acessar o post AWS CLOUD PRACTITIONER – PREPARAÇÃO PARA O EXAME E SIMULADOS para entender melhor o formato do exame e o que será abordado. E assim, esse resumo está dividido em: Introdução a nuvem AWS, Core Services, Integrated Services, Arquitetura, Segurança, Definição de preço e suporte, outros serviços.

1. INTRODUÇÃO A NUVEM AWS
Abordagem de alterações de gerenciamento, testes, confiabilidade e planejamento de capacidade é mais ágil e eficiente. A AWS é uma plataforma que oferece soluções em cloud flexíveis, confiáveis, escaláveis, fáceis de usar e econômicas.

Reduzir riscos:

Por ser capaz de aprender e adaptar-se rapidamente as mudanças (reduz o custo da mudança)
Riscos de segurança por permitir testar com frequência e efetuar correções rápidas
Escalabilidade

Redimensionar seus recursos conforme necessário
Confiabilidade

Capacidade de um sistema se recuperar de falhas de infraestrutura ou serviço
Capaz de adquirir recursos computacionais para atender à demanda e mitigar interrupções
Data Centers em todo o mundo (AWS Regions) que estão em locais isolados (Availability Zones)
Availability Zones são DCs separados com alimentação redudante, redes e conectividade
Segurança dos dados

Clientes mantém propriedade total sobre seus dados (incluindo região que os armazena, como lida com criptografia e quem mantém as chaves de criptografia)
Interfaces AWS
Os usuários AWS podem criar e gerenciar recursos de três maneiras:

Console de Gerenciamento AWS: interface gráfica para acessar recursos da AWS
Interface de linha de comando (CLI): permite controlar os serviços da AWS
SDKs: permite acessar AWS utilizando linguagens de programação
Os três utilizam como referência a API da AWS. Com as Interfaces AWS, há mais flexibilidade de criar e acessar os recursos em qualquer lugar.

The 6 advantages of cloud are:

Trade capital expense for variable expense
Benefit from massive economies of scale
Stop guessing about capacity
Increase speed and agility
Stop spending money running and maintaining data centers
Go global in minutes
2. CORE SERVICES
2.1. Compute: EC2 (Elastic Compute Cloud)

É um serviço que disponibiliza capacidade computacional segura e redimensionável na nuvem. A interface permite que você obtenha e configure a capacidade com o mínimo de esforço. Ele oferece controle total de seus recursos e permite trabalhar no ambiente das AWS. No EC2, o cliente gerencia a infraestrutura virtual das VMs (configuração do SO, patchs de segurança e rede).

Instâncias do EC2 são Pay as you go (pelas instâncias em execução). Ampla seleção de hw/sw e hospedagem global. Um Host dedicado do EC2 é um servidor físico com a capacidade de instância do EC2 totalmente dedicada a seu uso. Hosts dedicados permite que você use suas licenças de software existentes por soquete, por núcleo ou por VM, incluindo o Windows Server, o Microsoft SQL Server, o SUSE e o Linux Enterprise Server.

Host dedicado	Instâncias dedicadas
Faturamento	Faturamento por host	Faturamento por instância
Visibilidade de soquetes, núcleos e ID de host	Fornece visibilidade do número de soquetes e núcleos físicos	Sem visibilidade
Afinidade de hosts e instâncias	Permite implantar de forma consistente suas instâncias no mesmo servidor físico com o momento	Sem suporte
As instâncias spot do Amazon EC2 permitem aproveitar a capacidade não utilizada do EC2 na Nuvem AWS. Em comparação com a definição de preço sob demanda, as instâncias spot oferecem descontos de até 90%. Elas podem ser usadas para vários aplicativos stateless, tolerantes a falhas e flexíveis como big data, cargas de trabalho conteinerizadas, CI/CD, servidores web, computação de alta performance e outras cargas de trabalho de teste e desenvolvimento.

Como as instâncias spot são estreitamente integradas a outros serviços da AWS como Auto Scaling, EMR, ECS, CloudFormation, Data Pipeline e AWS Batch, você pode escolher como iniciar e manter os aplicativos em execução nas instâncias spot.

Além disso, você pode combinar facilmente instâncias spot com instâncias sob demanda e reservadas para otimizar ainda mais o custo e a performance das cargas de trabalho. Você também tem a opção de hibernar, parar ou encerrar as instâncias spot quando o EC2 solicitar a devolução da capacidade, com dois minutos de aviso prévio. Somente a AWS oferece acesso à capacidade computacional não utilizada em uma escala tão massiva, e com um desconto de até 90%.


Diferenças entre Spot Instances x On-Demand Instances

 	Spot Instances	On-Demand Instances
Launch time	Can only be launched immediately if the Spot Request is active and capacity is available.	Can only be launched immediately if you make a manual launch request and capacity is available.
Available capacity	If capacity is not available, the Spot Request continues to automatically make the launch request until capacity becomes available.	If capacity is not available when you make a launch request, you get an insufficient capacity error (ICE).
Hourly price	The hourly price for Spot Instances varies based on demand.	The hourly price for On-Demand Instances is static.
Instance interruption	You can stop and start an Amazon EBS-backed Spot Instance. In addition, the Amazon EC2 Spot service can interrupt an individual Spot Instance if capacity is no longer available, the Spot price exceeds your maximum price, or demand for Spot Instances increases.	You determine when an On-Demand Instance is interrupted (stopped, hibernated, or terminated).
Para usar Instâncias spot, crie uma solicitação de Instância Spot que pode incluir o preço máximo que você está disposto a pagar por hora por instância (o padrão é o preço sob demanda) e outras limitações como o tipo de instância e a zona de disponibilidade. As instâncias spot são executadas até que você as interrompa ou encerre, ou até que o EC2 as interrompa.

Quando usar Instâncias spot, você deverá estar preparado para interrupções. O EC2 poderá interromper a Instância spot quando o preço spot exceder o preço máximo, quando a demanda por Instâncias spot aumentar ou quando a oferta de Instâncias spot diminuir. Quando o EC2 interrompe uma Instância spot, ele fornece um aviso de interrupção de Instância spot, enviando à instância um aviso de dois minutos antes que o Amazon EC2 a interrompa.

Spot instances: are good for short term requirements as they can be very economical. However, you may find that the instance is terminated if the spot market price moves
On-Demand: is the best choice for this situation as it is the most economical option that will ensure no interruptions. Also when you want low cost and flexibility of EC2 without any up-front payment or long-term commitment.
Reserved instances: are good for long-term, static requirements as you must lock-in for 1 or 3 years in return for a decent discount (applications with steady state or predictable usage).
Dedicated instances: are EC2 instances that run on hardware dedicated to a single customer
Uma AMI (Amazon Machine Image) fornece as informações necessárias para iniciar uma instância. Pode ser considerado um snapshot para recriação de instância. O EC2 Snapshot é o ponto para novos volumes ou backup. Existem três categorias de AMIs:

Community AMIs– generally you just select the operating system you want. It’s free to use.
AWS Marketplace AMIs– pay to use, generally come packaged with additional, licensed software.
My AMIs– AMIs that you create yourself.
2.2. Compute: ECS (Elastic Container Service)

É um serviço de gerenciamento de contêineres altamente dimensionável e rápido que facilita a execução, a interrupção e o gerenciamento de contêineres do Docker em um cluster. Você pode hospedar seu cluster em uma infraestrutura sem servidor gerenciada pelo ECS ao iniciar seus serviços ou tarefas usando o tipo de inicialização Fargate. Para obter mais controle, você pode hospedar suas tarefas em um cluster de instâncias do EC2 gerenciado usando o tipo de inicialização EC2.


2.3. Storage: EBS (Elastic Block Store)

É um serviço de armazenamento de blocos de alta performance, projetado para o uso com as instâncias do EC2, para workloads com alta taxa de transferência de dados e com transações em qualquer escala. EBS é o armazenamento utilizável somente com EC2.

Workloads como BD relacionais e não relacionais, aplicativos corporativos, aplicativos em contêiner, mecanismos de análise de big data, sistemas de arquivos e fluxos de trabalho de mídia são amplamente empregados no Amazon EBS. Você pode escolher entre quatro tipos de volume diferentes para equilibrar preço e desempenho ideais:

Latência abaixo de 10 ms para workloads de BD de alta performance, como o SAP HANA.
Transferência de dados de 1 GB/s para workloads sequenciais grandes, como o Hadoop.
Alterar os tipos de volume (com suporte a SSD incluem um volume projetado para aplicativos de alta performance e um volume de uso geral; com suporte a HDD são projetados para grandes workloads sequenciais como mecanismos de análise de big data DW).
Ajustar a performance ou aumentar o tamanho do volume sem interromper seus aplicativos essenciais, assim terá armazenamento econômico quando precisar.
Os volumes EBS são replicados em uma zona de disponibilidade (AZ) e podem ser facilmente escalonados para petabytes de dados. Além disso, é possível usar o EBS Snapshots com políticas de ciclo de vida automatizadas para fazer backup de seus volumes no Amazon S3 e, ao mesmo tempo, garantir a proteção geográfica de seus dados e da continuidade de negócios.

2.4. Storage: Amazon S3 (Simple Storage Service)

É um serviço gerenciado de armazenamento na nuvem que utiliza APIs (ou endpoints de VPCs) para armazenar e recuperar dados. Armazena um número praticamente ilimitado de objetos (imagens, vídeos, logs, etc.). Também oferece acesso de baixa latência por HTTP ou HTTPS.


O S3 pode ser acessado pelo Console, CLI e SDKs da AWS. O uso mais comum do S3 é para armazenamento de ativos de aplicativos, hospedagem de sites estáticos, recuperação de desastre e backup (possui alta durabilidade) e área de preparação para Big Data (pelo armazenamento escalável e performance do S3).

Os pontos de acesso do S3 simplificam o gerenciamento do acesso de dados para aplicativos que usam conjuntos de dados compartilhados no S3. Os pontos de acesso fornecem um caminho personalizado em um bucket, com um hostname e uma política e acesso únicos, que aplica as permissões e os controles de rede específicos para qualquer solicitação feita por meio do ponto de acesso.


O S3 é um armazenamento de objetos, você cria objetos, não arquivos. Também pode criar pastas dentro de buckets e também pode fazer upload de objetos. Existe o S3 Standard-IA e o S3 One Zone-IA.

O S3 usa um espaço para nome global , porém ao criar os buckets em uma região, os dados nunca saem dessa região, a menos que sejam explicitamente configurados com o CRR (Cross-region replication). Com o lifecycle management, você pode definir regras para transferir objetos entre classes de armazenamento em intervalos de tempo definidos.

2.5. STORAGE: S3 GLACIER
O Amazon S3 Glacier e o S3 Glacier Deep Archive são classes de armazenamento em nuvem do Amazon S3 seguro, resiliente e de custo extremamente baixo para arquivamento de dados e backups de longa duração. Essas classes foram projetadas para oferecer resiliência de 99,999999999% e disponibilizar recursos abrangentes de segurança e conformidade que podem ajudar a cumprir até mesmo os requisitos normativos mais rigorosos.

A classe de armazenamento Amazon S3 Glacier disponibiliza três opções de recuperação:

Recuperações aceleradas: retornam dados em 1 a 5 minutos; excelentes p/ arquivamento ativo.
Recuperações padrão: são concluídas em 3 a 5 horas e funcionam bem para atividades em que o tempo não é tão crucial, como dados de backup, edição de mídia ou análises de longo prazo.
Recuperações em massa: são a opção de recuperação mais barata, e retornam grandes quantidades de dados em 5 a 12 horas.
O S3 Glacier Deep Archive oferece armazenamento de objetos seguro e durável para retenção de dados no longo prazo, acessados uma ou duas vezes por ano. É ideal para fornecer proteção offline dos ativos de dados mais importantes da sua empresa ou quando a retenção de dados no longo prazo é necessária para requisitos de política corporativa, contratuais ou de conformidade regulamentar.

2.6. Storage: EFS (Elastic File System)

Fornece um sistema de arquivos NFS (Network File System) elástico, simples, escalável e totalmente gerenciado para uso com os serviços de nuvem AWS e os recursos local. Ele foi desenvolvido para escalar sob demanda até petabytes sem interromper os aplicativos, aumentando e diminuindo automaticamente à medida que você adiciona e remove arquivos, eliminando a necessidade de provisionar e gerenciar a capacidade com base no crescimento. Em NFS não pode ser instalado SO (sistema operacional).

O Amazon EFS oferece duas classes de armazenamento:

Standard
Infrequent Access (EFS IA): fornece preço/performance com custo otimizado para arquivos que não são acessados todos os dias.
Amazon EFS usa o NFS e é um sistema de armazenamento de arquivos. O Amazon EBS armazena em nível de bloco (para instâncias do EC2). E o S3 é um sistema de armazenamento de objetos.

O Amazon EFS foi criado para fornecer acesso compartilhado massivamente paralelo para milhares de instâncias do Amazon EC2, permitindo que seus aplicativos alcancem altos níveis em taxas de transferências agregadas e IOPS com latências baixas e consistentes.

2.7. Storage: AWS Storage Gateway

É um serviço de armazenamento na nuvem híbrida que oferece acesso local a armazenamento na nuvem praticamente ilimitado. Os clientes usam o Storage Gateway para simplificar o gerenciamento de armazenamento e reduzir os custos de armazenamento na nuvem híbrida.

A mudança de backups de fita para a nuvem
A redução do armazenamento local com compartilhamentos de arquivo baseados na nuvem
A disponibilização de acesso de baixa latência a dados na AWS para aplicativos locais
Migração, arquivamento, processamento e recuperação de desastres. 
Para oferecer suporte a esses casos de uso, o serviço oferece três tipos diferentes de gateway: gateway de fitas, gateway de arquivos e gateway de volumes. Esses gateways conectam de forma transparente aplicativos locais ao armazenamento na nuvem, armazenando dados em caches locais para oferecer acesso de baixa latência.

A Gateway Virtual Tape Library pode ser usada com softwares de backup populares, como NetBackup, Backup Exec e Veeam. Usa um trocador de mídia virtual e unidades de fita.

2.8. INFRA GLOBAL AWS
AWS Regions
São regiões que hospedam uma ou mais Availability Zones. Ao escolher região, considere latência, minimizar custos e cumprir requisitos normativos. Pode ser implementado recursos em várias regiões (para melhor atender a sua empresa).

Exemplo: servidor de deploy em uma região e base de clientes em outra. Ou os mesmos recursos em várias regiões, permitindo uma experiência global consistente (independente da localização do cliente).

As regiões são entidades completamente separadas. Os recursos em uma região não são replicados automaticamente a outras (e nem todos os serviços estão disponíveis em todas as regiões).

Availability Zones
Conjunto de DCs dentro de uma região. São isoladas uma da outra, mas conectadas por uma rede rápida e de baixa latência. Cada uma possui sua própria infraestrutura (alimentação, geradores de backup, redes e conectividade). O isolamento das zonas garante proteção de falhas em outras zonas (alta disponibilidade e redundância de dados em uma região).

Edge locations
Hospedam CDNs (redes de entrega de conteúdos) – Amazon Cloudfront, que é utilizado para entregar conteúdo aos clientes, através de roteamentos ao ponto de presença mais próximo.

2.9. Network: VPC (Virtual Private Cloud)

O VPC permite provisionar uma seção da Nuvem AWS isolada logicamente na qual é possível executar recursos da AWS em uma rede virtual que você mesmo define. Você tem controle total sobre seu ambiente de redes virtuais, incluindo a seleção do seu próprio intervalo de endereços IP, a criação de sub-redes e a configuração de tabelas de rotas e gateways de rede. Você pode usar IPv4 e IPv6 na VPC para acessar recursos e aplicativos com segurança e facilidade.

Boa parte da complexidade da configuração de uma rede foi abstraida sem prejudicar o controle, a segurança e a usabilidade
Clientes podem definir itens de configuração de rede, endereço IP, sub-redes e tabelas roteamento
Personalizar regras de roteamento e controle de tráfego de e/s
Há vários produtos AWS que herdam e aproveitam a segurança incorporadas a VPC
Amazon VPC é um serviço fundamental e se integra a vários serviços da AWS. Por exemplo, instâncias EC2 são implantadas na VPC.

E possui as seguintes configurações:

Uma lista de controle de acesso (ACL) à rede é uma camada de segurança opcional para sua VPC que funciona como firewall para controlar o tráfego de entrada e saída de uma ou mais sub-redes. Você pode configurar Network ACLs com regras semelhantes às dos grupos de segurança a fim de adicionar uma camada extra de segurança à sua VPC. Opera no nível da subnet.

2.10. Network: AWS Direct Connect

Permite conectar o ambiente AWS ao DC (ou escritório local) através de uma conexão dedicada de alta velocidade e baixa latência, que bypass os provedores de serviços de Internet em seu caminho de rede.

Um local do AWS Direct Connect fornece acesso ao AWS na região à qual está associado e também a outras regiões dos EUA. Permite particionar logicamente as conexões de fibra ótica em várias conexões lógicas chamadas VLAN (Virtual Local Area Networks).

Benefits:

Reduce cost when using large volumes of traffic
Increase reliability (predictable performance)
Increase bandwidth (predictable bandwidth)
Decrease latency
2.11. Segurança AWS

Os grupos de segurança funcionam como um firewall integrado para seus servidores virtuais. Com isso, você tem total controle sobre o nível de acesso das suas instâncias.

Método para filtrar o tráfego das suas instâncias
As instâncias podem ser totalmente privada até totalmente pública
Regras para arquiteturas multicamadas

3. INTEGRATED SERVICES
3.1. ELB (Elastic Load Balancing)

Distribui automaticamente o tráfego de entrada de aplicativos entre diversos destinos, como instâncias do Amazon EC2, contêineres, endereços IP e funções Lambda. O serviço pode lidar com a carga variável de tráfego dos aplicativos em uma única zona de disponibilidade ou em diversas zonas de disponibilidade.

O Elastic Load Balancing oferece três tipos de load balancers, todos eles com a alta disponibilidade, a escalabilidade automática e a segurança robusta necessárias para tornar os aplicativos tolerantes a falhas

Application Load Balancer (ALB): atua na camada 7 e roteia conexões com base no conteúdo da solicitação. Processam o tráfego no nível HTTP, HTTPS (camada 7).
Network Load Balancer (NLB): atua na camada 4 e roteia conexões com base nos dados do protocolo IP. Os Processam o tráfego no nível TCP (camada 4).
Classic Load Balancer (CLB): fornece balanceamento de carga básico nas camadas 4 e 7. Processam o tráfego nos níveis TCP, SSL, HTTP e HTTPS (camadas 4 e 7)
O ELB pode distribuir o tráfego recebido pelas instâncias do Amazon EC2 em uma única AZ ou em várias AZs, mas não entre regiões. É usado para distribuir a carga e introduzir tolerância a falhas distribuindo conexões entre instâncias do EC2.

3.2. Auto scaling

Ajuda a garantir o número correto de instâncias do EC2 disponíveis para processar a carga dos aplicativos. Permite adicionar e remover instâncias de acordo com as condições especificadas.

A Escalabilidade é para garantir que os workloads tenham recursos suficientes do EC2 p/ atender a requisitos dinâmicos de performance
A Automação é para dimensionar o provisionamento de recursos do EC2 para que ocorra sob demanda
Os componentes do Auto Scaling são:


No Auto Scaling dinâmico, pode criar alarmes no CloudWatch, com base nas informações de performance de suas instâncias EC2 ou de um load balancer.

Scaling vertically: através do aumento de um recurso individual, por exemplo, atualizando um servidor com um disco rígido maior ou uma CPU mais rápida.

Scaling horizontal: através do aumento no número de recursos, por exemplo, adicionando mais discos rígidos a uma array de armazenamento ou mais servidores para suportar um aplicativo).

3.3. Network: Route 53

É um serviço de DNS projetado para rotear usuários finais a endpoints (que pode ser uma aplicação que precisa converter o nome de domínio em IP).

Entre as principais funções do Route 53: registro de domínio, DNS global e altamente disponível, health checking (availability monitoring), vários algoritmos de roteamento (traffic management), IPv4 e IPv6, integrado a outros serviços AWS.

As principais routing policies são Simple, Weighted, Latency based, Failover, Geo-location, Geo-Proximity, Multi-Value e Traffic Flow.

3.4. Database RDS (Relational Database Service)

É um serviço gerenciado que configura e opera um BD relacional na nuvem. Permite que você se concentre em performance, alta disponibilidade, segurança e compatibilidade necessárias.

Entre os principais desafios em manter um BD relacional: manutenção do servidor e energia, instalação do software e patches, backups, alta disponibilidade, limites de escalabilidade, segurança de dados, instalação de SO e patches.

Você pode executar uma instância de BD usando o Amazon VPC. Ao usar VPC, você tem controle do seu ambiente de rede virtual (intervalo de endereços IP, sub-redes, roteamento e listas de controle de acesso).

Dois conceitos importantes de RDS:

Alta disponibilidade com Multi-AZ: gera uma cópia stand by da instância do BD em outra availability zone (dentro da mesma VPC). Os dados são replicados de forma sincrona. Ajuda na manutenção e falhas nas instâncias de BD.
Réplicas de leitura: método de replicação assíncrona, onde são descarregadas consultas de leitura da instância de dados mestra. Ideal para cargas de trabalho do BD com uso intensivo de leitura.
Os principais benefícios do RDS: altamente escalável, alta performance, fácil de administrar (console de gerenciamento AWS, CLI ou chamadas API), disponível e durável, seguro e compatível (controle e segurança via VPC ou não).

3.5. Compute: Lambda

É um serviço que permite executar código sem provisionar ou gerenciar recursos (serverless). Executa seu código somente quando necessário (orientada a eventos) e dimensiona automaticamente as solicitações.

O AWS Lambda está em uma infraestrutura altamente disponível (inclui manutenção de servidor e SO), com provisionamento de capacidade, Auto Scaling, monitoramento e registro de log. Oferece suporte a diversas linguagens de programação: Node .JS, Java, C# e Python. O CloudWatch Events é onde configura os triggers.

O AWS Lambda pode ser usado em diversos aplicativos, tais como backup automatizados, objetos de processamento enviados para o S3, IoT, etc.

3.6. Elastic Beanstalk

É um PaaS, ou seja, você possui toda a infraestutura e plataforma criada para você, de modo a colocar o código da aplicação, conforme necessário. Permite a implementação rápida de seus aplicativos e reduz a complexidade de gerenciamento.

Basta fazer o upload de seu código e o Elastic Beanstalk se encarrega automaticamente da implementação, desde o provisionamento de capacidade, o balanceamento de carga e a escalabilidade automática até o monitoramento da saúde do aplicativo.

AWS Elastic Beanstalk can be used to quickly deploy and manage applications in the AWS Cloud. However, you do still need to deploy within a VPC so more AWS expertise is required


3.7. Simple Notification Service (SNS)

É um serviço de mensagens e comunicações móveis de publicação / assinatura (pub/sub) flexível e totalmente gerenciado. Também coordena a entrega de mensagens para endpoints e clientes assinantes.

Permite desacolpar e ajustar a escala de microsserviços, sistemas distribuidos e aplicativos serverless. Eventos que disparam e-mail ao administrador, microsserviços que se comunicam entre si, etc.


Os principais conceitos do SNS são:

Topics: como rotula e agrupa diferentes pontos de extremidade para os quais envia mensagens.
Subscriptions: os pontos de extremidade para os quais um tópico envia mensagens.
Publishers: a pessoa / alarme / evento que envia ao SNS a msg a ser enviada.
3.8. Management: Amazon CloudWatch

Monitora seus recursos AWS e os aplicativos que você executa em tempo real (métricas como utlização de CPU, transferência de dados, etc.). O CloudWatch fornece dados e insights para monitorar aplicativos, responder às alterações de performance em todo o sistema, otimizar a utilização de recursos e obter uma visualização unificada da integridade operacional.

O CloudWatch coleta dados de monitoramento e operações na forma de logs, métricas e eventos, oferecendo uma visualização unificada dos recursos, dos aplicativos e dos serviços da AWS executados na AWS e em servidores locais. Você pode usar o CloudWatch para detectar comportamento anômalo em seus ambientes, definir alarmes, visualizar logs e métricas lado a lado, executar ações automatizadas, resolver problemas e descobrir insights para manter seus aplicativos em perfeita execução.

A capacidade de automaticamente reagir às mudanças é o principal recurso do CloudWatch. Os principais componentes do CloudWatch são: métricas, alarmes, eventos, logs e dashboards.


3.9. Amazon CloudTrail

É um serviço que possibilita governança, conformidade, auditoria e de riscos em sua conta da AWS. Permite registrar, monitorar continuamente e reter a atividade da conta relacionada às ações executadas na infraestrutura da AWS.


Disponibiliza o histórico de eventos da atividade da conta AWS (inclusive ações via Console, SDKs, CLIs e de outros Serviços da AWS). É usado para simplificar as auditorias de compatibilidade ao registrar e armazenar automaticamente logs de evento de ações executadas em sua conta da AWS.

Qual é a diferença entre o CloudWatch Events e o AWS CloudTrail?

Com o CloudWatch, você pode definir regras para monitorar eventos específicos e executar ações de maneira automática. O AWS CloudTrail é um serviço que registra chamadas de API / atividades da conta e entrega arquivos de log contendo chamadas de API para seu bucket do Amazon S3 ou um grupo de log do CloudWatch Logs, com o intuito de conformidade, auditoria e gestão de riscos.

3.10. AWS Artifact

Portal gratuito de autoatendimento para acesso sob demanda aos relatórios de conformidade da AWS. Os relatórios de System & Organization Control (SOC) da AWS são relatórios de exame de terceiros independentes que demonstram como a AWS atende aos principais controles e objetivos de conformidade. O propósito desses relatórios é ajudar você e os seus auditores a entenderem os controles estabelecidos na AWS para apoiar as operações e a conformidade.

O relatório SOC 1 e SOC 2 da AWS estão disponível para clientes da AWS por meio do AWS Artifact. Relatório de segurança, disponibilidade e confidencialidade SOC 3 da AWS, disponível publicamente como um whitepaper.

3.11. Storage: CloudFront CDN (Content Delivery Network)

É uma rede de entrega de conteúdo. Ao utilizar o CloudFront, você aproveita diversos edge locations espalhados pelo mundo para entregar conteúdo, garantido baixa latência na interação com os usuários através do uso de caches.

Está integrado a outros serviços AWS, tais como AWS WAF (Web Application Firewall), Route 53, etc. Pode ser usado para conteúdos estáticos e dinâmicos.

Casos de uso: armazenamento em cache de ativos estáticos, streaming de vídeo ao vivo e sob demanda, segurança e proteção contra DDoS e conteúdo dinâmico.

3.12. Management: Amazon CloudFormation

Simplifica a tarefa de criar grupos de recursos relacionados a seus aplicativos. O foco é a automação do provisionamento de recursos.

O CloudFormation lê o arquivo modelo (JSON ou YAML) e o output é o provisionamento de recursos (conhecido como pilha). Você pode criar, atualizar e excluir pilhas (stacks).


4. ARQUITETURA
Os cinco pilares são:

Segurança: IAM, controles de detecção, resposta a incidentes, proteção de infraestrutura e dados. Aplica o princípio de privilégio mínimo e segurança em todas as camadas. Com o modelo de responsabilidade compartilhada, você foca na proteção dos dados da aplicação e SO (e a AWS oferece infraestrutura e serviços seguros).
Confiabilidade: recuperar problemas/falhas (automaticamente), gerenciamento de alterações, previsão, resposta e prevenção de falhas.
Eficiência de performance: selecionar soluções personalizáveis para inovar continuamente (tecnologias avançadas, alcance global em minutos, arquitetura serverless, etc.) .
Otimização de custos: refinamento e aprimoramento contínuo dos sistemas. Usar recursos econômicos, combinar oferta e demanda, conscientização sobre despesas e otimizar ao longo do tempo.
Excelência operacional: gerenciar e automatizar alterações, responder a eventos e definir os padrões.
Tolerância a falhas

Capacidade de um sistema permanecer operacional
Redundância integrada do componente de um aplicativo
Os mecanismos de Disaster Recovery: o mais rápido é o Multi Site; o mais lento é Backup & Restore.


Os 5 pilares AWS Well-Architected Framework são:

Operational Excellence: perform operations as code, annotate documentation, make frequent, small and reversible changes, refine operations procedures frequently, anticipate failure e learn from all operational failures
Security: implement a strong identity foundation, enable traceability, apply security at all layers, automate security best practices, protect data in transit and at rest e prepare for security events
Reliability: test recovery procedures, automatically recover from failure, scale horizontally to increase aggregate system availability, stop guessing capacity e manage change in automation
Performance Efficiency: democratize advanced technologies, go global in minutes, use serverless architectures, experiment more often e mechanical sympathy
Cost Optimization: adopt a consumption model, measure overall efficiency, stop spending money on data center operations, analyze and attribute expenditure e use managed services to reduce cost of ownership
Mais detalhes em: https://aws.amazon.com/pt/architecture/well-architected/

5. SEGURANÇA
Uma infraestrutura resiliente, projetada para alta segurança e proteções fortes (safe guards) para ajudar a proteger a privacidade dos clientes.

Atenda aos requisitos de conformidade (automação centralizada, controle de segurança e supervisão adicional)
Modelo de responsabilidade compartilhada: herde controles de segurança na AWS. Coloque em camadas seus controles
Segurança de rede: firewalls integrados, criptografia em trânsito, conexões privadas/dedicadas, mitigação de DDoS.
Gerenciamento de inventário e configuração: ferramentas de definição e gerenciamento de modelos
Criptografia de dados: recursos de criptografia, gerenciamento e armazenamento de chaves
Monitoramento e registro em log
AWS Marketplace: parceiros qualificados que se integram com os controles
O AWS Key Management Service (KMS) facilita a criação e gerenciamento de chaves criptográficas e o seu uso em serviços AWS e em aplicativos. Já o AWS CloudHSM é um Hardware Security Module (HSM) baseado na nuvem que permite gerar e usar facilmente suas próprias chaves de criptografia na Nuvem.

O Amazon GuardDuty oferece detecção de ameaças e monitoramento de segurança contínuo de comportamentos mal-intencionados ou não autorizados para ajudar a proteger suas contas e cargas de trabalho AWS.

Os security groups são stateful; portanto, se você permitir a passagem do tráfego, o tráfego de retorno será automaticamente permitido, mesmo que nenhuma regra corresponda ao tráfego. Os security groups podem ser configurados em uma VPC, EC2 etc.

Os security groups facilitam o agrupamento de recursos usando as tags atribuídas a eles. Você pode agrupar recursos que compartilham uma ou mais tags. Os grupos de recursos facilitam o gerenciamento e automatizam as tarefas em grandes números de recursos de uma vez.

5.1. Modelo de responsabilidade compartilhada

User Data	Chave de acesso e métodos de criptografia são criados pelo cliente	Cliente
Application	AWS não controla a sua aplicação	Cliente
Guest OS	AWS não interfere na escolha. Pode ser windows, linux, etc.	Cliente
Hypervisor	AWS usa Hypervisor baseado em Xex. É seguro e escalável	AWS
Network	Protocolos de rede proprietários (VPC, etc.) para prover segurança	AWS
Physical	Gerenciamento físico (acesso restrito a DCs, etc.)	AWS
Os clientes que implantam uma instância do EC2 são responsáveis pelo gerenciamento do SO convidado (o que inclui atualizações e patches de segurança), por qualquer utilitário ou software de aplicativo instalado pelo cliente nas instâncias, bem como pela configuração do firewall disponibilizado pela AWS (chamado de grupo de segurança) em cada instância.

A AWS é responsável pela “segurança da nuvem”. Isso inclui a proteção da infraestrutura que executa todos os serviços oferecidos na nuvem da AWS. Essa infraestrutura é composta pelo hardware, software, rede e instalações que executam os serviços da AWS Cloud.

O cliente é responsável pela “segurança na nuvem”. A responsabilidade do cliente depende do serviço consumido, mas inclui aspectos como o IAM, criptografia de dados, proteção do tráfego de rede e sistema operacional, configuração de rede e firewall.

5.2. IAM (Identity and Access Management)

É um recurso gratuito que permite gerenciar com segurança o acesso aos serviços e recursos da AWS. Usando o IAM, você pode criar e gerenciar usuários e grupos da AWS e usar permissões para conceder e negar acesso a recursos da AWS.

Trabalha com os conceitos de Group – User (credenciais permanentes; pode ser usuário e senha, chave de acesso, chave secreta, etc.) – Role (método de autenticação; não são permissões).

A permissão ocorre na Policy Docs que é um objeto separado. Esse JSON pode ser anexado a um grupo, usuário ou role. Cada ação ocorrida em APIs (maioria dos serviços é utilizada por APIs) é registrada no CloudTrail.

IAM – casos de uso:

Controle de acesso aos recursos AWS (APIs de serviços e recursos específicos). Permite adicionar condições (horário de uso para um usuário, seu IP de origem, se estão usando SSL ou MFA).
MFA (Multi factor authentication)
Analisar o acesso
Integração ao diretório corporativo (como o MSFT AD)
Gerencie permissões com grupo; configure uma política de senha forte
Com a IAM Roles, você pode delegar permissões a recursos para usuários e serviços sem usar credenciais permanentes (por exemplo, nome de usuário e senha).

Uma IAM policy é um documento de política usado para definir permissões que podem ser aplicadas a usuários, grupos e roles. Você não aplica a política ao serviço, aplica-a à função. A role é usada para atribuir permissões ao serviço da AWS.

5.3. Amazon Inspector

É um serviço de avaliação de segurança automatizado. Avalia vulnerabilidades e desvios das melhores práticas. Produz relatórios com descobertas de segurança e etapas priorizadas para a correção. É baseado em agentes e orientado por API.


5.4. AWS Shield

É um serviço gerenciado contra DDoS que protege aplicações em execução na AWS. Protege outros recursos da AWS:

Route 53: proteção zonas hospedadas do Route 53 contra DDoS ataques – inundações, ataques de reflexão,etc.
CloudFront: proteções nas camadas 3 e 4 de infraestrutura, usando engenharia de tráfego
VPC
5.5. Segurança e conformidade

AWS compartilha informações de segurança: obtenções de certificado do setor, publicação de práticas de segurança e controle, relatórios de conformidade.

Programas de garantia – a AWS fornece informações e recursos de conformidade para suporte jurídico/normativo, certificações/declarações e alinhamentos/estruturas.

A AWS permite que as entidades cobertas e seus associados comerciais sujeitos à lei Health Insurance Portability and Accountability Act (HIPAA – Lei de portabilidade e responsabilidade de provedores de saúde) de 1996 dos EUA se beneficiem do ambiente seguro da AWS para processamento, manutenção e armazenamento de informações protegidas relacionadas à saúde.

E também CJIS (Serviço de Informação da Justiça Criminal), CSA (Cloud Security Alliance), FERPA (Family Educational Rights and Privacy) e MPAA (Motion Picture Association of America).

5.6. AWS Personal Health Dashboard

Fornece alertas e orientações de remediação quando a AWS enfrenta eventos que podem afetá-lo. Há uma exibição personalizada do desempenho e da disponibilidade dos serviços da AWS subjacentes aos seus recursos da AWS. O painel exibe informações relevantes e oportunas para ajudar a gerenciar eventos em andamento e fornece notificações proativas para ajudar a planejar atividades programadas.


AWS Service Health Dashboard exibe o status dos serviços (service availability) no Dashboard.


5.7. AWS Config

É um serviço que permite acessar, auditar e avaliar as configurações dos recursos da AWS. O Config monitora e grava continuamente registros das configurações de recursos da AWS e lhe permite automatizar a avaliação das configurações registradas com base nas configurações desejadas.

Com o Config, você pode analisar alterações feitas nas configurações e relacionamentos entre os recursos da AWS, aprofundar-se de forma detalhada no histórico de configuração de recursos e determinar a conformidade geral em relação às configurações especificadas em suas diretrizes internas. Dessa forma, você pode simplificar a auditoria de conformidade, a análise de segurança, o gerenciamento de mudanças e a solução de problemas operacionais.


6. DEFINIÇÃO DE PREÇO E SUPORTE
6.1. Detalhes da definição de preço

Possui as seguintes modalidades:

Pay as you go: serviços pagos conforme o uso (sem penalização de saída)
Capacidade reservada: pode economizar até 75% em relação à capacidade sob demanda equivalente. Estão disponíveis em três opções: AURI (tudo adiantado), PURI (parcialmente adiantado) e NURI (nenhum pagamento adiantado). Quanto maior o pagamento adiantado, maior será o desconto.
Sua organização pode minimizar riscos, gerenciar orçamentos de forma mais previsível e cumprir políticas que exigem compromissos a longo prazo. Serviços como EC2 e RDS podem utilizar capacidade reservada.

Pague por:

Capacidade computacional
Armazenamento
Transferência de dados de saída (agregada)
Não há cobrança para:

Transferência de dados de entrada

Capacidade reservada

As instâncias reservadas proporcionam um desconto significativo (até 75%) em comparação com a definição de preço das instâncias por demanda e podem ser compradas por um período de 1 ou 3 anos. Ao serem atribuidas a uma zona de disponibilidade específica, elas disponibilizam uma reserva de capacidade, podendo executar instâncias quando for necessário. 

Os clientes têm a flexibilidade de alterar a zona de disponibilidade, o tamanho da instância e o tipo de rede de suas instâncias reservadas padrão. O nível gratuito da AWS inclui 750 horas de instâncias t2.micro Linux e Windows por mês por um ano.

Compre instâncias reservadas conversíveis se precisar de flexibilidade adicional, como SO, famílias de instâncias, ou locações diferentes durante o período de vigência. As instâncias reservadas conversíveis oferecem um desconto considerável (até 54%) em comparação às instâncias sob demanda e podem ser compradas por um período de vigência de 1 ou 3 anos.

Há três tipos de instâncias reservadas: Standard RIs, Convertible RIs e Scheduled RIs.

As três opções de reserva que a AWS oferece:

All Upfront: o cliente opta por pagar pelo custo total da instância em uma única vez de acordo com o período escolhido (1 ano ou 3 anos). O custo é à vista e englobará o valor total do período, não haverá cobranças mensais adicionais sobre a instância reservada. Nesse modelo o desconto pode chegar à 60%.
Partial Upfront: o cliente opta por pagar um valor menor à vista (se compararmos ao modelo All Upfront) e as cobranças mensais terão um grande desconto. No geral, o desconto gira em torno de 35%.
No Upfront: o cliente não pagará nenhum valor à vista, porém o desconto será aplicado da mesma forma nas cobranças mensais. Lembre-se que ao efetuarmos uma reservas estamos fechando um contrato com AWS e as cobranças mensais pela instância serão realizadas nos meses decorrentes do contrato. Nesse modelo, o desconto gira em torno de 30%.
Fatores de Custo

EC2: faturamento por segundo/hora (cobrança quando as instâncias estão em execução). A definição de preço varia de acordo com a região, SO, tipo e tamanho da instância.
S3: preço baseado em solicitações (número e tipo) e transferência de dados (dados transferidos para fora da região S3).
EBS: cobrança baseada na quantidade de volumes provisionada por mês. Transferência de dados de saída tem cobrança (dados de entrada não); também GB adicional de dados armazenados em Snapshots.
RDS: faturamento por hora e GB/mês adicional de backup ; pode haver modelo de cobrança sob demanda ou instâncias reservadas.
CloudFront: definição de preço com base em solicitações e transferência de dados para fora
AWS Cost Explorer: permite uma análise detalhada dos dados de custos e uso para identificar tendências, indicar os fatores determinantes dos custos e detectar anomalias. Também criar relatórios de uso e custos (ambos em um nível mais resumido) ou para solicitações altamente específicas.

AWS Budgets: permite definir orçamentos personalizados que enviam alertas quando o uso ou os custos excedem (ou tendem a exceder) o valor orçado. Também pode ser usado para definir metas de utilização ou cobertura de reservas e receber alertas quando a utilização cair abaixo do limite definido.

Os preços da Amazon incluem opções de pay-as-you-go, save when you reserve and pay less by using more. A Amazon não oferece ELAs, descontos fora do horário de pico ou descontos de uso global.

6.2. Trusted Advisor

É uma ferramenta que fornece orientações em tempo real para ajudar a provisionar recursos de acordo com as melhores práticas da AWS (que podem ser usadas em novos fluxos de trabalho, desenvolver aplicativos, aprimoramentos contínuos, etc.).

Casos indicam que o Trusted Advisor ajudou ao destacar: Instâncias do EC2 não utilizadas, Instâncias reservadas do Amazon EC2, volumes não utilizados do Amazon EBS, etc.



6.3. AWS Support

O suporte é fornecido para:

Testar com a AWS
Usar a AWS em produção
Usar essencialmente para os negócios da AWS
Orientações proativas (gerente técnico de conta – TAM)
Melhores práticas (Trusted Advisor)
Assistência à conta (AWS Support Concierge)
O AWS Support oferece quatro planos de suporte:

Suporte básico
Developer Support
Business Support
Enterprise Support
https://aws.amazon.com/pt/premiumsupport/plans/

6.4. TCO (Total Cost Ownership)

As calculadoras de TCO permitem estimar a redução de custo ao usar a AWS e oferecem um conjunto de relatórios detalhados (server hw, network hw, hw maintenance, power and cooling, data center space, personnal/staff and aws instances). As calculadoras também permitem modificar as suposições de acordo com suas necessidades empresariais.

Estimate your AWS billing

To estimate the costs of migrating on-premises infrastructure to AWS, use the AWS Total Cost of Ownership (TCO) Calculator.
If you plan to migrate significant infrastructure to AWS, use the AWS Sales & Business Development contact form, and then choose I need to speak to someone in sales.
To estimate a bill, use the AWS Pricing Calculator. Enter your planned resources by service, and the AWS Pricing Calculator provides an estimated cost per month.
To forecast your costs, use the AWS Cost Explorer. Use cost allocation tags to divide your resources into groups, and then estimate the costs for each group.
Uma tag é um rótulo (chave e um valor) que você ou a AWS atribui a um recurso da AWS. Pode ser usada para organizar os recursos e tags de alocação de custos para acompanhar os custos da AWS em um nível detalhado. Depois de ativar as tags de alocação de custos, a AWS as utiliza para organizar seus custos de recursos no cost allocation report, facilitando a categorização e o controle dos custos da AWS.

6.5. Consolidated billing for AWS Organizations

Usado para consolidar o faturamento e o pagamento de várias contas da AWS. Todas as organizações possuem uma conta mestra (pagante) que paga as cobranças de todas as contas-membro (vinculadas). O uso em conjunto permite compartilhar os descontos de preços por volume, de instância reservada e os Savings Plans.

Isso pode resultar em um custo mais baixo para o seu projeto, departamento ou empresa do que com contas independentes individuais. O faturamento consolidado é oferecido sem qualquer custo adicional.

7. OUTROS SERVIÇOS
7.1. Compute

Fargate: é um mecanismo serverless para contêineres que funciona com o Amazon Elastic Container Service (ECS) e com o Amazon Elastic Kubernetes Service (EKS). O Fargate elimina a necessidade de provisionar e gerenciar servidores, permite que você pague pelos recursos por aplicativo. Executa cada tarefa ou pod no próprio kernel do serviço.

7.2. Database

DynamoDB (noSQL): é um BD de chave-valor e documento que oferece desempenho de milissegundos com um dígito em qualquer escala. Se estende por várias regiões e armazenamento em cache na memória para aplicativos em escala.

Aurora: é um BD relacional compatível com MySQL e PostgreSQL e criado para a nuvem que combina a performance e a disponibilidade de BD comerciais com a simplicidade e a economia de BD open source. É até cinco vezes mais rápido que bancos de dados MySQL padrão e três vezes mais rápido que bancos de dados PostgreSQL padrão. Oferece um sistema de armazenamento distribuído, tolerante a falhas e com recuperação automática que escala automaticamente para até 64 TB por instância de banco de dados. O Amazon Aurora é gerenciado pelo Amazon Relational Database Service (RDS).

MariaDB: é um BD relacional de open source, que foi criado pelos desenvolvedores originais do MySQL. O Amazon RDS facilita a configuração, a operação e a escalabilidade de implantações do servidor MariaDB na nuvem. Com o Amazon RDS, você pode implantar bancos de dados na nuvem escaláveis do MariaDB em minutos, com capacidade de hardware redimensionável e econômica.

Redshift: é um produto de DW que faz parte da AWS. Com o Redshift, você pode consultar petabytes de dados estruturados e semiestruturados em DW e data lakes usando SQL padrão. O Redshift permite salvar facilmente os resultados das consultas de volta no data lake do S3 usando formatos abertos, como o Apache Parquet, para análises adicionais de outros serviços analíticos como Amazon EMR, Amazon Athena e Amazon SageMaker.

DMS (migração): ajuda você a migrar BD para a AWS de modo rápido e seguro. O BD de origem permanece totalmente operacional durante a migração, minimizando o tempo de inatividade de aplicativos que dependem do BD. O DMS viabiliza migrações homogêneas, como de Oracle para Oracle, além de migrações heterogêneas entre plataformas de BD diferentes, como de Oracle ou de Microsoft SQL Server para Amazon Aurora. Ao migrar BD para o Amazon Aurora, o Amazon Redshift, o Amazon DynamoDB ou o Amazon DocumentDB (com compatibilidade com o MongoDB), você pode usar o DMS grátis por seis meses.

(DB2 não é suportado na AWS)

7.3. Security & Identity

WAF (Web Application Firewall): é um firewall que ajuda a proteger os  aplicativos ou APIs contra exploits comuns na web. Fornece controle sobre como o tráfego atinge seus aplicativos, permitindo criar regras de segurança que bloqueiam padrões de ataque comuns, como injeção de SQL ou scripts entre sites, e regras que filtram padrões de tráfego específicos. As Regras gerenciadas do WAF abordam questões como os 10 principais riscos de segurança da OWASP.

7.4. Analytics

EMR (Elastic Map Reduce): é a plataforma de big data em Cloud para processar grandes quantidades de dados usando ferramentas de código aberto, como Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi e Presto. Com o EMR, você pode executar análises em escala de Petabytes a menos da metade do custo das soluções tradicionais locais e 3x mais rápido que o Apache Spark padrão.

Kinesis: permite consumir dados em tempo real como vídeo, áudio, logs de aplicativos, clickstreams de sites e dados de telemetria de IoT para machine learning, análises e outros aplicativos. Ainda processar e analisar dados assim recebidos e responder instantaneamente, em vez de aguardar a conclusão da coleta de dados para poder iniciar o processamento.

7.5. Application Services

API Gateway: é um serviço gerenciado que permite que desenvolvedores criem, publiquem, mantenham, monitorem e protejam APIs em qualquer escala com facilidade. Usando o API Gateway, você pode criar APIs do RESTful e APIs do WebSocket que habilitam aplicativos de comunicação bidirecionais em tempo real. O API Gateway dá suporte a cargas de trabalho conteinerizadas e sem servidor, além de aplicativos da web.

SQS (Simple Queue Service): é um serviço de filas de mensagens gerenciado que permite o desacoplamento e a escalabilidade de microsserviços, sistemas distribuídos e aplicativos sem servidor. O SQS elimina a complexidade e a sobrecarga associadas ao gerenciamento e à operação de middleware orientado a mensagens, além de permitir que os desenvolvedores se dediquem a criar diferenciais.

7.6. Enterprise Applications

Workspaces: é uma solução de desktop como serviço (DaaS) gerenciada e segura. Provisiona desktops Windows ou Linux em minutos e escala rapidamente para oferecer milhares de desktops a funcionários em todo o mundo. O pagamento pode ser feito mensalmente ou por hora e apenas pelos WorkSpaces executados, ajudando você a economizar dinheiro em comparação aos desktops tradicionais e às soluções de Virtual Desktop Infrastructure (VDI – Infraestrutura de desktop virtual) no local.

7.7. Artificial Intelligence

O Amazon SageMaker é o serviço de ML para criar, treinar e implantar modelos de ML rapidamente. Ele remove a complexidade que atrapalha a implementação bem-sucedida do ML desde a execução de modelos para detecção de fraudes em tempo real, passando pela análise virtual de impactos biológicos de medicamentos em potencial, até a previsão de êxito no roubo de bases no baseball.

7.8. AWS Developer Tool

CodePipeline: automatize pipelines de CI/CD para oferecer atualizações rápidas e confiáveis. CodeCommit: hospede com segurança repositórios Git privados altamente escaláveis.

CodeBuild: compile e teste código com escalabilidade contínua. CodeDeploy: automatize implantações de código para manter a disponibilidade dos aplicativos.

X-ray: analise e depure aplicações distribuídas em produção. Codestar: desenvolva, crie e implante aplicativos na AWS. Com o AWS CodeStar, é possível configurar toda a sua cadeia de ferramentas de entrega contínua, possibilitando que você comece o lançamento de códigos mais rapidamente.

OpsWorks: é um serviço de gerenciamento de configurações que oferece instâncias gerenciadas do Chef e do Puppet, permitindo automatizar a forma como os servidores são configurados, implantados e gerenciados em instâncias do Amazon EC2 ou ambientes de computação no local. O OpsWorks tem três ofertas, AWS OpsWorks for Chef Automate, AWS OpsWorks for Puppet Enterprise e AWS OpsWorks Stacks.









# ISP-Toolbox
Inventário de infraestrutura com aplicação prática e didática num ambiente de provedores de Internet.

## Resumo: 
Criar uma ferramenta que facilite a elaboração do projeto inicial de um provedor de Internet é o objetivo principal deste projeto. Além disso, essa ferramenta servirá como material de estudo e teste tanto para estudantes quanto para profissionais que desejam ingressar ou já atuam no ramo de Provedores de Internet (ISP - Internet Service Provider).

O nosso produto mínimo viável (MVP) consistirá na disponibilização de um ambiente simulado, desenvolvido no software PNETlab. Dispondo de uma infraestrutura básica e organizada de ativos de rede que constitui um ISP. Esse laboratório estará disponivel para venda na loja online do próprio PNETlab.

Assim como, a relevância desse projeto vai além do âmbito educacional, uma vez que também desempenha um papel fundamental ao servir como guia para pequenos provedores de Internet. Muitas vezes, essas empresas crescem de maneira desorganizada devido à falta de ferramentas acessíveis para o gerenciamento de sua infraestrutura. Além disso, reconhecemos que a detecção de problemas na rede pode ser um desafio significativo. Tal qual a falta de planejamento adequado ao expandir a infraestrutura pode criar obstáculos consideráveis.

Portanto, nossos esforços se concentrarão em abordar conceitos pertinentes as matérias de Tecnologias de Enlace de Redes, Roteamento e Administração de Sistemas Abertos. Ao fazer isso, esperamos preencher uma lacuna importante no setor de ISPs, contribuindo para a eficiência e a ordem na expansão desses provedores. Essa iniciativa visa facilitar o processo de planejamento e crescimento destas empresas, e assim promover um setor mais coeso e eficaz.

## Introdução:
A prestão de serviço de internet está bem difundida na grande parte das regiões metropolitanas do Brasil. Mesmo assim, o mercado de ISPs (Internet Service Provider) continua em constante crescimento. Para a redação do site Infor Channel (2022), Os provedores de internet são os principais motores de desenvolvimento de Banda Larga no Brasil. Logo, ainda existem espaços e regiões que carecem desse tipo de serviço, dando espaço para o mercado de provedores continuarem crescendo.

O desafio de fornecer internet de qualidade para residências e empresas engloba vários processos e etapas, tanto em âmbitos físicos quanto lógicos. Um dos estágios mais importantes para assegurar uma boa qualidade no serviço, é o projeto inicial. De acordo com Peterson Fontes em Os desafios do ISP brasileiro (2022). "Para não ter dor de cabeça mais tarde, é imprescindível planejar o seu negócio desde o princípio e desenhar objetivos e metas claras (de vendas, financeiras, operacionais)".
Nossa proposta é desenvolver uma ferramenta que auxilie na elaboração do projeto inicial de um provedor de internet, além de servir como material de estudo e teste para alunos e profissionais da área de ISPs. Para isso, utilizaremos o PNETlab, um software capaz de emular dispositivos de rede, como roteadores, switches, firewalls, DNS, entre outros. O diferencial do nosso projeto é a criação de um ambiente prático e funcional, permitindo a aplicação de estratégias operacionais para estudo e implementação em novos provedores. Isso nos distingue dos concorrentes, pois oferecemos uma solução completa e pronta para uso no desenvolvimento e aprimoramento de ISP. Outra vantagem de nosso produto é a possibilidade de comercialização do nosso ambiente através da mesma ferramenta que utilizamos para construí-lo, o PNETlab.

## Justificativa:
A justificativa desse projeto está na integração de conhecimentos das disciplinas de Roteamento, Administração de Sistemas Abertos e Tecnologias de Enlace de Redes, com foco na criação de uma ferramenta essencial para provedores de internet. A disciplina de Roteamento aborda o conhecimento acerca das configurações de rotas e suas particularidades, englobando tópicos previstos na ementa, tais como o conceito de roteamento estático e dinâmico (1.3.1). Essa compreensão é fundamental para configurar as rotas de rede de forma eficaz, garantindo a conectividade e a otimização do tráfego. Assim como todas características e particularidades que envolvem os roteamentos entre o protocolo OSPF (2.7) e protocolo BGP (3.3). 

Administração de Sistemas Abertos fomenta os conhecimentos necessários para o gerenciamento de maneira organizacional e segura da infraestrutura. Tópicos da ementa, como personalização do armazenamento dos LOGS - Logrotate, são importantes porque permitem a gestão eficiente dos registros do sistema, ajudando na identificação de problemas e no monitoramento da rede. A configuração de um servidor de LOGS remoto (4.2) é fundamental para centralizar informações de logs, o que facilita a análise e a resposta a incidentes. Além disso, o tópico 8.5 - Backup e restore é importantíssimo, uma vez que a realização regular de backups é uma medida de segurança para preservação dos dados e a recuperação de sistemas em caso de falhas.

Por fim, Tecnologias de Enlace são aplicadas na simulação e testes de conectividade. Abrangendo a configuração de equipamentos e serviços de rede, incluindo enlaces de rede como roteadores e switches. Apresentar protocolos de enlace utilizados em LANs e WANs. Conhecer equipamentos ativos de rede que funcionam nos níveis físico e de Enlace bem como suas principais funcionalidades. Dentre os tópicos da ementa aplicados no projeto se destacam: 1 - Redes Ethernet e dependentes, 2 - Evolução das redes Ethernet, 3 - Principais equipamentos das camadas física e de enlace, 4 - Switches Ethernet, 5 - Protocolos de enlace para WANs. Do ponto de vista de relevância entre as matérias, seria esta a que mais se destacaria pelo conhecimento fomentado.   



## Objetivos gerais e específicos:
O objetivo geral deste projeto consiste em desenvolver uma ferramenta abrangente e interativa que auxilie na criação do plano inicial para provedores de internet no Brasil. Além disso, a ferramenta será utilizada como material de estudo e teste por estudantes e profissionais que desejam ingressar ou já atuam na área de ISPs. O principal propósito é simplificar a elaboração de planos de negócios, estratégias operacionais, bem como configurar os equipamentos e serviços de rede necessários para o sucesso dos provedores de internet, colaborando assim com a expansão e melhoria da qualidade dos serviços em regiões carentes.


## Objetivos específicos:
1. Desenvolvimento da ferramenta de elaboração de inventário para infraestrutura:
Desenvolver uma plataforma base que permita aos usuários a criação de uma planta estrutural, dispondo de equipamentos que constituem a base de provedores de internet. Pois, atualmente em mercado, não existe ferramentas com esta finalidade. Cujo objetivo é facilitar a elaboração do escopo inicial da infraestrutura de um ISP.   

2. Configuração de equipamentos e serviços de redes:
Integrar o PNETlab, um software que possibilita a emulação de dispositivos de rede, à plataforma. Isso permitirá que os usuários simulem configurações em equipamentos como roteadores, switches, firewalls e servidores DNS para melhor compreender seu funcionamento prático.

3. Apoio a exapansão planejada:
Essa ferramenta capacitará os provedores de internet a tomarem medidas precisas na expansão de seus serviços, proporcionando clareza quanto aos próximos passos e aos objetivos necessários para alcançá-los.

4. Testes e Simulações Práticas:
Possibilitar aos usuários a realização de simulações práticas e testes em um ambiente controlado para avaliar e aprimorar suas habilidades na configuração de dispositivos de rede. Retornando assim uma segurança de que o ambiente na qual está sendo manipulado não está em produção. Isso garante ao usuário que não haverá interferencias nos serviços que estão atuando no momento. E quando houver a certeza de que os testes lograram êxito, será possível estar aplicando em ambiente de produção.

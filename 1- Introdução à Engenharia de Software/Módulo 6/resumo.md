# Glossário de Engenharia de Software - Resumo Temático

## 1. Desenvolvimento e Metodologias
| Termo | Definição |
|-------|-----------|
| **SDLC** | Processo sistemático para desenvolver software de alta qualidade com prazo e orçamento previsíveis |
| **Waterfall** | Método sequencial onde a saída de uma fase é a entrada da próxima |
| **Agile** | Método iterativo com sprints, liberando código funcional ao final de cada ciclo |
| **V-shape model** | Método com fases de "validação" e "verificação" correspondentes |
| **MVP** | Versão básica do software para validação de premissas com stakeholders |

## 2. Papéis e Responsabilidades
| Termo | Definição |
|-------|-----------|
| **Frontend developers** | Desenvolvem a parte cliente (o que usuário vê e interage) |
| **Backend developers** | Trabalham no servidor antes do envio para o cliente |
| **Fullstack developers** | Atuam tanto no frontend quanto no backend |
| **Product owner** | Tem a visão do produto e conhece necessidades do usuário final |
| **Project manager** | Garante execução suave do projeto, lidando com planejamento e comunicação |
| **QA engineer** | Garante qualidade e que o software atenda requisitos do cliente |
| **Site reliability engineer** | Combina engenharia de software com gerenciamento de sistemas IT |
| **System architect** | Projeta e comunica a arquitetura do sistema para a equipe |
| **Technical writer** | Produz documentação para o usuário final |
| **UX designer** | Define como o software se comporta da perspectiva do usuário |

## 3. Arquitetura e Padrões
| Termo | Definição |
|-------|-----------|
| **2-tier/Client-Server** | Modelo onde servidor hospeda e gerencia recursos para o cliente |
| **3-tier** | Organiza aplicação em três camadas: apresentação, aplicação e dados |
| **Microservices** | Abordagem que quebra funcionalidade em componentes modulares |
| **Service-oriented architecture (SOA)** | Serviços fracamente acoplados que se comunicam via protocolo de rede |
| **Event-driven** | Foca em produtores e consumidores de eventos |
| **Peer-to-peer (P2P)** | Arquitetura descentralizada onde nós são clientes e servidores |
| **Component-based architecture** | Foca na decomposição do design em componentes lógicos |

## 4. Ambientes e Implantação
| Termo | Definição |
|-------|-----------|
| **Production environment** | Infraestrutura que executa e entrega aplicação ao usuário final |
| **Staging environment** | Ambiente que replica o de produção para testes finais |
| **On-premises deployment** | Organização responsável por hardware e infraestrutura local |
| **Public Cloud** | Infraestrutura na nuvem provisionada via internet |
| **Private Cloud** | Nuvem provisionada para uso exclusivo de uma organização |
| **Hybrid Cloud** | Combinação de nuvens públicas e privadas |

## 5. Componentes de Produção
| Termo | Definição |
|-------|-----------|
| **Firewall** | Previne acesso não autorizado à rede privada |
| **Load balancer** | Distribui tráfego de rede entre múltiplos servidores |
| **Proxy server** | Servidor intermediário que gerencia requisições entre camadas |
| **Database Management System (DBMS)** | Controla banco de dados conectando-o a usuários ou programas |

## 6. Desenvolvimento Frontend
| Termo | Definição |
|-------|-----------|
| **HTML** | Cria a estrutura física de websites |
| **CSS** | Define estilos, cores, fontes e layouts para websites |
| **JavaScript** | Adiciona interatividade a websites |
| **SASS/LESS** | Aprimoram CSS com variáveis, funções e organização |
| **Responsive design** | Website se redimensiona automaticamente para o dispositivo |

## 7. Conceitos de Programação
| Termo | Definição |
|-------|-----------|
| **Interpreted language** | Código executado por interpretador (ex: Python, JavaScript) |
| **Compiled language** | Código compilado em arquivo executável (ex: C++, Rust) |
| **Object-Oriented Programming (OOP)** | Foca em objetos que contêm dados e métodos |
| **Function/Method/Procedure** | Trecho de código estruturado e reutilizável |
| **Variable** | Valor que pode mudar dependendo de condições |
| **Constant** | Item de dados cujo valor não muda no programa |
| **Array** | Elementos do mesmo tipo armazenados em ordem sequencial |
| **Vector** | Similar a arrays mas com tamanho dinâmico |
| **Branching** | Lógica onde programa toma decisões baseadas em condições |
| **Loop** | Sequência de instruções que repete até condição específica |

## 8. Banco de Dados e Consultas
| Termo | Definição |
|-------|-----------|
| **SQL** | Linguagem mais popular para consultar bancos de dados |
| **Query** | Instruções pré-definidas para fazer requisições a banco de dados |
| **CRUD** | Tipos comuns de consultas: Create, Read, Update, Delete |
| **Object-Relational Mapping (ORM)** | Ferramentas para conectar e recuperar dados do banco |

## 9. Testes e Qualidade
| Termo | Definição |
|-------|-----------|
| **Unit testing** | Testa o menor componente isolável do sistema |
| **Integration testing** | Testa componentes integrados em produto maior |
| **System testing** | Teste quando aplicação é considerada completa |
| **User Acceptance Testing (UAT)** | Teste realizado pelo usuário final |
| **Functional testing** | Testa entradas e saídas sem olhar código interno |
| **Non-functional testing** | Testa atributos como performance, escalabilidade |
| **Regression testing** | Confirma que mudanças não afetam funcionalidades existentes |
| **Black-box testing** | Teste sem conhecimento da estrutura interna |
| **Test case** | Contém passos, entradas e saídas esperadas para teste |

## 10. Ferramentas e Práticas
| Termo | Definição |
|-------|-----------|
| **Git** | Repositório para controle de versão e branches |
| **IDE** | Ambiente de desenvolvimento integrado para gerenciar código |
| **CI/CD** | Práticas de integração e entrega/implantação contínuas |
| **Framework** | Fornece maneira padrão de construir e implantar aplicações |
| **Library** | Coleções de código reutilizável |
| **Package manager** | Gerencia instalação e manutenção de pacotes de software |
| **Pair programming** | Dois desenvolvedores trabalham juntos em um computador |
| **Driver/navigator** | Estilo onde um escreve código e outro revisa e direciona |
| **Ping-pong** | Estilo com desenvolvimento orientado a testes |
| **Strong style** | Estilo onde júnior aprende com desenvolvedor experiente |

## 11. Documentação e Modelagem
| Termo | Definição |
|-------|-----------|
| **UML diagrams** | Diagramas que comunicam estrutura e comportamento do sistema |
| **Pseudocode** | Ponte benéfica para o código, seguindo a lógica que será implementada |
| **SRS** | Documento que combina requisitos dos stakeholders |
| **SysRS** | Especificação de requisitos do sistema com capacidades adicionais |
| **URS** | Descreve necessidades e expectativas dos usuários finais |
| **SDD** | Coleção de especificações técnicas para implementação do design |
| **User stories** | Explicação de requisitos da perspectiva do usuário final |
| **Use cases** | Descrição de como usuário interage com o sistema |
| **SOP** | Documentação passo a passo para tarefas complexas específicas |

## 12. Conceitos Avançados
| Termo | Definição |
|-------|-----------|
| **Distributed system** | Sistema com múltiplos serviços em máquinas diferentes |
| **Encapsulation** | Agrupa dados e métodos para esconder estado interno |
| **Inheritance** | Subclasse herda propriedades e métodos da classe pai |
| **Extensibility** | Capacidade de adicionar comportamento sem mudar outros componentes |
| **API gateway** | Roteia API do cliente para serviço, orquestrando comunicação |
| **Business logic** | Dita resultados de transações e acesso a banco de dados |
| **Scalability** | Capacidade de lidar dinamicamente com carga variável |
| **Load** | Número de usuários concorrentes, transações e transferência de dados |
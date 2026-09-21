# Integrantes: 
- Anna Cecilia Guimarães Maiques Lima de Carvalho -RM: 570955
- Caio Eguia Ceschini -RM: 573847
- Gabriel Henrique S. de Melo Rodrigues - RM: 573093
- Fernando Bonfim Hoefle - RM: 569920
- Arthur de Oliveira Carvalho - RM: 573499

# Problema

Condomínios que possuem carregadores para veículos elétricos enfrentam dificuldades no gerenciamento de uso, controle de consumo energético, agendamento e cobrança dos usuários.
O nosso projeto propõe um chatbot inteligente para auxiliar síndicos e moradores no gerenciamento de carregadores elétricos em condomínios.

# Funcionalidades 

- Consulta de consumo energético
- Reserva de carregadores
- Verificação de disponibilidade
- Consulta de cobranças
- Alertas de falhas técnicas
- Histórico de conversa
- Respostas contextualizadas para o cenário
- Testes de segurança
- Proteção contra tentativas de Prompt Injection

# Tecnologias Utilizadas

Google Colab

OpenAI API 

OpenAI Agents SDK

SQLiteSession

Function Tools

Python 

Draw.io: Fluxograma 

YouTube

# Tecnologia IA utilizada:

A OpenAI API foi utilizada para fornecer os modelos de linguagem do chatbot. No projeto foi atualizado para utilizar o OpenAI Agents SDK, que organiza o funcionamento do agente e permite utilizar recursos como Agent, Runner, memória por sessão e Function Tools.
O Google Colab foi utilizado para criar, testar e executar o chatbot, no qual foram utilizados dois modelos diferentes durante os testes: "gpt-4o-mini" e "gpt-5-nano"

A comparação entre os modelos foi realizada utilizando o mesmo conjunto de testes.

# Melhorias da Sprint 3

Na Sprint 2, o histórico da conversa era controlado manualmente por meio de uma lista de mensagens. Na Sprint 3, o projeto passou a utilizar o 'OpenAI Agents SDK', com memória gerenciada por sessão utilizando 'SQLiteSession'.
Também foram adicionadas 'Function Tools' para organizar as funções do chatbot, como: consulta de consumo, consulta de cobrança, consulta de carregadores, reserva de carregadores, consulta de falhas.
A função de reserva também foi modificada para permitir que o usuário informe o número do carregador e o horário desejado.
Além disso, foram adicionados testes de segurança, incluindo testes de Prompt Injection, perguntas fora do contexto, perguntas sobre especificações técnicas não disponíveis, questões jurídicas, financeiras e de segurança elétrica.

# Como Executar o Projeto

1. Abrir o notebook no Google Colab.
2. Instalar a biblioteca OpenAI.
3. Configurar a chave da API utilizando os Secrets do Google Colab.
4. Executar todas as células do notebook.
5. Interagir com o chatbot pelo terminal de entrada.

# Configuração da API

A chave da OpenAI não deve ser armazenada diretamente no código.

O nosso projeto utiliza o recurso Google Colab Secrets para acessar a variável:
"OPENAI_API_KEY". Dessa forma, a chave permanece protegida e não é exposta no repositório.

# Relatório de evolução

[📄 Acessar o Relatório de Evolução](Relatorio_evolucao.pdf)

# Exemplo de Uso

Usuário:
Existe algum carregador disponível?

GoodCharge AI:
O carregador 1 está disponível.

Usuário: 
Posso reservar o carregador 2? 

GoodCharge AI: 
Não é possivel, poisele já está reservadoaté às 18h.

# Fluxograma

![Fluxograma](Fluxograma_GoodCharge.drawio.png) 

# Agent Modelo 

https://colab.research.google.com/drive/1K9HH_8OrJIZOVTua5ekDS9oa-dmTMwgd?usp=sharing 

# Modelo Final 

https://colab.research.google.com/drive/1sdJAWpYEzFZNSNDrnJJp23DSl-9LsN8o?usp=sharing 

# Modelo de Teste

https://colab.research.google.com/drive/1qYC9qGgdmIeXw6Agd3nHmMtVymeMBIB7?usp=sharing 

# Vídeo testes 

https://youtu.be/_NHyBWMqSGA 

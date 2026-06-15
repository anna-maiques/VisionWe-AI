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

# Tecnologias Utilizadas

Google Colab

OpenAI API 

Python 

Draw.io: Fluxograma 

YouTube

# Tecnologia IA utilizada:

A OpenAI API foi escolhida por causa da sua capacidade de compreender linguagem natural e gerar respostas contextualizadas. 
O Google Colab foi usado para criar, testar e executar o chatbot.

# Melhorias da Sprint 2

* Implementação de memória de conversa utilizando histórico de mensagens.
* Utilização de System Prompt, Few-Shot prompting e histórico de conversa.
* Testes realizados com os casos definidos na Sprint 1.

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

# Modelo Final 

https://colab.research.google.com/drive/1sdJAWpYEzFZNSNDrnJJp23DSl-9LsN8o?usp=sharing 

# Modelo de Teste

https://colab.research.google.com/drive/1qYC9qGgdmIeXw6Agd3nHmMtVymeMBIB7?usp=sharing 

# Vídeo testes 

https://youtu.be/_NHyBWMqSGA 

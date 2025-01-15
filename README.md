# 15/01/2024 - BANCO DE DADOS FUNDAMENTOS - IFRS - DAY 1

# 1. Resumo: Introdução a Bancos de Dados e Sistemas Gerenciadores

## Importância dos Bancos de Dados
- Bancos de dados são essenciais em sistemas de informação, presentes em diversos setores.
- Armazenam dados para permitir a manipulação e consulta por sistemas e usuários.
- Exemplos práticos: atendimento ao cliente e sistemas de gerenciamento.

## Dados, Informação e Conhecimento
- **Dado**: elemento bruto, sem significado imediato.
- **Informação**: dado trabalhado que possui sentido.
- **Conhecimento**: conjunto de informações organizadas e compreendidas.
- Os sistemas de informação trabalham a partir de dados para gerar conhecimento.

## Definição de Banco de Dados
- Conjunto organizado de dados armazenados eletronicamente.
- Exemplos: arquivos de texto, binários, registros, imagens, etc.
- Dados são gerenciados como uma única entidade, mas podem ser acessados individualmente conforme a estrutura definida.

## Sistema Gerenciador de Banco de Dados (SGBD)
- Intermediário entre usuários, aplicações e os dados armazenados.
- Permite operações como:
  - Inserção de novos dados.
  - Alteração de dados existentes.
  - Exclusão de dados.
  - Consulta de dados (operação mais comum).
- Usuários e aplicações não acessam diretamente os dados, mas interagem através do SGBD.

## Estrutura de Interação
1. **Usuário**: realiza solicitações (consulta, alteração, inserção, exclusão).
2. **Aplicação**: transmite as solicitações do usuário ao SGBD.
3. **SGBD**: gerencia os dados, garantindo integridade e segurança.
4. **Dados Físicos**: armazenados eletronicamente em arquivos no disco rígido.

## Funções do SGBD
- Gerencia a interação entre usuários/aplicações e os dados.
- Mantém o banco em funcionamento normal e protege os dados armazenados.
- Garante que os dados sejam manipulados de forma segura e eficiente.

# 2. Resumo: Conceitos e Arquiteturas de Banco de Dados

## Níveis de Abstração no Banco de Dados
1. **Camada Externa**:
   - Interage com o usuário e as aplicações.
   - Não acessa diretamente os arquivos de dados, apenas fornece interface para consultas, inserções e operações.

2. **Camada Lógica**:
   - Exclusiva do SGBD.
   - Cria esquemas lógicos que não existem fisicamente no disco.

3. **Camada Física**:
   - Armazena os arquivos reais no disco contendo os dados.

## Modelo Relacional de Banco de Dados
- Estabelece relações entre entidades tratadas como conjuntos.
- Oferece flexibilidade para manipular dados e relações.
- Amplamente utilizado devido à facilidade de acesso, segurança e rapidez.

## Arquiteturas de Banco de Dados
1. **Plataforma Centralizada**:
   - Banco de dados único em um "Main Frame".
   - Terminais burros (sem capacidade de processamento) acessam o banco via Main Frame.

2. **Sistema de Computador Pessoal**:
   - Banco de dados local no PC.
   - Não depende de servidores ou redes.

3. **Cliente-Servidor**:
   - Cliente realiza operações de entrada e saída.
   - Servidor central armazena e processa os dados.

4. **Banco de Dados Distribuídos**:
   - Dados espalhados por vários servidores.
   - Clientes acessam dados de qualquer servidor.

## Características de um SGBD
- **Autocontenção**:
  - Armazena dados e metadados (descrições dos dados).

- **Independência de Dados**:
  - Dados e metadados independem das aplicações que os acessam.

- **Abstração**:
  - Usuário não precisa saber como os dados são armazenados ou manipulados.

- **Visões**:
  - Limitação de acesso a determinados conjuntos de dados.

- **Controle de Transações**:
  - Garante a integridade do banco de dados.

- **Controle de Concorrência**:
  - Gerencia acessos simultâne## Conclusão
- Conceitos fundamentais sobre banco de dados, SGBD e suas propriedades foram apresentados.
- Destacou-se a importância do SGBD para abstrair detalhes e garantir integridade, segurança e desempenho.os aos mesmos dados.

## Exemplos de SGBDs
- **Comerciais**: Oracle, MySQL, PostgreSQL, SQL Server, Microsoft Access.
- O Access é simples e fácil de usar, mas possui limitações como controle de concorrência.


# 16/01/2024 - BANCO DE DADOS FUNDAMENTOS - IFRS - DAY 2


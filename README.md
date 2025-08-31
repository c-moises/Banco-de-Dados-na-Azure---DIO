# Banco-de-Dados-na-Azure---DIO
Configuração de instância de banco de dados na Microsoft Azure. 

-----------------------------------------------------------------

## Objetivos
- Criar e configurar uma instância de banco de dados no Azure.
- Praticar a documentação técnica de forma simples e clara.
- Utilizar o GitHub para compartilhar conhecimento e registrar o aprendizado.

-------------------------------------------------------------------

## Passo a Passo

### 1. Acesso ao Portal
- Entrei no portal [https://portal.azure.com](https://portal.azure.com).

### 2. Criação da Instância de Banco de Dados
- Cliquei em **“Criar um recurso”**.
- Selecionei **Banco de Dados** → **Azure SQL Database**.
- Configurei os principais campos:
  - Nome do banco: `meu-sql-dio`
  - Tipo: Banco de dados único
  - Região: `East US`
  - Grupo de Recursos: `rg-desafio-dio`
  - Usuário administrador e senha criados para acesso

### 3. Configuração Adicional
- Escolhi a camada de preço básica (para testes).
- Ativei o firewall para permitir acesso do meu IP.

### 4. Revisão e Criação
- Cliquei em **Revisar + Criar**.
- Após a validação, finalizei em **Criar**.

### 5. Teste de Conexão
- Usei o **Query Editor do Azure** para conectar ao banco.
- Criei uma tabela simples de teste para validar a instância.

-----------------------------------------------------------------------

## Conclusão
Com este desafio aprendi a:
- Criar e configurar um **Azure SQL Database**.
- Entender melhor opções como **camadas de preço, firewall e credenciais**.
- Usar o **Query Editor** para validar a criação e manipulação básica do banco.
- Documentar o processo no GitHub, facilitando revisões futuras.
- Criei uma tabela simples de teste para validar a instância.


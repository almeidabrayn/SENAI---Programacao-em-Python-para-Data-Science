# SENAI - Programação em Python para Data Science

📚 Aulas e Projeto Python para Data Science

## 🚀 Como Executar

### Pré-requisitos
- Python
- Visual Studio Code com Extensão em Python ou qualquer outro copilador Python

### Passo a Passo

1. **Importar no Eclipse**
   - Abra o Eclipse
   - `File` → `Import` → `Existing Projects into Workspace`
   - Selecione a pasta do projeto

2. **Configurar Banco de Dados**
   - Abra seu cliente SQL (MySQL Workbench, DBeaver, HeidiSQL ou similar)
   - Execute o arquivo: `sql/script_biblioteca.sql`
   - Verifique se as tabelas foram criadas corretamente

3. **Configurar Conexão**
   - Edite o arquivo: `src/util/Conexao.java`
   - Atualize: URL, usuário e senha do seu banco de dados

4. **Executar Aplicação**
   - Clique direito em `MenuPrincipal.java`
   - Selecione `Run As` → `Java Application`

## 🔧 Configuração Avançada

### Banco de Dados Alternativos
Se estiver usando XAMPP:
- Servidor: `localhost:3306`
- Usuário padrão: `root` (senha em branco)

### Dependências
- O driver JDBC está incluído em `/lib/`
- Versão do MySQL Connector: 8.0.xx

## ⁉️ Solução de Problemas
Se encontrar erros de conexão:
1. Verifique se o MySQL está rodando
2. Confira usuário/senha no `Conexao.java`

3. Teste a conexão usando outro cliente SQL

# OrdemCronologicaMarvel

## Objetivo

Listar todos os filmes e séries canônicas da Marvel para poder assistir em ordem cronológica ou de lançamento e marcar quais já foram assistidos.

## Inicialização

Ativar o ambiente virtual
```
venv\Scripts\activate
```

Instalar os pacotes requisitados
```
pip install -r requirements.txt
```

Extrair pacotes requisitados do ambiente virtual
```
pip freeze > requirements.txt
```

## Passos do projeto

### Passo 1
Pegar os dados em um csv com informações extraídas manualmente de um site e normalizar ele em uma tabela do sqlite.

### Passo 2
Automatizar a extração de dados da cronologia de algum site ou plataforma. Pesquisar aqueles que são mais confiáveis. Adicionar também as fases da Marvel nessa nova extração.

### Passo 3
Criar um CRUD para poder adicionar, ler, dar update e deletar os filmes e status via Swagger. Também deve ser possível ler em ordem cronológica e de lançamento e marcar ou desmarcar os que eu já assisti.
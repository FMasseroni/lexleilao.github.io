# Guia GitHub para Não Técnicos

Este guia foi criado para ajudar pessoas sem conhecimento técnico a utilizar o GitHub para hospedar e gerenciar o site institucional da LexLeilão.

## O que é o GitHub?

O GitHub é uma plataforma que permite armazenar, gerenciar e compartilhar código. Também oferece hospedagem gratuita para sites estáticos através do GitHub Pages.

## Passo a Passo para Publicar o Site da LexLeilão

### 1. Criar uma Conta no GitHub

1. Acesse [github.com](https://github.com)
2. Clique em "Sign up" (Cadastrar-se)
3. Preencha seu e-mail, crie uma senha e escolha um nome de usuário
4. Siga as instruções para verificar sua conta

### 2. Criar um Novo Repositório

1. Após fazer login, clique no botão "+" no canto superior direito
2. Selecione "New repository" (Novo repositório)
3. Nomeie o repositório como "lexleilao.github.io" (substitua "lexleilao" pelo seu nome de usuário)
4. Adicione uma descrição: "Site institucional da LexLeilão"
5. Mantenha a opção "Public" (Público) selecionada
6. Marque a opção "Add a README file" (Adicionar um arquivo README)
7. Clique em "Create repository" (Criar repositório)

### 3. Fazer Upload dos Arquivos do Site

1. No seu repositório, clique no botão "Add file" (Adicionar arquivo)
2. Selecione "Upload files" (Enviar arquivos)
3. Arraste todos os arquivos da pasta do site para a área de upload
   - index.html
   - styles.css
   - guia_github_para_nao_tecnicos.html
   - guia_github_para_nao_tecnicos.md
   - pasta images (se houver)
4. Adicione uma mensagem de commit: "Upload inicial do site institucional"
5. Clique em "Commit changes" (Confirmar alterações)

### 4. Ativar o GitHub Pages

1. No seu repositório, clique na aba "Settings" (Configurações)
2. No menu lateral esquerdo, clique em "Pages" (Páginas)
3. Em "Source" (Fonte), selecione "main" (principal) no dropdown
4. Selecione "/ (root)" como pasta
5. Clique em "Save" (Salvar)
6. Aguarde alguns minutos - o GitHub mostrará uma mensagem com a URL onde seu site está publicado

### 5. Configurar Domínio Personalizado (Opcional)

1. Ainda na seção GitHub Pages, digite seu domínio (ex: "lexleilao.com") no campo "Custom domain" (Domínio personalizado)
2. Clique em "Save" (Salvar)
3. Siga as instruções para configurar os registros DNS no seu provedor de domínio

## Como Editar o Site

### Editar Arquivos Diretamente no GitHub

1. Navegue até o arquivo que deseja editar no seu repositório
2. Clique no ícone de lápis (Editar) no canto superior direito do arquivo
3. Faça suas alterações no editor
4. Adicione uma mensagem de commit descrevendo suas alterações
5. Clique em "Commit changes" (Confirmar alterações)

### Editar Preços e Planos

Para editar os preços e planos no site:

1. Navegue até o arquivo `index.html` no seu repositório
2. Clique no ícone de lápis para editar
3. Localize a seção com id "planos" (use Ctrl+F e pesquise por "planos")
4. Modifique os valores de preço nas tags `<span class="price monthly">` e `<span class="price annual">`
5. Modifique as descrições e recursos conforme necessário
6. Adicione uma mensagem de commit descrevendo suas alterações
7. Clique em "Commit changes" (Confirmar alterações)

## Dicas Importantes

- **Sempre faça backup** antes de editar arquivos importantes
- **Teste as alterações** acessando seu site após cada modificação
- **Seja paciente** - as alterações podem levar alguns minutos para aparecer no site publicado
- **Use mensagens de commit descritivas** para manter um histórico claro das alterações

## Precisa de Ajuda?

Se você encontrar dificuldades, considere:

1. Consultar a [documentação oficial do GitHub Pages](https://docs.github.com/pt/pages)
2. Pedir ajuda a um colega com conhecimento técnico
3. Contratar um profissional para fazer alterações mais complexas

---

Este guia foi criado como parte do projeto LexLeilão - A Disney dos Leilões Imobiliários.

# Pearson Kit Bailey 3 - Site B2B Estático

Site institucional para venda B2B de Material Pedagógico Pearson Kit Bailey 3.

## Stack Tecnológica

- **HTML5** puro
- **CSS3** puro (sem frameworks)
- **JavaScript** vanilla (sem bibliotecas)
- **Google Fonts** (Inter)

## Estrutura de Arquivos

```
pearson-b2b-site/
├── index.html      # Estrutura HTML completa
├── style.css       # Estilos responsivos
├── script.js       # Interatividade (FAQ, animações, smooth scroll)
├── vercel.json     # Configuração de deploy Vercel
└── README.md       # Este arquivo
```

## Como fazer o deploy no Vercel

### Passo 1: Criar repositório no GitHub

1. Acesse https://github.com/new
2. Nome do repositório: `pearson-b2b-site` (ou outro nome de sua preferência)
3. Deixe como **Público**
4. **NÃO** marque "Add a README file" (já temos um)
5. Clique em **Create repository**

### Passo 2: Subir arquivos para o GitHub

No terminal, execute os seguintes comandos dentro da pasta do projeto:

```bash
# Inicializar repositório Git
git init

# Adicionar todos os arquivos
git add .

# Fazer o primeiro commit
git commit -m "Initial commit - Pearson B2B site"

# Adicionar o repositório remoto (substitua SEU_USUARIO pelo seu username do GitHub)
git remote add origin https://github.com/SEU_USUARIO/pearson-b2b-site.git

# Fazer push para o GitHub
git push -u origin main
```

Se o Git pedir suas credenciais:
- **Username**: seu username do GitHub
- **Password**: use um **Personal Access Token** (não use sua senha normal)
  - Para criar um token: https://github.com/settings/tokens/new
  - Marque a permissão `repo`
  - Copie o token e use como senha

### Passo 3: Conectar ao Vercel

1. Acesse https://vercel.com
2. Faça login com sua conta GitHub
3. Clique em **Add New...** → **Project**
4. Na lista de repositórios, encontre `pearson-b2b-site`
5. Clique em **Import**
6. **NÃO** altere nenhuma configuração (Framework Preset: Other)
7. Clique em **Deploy**

### Passo 4: Aguardar o deploy

- O Vercel fará o build e deploy automaticamente
- Em ~30 segundos, seu site estará online
- Você receberá uma URL do tipo: `https://pearson-b2b-site.vercel.app`

### Passo 5: Testar o site

1. Acesse a URL fornecida pelo Vercel
2. Teste todos os links do WhatsApp
3. Teste a responsividade (mobile e desktop)
4. Teste o FAQ (acordeão)
5. Teste o scroll suave

## Deploy futuro (atualizações)

Sempre que fizer alterações:

```bash
git add .
git commit -m "Descrição da alteração"
git push
```

O Vercel detecta automaticamente e faz o redeploy.

## Contato

**Gabriel Ferraz**
WhatsApp: (15) 99721-8883
Email: hbrielferraz@gmail.com
Sorocaba/SP

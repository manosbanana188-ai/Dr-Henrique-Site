# Site Dr. Henrique Tristão · Cirurgia Plástica

Site institucional em HTML, CSS e JavaScript puros (sem build, sem dependências).

## Estrutura
- `index.html`: página completa (início, sobre, procedimentos, atendimento, locais, contato, política de privacidade e páginas de cada procedimento por hash, ex.: `#p-rinoplastia`).
- `img/`: fotos otimizadas (WebP), imagem de compartilhamento `og.png`, favicon e versões da logo.

## Publicar no GitHub Pages
1. Crie um repositório e envie estes arquivos na raiz.
2. Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`.
3. Para domínio próprio, adicione o arquivo `CNAME` com o domínio e aponte o DNS.

## Dados a editar
Abra `index.html` e procure por `const CONFIG` (no final do arquivo):
- `uf`: UF do CRM (hoje vazio, aparece como "a confirmar").
- `locais[].endereco`: endereço completo de cada consultório.
- `whatsapp`, `instagram`, `crm`, `rqe`.

Textos ainda a confirmar na seção "Sobre": formação e trajetória. Procure por `a confirmar` no arquivo.

## Antes de divulgar
- Em `<head>`, troque `img/og.png` por URL absoluta nas tags `og:image` e `twitter:image` (ex.: `https://seudominio.com.br/img/og.png`).
- Preencha o controlador/encarregado (LGPD) na política de privacidade.
- Confirme a autorização de uso das fotografias.
- Conteúdo escrito para respeitar a Resolução CFM nº 2.336/2023: sem depoimentos, sem antes e depois, sem promessa de resultado.

## Fontes
Carregadas do Google Fonts (Instrument Serif e Figtree).

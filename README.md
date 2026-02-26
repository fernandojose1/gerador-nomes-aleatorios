# 🎯 Gerador de Nomes Aleatórios

Projeto web estático para gerar nomes de **menino**, **menina** e **pet** com filtros, histórico e favoritos.

## O que foi melhorado nesta versão

- Base de nomes ampliada em todas as categorias.
- Busca por trecho (`contém`) além de filtro por inicial.
- Filtro por comprimento máximo.
- Opção para evitar repetição recente.
- Histórico dos últimos 10 nomes (persistido na sessão).
- Favoritos persistidos em `localStorage`.
- Copiar nome com fallback para navegadores sem `navigator.clipboard`.
- Compartilhamento com `navigator.share` e fallback para WhatsApp.
- Tema claro/escuro persistente.
- Atalho: `Espaço` para gerar (sem conflitar com campos de digitação).

## Executar localmente

```bash
python3 -m http.server 4173
```

Acesse `http://localhost:4173`.

## Stack

- HTML5
- CSS3
- JavaScript (vanilla)
- Bootstrap 5
- Bootstrap Icons

## Licença

MIT

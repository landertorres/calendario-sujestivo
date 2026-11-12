# Agenda 2027 — DBV/AM, AVT/AM e AAmaR

Página web estática (um único `index.html`) com o calendário 2027:

- **DBV/AM**: agenda sugestiva dos Desbravadores
- **AVT/AM**: calendário dos Aventureiros
- **AAmaR**: calendário base da AAmaR (Igreja Local e UNoB/AAmaR) com as datas de DBV e AVT juntas

Funciona no navegador do celular (Android e iOS) e no computador, sem instalação.
Links diretos por aba: `#aamar`, `#avt` (a aba DBV/AM abre por padrão).

## Publicar no GitHub Pages

1. Crie um repositório (ex.: `agenda-2027`).
2. Envie `index.html`, `README.md` e `.nojekyll` para a raiz (branch `main`).
3. Em **Settings → Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
4. Em alguns minutos a página fica em `https://SEU-USUARIO.github.io/agenda-2027/`.

## Editar as datas

As datas estão dentro do `index.html`, na parte `<script>`:
`EV` (DBV/AM), `AV` (AVT/AM) e `CAL` (calendário base AAmaR).

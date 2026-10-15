# Site do Drehmer & Feldmann Advogados

Site estático (HTML e CSS, sem build), publicado pelo GitHub Pages a partir da branch `main`. Qualquer commit na `main` vai ao ar em um ou dois minutos.

## Regras de trabalho
- Nada vai para a `main` sem a Camila aprovar a prévia. Mostre a página antes (artifact de prévia) e só então faça o push.
- Responsáveis: Frederico Luis Streppel Drehmer (sócio, OAB/RS 89.062), Thiago Feldmann (sócio, OAB/RS 76.956), Camila Feldmann (advogada associada, OAB/RS 96.815). Sociedade: OAB/RS 10.900.
- O site é publicidade de advocacia: siga o Provimento 205/2021 da OAB. Sem promessa de resultado, sem menção a honorários ou descontos, sem tom de urgência, sem chamadas comerciais. Conteúdo informativo e sóbrio.
- Não divulgar a atividade de investimento/arrematação dos sócios junto com a advocacia.
- Ao nomear empresas, empreendimentos ou processos em textos, toda afirmação precisa de fonte pública citada.

## Estrutura e estilo
- `index.html`: página única. Cores e fontes estão nos tokens `:root` no topo do `<style>`; reutilize-os em páginas novas.
- Tipografia: Spectral (títulos) e IBM Plex Sans (texto), via Google Fonts.
- Visual: fundo branco, azul-ardósia da logo como destaque, muito espaço em branco, sem enfeites.
- Textos novos (artigos, páginas por empreendimento) viram arquivos HTML próprios com o mesmo cabeçalho e rodapé da página principal.

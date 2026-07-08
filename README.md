# SIG Assistência Social do Município do Rio de Janeiro — V1

Mapa institucional da rede de assistência social do Município do Rio de Janeiro, com CAS, CRAS e CREAS.

## Como publicar no GitHub Pages

1. Crie um repositório público no GitHub.
2. Envie todos os arquivos desta pasta para o repositório.
3. No GitHub, vá em **Settings > Pages**.
4. Em **Build and deployment**, selecione:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Clique em **Save**.
6. Após alguns instantes, o site ficará disponível em um link do tipo:
   `https://seuusuario.github.io/nome-do-repositorio/`

## Arquivos principais

- `index.html`: mapa interativo pronto para publicação.
- `dados/equipamentos.geojson`: base geográfica dos equipamentos.
- `dados/equipamentos.csv`: base tabular dos equipamentos.

## Observação técnica

As coordenadas dos equipamentos estão aproximadas por bairro/CAS e devem ser validadas por geocodificação oficial antes de uso técnico ou operacional.

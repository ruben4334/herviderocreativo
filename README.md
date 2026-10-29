# Hervidero Creativo — landing provisional

Landing temporal de **herviderocreativo.com** mientras se construye la web definitiva.
Se publica con GitHub Pages desde la rama `main` (carpeta raíz).

- `index.html` — versión activa (interactiva: cambia con la hora y esconde 5 secretos). Para previsualizar otra hora: `?hora=21.5`.
- `versiones/` — alternativas: `interactiva.html`, `fuego.html`, `naturaleza.html`, `castilla-la-mancha.html`.
  Para cambiar la portada, copia la que quieras encima de `index.html`.
- `CNAME` — dominio propio para GitHub Pages.

## DNS (GoDaddy)
- `A @` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `CNAME www` → ruben4334.github.io
- No tocar los registros MX / TXT / CNAME de Zoho Mail.

Cuando el hosting definitivo esté listo, basta con cambiar esos registros DNS.

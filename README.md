# Alloy Special FIDC — Simulador

Simulador operacional do FIDC Alloy Special. A pagina fica em **https://eduardosantos-svg.github.io/alloy-special/** e pede senha.

Os dados (cedentes, CNPJs e carteiras do Credimap) estao criptografados dentro do `index.html` com AES-256-GCM e chave derivada por PBKDF2. Sem a senha o codigo-fonte nao revela nada, e a descriptografia acontece no navegador — nada trafega para servidor.

## Atualizar

Add file -> Upload files -> arraste o `index.html` novo -> Commit changes. Em cerca de um minuto o link ja esta atualizado.

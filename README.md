# 📦 Static API

Repositorio que expone un endpoint JSON estático utilizando GitHub Pages.

Este proyecto simula una API REST simple (solo GET) devolviendo datos fijos, ideal para:

- Pruebas
- Mocking de integraciones
- Prototipos rápidos

---

## 🌐 Endpoint

https://github.com/juarezgerman/static-api/[nombre-de-archivo].json

donde [nombre-de-archivo] puede ser:
- data.json          → OK
- data-error.json    → error genérico
- data-timeout.json  → simula timeout
- data-notfound.json → 404 lógico

o los que uso por ahora:
- responder.json
- transferir.json
- adjuntar.json
- desconectar.json

POR EJEMPLO: https://juarezgerman.github.io/static-api/responder.json

Para probar con curl:
curl https://juarezgerman.github.io/static-api/responder.json

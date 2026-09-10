<p align="center">
  <img src="docs/banner.svg" alt="OpenAPI Starter banner" width="100%" />
</p>

<h1 align="center">openapi-starter</h1>

<p align="center">
  <strong>EN</strong> Minimal OpenAPI 3.x YAML example for API docs<br/>
  <strong>PT</strong> Exemplo mínimo OpenAPI 3.x YAML para docs de API
</p>

<p align="center">
  <a href="https://github.com/manansbdb/openapi-starter/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/OpenAPI-6BA539?style=for-the-badge" alt="OpenAPI" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| A **minimal OpenAPI 3.x** document plus a sample `paths` fragment for users. | Um documento **OpenAPI 3.x mínimo** e um fragmento `paths` de exemplo. |
| Copy `openapi.yaml` into your API repo and extend paths/components. | Copia `openapi.yaml` para a API e estende paths/components. |

```mermaid
flowchart LR
  A["📄 openapi.yaml"] --> B["📎 examples/paths-users.yaml"]
  B --> C["🔍 Swagger / Redoc"]
  C --> D["✅ Documented API"]
  style A fill:#6BA539,stroke:#3f6212,color:#fff
  style B fill:#0ea5e9,stroke:#0369a1,color:#fff
  style C fill:#6366f1,stroke:#4338ca,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/openapi-starter.git
cd openapi-starter
```

### 2) Copy into your API / Copia para a API

```bash
mkdir -p /path/to/your-api/openapi
cp openapi.yaml /path/to/your-api/openapi/
cp examples/paths-users.yaml /path/to/your-api/openapi/
# merge path fragments into openapi.yaml as needed
```

### Requirements / Requisitos

- `git`
- Optional: Swagger UI / Redoc / spectral (all free options exist)

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/openapi-starter.git
# open openapi.yaml — preview with any free OpenAPI viewer
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `openapi.yaml` | Root OpenAPI document |
| `examples/paths-users.yaml` | Sample paths fragment |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
openapi-starter/
├── docs/banner.svg
├── openapi.yaml
├── examples/paths-users.yaml
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb

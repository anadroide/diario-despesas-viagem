# Diário de Despesas de Viagem

App web (PWA) para registar as despesas de uma viagem: voos, estadias, comida, transportes… com totais por categoria, por local e por dia.

- Funciona offline e instala-se no telemóvel ("Adicionar ao ecrã inicial").
- Os dados ficam guardados no browser de cada pessoa; não há servidor nem conta.
- Publicada com GitHub Pages a partir deste repositório.

## App Android (APK)

A pasta `android/` contém uma app que abre a PWA. Cada push constrói o APK via GitHub Actions e publica-o na release **latest**:
`https://github.com/anadroide/diario-despesas-viagem/releases/latest`

A chave de assinatura vive nos segredos do repositório (`KEYSTORE_B64`, `KEYSTORE_PASSWORD`), nunca no código.

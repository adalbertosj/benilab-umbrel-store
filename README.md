# Benilab Umbrel Store

Loja comunitária do Umbrel com os apps do homelab **Benilab**.

## Como adicionar ao Umbrel

**App Store › ⋯ › Community App Stores**, cole o endereço abaixo e clique em **Add**:

```
https://github.com/adalbertosj/benilab-umbrel-store
```

## Apps

| App | Para que serve |
|---|---|
| **OmniView** | CFTV inteligente: ao vivo, gravação contínua, linha do tempo, IA e reconhecimento facial |
| **OmniView Ponte** | Leva as câmeras de outro servidor (webcam USB ou câmera de notebook) para o OmniView |

## Adicionar um app novo

Cada app é uma pasta `adalberto-<nome>/` com `umbrel-app.yml` (id `adalberto-<nome>`) e
`docker-compose.yml`. O id da loja (`adalberto`) é o prefixo obrigatório de todos os apps.

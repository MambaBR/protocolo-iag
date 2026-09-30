# Como verificar a autenticidade deste documento

Este documento possui assinatura digital. A assinatura garante que o texto não foi alterado e que veio de uma chave específica.

## O que você precisa

- O arquivo `PROTOCOLO-0.8.md`
- O arquivo `PROTOCOLO-0.8.md.asc` (assinatura)
- O arquivo `PROTOCOLO-0.8.md.sha256` (hash)
- O arquivo `CHAVE-PUBLICA.asc` (chave pública)
- Ferramenta PGP (GPG, OpenPGP, ou biblioteca equivalente)

## Passo 1 — Importar a chave pública

```bash
gpg --import CHAVE-PUBLICA.asc
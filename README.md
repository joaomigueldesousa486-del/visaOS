# VisaOS v1.0 (ARM64 Pro)

Sistema operacional baseado em **Alpine Linux** e **Linux Mobile (Phosh)**, otimizado para arquitetura **ARM64** com ferramentas nativas de diagnóstico, rede e gravação via Fastboot.

**Criador:** Joao Souza Neres | Engenheiro Linux

## Recursos e Comandos Nativos
- `linux` — Inicializa o ambiente Alpine Linux nativo
- `sistema` — Diagnóstico completo de hardware e recursos
- `rede` — Verificação de IP público e status de conectividade
- `gravar` — Detecção e gravação de imagens em dispositivos via Fastboot
- `matriz` — Modo visual de terminal

## Compatibilidade de Hardware (Imagem Nativa)
- **Xiaomi Pocophone F1 (`beryllium`)** — Build com interface Phosh / Wayland

## Como Baixar e Instalar
1. Acesse a aba **Releases** deste repositório e baixe a imagem oficial `.img.xz`.
2. Descompacte o arquivo (`xz -d nome-do-arquivo.img.xz`).
3. Conecte o aparelho com bootloader desbloqueado em modo Fastboot e utilize o utilitário de gravação.


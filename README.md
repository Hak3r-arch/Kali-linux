# 🐉 Kali Linux NetHunter - Instalador Automático

Este script instala la versión oficial de Kali NetHunter en Termux.

## 🚀 Instalación rápida
Copia y pega este comando en tu Termux:

```bash
pkg update -y && pkg upgrade -y && pkg install python git -y && git clone https://github.com/Hak3r-arch/kali-linux && cd kali-linux && python kali-linux.pyc
```

## 🖥️ Cómo iniciar Kali
Una vez finalizada la instalación, usa:
* `nethunter` - Para entrar a la terminal de Kali.
* `nethunter kex &` - Para iniciar el modo escritorio (GUI).

**Nota:** Se recomienda tener al menos 10GB de espacio libre.

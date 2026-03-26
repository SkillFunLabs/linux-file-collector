# 📁 Linux File Collector

> GUI tool to collect files by extension from Linux folders — bilingual (English / Portuguese)

![Python](https://img.shields.io/badge/Python-3.6%2B-blue?logo=python)
![Linux](https://img.shields.io/badge/Linux-Fedora%20%7C%20Ubuntu%20%7C%20Arch-orange?logo=linux)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green)
![License](https://img.shields.io/badge/License-MIT-green)
![Language](https://img.shields.io/badge/Language-EN%20%2F%20PT-yellow)
![Tested](https://img.shields.io/badge/Tested%20on-Nobara%20Linux-blueviolet)

---

## 🇬🇧 English

### What it does

**Linux File Collector** is a graphical tool (GUI) built in Python + Tkinter that scans a folder and copies all files matching a chosen extension into a destination folder.

Useful for quickly gathering all files of a specific type — photos, documents, audio, scripts — from a folder tree, without manually browsing every subfolder.

### Features

- 🖥️ Clean dark-themed graphical interface — no terminal needed
- 🌐 Bilingual: switch between **English** and **Portuguese** at any time
- 📂 Choose any source folder to scan (recursive)
- 🔍 Select extension from a dropdown (pdf, jpg, mp3, py...) or type a custom one
- 📁 Choose any destination folder for the collected files
- 🚫 Option to skip hidden folders (folders starting with `.`)
- ⚙️ Runs the scan in a **background thread** — UI stays responsive
- ✅ Handles **duplicate filenames** automatically (adds `_1`, `_2`, etc.)
- ❌ Cancel button to stop an ongoing scan at any time
- 📊 Summary at the end: total found, copied, and errors

### Requirements

- Python 3.6 or later
- Tkinter (usually included with Python on Linux)
- No installation required — just run the launcher

### How to use

1. Download or clone this repository
2. Open a terminal in the project folder
3. Run the launcher:
   ```bash
   bash iniciar.sh
   ```
4. The launcher will automatically check for Python 3 and Tkinter, install if missing, and open the app
5. Choose source folder, destination folder, extension, and click **START COLLECTION**

> **Note:** The launcher supports Fedora/Nobara (dnf), Ubuntu/Debian (apt), Arch (pacman), and openSUSE (zypper). Tested on **Nobara Linux**.

### Manual launch (without launcher)

```bash
python3 coletor_linux.py
```

---

## 🇵🇹 Português

### O que faz

O **Coletor de Ficheiros Linux** é uma ferramenta gráfica (GUI) feita em Python + Tkinter que varre uma pasta e copia todos os ficheiros com a extensão escolhida para uma pasta de destino.

Útil para recolher rapidamente todos os ficheiros de um determinado tipo — fotos, documentos, áudio, scripts — de uma árvore de pastas, sem ter de navegar manualmente em cada subpasta.

### Funcionalidades

- 🖥️ Interface gráfica com tema escuro — sem necessidade de terminal
- 🌐 Bilingue: muda entre **Português** e **Inglês** a qualquer momento
- 📂 Escolhe qualquer pasta de origem para varrer (recursivo)
- 🔍 Seleciona extensão num dropdown (pdf, jpg, mp3, py...) ou escreve uma personalizada
- 📁 Escolhe qualquer pasta de destino para os ficheiros recolhidos
- 🚫 Opção para ignorar pastas ocultas (pastas que começam com `.`)
- ⚙️ Executa a varredura em **segundo plano** — a interface não bloqueia
- ✅ Trata **nomes duplicados** automaticamente (adiciona `_1`, `_2`, etc.)
- ❌ Botão de cancelar para parar a operação a qualquer momento
- 📊 Resumo no final: total encontrado, copiado e erros

### Requisitos

- Python 3.6 ou superior
- Tkinter (normalmente incluído com o Python no Linux)
- Não requer instalação — basta correr o lançador

### Como usar

1. Descarrega ou clona este repositório
2. Abre um terminal na pasta do projeto
3. Corre o lançador:
   ```bash
   bash iniciar.sh
   ```
4. O lançador verifica automaticamente Python 3 e Tkinter, instala se faltar, e abre a app
5. Escolhe pasta de origem, pasta de destino, extensão e clica em **INICIAR COLETA**

> **Nota:** O lançador suporta Fedora/Nobara (dnf), Ubuntu/Debian (apt), Arch (pacman) e openSUSE (zypper). Testado em **Nobara Linux**.

### Lançamento manual (sem lançador)

```bash
python3 coletor_linux.py
```

---

## 📂 File Structure

```
linux-file-collector/
├── coletor_linux.py    # Main Python GUI application
├── iniciar.sh          # Launcher — checks dependencies and opens the app
├── LICENSE
└── README.md
```

---

## 🖥️ Compatibility

| Distro | Package Manager | Tested |
|---|---|---|
| Fedora / Nobara | dnf | ✅ Yes |
| Ubuntu / Debian | apt | ✅ Should work |
| Arch Linux | pacman | ✅ Should work |
| openSUSE | zypper | ✅ Should work |

---

## 📄 License

MIT — free to use, modify and distribute.

# 🏷️ ZPL Web Studio Desktop

O **ZPL Web Studio Desktop** é uma aplicação para visualização, edição, conversão e geração de etiquetas no padrão **ZPL (Zebra Programming Language)**. O aplicativo roda localmente no Windows com interface web embarcada e utilitários de renderização/compilação standalone.

---

## 🚀 Funcionalidades

- **Edição em Tempo Real:** Edite códigos ZPL e visualize as alterações de forma dinâmica.
- **Renderização e Suporte a Binários:** Integração nativa com utilitários auxiliares (como `labelize.exe`) para pré-visualização precisa.
- **Standalone & Portable:** Funciona como um executável único (`.exe`), sem necessidade de instalação do Python na máquina do usuário final.
- **Interface Intuitiva:** Frontend leve construído com HTML, CSS e JavaScript.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem Principal:** Python 3.x
- **Frontend / Interface:** HTML5, CSS3, JavaScript (Templates Jinja2 / Static)
- **Empacotamento:** PyInstaller
- **Utilitários Embutidos:** `labelize.exe`

---

## 📁 Estrutura do Projeto

```text
zpl_desktop/
├── desktop_app.py        # Ponto de entrada do aplicativo Python
├── build_exe.bat         # Script automatizado para geração do .exe
├── requirements.txt      # Dependências do projeto em Python
├── labelize.exe          # Executável auxiliar de suporte
├── templates/            # Arquivos HTML da interface
├── static/               # Arquivos CSS, JS e imagens
└── dist/                 # Diretório onde o executável final é gerado

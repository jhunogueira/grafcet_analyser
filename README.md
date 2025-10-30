#  Analisador SFC/GRAFCET - Manufatura Integrada

Aplicação web para análise e validação de arquivos GRAFCET em formato PLCopenXML exportados do Codesys.

## 📋 Funcionalidades

- Upload de arquivos XML (PLCopenXML)
- Validação de etapa inicial única
- Verificação de transições com condições
- Interface moderna e responsiva
- Feedback visual detalhado dos resultados

## 🚀 Como executar

### Pré-requisitos

- Python 3.7 ou superior
- pip (gerenciador de pacotes Python)

### Instalação

1. Clone ou baixe este repositório

2. Instale as dependências:
\`\`\`bash
pip install flask
\`\`\`

3. Execute a aplicação:
\`\`\`bash
python app.py
\`\`\`

4. Acesse no navegador:
\`\`\`
http://localhost:5000
\`\`\`

## 📁 Estrutura do Projeto

\`\`\`
grafcet-analyzer/
├── app.py                 # Aplicação Flask principal
├── modules/
│   └── analyser.py       # Lógica de análise do GRAFCET
├── templates/
│   ├── base.html         # Template base
│   ├── index.html        # Página inicial
│   └── resultado.html    # Página de resultados
├── static/
│   └── css/
│       └── style.css     # Estilos da aplicação
├── uploads/              # Pasta para arquivos enviados
├── .gitignore           # Arquivos ignorados pelo Git
└── README.md            # Este arquivo
\`\`\`

## 🎨 Melhorias Implementadas

### Organização
- ✅ Estrutura de pastas profissional
- ✅ Separação de lógica de negócio (módulo analyser)
- ✅ Templates com herança (base.html)
- ✅ Arquivos estáticos organizados

### Visual
- ✅ Design moderno e responsivo
- ✅ Gradientes e sombras sutis
- ✅ Feedback visual claro (sucesso, aviso, erro)
- ✅ Animações suaves
- ✅ Ícones emoji para melhor UX
- ✅ Cards com hover effects

### Funcionalidades
- ✅ Flash messages para feedback
- ✅ Validação de arquivo melhorada
- ✅ Tratamento de erros robusto
- ✅ Limite de tamanho de arquivo
- ✅ Preview do nome do arquivo selecionado
- ✅ Estatísticas de análise

## 📝 Uso

1. Acesse a página inicial
2. Leia os passos para um bom planejamento
3. Exporte seu GRAFCET do Codesys em formato XML
4. Faça upload do arquivo
5. Visualize os resultados da análise

## 🔧 Tecnologias

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3, JavaScript
- **Análise XML**: xml.etree.ElementTree

## 📄 Licença

Projeto educacional - Manufatura Integrada FMS

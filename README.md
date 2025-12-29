# 📇 Contact Connector

**Contact Connector** é uma aplicação web que permite gerar **links personalizados do WhatsApp** a partir de uma lista de contatos em Excel ou CSV.  
Ideal para uma comunicação rápida, organizada e personalizada.

🔗 **Acesse o projeto:**  
https://luccasfsilva.github.io/ContactConnector/

---

## 🚀 Funcionalidades

- 📂 Upload de arquivos **Excel (.xlsx, .xls)** e **CSV (.csv)**
- 👀 Pré-visualização dos contatos carregados
- 🧩 Uso de **placeholders** para personalização de mensagens (ex: `{name}`)
- 🔗 Geração automática de links individuais do WhatsApp
- 📱 Opção de informar seu número de WhatsApp
- ⬇️ Download dos links gerados em formato **CSV**

---

## 🧠 Como funciona

1. **Carregue o arquivo de contatos**
   - O arquivo deve conter as colunas:
     - `name`
     - `phoneNumber`

2. **Informe seu número do WhatsApp (opcional)**
   - Se preenchido, a conversa será iniciada por você
   - Se não for preenchido, o link abrirá diretamente no contato

3. **Digite a mensagem**
   - Utilize `{name}` para personalizar automaticamente cada mensagem

4. **(Opcional) Adicione um texto complementar**

5. **Clique em “Gerar Links”**

6. **Faça o download do CSV com todos os links gerados**

---

## 🗂 Estrutura do Projeto

```text
📦 ContactConnector
├── index.html        # Página principal
├── css/              # Estilos da aplicação
├── js/               # Lógica de leitura e geração dos links
├── assets/           # Imagens e ícones
└── README.md         # Documentação


## ✉️ Exemplo de Mensagem

```text
Olá {name}, tudo bem?
Estou entrando em contato para compartilhar uma novidade com você 😊




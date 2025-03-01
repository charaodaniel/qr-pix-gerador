# 📌 App para Converter Chaves Pix em QR Code e Link "Copia e Cola"

## 🎯 Objetivo
Criar um aplicativo web e/ou mobile que converta chaves Pix em QR Codes e gere o link para "Copia e Cola", permitindo fácil compartilhamento e recebimento de pagamentos de forma intuitiva e segura.

---

## 🚀 Funcionalidades Principais

### ✅ Entrada de Chave Pix
- [ ] Permitir ao usuário inserir qualquer tipo de chave Pix: CPF/CNPJ, telefone, e-mail ou chave aleatória.
- [ ] Opção para inserir um valor fixo e uma descrição opcional do pagamento.
- [ ] Validação da chave Pix para evitar erros antes da conversão.

### ✅ Geração de QR Code
- [ ] Criar um QR Code dinâmico e personalizado com a chave Pix.
- [ ] Customização do QR Code, permitindo alterar cores e adicionar um logotipo.
- [ ] Opção de baixar o QR Code como imagem PNG ou SVG.

### ✅ Geração do Link "Copia e Cola"
- [ ] Criar automaticamente o código Pix Copia e Cola.
- [ ] Botão de "Copiar para Área de Transferência" para facilitar o compartilhamento.

### ✅ Compartilhamento Rápido
- [ ] Compartilhamento do QR Code e do link Pix via WhatsApp, Telegram, e-mail e redes sociais.
- [ ] Opção de salvar o QR Code como contato na agenda para reuso rápido.

### ✅ Histórico e Favoritos
- [ ] Registro de chaves Pix já utilizadas, permitindo fácil acesso.
- [ ] Opção para marcar chaves como favoritas para reutilização.

### ✅ Segurança e Privacidade
- [ ] Criptografia dos dados para maior segurança.
- [ ] Modo anônimo para gerar QR Codes sem salvar no histórico.

---

## 💡 Melhorias e Diferenciais
- [ ] Modo escuro para melhor usabilidade.
- [ ] Suporte a múltiplos idiomas (PT-BR, EN, ES) para maior acessibilidade.
- [ ] Interface responsiva e intuitiva, adaptada para dispositivos móveis e desktops.
- [ ] Widget para sites, permitindo que empresas integrem a geração de QR Codes Pix em seus sistemas.

---

## 📱 Tecnologias Sugeridas (usando Python)

### **Backend:**
- [ ] Flask ou FastAPI para criar a API.

### **Frontend:**
- [ ] Flask com Jinja (para um app web simples).

### **Banco de Dados:**
- [ ] Firebase (para armazenar históricos).

### **Bibliotecas Python:**
- [ ] `qrcode` para geração de QR Codes.
- [ ] `pyshorteners` para encurtar links do Pix Copia e Cola.
- [ ] `cryptography` para segurança dos dados.
- [ ] `flask-cors` para permitir requisições externas no backend.

---

## 📌 Como Contribuir
1. Faça um fork do repositório
2. Clone o projeto: `git clone https://github.com/seu-usuario/seu-repositorio.git`
3. Crie uma branch: `git checkout -b nova-feature`
4. Implemente sua feature e commit: `git commit -m "Adiciona nova funcionalidade"`
5. Faça um push: `git push origin nova-feature`
6. Abra um Pull Request 🚀

---

## 📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

# Cartão de Visita Digital

Um cartão de visita digital moderno e responsivo criado com HTML e CSS puro, inspirado no design da imagem de referência fornecida.

## 📋 Características

- **Design Responsivo**: Funciona perfeitamente em dispositivos móveis e desktop
- **Degradê Moderno**: Fundo com gradiente verde similar à referência
- **Foto Circular**: Espaço para sua foto de perfil
- **Editável**: Textos podem ser editados diretamente no navegador
- **Redes Sociais**: Links para LinkedIn, Instagram, WhatsApp e GitHub
- **Animações Suaves**: Efeitos hover e transições elegantes
- **Acessibilidade**: Suporte a modo escuro e redução de movimento

## 🚀 Como Usar

### 1. Personalização Básica

1. **Substitua sua foto**: 
   - Edite o arquivo `index.html`
   - Encontre a linha: `<img src="https://via.placeholder.com/120x120/cccccc/666666?text=Sua+Foto" alt="Foto de perfil" id="profile-photo">`
   - Substitua o `src` pelo caminho da sua foto ou URL

2. **Edite as informações**:
   - Abra o `index.html` no navegador
   - Clique nos textos para editá-los diretamente
   - Ou edite diretamente no código HTML

3. **Atualize os links**:
   - Modifique os links de telefone, email e redes sociais no HTML
   - Substitua os URLs pelos seus perfis reais

### 2. Hospedagem no GitHub

1. **Crie um repositório**:
   ```bash
   # No GitHub, crie um novo repositório público
   # Nome sugerido: cartao-visita-digital
   ```

2. **Faça upload dos arquivos**:
   - `index.html`
   - `style.css`
   - Sua foto de perfil (se local)

3. **Ative o GitHub Pages**:
   - Vá em Settings > Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Clique em Save

4. **Acesse seu cartão**:
   - URL será: `https://seuusuario.github.io/cartao-visita-digital`

### 3. Gerando QR Code

1. **Use um gerador online**:
   - QR Code Generator (qr-code-generator.com)
   - QRCode Monkey (qrcode-monkey.com)
   - Google Charts API

2. **Cole a URL do GitHub Pages**

3. **Baixe o QR Code** em alta resolução

4. **Imprima ou compartilhe** o QR Code

## 🎨 Personalização Avançada

### Cores do Degradê

No arquivo `style.css`, encontre:
```css
.header-section {
    background: linear-gradient(135deg, #2d5a27 0%, #1a3d1a 100%);
}
```

Substitua pelas cores de sua preferência.

### Redes Sociais

Para adicionar/remover redes sociais, edite a seção `.social-links` no HTML e adicione os estilos correspondentes no CSS.

### Responsividade

O cartão já é responsivo, mas você pode ajustar os breakpoints no CSS:
- `@media (max-width: 480px)` - Smartphones
- `@media (max-width: 360px)` - Smartphones pequenos

## 📱 Compatibilidade

- ✅ Chrome/Edge/Safari/Firefox (versões modernas)
- ✅ iOS Safari
- ✅ Android Chrome
- ✅ Dispositivos móveis e tablets
- ✅ Impressão (layout otimizado)

## 🔧 Estrutura dos Arquivos

```
cartao-visita-digital/
├── index.html          # Estrutura principal
├── style.css           # Estilos e responsividade
├── README.md           # Este arquivo
└── foto-perfil.jpg     # Sua foto (opcional)
```

## 💡 Dicas

1. **Foto de Perfil**: Use uma imagem quadrada (1:1) para melhor resultado
2. **Textos**: Mantenha descrições concisas para melhor legibilidade
3. **Links**: Teste todos os links antes de compartilhar
4. **QR Code**: Teste o QR Code em diferentes dispositivos
5. **Backup**: Mantenha uma cópia local dos arquivos

## 🆘 Solução de Problemas

**QR Code não funciona?**
- Verifique se o repositório está público
- Confirme se o GitHub Pages está ativado
- Aguarde alguns minutos para propagação

**Foto não aparece?**
- Verifique o caminho da imagem
- Certifique-se que a imagem está no repositório
- Use URLs absolutos para imagens externas

**Layout quebrado no mobile?**
- Limpe o cache do navegador
- Verifique se não há erros no CSS
- Teste em modo incógnito

## 📞 Suporte

Se precisar de ajuda adicional, você pode:
- Verificar a documentação do GitHub Pages
- Usar ferramentas de desenvolvedor do navegador (F12)
- Consultar tutoriais sobre HTML/CSS básico

---

**Criado com ❤️ usando HTML e CSS puro**


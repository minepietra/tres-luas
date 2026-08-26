# 🌙 TRÊS LUAS

**App de metas compartilhadas para você, sua irmã e mãe**

---

## ✨ Funcionalidades

### 🎯 Metas
- **6 Metas Diárias:**
  - 💪 Exercício físico
  - 🧘 Meditação/Exercício de respiração
  - 📖 Ler
  - 🦉 Duolingo
  - 📚 Estudar
  - ✨ Mantra

- **1 Meta Semanal:**
  - 🎨 Praticar um hobbie

### 📊 Dashboard
- Visualize o progresso de cada pessoa
- Veja quantas metas foram completadas na semana
- Motivação positiva (mostra só o que foi feito)

### 💬 Comentários
- Deixe mensagens de motivação para suas companheiras
- Sistema de comentários em tempo real

### 🔐 Admin
- **Só você (Adamine)** pode:
  - Editar a frase motivacional semanal
  - Gerenciar metas fixas
  - Configurar a app

### 📱 Mobile-First
- Funciona perfeitamente no smartphone
- Instala como um app de verdade (PWA)
- Funciona offline

---

## 🎨 Design

**Paleta de Cores:**
- Amarelo Manteiga: `#F5E6D3`
- Marrom Chocolate: `#6B4423`
- Creme: `#FBF8F3`

**Logo:** Três Luas com o texto "Juntas somos mais fortes"

---

## 🚀 Como Colocar no Ar

### Pré-requisitos:
- Conta Google ou GitHub
- 10 minutos do seu tempo

### Passo-a-Passo:
1. **Criar conta Supabase** (gratuito) → https://supabase.com
2. **Criar projeto** no Supabase
3. **Copiar as chaves** (URL + anon key)
4. **Fazer deploy** na Vercel (gratuito) → https://vercel.com

**Instruções detalhadas:** Veja `INSTRUCOES.md`

---

## 🔑 Credenciais de Demo

Para testar agora:

```
Email: adamine@example.com
Senha: senha123
(Adamine tem acesso ao painel admin)

Email: irma@example.com
Senha: senha123

Email: mae@example.com
Senha: senha123
```

---

## 📂 Estrutura do Projeto

```
tres-luas/
├── public/
│   ├── index.html
│   ├── manifest.json (PWA)
│   └── service-worker.js
├── src/
│   ├── index.js
│   └── tres-luas-app.jsx (componente principal)
├── package.json
└── README.md
```

---

## 🔄 Sincronização em Tempo Real

Quando configurar o Supabase:
- Mudanças de uma pessoa aparecem pra todas na hora
- Comentários sincronizam instantaneamente
- Sem necessidade de recarregar a página

---

## 🛠️ Tecnologias Usadas

- **React 18** - Interface
- **Supabase** - Banco de dados + autenticação
- **Vercel** - Deploy e hospedagem
- **PWA** - App instalável no celular

---

## 📝 Personalização

Você pode personalizar:
- ✅ Cores (amarelo, marrom, creme podem ser ajustados)
- ✅ Logo (sua imagem das 3 luas)
- ✅ Metas (adicionar/remover categorias)
- ✅ Frase motivacional (muda toda semana)
- ✅ Nomes de usuários

---

## 🎯 Roadmap Futuro

- [ ] Notificações push no celular
- [ ] Compartilhar progresso em stories
- [ ] Relatórios mensais em PDF
- [ ] Sistema de pontos/badges
- [ ] Integração com calendário
- [ ] Modo escuro

---

## 💚 Desenvolvido com Love

Para Adamine, sua irmã e sua mãe.

**Juntas somos mais fortes! 🌙✨**

---

## ❓ Dúvidas?

Qualquer coisa, avisa! Tô aqui pra ajudar.

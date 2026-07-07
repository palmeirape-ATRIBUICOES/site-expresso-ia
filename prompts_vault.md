# 🛡️ Biblioteca de Prompts (Prompt Vault) - Site Expresso com IA

Bem-vindo à sua biblioteca oficial de prompts! Copie e cole os prompts abaixo no seu assistente de Inteligência Artificial (Gemini, Claude, ChatGPT) para criar layouts específicos, seções ou refinar seu site de forma profissional.

---

## 1. Prompt Completo para Landing Page de Alta Conversão
Use este prompt para criar uma Landing Page inteira com design moderno e textos persuasivos.

```text
Você é um designer de produto e desenvolvedor front-end de elite.
Crie o código de uma Landing Page responsiva para o nicho de [Nicho do Seu Negócio].
Instruções técnicas:
1. Gere o arquivo "index.html" estruturado e o "index.css" separado com design moderno.
2. Paleta de cores: fundo dark mode (#090D1A), acentos em azul brilhante (#00C6FF) e tons de cinza claro para textos de leitura.
3. Seções a incluir:
   - Header simples com logo fictício e links de navegação ancorados.
   - Hero Section com Headline de forte impacto, botão de chamada para ação (CTA) chamativo e trust badges.
   - Grade de diferenciais (Grid) com 3 cards limpos sobre por que escolher o serviço.
   - Seção de Depoimentos estilizada em formato de cards de avaliação.
   - Accordion de FAQ interativo funcional com CSS/JS simples.
4. Garanta responsividade completa para aparelhos celulares.
```

---

## 2. Prompt para Refinar Cores e Estética (Glassmorphism / Premium)
Se você já tem o site, mas quer dar um visual mais moderno, semelhante a sites da Apple ou Stripe, envie este prompt junto com seu código CSS atual:

```text
Quero que você atualize as regras visuais do CSS fornecido para aplicar um efeito moderno de "Glassmorphic Premium".
Ajustes desejados:
1. Adicione um leve fundo semitransparente com desfoque nos cards: `background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.08);`.
2. Troque os cantos pontiagudos por cantos arredondados elegantes (`border-radius: 16px` ou `24px`).
3. Adicione uma sutil transição suave nos botões e links ao passar o mouse (`transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1)`).
4. Forneça apenas o arquivo CSS atualizado.
```

---

## 3. Prompts por Nicho Específico

### 🩺 Nicho: Saúde e Clínicas (Médicos, Psicólogos, Dentistas)
```text
Crie uma página de agendamento e apresentação clínica.
Foco: Passar autoridade, segurança e empatia.
Paleta recomendada: Fundo claro/clean (#F8FAFC), detalhes em azul marinho (#1E3A8A) e acentos em verde menta (#34D399).
Seções principais: Biografia com foto simulada, especialidades clínicas estruturadas em cards e botão direto integrado para agendar consulta via WhatsApp.
```

### 🍔 Nicho: Hamburguerias e Alimentação
```text
Crie uma página web para uma hamburgueria artesanal de alta qualidade.
Foco: Despertar o apetite visual imediato e facilitar o pedido.
Paleta recomendada: Modo escuro com tons de laranja/brasa (#F97316) e vermelho escuro.
Seções: Destaques do cardápio com preços simulados, horário de funcionamento com status "Aberto agora" dinâmico e link direto para o delivery digital.
```

### 📈 Nicho: Consultoria e Serviços Corporativos (Advogados, Contadores)
```text
Crie um site institucional moderno para prestação de serviços de [Consultoria/Advocacia].
Foco: Seriedade, sofisticação e conversão de leads qualificados.
Paleta recomendada: Tons de azul royal profundo, cinza grafite e detalhes dourados/âmbar para botões.
Seções: Áreas de atuação com descrição sucinta, botão para agendar avaliação estratégica e formulário simples de contato.
```

---

## 4. Prompt para Criar Botão Flutuante de WhatsApp
Adicione um botão fixo no canto inferior direito do site para que as pessoas possam falar com você a qualquer momento:

```text
Gere o código HTML e CSS de um botão flutuante redondo do WhatsApp para ficar fixado no canto inferior direito da tela.
O botão deve conter o ícone do WhatsApp (pode usar SVG simples ou link de imagem externa) e subir suavemente com um leve hover effect ao passar o mouse.
```

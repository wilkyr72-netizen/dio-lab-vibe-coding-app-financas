# 💸 App de Finanças Pessoais do Wesley com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural.  
O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

---

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**.  
Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**.  

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

---

## 🎯 Desafio

**Problema:** Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso.  

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**.  
Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]  
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

---

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê.  
Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue.  
Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o **Copilot Web** para revisar e melhorar o seu prompt antes de ir ao **Lovable**.  
A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]  
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”.  
> Quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

---

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação.  
Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo.  

Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;  
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta.  

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. **Agente Financeiro:** defina o comportamento e o tom de voz de um consultor financeiro pessoal.  
2. **Fluxo de Telas:** peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD.  
3. **Plano de MVP:** solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial.  

> [!TIP]  
> Se preferir, você pode fazer tudo com o **Copilot**.  
> O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

---

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua interações com o Lovable:

> Cria um app de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): (PRD)  
> Tentei criar uma meta chamada Reserva de Emergência, mas ela não apareceu no componente.  
> A impressão que tive foi que apenas o Assistente Financeiro a reconheceu, poderia verificar?  
> Além disso, onde vejo os gráficos e extrato?  
> Sim (Quer que eu adicione uma tela de relatórios com gráficos e extrato detalhado das transações?)  

**Resultado Final no Lovable:**  
https://conversa-fin-amigo.lovable.app/

<img width="1900" height="945" alt="image" src="https://github.com/user-attachments/assets/4f814684-08f5-48b9-9c64-47287d3d1c3e" />

---

## 🧾 Resumo das Funcionalidades do App

Este aplicativo de Finanças Pessoais Conversacional foi pensado para oferecer uma experiência simples, acessível e inteligente para quem deseja organizar seus gastos sem complicação.

### 🔐 Autenticação
- Tela de login com campos de **email** e **senha**.  
- Opção de **cadastro** para novos usuários.  
- Interface clara e acolhedora, com boas práticas de usabilidade.  

### 💬 Interface Conversacional
- Interações por **chat em linguagem natural**, simulando uma conversa com um consultor financeiro.  
- Registro de gastos direto no chat (ex.: “gastei R$30 no restaurante”).  

### 🧠 Inteligência Financeira
- **Classificação automática** das transações por categoria.  
- **Definição e acompanhamento de metas financeiras**.  
- Envio de **dicas personalizadas de economia** por um “Agente Financeiro Inteligente”.  

### 📊 Relatórios Visuais
- Geração de **relatórios simples e personalizados** com gráficos e resumos dos gastos.  
- Visualização clara do progresso em relação às metas.  

### ♿ Design Universal
- Interface acessível e inclusiva, pensada para funcionar bem para **todos os perfis de usuários**:  
  - Textos claros e linguagem simples.  
  - Botões grandes e fáceis de clicar.  
  - Contraste adequado para leitura.  
  - Navegação intuitiva e suporte a diferentes dispositivos.  

---

> Este conjunto de funcionalidades foi estruturado com base nos princípios do **Vibe Coding** e no PRD revisado, priorizando clareza, empatia e criatividade na solução de problemas reais.

---

## 📝 Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.  

### O que não funcionou como o esperado?
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valor para aprender mais sobre Vibe Coding.  

### O que aprendi sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa: quanto mais detalhes e clareza você dá, melhor é a interação.  


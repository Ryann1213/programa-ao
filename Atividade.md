

---

# 📘 Atividade: Mandando Bem no Git e GitHub

## **1. Análise de um Histórico de Commits**

Fui lá no GitHub, escolhi um projeto que achei interessante (pode ser qualquer um de sua escolha, tipo um jogo em JavaScript ou um site bonito em React) e fui direto na aba de **Commits**.

### Peguei 3 commits e analisei assim:

**Commit 1:**

* **Mensagem:** `fix: corrigido bug no formulário de login`
* **Arquivos alterados:** `login.js`, `style.css`
* **Motivo:** Provavelmente o botão de login não tava funcionando direito ou não tava validando o que o usuário digitava.
* **Impacto no projeto:** Corrigir isso ajudou a deixar o site mais confiável e funcional. Ninguém merece digitar tudo e dar erro, né?

**Commit 2:**

* **Mensagem:** `feat: adiciona modo escuro ao site`
* **Arquivos alterados:** `style.css`, `script.js`
* **Motivo:** Melhorar a experiência do usuário. Modo escuro virou moda e é top pra não forçar a vista.
* **Impacto:** Deixou o projeto mais moderno e atrativo.

**Commit 3:**

* **Mensagem:** `refactor: separa funções de login em outro arquivo`
* **Arquivos alterados:** `login.js`, `auth.js`
* **Motivo:** Melhorar a organização do código. Quando tudo tá num arquivo só, vira bagunça.
* **Impacto:** Deixa o projeto mais fácil de manter e entender.

## **2. A Importância das Mensagens de Commit**

A mensagem de commit é tipo o "diário" do que foi feito no código. Quando você escreve uma mensagem clara, ajuda todo mundo a entender o que rolou ali.

### Por que é importante:

* Se o projeto der ruim no futuro, a gente olha os commits pra descobrir onde começou o problema.
* Equipe grande? Todo mundo precisa entender o que você mudou sem ter que ler o código inteiro.
* Mensagem mal escrita = confusão certa.

### Exemplos:

* **Boa mensagem:** `fix: resolve erro ao salvar perfil do usuário`

  * Direta, diz o que foi feito e onde.
* **Ruim:** `arruma coisa`

  * Coisa? Que coisa? Ninguém vai saber o que foi feito.

---

## **3. O Conceito de Branching**

### O que é uma **branch**?

É tipo uma “linha paralela” do projeto onde você pode testar coisas novas sem mexer no projeto principal.

### Pra que serve?

* Criar uma branch te deixa livre pra fazer modificações sem medo de quebrar o projeto principal.
* Ideal pra quando você quer testar uma nova funcionalidade ou corrigir um bug.

### Como funciona:

* Você cria uma branch (`git checkout -b nova-funcionalidade`)
* Mexe o quanto quiser.
* Depois, se tudo estiver funcionando, junta com a principal (`git merge`).

### Exemplo prático:

Imagina que você tá criando um site e quer adicionar um sistema de comentários. Em vez de sair mexendo no código principal, você cria uma branch só pra isso (`comentarios-feature`). Assim, se der ruim, o resto do site segue funcionando de boa.

---


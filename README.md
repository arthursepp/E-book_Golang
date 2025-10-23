# 🐹 Go: É Simples, Mas Não É Fácil  

> Um e-book introdutório sobre programação com Golang — direto, didático e cheio de exemplos práticos.

---

## “Go é sobre clareza, e clareza é o primeiro passo para dominar a complexidade.”

## 📘 Sobre o E-book

Este e-book foi criado com o objetivo de apresentar os **fundamentos essenciais da linguagem Go**, de maneira simples, clara e com exemplos reais.

Com ele, você aprenderá a usar os blocos mais importantes da linguagem — **variáveis, tipos, funções e pacotes** — para criar aplicações bem estruturadas e com código limpo.

> 🧠 *“Simples não significa fácil — mas o Go foi feito para tornar o aprendizado leve, lógico e divertido.”*

---

## 🧭 Estrutura do Conteúdo

O e-book é dividido em **5 capítulos curtos**, com foco em exemplos práticos e contextos do mundo real:

### 1️⃣ Tipos e Variáveis: Entendendo Seus Dados  
Aprenda como o Go lida com números, textos e valores lógicos — e entenda por que o compilador forte do Go evita erros comuns de forma inteligente.

### 2️⃣ Tipos Compostos: Estruturando Informações  
Descubra como usar **slices** e **structs** para representar listas e entidades reais (como produtos, usuários e pedidos) de forma organizada e eficiente.

### 3️⃣ Funções: O Coração do Go  
Entenda como criar funções reutilizáveis, tratar erros e manter seu código limpo e modular.

### 4️⃣ Pacotes: Organizando Seu Código  
Aprenda a separar responsabilidades e reaproveitar código criando seus próprios pacotes — o segredo de qualquer projeto Go profissional.

### 5️⃣ Conectando Tudo: Pacotes + Funções + Tipos  
Um projeto final que junta tudo o que você aprendeu, mostrando na prática como essas partes se integram para formar uma aplicação completa.

---

## 🧩 Exemplo de Código

```go
package loja

type Produto struct {
    Nome  string
    Preco float64
}

func (p Produto) PrecoComDesconto(desconto float64) float64 {
    return p.Preco - (p.Preco * desconto / 100)
}
```

🛠️ Tecnologias

* Go (Golang) — linguagem principal do conteúdo

* Markdown / LaTeX / PDF — formato de estruturação do e-book

* Inteligência Artificial (ChatGPT) — utilizada para a geração e revisão de conteúdo
---

🧠 Autor

Arthur Souza Sepp
📍 Desenvolvedor e entusiasta de Golang
🔗 github.com/arthursepp

---

⚠️ Aviso

Este conteúdo foi gerado com apoio de Inteligência Artificial para fins de estudo e pesquisa.
Pode conter erros ou simplificações conceituais.
O objetivo é didático: facilitar o aprendizado inicial da linguagem Go.

---

📚 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para estudar, compartilhar e adaptar o material, desde que cite a fonte.

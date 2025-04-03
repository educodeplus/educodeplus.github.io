# Lição 3: Variáveis e Tipos de Dados Básicos

---

## 1. Recapitulação das Lições Anteriores

**Lição 1: Boas-Vindas e Metodologia do Curso**  
- Apresentamos o curso, explicamos a metodologia e como fazer uma cópia do notebook para edição.  
- Você aprendeu a utilizar o Google Colab e a estrutura de atividades com templates e asserts.

**Lição 2: Primeiros Passos com Google Colab e Python**  
- Exploramos o ambiente do Google Colab e os comandos básicos do Python.  
- Praticamos a impressão de mensagens, a criação de variáveis e operações aritméticas simples, utilizando templates para preencher e asserts para validação.

---

## 2. Introdução às Variáveis

Em Python, **variáveis** são usadas para armazenar dados que podem ser utilizados e manipulados ao longo do seu código. Pense nas variáveis como "caixinhas" onde você guarda informações que poderão ser usadas posteriormente.  

**Exemplos de variáveis:**
- **Inteiros (int):** Números inteiros, como `5`, `10` ou `-3`.
- **Números de Ponto Flutuante (float):** Números com casas decimais, como `3.14` ou `2.0`.
- **Strings (str):** Sequências de caracteres, como `"Olá"` ou `"EduCodePlus"`.

---

## 3. Tipos de Dados Básicos

Vamos ver na prática como criar variáveis e verificar seus tipos usando a função `type()`.

```python
# Exemplo: criação de variáveis e verificação dos seus tipos

# Variável inteira
numero_inteiro = 10
print("Número Inteiro:", numero_inteiro, "- Tipo:", type(numero_inteiro))

# Variável float (ponto flutuante)
numero_float = 3.14
print("Número Float:", numero_float, "- Tipo:", type(numero_float))

# Variável string
texto = "Aprender Python é divertido!"
print("Texto:", texto, "- Tipo:", type(texto))
```

---

## 4. Atividade 1: Criação de Variáveis

**Objetivo:**  
Crie três variáveis:  
- `idade`: armazene um número inteiro representando sua idade.  
- `altura`: armazene um número float representando sua altura (por exemplo, `1.75`).  
- `nome`: armazene uma string com o seu nome.

**Instruções:**  
Preencha o código template abaixo substituindo os `"..."` pelos valores correspondentes:

```python
# Preencha os valores nas variáveis
idade = ...    # Insira sua idade como um número inteiro
altura = ...   # Insira sua altura como um número float, ex: 1.75
nome = "..."   # Insira seu nome

# Exibe os valores e seus tipos
print("Nome:", nome)
print("Idade:", idade, "- Tipo:", type(idade))
print("Altura:", altura, "- Tipo:", type(altura))
```

### Verificação da Atividade 1

Execute o código abaixo para validar se as variáveis foram preenchidas corretamente:

```python
# Verificação da atividade de criação de variáveis
assert type(idade) == int, "A variável 'idade' deve ser um número inteiro."
assert type(altura) == float, "A variável 'altura' deve ser um número float."
assert type(nome) == str and nome != "..." and nome.strip() != "", "A variável 'nome' deve ser uma string válida."
print("Atividade 1: Variáveis criadas corretamente!")
```

---

## 5. Resumo da Lição 3

Hoje você aprendeu:
- O que são variáveis e como elas funcionam no Python.
- Os principais tipos de dados básicos: inteiros, floats e strings.
- Como criar variáveis e verificar seus tipos utilizando a função `type()`.
- A importância da prática e da repetição para fixar os conceitos aprendidos.

---

## 6. Próximos Passos

Na próxima lição, daremos continuidade explorando mais profundamente os **operadores aritméticos** e como utilizá-los para realizar operações matemáticas. Continue praticando e revisando os conceitos para fortalecer sua compreensão.

Bom aprendizado e até a próxima lição!

# Lição 2: Primeiros Passos com Google Colab e Python

Nesta lição, vamos explorar o ambiente do Google Colab e dar os primeiros passos com a linguagem Python. Você aprenderá como executar comandos simples, utilizar variáveis e realizar operações aritméticas básicas. Vamos também colocar a mão na massa com atividades práticas!

---

## 1. Explorando o Google Colab

O Google Colab é uma ferramenta online que permite executar código Python diretamente no navegador. Algumas dicas para usar o Colab:

- **Executar células:** Clique no botão de "play" à esquerda de cada célula ou pressione `Shift + Enter`.
- **Adicionar novas células:** Use o menu ou os atalhos para inserir novas células de código ou texto.
- **Salvar alterações:** Lembre-se que você já fez uma cópia do notebook na Lição 1; todas as suas edições serão salvas nesse arquivo.

---

## 2. Noções Básicas de Python

Python é uma linguagem de programação conhecida por sua simplicidade e clareza. Nesta lição, você verá:

- **Impressão de mensagens:** Usando a função `print()`.
- **Criação de variáveis:** Armazenando dados para uso posterior.
- **Operações aritméticas simples:** Como adição, subtração, multiplicação e divisão.

---

## 3. Exemplo: Imprimindo uma Mensagem

Vamos começar com um exemplo simples. Execute o código abaixo para imprimir uma mensagem na tela:

```python
# Exemplo simples: imprimindo uma mensagem
print("Olá, seja bem-vindo(a) ao EduCodePlus!")
```

---

## 4. Atividade 1: Personalize sua Mensagem

**Objetivo:** Crie uma variável chamada `mensagem` e atribua a ela uma mensagem personalizada. Em seguida, imprima essa mensagem.

Edite o código abaixo substituindo os `"..."` pela sua mensagem:

```python
# Preencha sua mensagem personalizada
mensagem = "..."  # Insira aqui sua mensagem

# Imprime a mensagem personalizada
print(mensagem)
```

### Verificação da Atividade 1

Execute o código de verificação abaixo para confirmar que você inseriu sua mensagem corretamente:

```python
# Verificação simples para a atividade 1
assert mensagem != "..." and mensagem.strip() != "", "Por favor, insira uma mensagem personalizada na variável 'mensagem'."
print("Atividade 1: Mensagem personalizada correta!")
```

---

## 5. Introdução às Operações Aritméticas

Em Python, você pode realizar operações matemáticas básicas. Vamos ver um exemplo:

```python
# Exemplo de operação aritmética
a = 5
b = 3
resultado = a + b
print("Soma:", resultado)
```

---

## 6. Atividade 2: Calcule uma Soma

**Objetivo:** Utilize duas variáveis, `numero1` e `numero2`, e crie uma terceira variável `soma` que armazene a soma dos dois números.

Complete o código abaixo:

```python
# Preencha os valores e a operação de soma
numero1 = 10
numero2 = 15
soma = ...  # Insira a operação correta para somar numero1 e numero2

print("A soma é:", soma)
```

### Verificação da Atividade 2

Use o código a seguir para verificar se a soma foi calculada corretamente:

```python
# Verificação da atividade 2
assert soma == numero1 + numero2, "Verifique a operação de soma. Ela não está correta."
print("Atividade 2: Soma correta!")
```

---

## 7. Resumo da Lição 2

Hoje você aprendeu:
- Como navegar e executar comandos no ambiente do Google Colab.
- Noções básicas da linguagem Python, como imprimir mensagens e criar variáveis.
- Como realizar operações aritméticas simples e validar suas respostas com asserts.

---

## 8. Próximos Passos

Na próxima lição, aprofundaremos mais no mundo do Python, explorando outros tipos de dados e continuando a praticar com atividades que reforçam o aprendizado.

Bom trabalho e até a próxima lição!

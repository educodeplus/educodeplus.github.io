# Lição 4: Operadores Aritméticos e Expressões

---

## 1. Recapitulação das Lições Anteriores

**Lição 1: Boas-Vindas e Metodologia do Curso**  
- Apresentação do curso, explicação da metodologia e orientações para fazer uma cópia do notebook.

**Lição 2: Primeiros Passos com Google Colab e Python**  
- Exploração do ambiente do Google Colab, execução de comandos simples, criação de variáveis e operações aritméticas básicas.

**Lição 3: Variáveis e Tipos de Dados Básicos**  
- Conceito de variáveis e os principais tipos de dados (inteiros, floats e strings).  
- Verificação dos tipos utilizando a função `type()`.

---

## 2. Introdução aos Operadores Aritméticos

Em Python, os operadores aritméticos permitem realizar cálculos e manipulações numéricas. Vamos conhecer alguns dos principais operadores:

- **Adição (`+`)**: Soma dois valores.
- **Subtração (`-`)**: Subtrai um valor de outro.
- **Multiplicação (`*`)**: Multiplica dois valores.
- **Divisão (`/`)**: Divide um valor por outro (o resultado é sempre um float).
- **Divisão Inteira (`//`)**: Divide e retorna apenas a parte inteira do resultado.
- **Módulo (`%`)**: Retorna o resto da divisão entre dois números.
- **Exponenciação (`**`)**: Calcula a potência de um número.

---

## 3. Exemplos de Expressões Aritméticas

Vamos ver alguns exemplos na prática:

```python
# Exemplo de adição
soma = 8 + 12
print("Soma:", soma)

# Exemplo de subtração
diferenca = 20 - 5
print("Diferença:", diferenca)

# Exemplo de multiplicação
produto = 4 * 3
print("Produto:", produto)

# Exemplo de divisão (resultado float)
divisao = 15 / 2
print("Divisão:", divisao)

# Exemplo de divisão inteira
divisao_inteira = 15 // 2
print("Divisão Inteira:", divisao_inteira)

# Exemplo de módulo
resto = 15 % 2
print("Resto:", resto)

# Exemplo de exponenciação
potencia = 2 ** 3
print("Potência:", potencia)
```

---

## 4. Atividade Prática: Complete as Expressões

**Objetivo:**  
Complete as expressões nos códigos abaixo substituindo os `"..."` para que as operações sejam realizadas corretamente.

### Atividade 1: Soma e Multiplicação

Preencha o código para que a variável `resultado1` receba o resultado da soma de 7 e 5, multiplicado por 3.

```python
# Complete a expressão abaixo:
resultado1 = (7 + 5) * 3
print("Resultado 1:", resultado1)
```

### Verificação da Atividade 1

```python
assert resultado1 == (7 + 5) * 3, "Verifique sua operação para 'resultado1'. O valor esperado é 36."
print("Atividade 1: Operação correta!")
```

### Atividade 2: Divisão e Módulo

Preencha o código para que a variável `resultado2` receba o valor da divisão de 50 por 8 e, em seguida, armazene em `resto2` o resto dessa divisão inteira.

```python
# Complete as expressões abaixo:
resultado2 = 50 / 8      # Divisão comum (resultado float)
resto2 = 50 % 8          # Resto da divisão

print("Resultado 2 (Divisão):", resultado2)
print("Resto 2 (Módulo):", resto2)
```

### Verificação da Atividade 2

```python
assert abs(resultado2 - 6.25) < 1e-6, "Verifique a operação de divisão para 'resultado2'. O valor esperado é 6.25."
assert resto2 == 2, "Verifique a operação de módulo para 'resto2'. O valor esperado é 2."
print("Atividade 2: Operações corretas!")
```

---

## 5. Desafio

### Desafio Parte 1: Corrija o Código Errado

O código abaixo foi escrito para calcular a média de três números: 12, 18 e 24. Entretanto, a operação não está utilizando os parênteses de forma correta, o que gera um resultado equivocado.

**Instrução:**  
Corrija o código para que a média seja calculada corretamente e o valor 18 seja armazenado na variável `media_corrigida`.

```python
# Código com erros:
media_errada = 12 + 18 + 24 / 3

# Sua correção:
media_corrigida = ...  # Corrija a operação para calcular a média corretamente

# Verificação:
assert media_corrigida == 18, "Desafio Parte 1: O valor de 'media_corrigida' deve ser 18."
print("Desafio Parte 1: Código corrigido com sucesso!")
```

---

### Desafio Parte 2: Crie uma Expressão Aritmética

Crie uma expressão única que realize as seguintes operações em sequência:
1. Divida 100 por 4.
2. Multiplique o resultado por 3.
3. Some 5 ao resultado final.

Atribua o valor final à variável `resultado_desafio`.

```python
resultado_desafio = ...  # Crie sua expressão única para realizar as operações descritas

# Verificação:
assert resultado_desafio == 80, "Desafio Parte 2: O valor de 'resultado_desafio' deve ser 80."
print("Desafio Parte 2: Expressão criada com sucesso!")
```

---

## 6. Resumo da Lição 4

Nesta lição você aprendeu:
- Os principais operadores aritméticos em Python e como usá-los.
- Como criar e avaliar expressões aritméticas simples.
- A importância da ordem das operações, utilizando parênteses para definir a sequência correta.

---

## 7. Próximos Passos

Na próxima lição, começaremos a trabalhar com estruturas de dados, dando início ao estudo das listas, que permitirão organizar e manipular conjuntos de valores de forma prática.

Bom trabalho e continue praticando os conceitos de hoje!

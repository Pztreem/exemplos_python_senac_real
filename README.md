# 📚 Exercícios em Python

Este repositório contém dois programas simples em Python utilizando estruturas condicionais (`if`, `elif` e `else`).

---

# 📄 nota.py

Programa que solicita a nota de um aluno e mostra o conceito correspondente.

## ✅ Funcionamento

- Nota ≥ 90 → `A - Excelente`
- Nota ≥ 80 → `B - Muito Bom`
- Nota ≥ 70 → `C - Bom`
- Nota ≥ 60 → `D - Regular`
- Nota < 60 → `F - Reprovado`

## ▶️ Exemplo

```bash
digite a nota do aluno: 85
B - Muito Bom
```

## 💻 Código utilizado

```python
import os
os.system('cls')

nota = float(input("digite a nota do aluno:    "))

if nota >= 90:
    print ('A - Excelente')
elif nota >= 80:
    print ('B - Muito Bom')
elif nota >= 70:
    print ('C - Bom')
elif nota >= 60:
    print ('D - Regular')
else:
    print ('F - Reprovado')
```

---

# 📄 renata.py

Programa que pergunta se há aula no período da tarde.

## ✅ Funcionamento

- Resposta `sim` → `Estou fora`
- Resposta `nao` → `Estou dentro`
- Qualquer outra resposta → `resposta invalida`

## ▶️ Exemplo

```bash
Tem aula de tarde? (sim/nao): sim
Estou fora
```

## 💻 Código utilizado

```python
import os
os.system('cls')

print ('responda sem acento')
aula_tarde = input("Tem aula de tarde? (sim/nao): ")

if aula_tarde.lower() == "sim":
    print("Estou fora")
if aula_tarde.lower() == "nao":
    print("Estou dentro")
else:
    print("resposta invalida")
```

---

# 🚀 Como executar

1. Instale o Python 3
2. Execute um dos arquivos:

```bash
python nota.py
```

ou

```bash
python renata.py
```

---

# 🛠️ Tecnologia utilizada

- Python 3

---

# 👨‍💻 Autor

Pedro Henrique Leonel de Oliveira

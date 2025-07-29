# ✅ Interface vs Classe Abstrata em Java

Este projeto simples foi criado para mostrar, de forma prática, a diferença entre **interface** e **classe abstrata** em Java, usando um exemplo de cálculo de imposto (`TaxService`).

---

## 📘 Conceitos

### Interface
- Um **contrato** que obriga a classe que a implementa a definir todos os métodos.
- Não possui estado (atributos de instância).
- Suporta herança múltipla (pode implementar várias interfaces).
- Ideal para definir **comportamento comum** entre classes que não possuem relação direta.

### Classe Abstrata
- Pode conter métodos com ou sem implementação.
- Pode ter atributos e construtores.
- Permite **compartilhar lógica comum** entre subclasses.
- Só pode ser herdada por uma classe por vez.

---

## 🔍 Diferenças principais

| Característica                    | Interface                        | Classe Abstrata                   |
|----------------------------------|----------------------------------|-----------------------------------|
| Métodos com implementação        | Só com `default` ou `static`     | Pode ter qualquer método comum    |
| Atributos                        | Não possui                       | Pode ter                         |
| Herança múltipla                 | Sim                              | Não                               |
| Obrigatoriedade de métodos       | Todos                            | Só os `abstract`                 |
| Foco principal                   | Contrato                         | Lógica compartilhada              |

---

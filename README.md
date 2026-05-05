
# 🔐 Projeto: Teste de Força Bruta com Medusa 

## 📌 Sobre o projeto

Esse projeto foi desenvolvido como parte do curso de cibersegurança, com o objetivo de entender como funciona um ataque de força bruta.

Durante o curso, foram apresentadas ferramentas mais completas, porém, devido a limitações técnicas, o projeto foi adaptado para um ambiente mais simples, mantendo o foco no aprendizado.

---

## 🎯 Objetivo

* Entender o que é ataque de força bruta
* Conhecer como funciona a ferramenta Medusa
* Identificar riscos de senhas fracas

---

## 🧰 Ferramentas apresentadas no curso

* Kali Linux
* Metasploitable 2
* DVWA (Damn Vulnerable Web Application)
* Medusa
* Nmap

---

## 🛠️ Ferramentas utilizadas neste projeto

* Ubuntu (WSL)
* Medusa
* Wordlist simples (arquivo de senhas)

---

## 🧠 O que é força bruta?

Ataque de força bruta é quando um programa testa várias senhas automaticamente até encontrar a correta.

Isso acontece principalmente quando são usadas senhas simples, como "1234" ou "admin".

---

## ⚙️ Como seria o teste

O processo consiste em:

* Definir um usuário alvo
* Criar uma lista de possíveis senhas
* Executar tentativas automáticas com o Medusa

### Exemplo de comando:

```bash
medusa -h 127.0.0.1 -u teste -P senhas.txt -M ssh
```
---

## 📂 Exemplo de wordlist

```
1234
admin
password
teste
```

---

## 📊 Resultado esperado

Caso a senha esteja na lista, o sistema pode retornar:

```
ACCOUNT FOUND: [ssh] Host: 127.0.0.1 User: teste Password: 1234
```

---

## ⚠️ O que aprendi

* Senhas simples são vulneráveis
* Ataques automatizados são rápidos
* Segurança depende de boas práticas

---

## 🛡️ Como se proteger

* Usar senhas fortes
* Evitar senhas comuns
* Limitar tentativas de login
* Utilizar autenticação em dois fatores

---

## 📚 Conclusão

Mesmo sendo iniciante, consegui entender conceitos importantes de cibersegurança e como ataques podem acontecer na prática.

A adaptação do projeto permitiu continuar o aprendizado mesmo sem ambiente completo.


# Desafio DIO - Gerenciamento de instâncias EC2 na AWS

## 📌 Descrição
Repositório com a documentação do desafio da DIO sobre criação e gerenciamento de instâncias EC2 na AWS.

---

## 🎯 Objetivo
Demonstrar que a instância EC2 foi criada, acessada e que comandos básicos do Linux foram executados.

---

## 🧭 Resumo da instância (preencha se quiser)
- Região: sa-east-1 (São Paulo)
- AMI: Ubuntu 24.04 LTS
- Instance type: <ex.: t2.micro>
- Instance ID: <coloque aqui, ex.: i-03ded6d03164222a0>
- Public IPv4: <coloque aqui se desejar>

---

## ✅ Passo a passo realizado
1. Criei a instância EC2 (Ubuntu 24.04 LTS) pela AWS Console.
2. Conectei à instância utilizando **EC2 Instance Connect** (terminal no navegador).
3. Executei comandos de verificação no Linux para validar o ambiente.

### Comandos executados (exemplos)
```bash
whoami
uname -a
lsb_release -a
df -h
free -h
uptime
curl http://169.254.169.254/latest/meta-data/instance-id

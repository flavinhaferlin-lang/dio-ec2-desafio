# Desafio DIO - Gerenciamento de instâncias EC2 na AWS

## 📌 Descrição
Repositório com a documentação do desafio da DIO sobre criação e gerenciamento de instâncias EC2 na AWS.

---

## 🎯 Objetivo
Demonstrar que a instância EC2 foi criada, acessada e que comandos básicos do Linux foram executados.

---

## 🧭 Resumo da instância 
- Região: sa-east-1 (São Paulo)
- AMI: Ubuntu 24.04 LTS

---

## ✅ Passo a passo realizado
1. Criei a instância EC2 (Ubuntu 24.04 LTS) pela AWS Console.
2. Conectei à instância utilizando **EC2 Instance Connect** (terminal no navegador).
3. Executei comandos de verificação no Linux para validar o ambiente.

### Comandos executados
```bash
whoami
uname -a
lsb_release -a
df -h
uptime
curl http://169.254.169.254/latest/meta-data/instance-id

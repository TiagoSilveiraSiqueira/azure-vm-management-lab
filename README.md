# 🚀 Gerenciamento de Máquinas Virtuais no Azure

## 📌 Descrição
Projeto prático desenvolvido para demonstrar a criação e gerenciamento de máquinas virtuais no Microsoft Azure.

---

## ☁️ Criação da VM

- Nome: vm-lab-tiago
- Região: Brazil South
- Sistema Operacional: Windows Server 2022
- Tamanho: B2s

---

## 🌐 Configuração de Rede

- VNet criada automaticamente
- IP público habilitado
- NSG liberando porta 3389 (RDP)

---

## 💾 Gerenciamento de Discos

- Disco do sistema: Standard SSD
- Testes realizados:
  - Anexação de disco
  - Desanexação de disco (sem perda de dados)

---

## 🔍 Monitoramento

- Azure Monitor utilizado
- Métricas analisadas:
  - CPU
  - Rede
  - Disco

---

## 🧠 Aprendizados

- Criação de máquinas virtuais
- Configuração de rede e segurança
- Gerenciamento de storage
- Monitoramento de recursos

---

## 🔧 Boas práticas

- Evitar exposição direta de RDP
- Utilizar Azure Bastion em produção
- Desligar VM quando não estiver em uso
- Organizar recursos com Resource Groups

---

## 👨‍💻 Autor

Tiago Silveira Siqueira  
Analista de Infraestrutura Pleno
``

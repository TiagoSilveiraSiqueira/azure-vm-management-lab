# 🚀 Gerenciamento de Máquinas Virtuais no Azure

## 📌 Descrição
Este projeto foi desenvolvido como parte do laboratório da DIO com o objetivo de demonstrar o entendimento sobre criação e gerenciamento de máquinas virtuais no Microsoft Azure.

O foco principal foi a compreensão dos conceitos de infraestrutura em nuvem (IaaS), incluindo provisionamento, rede, armazenamento e monitoramento.

---

## ⚠️ Considerações sobre o Ambiente

Durante a execução do laboratório, não havia uma assinatura ativa no Microsoft Azure disponível, o que impossibilitou a criação real de recursos na plataforma.

Diante dessa limitação, foi adotada uma abordagem técnica baseada em:

- Navegação no portal Azure para análise das opções de configuração
- Estudo da documentação oficial da Microsoft
- Simulação do processo de criação e gerenciamento de máquinas virtuais
- Documentação das etapas e boas práticas utilizadas em ambientes reais

Essa abordagem reflete um cenário comum em ambientes corporativos, onde restrições de acesso exigem análise, planejamento e documentação antes da implementação.

---

## ☁️ Conceito de Máquinas Virtuais no Azure

Máquinas Virtuais (VMs) no Azure são recursos de computação na nuvem que permitem executar sistemas operacionais e aplicações sem a necessidade de hardware físico local.

### Principais características:

- Escalabilidade sob demanda
- Alta disponibilidade
- Modelo IaaS (Infrastructure as a Service)
- Integração com serviços de rede e segurança

---

## ⚙️ Processo de Criação de uma VM (Simulação)

### Etapas analisadas:

1. **Definição de parâmetros básicos**
   - Nome da VM: `vm-lab-tiago`
   - Região: Brazil South
   - Sistema operacional: Windows Server 2022
   - Tamanho: B2s

2. **Autenticação**
   - Usuário administrador
   - Senha segura ou chave SSH

3. **Configuração de rede**
   - Criação de Virtual Network (VNet)
   - Subnet associada
   - Atribuição de IP público
   - Associação de Network Security Group (NSG)

4. **Validação e implantação**
   - Revisão de configurações
   - Validação do deployment

---

## 🌐 Configuração de Rede

A rede da VM é baseada em componentes fundamentais do Azure:

- **VNet (Virtual Network):** rede privada isolada
- **Subnet:** segmentação da rede
- **IP público:** acesso externo à VM
- **NSG (Network Security Group):** controle de tráfego

### Exemplo de regra de segurança:

- Porta 3389 (RDP) liberada para acesso remoto
- Restrição de acesso recomendada por IP

---

## 💾 Gerenciamento de Discos

As VMs utilizam discos gerenciados no Azure:

### Tipos de discos:

- Standard HDD
- Standard SSD
- Premium SSD

### Operações analisadas:

- Criação de disco do sistema (OS Disk)
- Adição de disco de dados
- Desanexação de disco sem perda de dados

---

## 🔍 Monitoramento

O Azure fornece ferramentas para monitoramento de desempenho e saúde da VM:

### Recursos utilizados:

- Azure Monitor
- Métricas de desempenho

### Principais indicadores:

- Uso de CPU
- Leitura e escrita de disco
- Tráfego de rede

---

## 🧠 Aprendizados

Durante o laboratório, foram consolidados os seguintes conhecimentos:

- Estrutura de provisionamento de VMs no Azure
- Configuração de rede (VNet, Subnet e NSG)
- Gerenciamento de armazenamento
- Conceitos de monitoramento e observabilidade
- Organização de recursos em ambiente cloud

---

## 🔧 Boas práticas

- Evitar exposição direta de RDP/SSH na internet
- Utilizar Azure Bastion para acesso seguro
- Aplicar regras restritivas em NSG
- Monitorar custos e uso de recursos
- Utilizar Resource Groups para organização

---

## 🔄 Aplicação em Ambiente Corporativo

Os conceitos abordados neste laboratório são diretamente aplicáveis a cenários reais de infraestrutura, como:

- Provisionamento de servidores em nuvem
- Migração de ambientes on-premises
- Implementação de políticas de segurança
- Monitoramento de ativos críticos

---

## 👨‍💻 Autor

**Tiago Silveira Siqueira**  
Analista de Infraestrutura Pleno

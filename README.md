# 🖥️ Criação de Máquina Virtual Windows no Azure via Portal

Este repositório documenta o processo de criação de uma máquina virtual do Windows no [Microsoft Azure](https://portal.azure.com) utilizando o **Portal do Azure**. O tutorial foi seguido com base na documentação oficial:  
🔗 [Início Rápido: Criar uma máquina virtual do Windows no Portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)

---

## 🧭 Sumário

1. [Objetivo](#objetivo)
2. [Requisitos](#requisitos)
3. [Passo a Passo](#passo-a-passo)
4. [Considerações Finais](#consideracoes-finais)
5. [Recursos Úteis](#recursos-uteis)

---

## 🎯 Objetivo

O objetivo deste projeto é aprender e documentar os passos necessários para criar uma máquina virtual do Windows no Azure usando o Portal Web da plataforma.

---

## 💻 Requisitos

- Uma conta ativa no [Azure](https://portal.azure.com).
- Acesso à Internet.
- Conhecimentos básicos sobre máquinas virtuais e sistemas operacionais Windows.
- (Opcional) Conta no GitHub para versionamento do projeto.

---

## ⚙️ Passo a Passo

### 1. Acessar o Portal do Azure

1. Faça login no [Portal do Azure](https://portal.azure.com).
2. Clique em **"Criar um recurso"** na barra lateral esquerda.

### 2. Escolher o Tipo de VM

1. Procure por **"Windows Server"**.
2. Selecione a versão desejada (ex: **Windows Server 2022 Datacenter**).
3. Clique em **"Criar"**.

### 3. Configurar a VM

| Campo | Descrição |
|-------|-----------|
| **Nome da VM** | Nome da máquina virtual |
| **Região** | Região onde será implantada |
| **Tamanho da VM** | Recomenda-se começar com B1ms ou similar |
| **Nome de usuário** | Usuário administrador |
| **Senha** | Senha forte com pelo menos 12 caracteres |

> 💡 Certifique-se de usar uma senha forte e configurar grupos de segurança de rede (NSG) conforme necessário.

### 4. Implantar a VM

1. Revise as configurações.
2. Clique em **"Criar"**.
3. Aguarde a conclusão do processo (geralmente alguns minutos).

### 5. Acessar a VM

1. Após a implantação, clique em **"Conectar" > "RDP"**.
2. Baixe o arquivo `.rdp`.
3. Abra-o com o Remote Desktop Connection.

---

## ✅ Considerações Finais

Com este tutorial, foi possível entender o funcionamento básico do Azure para criação de VMs Windows. É importante lembrar que:

- Sempre revise as políticas de segurança antes de expor a VM à internet.
- Monitore custos regularmente, especialmente se for uma assinatura paga.
- Este é apenas o início — há muitas outras funcionalidades do Azure a serem exploradas!

---

## 📘 Recursos Úteis

- [Documentação Oficial do Azure - VMs Windows](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/)
- [GitHub Quick Start](https://github.com/Knowledge-People/GitHub-Quick-Start)
- [Formação GitHub Certification](https://learn.gitbook.com/)
- [Guia Markdown no GitHub](https://docs.github.com/pt/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

---

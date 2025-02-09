# 🚀 Desafio: Ferramentas de Implantação no Azure

Bem-vindo ao desafio de projeto **Ferramentas de Implantação no Azure**! O objetivo deste desafio é aprender a utilizar diferentes ferramentas disponíveis na plataforma Azure para gerenciar e implantar recursos de maneira eficiente e automatizada.

## 🎯 Objetivos do Desafio

- Compreender e utilizar as ferramentas de implantação no Azure.
- Explorar o **Portal do Azure** e suas funcionalidades.
- Utilizar **Azure Cloud Shell, CLI do Azure e Azure PowerShell**.
- Conhecer o **Azure Arc** e sua finalidade.
- Aprender sobre o **Azure Resource Manager (ARM)** e os **modelos do ARM do Azure**.

## 📌 Passo a Passo

### 1️⃣ Portal do Azure
- Interface gráfica baseada na web para gerenciamento e monitoramento de serviços.
- Permite criar, modificar e excluir recursos de maneira visual.
- Disponível em: [Portal do Azure](https://portal.azure.com/)

### 2️⃣ Azure Cloud Shell
- Ambiente de terminal baseado em navegador integrado ao **Portal do Azure**.
- Suporta **Bash** e **PowerShell**, permitindo executar comandos sem precisar instalar ferramentas localmente.
- Acesso via: [Azure Cloud Shell](https://shell.azure.com/)

### 3️⃣ CLI do Azure
- Interface de linha de comando para gerenciar recursos no Azure.
- Compatível com Windows, macOS e Linux.
- Exemplo de uso:
  ```sh
  az login  # Autenticar no Azure
  az group create --name MeuGrupo --location eastus  # Criar um grupo de recursos
  ```
- Instalação e mais detalhes: [Azure CLI](https://learn.microsoft.com/pt-br/cli/azure/)

### 4️⃣ Azure PowerShell
- Conjunto de módulos do PowerShell para gerenciamento do Azure.
- Útil para **automatização de tarefas** e **gerenciamento avançado** de recursos.
- Exemplo de uso:
  ```powershell
  Connect-AzAccount  # Autenticar no Azure
  New-AzResourceGroup -Name MeuGrupo -Location EastUS  # Criar um grupo de recursos
  ```
- Instalação e mais detalhes: [Azure PowerShell](https://learn.microsoft.com/pt-br/powershell/azure/overview)

### 5️⃣ O que é Azure Arc?
- Serviço que permite gerenciar recursos **on-premises e multicloud** diretamente pelo Azure.
- Fornece **governança, conformidade e segurança centralizadas** para servidores, clusters Kubernetes e bancos de dados.
- Mais informações: [Azure Arc](https://learn.microsoft.com/pt-br/azure/azure-arc/overview)

### 6️⃣ Azure Resource Manager (ARM)
- **Azure Resource Manager (ARM)** é a camada de gerenciamento do Azure para provisionamento de recursos.
- Facilita **implantação, atualização e exclusão** de recursos de maneira controlada.
- Permite o uso de **Modelos do ARM** para padronizar implantações.

### 7️⃣ Modelos do ARM do Azure
- Arquivos **JSON** que definem a configuração dos recursos a serem implantados.
- Suportam **infraestrutura como código (IaC)**, tornando as implantações repetíveis e consistentes.
- Exemplo básico de modelo do ARM:
  ```json
  {
    "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
    "contentVersion": "1.0.0.0",
    "resources": [
      {
        "type": "Microsoft.Resources/resourceGroups",
        "apiVersion": "2021-04-01",
        "location": "eastus",
        "name": "MeuGrupo"
      }
    ]
  }
  ```
- Mais informações: [Modelos do ARM](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/templates/overview)

## 📚 Recursos Extras

- 📖 [Documentação Oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- 🎥 [Microsoft Learn - Cursos Gratuitos](https://learn.microsoft.com/pt-br/training/)
- 💬 [Fórum da Comunidade Microsoft](https://learn.microsoft.com/pt-br/answers/topics/azure.html)

💡 **Dica:** Compartilhe seu progresso e aprendizado! 🚀

---

### ✨ Contribuição
Se desejar contribuir com melhorias ou sugestões, fique à vontade para enviar um pull request.

📌 **Desafio desenvolvido para aprendizado e prática no uso de ferramentas de implantação no Azure.**


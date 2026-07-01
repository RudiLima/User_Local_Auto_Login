# 🔐 Script de Criação de Usuário e Logon Automático (Windows)

Este script em PowerShell automatiza a criação (ou atualização) de um usuário local no Windows e configura o **logon automático** da máquina.

---

## ⚙️ Funcionalidades

O script realiza as seguintes ações:

- ✅ Cria um usuário local (caso não exista)
- ✅ Atualiza a senha de um usuário existente
- ✅ Adiciona o usuário ao grupo **Users**
- ✅ Define senha como:
  - Nunca expira
  - Não pode ser alterada pelo usuário
- ✅ Configura **logon automático** no Windows
- ✅ Ajusta o registro do sistema automaticamente

---

## 📥 Parâmetros de Configuração

Antes de executar, edite os valores no início do script:

```powershell
$usuario = "SEU USUARIO"
$senha   = "SUA SENHA"

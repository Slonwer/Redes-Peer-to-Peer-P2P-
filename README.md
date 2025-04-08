# Redes-Peer-to-Peer-P2P-
REPOSITORIO PARA TESTE DE REDE DE IP PARA OUTRA MAQUINA


# 🕸️ Redes Peer-to-Peer (P2P) - Script de Diagnóstico de Rede

Este projeto automatiza a coleta de informações de rede em sistemas Windows e gera um relatório completo em formato `.txt` e `.pdf`, ideal para estudos, análises técnicas ou trabalhos acadêmicos.

## 📂 Estrutura do Projeto
Redes-Peer-to-Peer-P2P/ │ ├── info-ip.ps1 # Script PowerShell para coletar IP, Gateway e Máscara ├── converter-pdf.ps1 # Script que converte o relatório gerado para PDF via Microsoft Word ├── relatorio_rede.txt # Arquivo de relatório gerado automaticamente ├── relatorio_rede.pdf # Versão PDF do relatório ├── README.md # Este arquivo de documentação └── SH/ # (Opcional) Scripts adicionais

---

## 🚀 Como usar

### 1. ⚙️ Habilitar execução de scripts no PowerShell

Abra o PowerShell como administrador e execute:

```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\info-ip.ps1
.\converter-pdf.ps1

===== RELATÓRIO DE REDE =====

Endereço IPv4     : 192.168.1.100
Gateway Padrão    : 192.168.1.1
Máscara de Sub-rede: 255.255.255.0

Relatório gerado em: C:\Users\SeuNome\Documents\Redes-Peer-to-Peer-P2P-\relatorio_rede.txt


Se quiser, posso incluir imagens, GIFs de demonstração ou um botão de "Execute no PowerShell" usando badges no topo do README. Deseja que eu personalize com mais recursos?

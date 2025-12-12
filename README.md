# 🖥️ Monitoramento de CPU e RAM (Python)

Um script simples em Python para monitorar em tempo real o uso de **CPU** e **memória RAM** do sistema.  
Ideal para quem está aprendendo infraestrutura, suporte técnico ou deseja ter ferramentas próprias de diagnóstico.

---

## 🚀 Funcionalidades

- Monitoramento em tempo real
- Exibe:
  - Uso da CPU (%)
  - Uso da Memória RAM (%)
  - Quantidade de RAM usada (GB)
  - Total de RAM disponível
- Atualização automática a cada 1 segundo
- Compatível com Windows, Linux e macOS
- Interface limpa no terminal

---

## 📦 Requisitos

Antes de executar, instale a biblioteca necessária:

```bash
pip install psutil

---

▶️ Como executar

No terminal, dentro da pasta do projeto, digite:

python monitoramento.py

---

A saída será parecida com:

=== MONITORAMENTO DO SISTEMA ===
Uso de CPU: 15%
Uso de RAM: 63%
RAM usada: 5.02 GB
RAM total: 8.0 GB

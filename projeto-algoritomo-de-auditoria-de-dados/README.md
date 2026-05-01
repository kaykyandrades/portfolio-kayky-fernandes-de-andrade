# 📊 Algoritmo de Auditoria de Dados Financeiros

## 📝 Descrição do Projeto
Este projeto consiste num sistema de auditoria automatizada desenvolvido em Python para a validação de transações comerciais. O objetivo principal é monitorizar o fluxo de vendas diárias, identificando discrepâncias financeiras e garantindo que as operações permaneçam dentro dos limites de segurança preestabelecidos.

Desenvolvido como parte dos estudos de **Engenharia de Software** na **Unicid** (2026), o algoritmo implementa lógicas de verificação rigorosas, como o estado de "Quarentena" para médias excedentes e a sinalização de "Revisão Manual" para vendas que apresentam anomalias estatísticas.

## 🚀 Funcionalidades e Lógicas
O sistema realiza três níveis de verificação crítica:
* **Controle de Limite Global:** Utiliza a palavra-chave `global` para permitir que o limite de segurança seja atualizado em tempo real durante a execução.
* **Estado de Quarentena:** O sistema entra em modo "SISTEMA EM QUARENTENA" se a média aritmética das vendas ultrapassar o limite definido.
* **Detecção de Discrepância (Outliers):** Aciona a flag "REVISÃO MANUAL" caso qualquer venda individual seja superior ao dobro da média calculada.
* **Casting e Tipagem:** Implementa conversão rigorosa de dados para `float` e exibe os tipos de dados processados para garantir a integridade dos cálculos.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3.x.
* **Ambiente:** Desenvolvido inicialmente no Google Colab.
* **Conceitos:** Escopo de variáveis, Estruturas Condicionais, Manipulação de Strings (f-strings) e Funções Matemáticas (`max()`).

## 🔧 Como Executar
1. Clone o repositório.
2. Certifique-se de ter o Python instalado no seu ambiente.
3. Execute o script:
   ```bash
   python algoritmo_de_auditoria_de_dados.py
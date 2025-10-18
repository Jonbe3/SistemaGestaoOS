# 🛠️ Sistema de Gestão de Ordens de Serviço

Projeto desenvolvido para a disciplina **Programação Orientada a Objetos (POO)** —  
Curso de **Ciência da Computação**, 2025.

---

## 🎯 Objetivo
Criar um sistema de gerenciamento de ordens de serviço (OS) para uma empresa de manutenção técnica, aplicando os principais conceitos de **Programação Orientada a Objetos** sem usar herança ou polimorfismo.

---

## 📦 Estrutura do Sistema

### Classes principais
- **Cliente** – Armazena dados dos clientes.
- **Tecnico** – Representa técnicos e suas especialidades.
- **Equipamento** – Registra os equipamentos consertados.
- **Servico** – Contém os serviços realizados e seus custos.
- **OrdemServico** – Conecta cliente, técnico, equipamento e serviços.
- **Relatorio** – Gera relatórios mensais das ordens.
- **SistemaGestaoOS** – Classe principal (main) para simular o sistema.

### Interface
- **Registravel** – Interface implementada por Cliente, Técnico e Ordem de Serviço com o método `registrar()`.

---

## ⚙️ Funcionalidades
✅ Cadastro de clientes, técnicos e equipamentos  
✅ Abertura de ordens de serviço  
✅ Adição de serviços com custo  
✅ Atualização de status (Aberta, Em andamento, Concluída)  
✅ Cálculo automático do custo total  
✅ Geração automática do número da OS  
✅ Relatório mensal simples no console  

---

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/SistemaGestaoOS.git
   cd SistemaGestaoOS

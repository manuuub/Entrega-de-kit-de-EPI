# 🛡️ Sistema de Gestão e Controle de Entrega de EPIs

Proposta de automação e controle digital de Equipamentos de Proteção Individual (EPI) desenvolvida para a **Caldeiraria Ferro Forte (Jundiaí)**. 

O projeto elimina o uso de fichas de papel, garante 100% de conformidade nas entregas obrigatórias por setor e automatiza a identificação dos funcionários via leitura de crachá (IoT).

---

## 🛠️ Tecnologias Utilizadas
- **Backend:** PHP puro (arquitetura organizada em formulário, lógica de processamento e relatório)
- **Frontend:** HTML5, CSS3 (com alertas visuais condicionados)
- **Banco de Dados:** MySQL
- **Automação:** Conceito de leitor IoT (RFID/NFC) para identificação por crachá

---

## 📌 Principais Funcionalidades & Regras do Sistema
- **Controle de Kits por Setor:** Validação dos itens obrigatórios para Solda, Pintura e Montagem.
- **Alertas de Inconsistência:** Aviso em tempo real caso algum EPI obrigatório esteja zerado no kit.
- **Aprovação do Supervisor:** Requer validação para entregas com mais de 3 unidades do mesmo item ou valor total superior a R$ 400,00.
- **Histórico & Auditoria:** Armazenamento dos dados de entrega por no mínimo 5 anos.

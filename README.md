# Projeto Az Monitor
Descrever como configurar monitoramento de VMs no Microsoft Azure, com foco em eventos críticos como a exclusão de máquinas virtuais

## 📌 Objetivo

Demonstrar como manter visibilidade e controle sobre recursos no Azure, utilizando ferramentas como Azure Monitor, Log Analytics e Alertas.

## 🛠️ Ferramentas Utilizadas

- Azure Monitor
- Log Analytics Workspace
- Action Groups
- Alertas de Métricas e Atividades
- GitHub

## 📋 Etapas Realizadas

1. Criação de uma VM no Azure
2. Ativação do diagnóstico e envio de logs para o Log Analytics
3. Criação de alertas para eventos críticos (ex: exclusão de VM)
4. Configuração de Action Groups para envio de notificações
5. Teste e validação dos alertas

## 💡 Dicas e Observações

- Sempre vincule a VM a um Log Analytics Workspace.
- Use filtros específicos ao criar alertas para evitar notificações desnecessárias.
- Teste os alertas com ações simuladas antes de aplicar em produção.

## 📚 Referências

- Documentação oficial do Azure Monitor

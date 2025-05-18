# Criação de Máquinas Virtuais no Microsoft Azure

## Introdução
- O lab aborda a criação de **máquinas virtuais (VMs)** no Microsoft Azure.
- Foco em ambientes de **teste e produção**, destacando a importância de escolher as configurações adequadas.

## Configurações Principais para Criar uma VM
- Escolha da **família de máquinas** (ex: séries B, D, E, etc.).
- Definição de:
  - Quantidade de vCPUs
  - Memória RAM
  - Armazenamento (tipo e tamanho)
  - Sistema operacional
- Ativação de:
  - **Backups automáticos**
  - **Alertas e notificações de desligamento**
- Boas práticas:
  - Não expor **portas desnecessárias** à internet.
  - **Configurações de segurança** para garantir integridade e proteção de dados.

## Escalonamento Automático (Auto Scale)
- Ajusta automaticamente a quantidade de VMs com base na **demanda de CPU** ou outros critérios.
- Importante em **períodos de pico**, como Black Friday.
- Evita sobrecargas e garante **alta disponibilidade**.

## Instâncias Spot
- **Mais baratas** que instâncias regulares.
- Podem ser **interrompidas a qualquer momento**.
- Ideais para:
  - **Ambientes de desenvolvimento**
  - **Testes não críticos**
- Não recomendadas para aplicações de produção que exigem alta disponibilidade.

## Ambientes de Trabalho Virtuais
- Utilização de **máquinas personalizadas** e **pools de hosts**.
- Permite:
  - Balanceamento de carga
  - Otimização de recursos
  - Suporte a múltiplos usuários simultâneos

## Práticas Recomendadas
- Planejar a VM conforme o **perfil de uso**.
- Usar escalonamento automático para economizar e melhorar performance.
- Aproveitar instâncias Spot em contextos apropriados.
- Configurar **segurança desde o início** (firewall, NSG, etc.).
- Habilitar **monitoramento e backup** desde a criação.


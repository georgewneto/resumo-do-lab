# Azure Essentials
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

- Criar conta gratuita
- Entrar na página inicial
  - alguns serviços são limitados por região, ou pela conta ser gratuita.
  - Idioma e região -> mudar idioma
  - Aparência -> mudar visual, posição da barra lateral, cores, etc
  - Todos os serviços
- Computação (PaaS, microserviços)
- Redes
  - Bastions - rede segura pra acessar nossas VMs
  - IPs, gateways, DNS, peering, Load balancing, conectividades
- Armazenamento
  - servidores, discos
  - migração (estratégias de migração)
- Obs.: Versão prévia: não tem garantia (SLA) e pode ser descontinuado sem aviso prévio.

# Máquinas virtuais
- Diferenças do tempo de SLA
  - quanto mais 9s, menos inatividade (tempo indisponível) do serviço
- opções de disponbilidade
  - conjuntos de escala de VMs, conjuntos de disponibilidade, balanceador de carga, redundância do armazenamento, recovery
- zonas de disponibilidade
  - até 3 zonas
- contas de armazenamento
  - replicação dos dados entre datacenters e regiões
- sistema operacional (imagem / arquitetura)
  - tamanho e valor mensal
  - necessário configurar: discos / redes / monitoramento
 
# Banco de dados
  - criação de servidor
  - autenticação
  - armazenamento do backup
  - previsão de custo mensal

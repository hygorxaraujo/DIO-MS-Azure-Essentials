# DIO-MS-Azure-Essentials
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Tipos de nuvem:
- Privada (local, on-premises)
- Pública (Azure, AWS, GCP)
- Híbrida

Benefícios do uso de nuvem:
- Alta disponibilidade e da escalabilidade na nuvem
- Confiabilidade e da previsibilidade na nuvem
- Segurança e da governança na nuvem
- Capacidade de gerenciamento na nuvem

Modelos de serviço de nuvem:
- IaaS: Infrastructure as a Service -> maior responsabilidade do cliente
- PaaS: Platforma as a Service
- SaaS: Software as a Service -> maior responsabilidade do provedor

Responsabilidade compartilhada por modelo:
![image](https://github.com/user-attachments/assets/1d052aa8-713a-41df-84f8-dce92fcd72ba)

Configurando recursos e dimensionamentos em máquinas virtuais:
- Região, opções de disponibilidade, zona de disponibilidade
- Tipo de segurança, imagem (windows, linux) e arquitetura
- Serviço spot com menor custo, mas sem confiabilidade
- Dimensionamento automático e manual
  - Definir condições para escalonamento
- Tamanhos de VM
- Conjunto de dimensionamento de VMs
- Regras de portas de entrada e saída
- Licensiamento
- Excluir armazenamento junto com VM
- Configurações de rede (rede virtual, sub redes, up público, portas de entrada, etc)
- Autenticação
- Desligamento automático
- Backup
- Atualização de SO
- Extensões para VMs (ex: antivirus, agente de monitoração)
- Pool de hosts, pessoal ou em pool (compartilhado)
  - Tipo de grupo de aplicativos (ex: área de trabalho)
- App Functions
  - Runtimes: .NET, Node.js, Python, Java, PowerShell Core, Custom Handler
  - Alguns runtimes apenas disponível em um tipo de SO (ex: Python apenas em Linux)
  - Hospedagem: sem servidor, premium e plano de serviço de app


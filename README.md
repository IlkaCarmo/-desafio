# 🌐 Gerenciamento de Instâncias EC2 na AWS

## ✨ Sobre este laboratório

Este laboratório foi uma oportunidade incrível para mergulhar de verdade no universo da AWS, especialmente no gerenciamento de instâncias EC2. Mais do que seguir passos técnicos, foi um exercício de entender como os serviços se conectam, como cada decisão impacta a infraestrutura e como documentar tudo de forma clara e útil.

Criei este repositório como um espaço para reunir tudo o que aprendi  não só os comandos e configurações, mas também os **insights que só vêm quando a gente põe a mão na massa**.

---

## 🎯 O que aprendi na prática

O Amazon EC2 (Elastic Compute Cloud) é um dos serviços mais fundamentais da AWS. Ele permite criar servidores virtuais sob demanda, com total controle sobre o sistema operacional, armazenamento, rede e segurança.
Durante o laboratório, percebi que o EC2 é como um “computador na nuvem”  mas com muito mais flexibilidade. Você escolhe tudo: desde a imagem do sistema (AMI), até o tipo de instância, o volume de armazenamento, e as regras de acesso.
O que mais me chamou atenção:
- Elasticidade: posso iniciar, parar, reiniciar ou terminar instâncias conforme a necessidade, sem depender de hardware físico.
- Escalabilidade: é possível aumentar ou reduzir recursos com poucos cliques, o que é essencial para aplicações que crescem rápido.
- Integração com outros serviços: EC2 conversa facilmente com EBS, CloudWatch, IAM, S3 e muitos outros — o que permite montar arquiteturas completas e automatizadas.
- Controle total: diferente de serviços gerenciados, o EC2 me dá liberdade para configurar tudo do zero, o que é ótimo para aprender e testar.
- 
Esse laboratório me ajudou a entender que EC2 não é só sobre “ligar uma máquina”, mas sim sobre construir ambientes sob medida, com segurança, desempenho e escalabilidade.


### 🔐 Segurança é prioridade
Configurar Security Groups foi um dos pontos mais importantes. Aprendi que abrir portas demais pode comprometer a segurança, e que é essencial limitar o acesso por IP e protocolo. Isso me fez pensar como a segurança na nuvem é **ativa e estratégica**, não só técnica.

### 💾 Associar volumes EBS
Conectar um volume EBS à instância foi um divisor de águas. Entendi como separar o armazenamento do processamento traz flexibilidade e persistência. Aprendi a montar, formatar e usar o volume como se fosse um disco local  e isso me deu uma visão mais clara de como **infraestrutura em nuvem simula o físico, mas com muito mais controle**.

### Explicação do Diagrama de Arquitetura

O diagrama representa uma arquitetura simples baseada em serviços da AWS, voltada para aplicações que exigem processamento, armazenamento e banco de dados. Ele mostra como os componentes se conectam e como o fluxo de dados acontece desde o usuário até os serviços em nuvem.
🔄 Fluxo de Interação
- Ator (Usuário): Representa a pessoa que interage com o sistema, seja via navegador ou dispositivo móvel.
- Interface de Usuário: O ponto de entrada da aplicação, onde o usuário envia arquivos ou faz requisições.
- Envio de Arquivo: O dado enviado pelo usuário é processado e armazenado.
- Amazon EC2: Instância responsável pelo processamento da aplicação. É o “cérebro” da arquitetura, executando o código e gerenciando as requisições.
- Amazon EBS: Volumes de armazenamento conectados à EC2, usados para guardar dados persistentes, arquivos temporários ou logs.
- Amazon RDS: Banco de dados relacional gerenciado, ideal para armazenar dados estruturados como informações de usuários, registros e transações.
🧠 Por que essa arquitetura?
Essa estrutura é eficiente para aplicações web que precisam de:
- Processamento sob demanda (EC2)
- Armazenamento persistente (EBS)
- Banco de dados confiável e escalável (RDS)
Ela também separa responsabilidades entre os serviços, o que facilita manutenção, escalabilidade e segurança.

![Criação da instância EC2](diagramaEC2.png)

---
## 💡 Reflexões finais

Esse laboratório me mostrou que trabalhar com EC2 não é só sobre “ligar uma máquina virtual”. É sobre **entender a arquitetura, pensar em segurança, planejar armazenamento e acompanhar o desempenho**. E acima de tudo, é sobre aprender a pensar como uma pessoa que constrói soluções na nuvem — com responsabilidade, clareza e propósito.

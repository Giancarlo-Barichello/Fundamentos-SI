# 📚 Notas de Aula - Sistemas de Informação

Repositório contendo anotações e resumos das aulas da disciplina.

---

# Aula 1 - Conceitos Básicos de Sistemas

## Tópicos abordados

### Sistemas
- O que é um sistema
- Para que serve
- Quando utilizar

### Elementos que compõem um sistema

#### Aspectos Estruturais
- Características
- Propriedades

#### Aspectos Funcionais
- Comportamentos
- Funcionalidades

### Arquiteturas de Sistemas
- Cliente-Servidor
- Ponto-a-Ponto (P2P)

---

# Aula 2 - Introdução ao GitHub

## Tópicos abordados

### GitHub
- Criação de conta
- Criação de repositório

### Objetivos do GitHub
- Controle de versão
- Backup de código-fonte

---

# Aula 3 - Oficina de Git

## Tópicos abordados

### Oficina Git

Repositório utilizado na oficina:

<https://github.com/alexandrezamberlan/oficinaGit>

### Trabalho Avaliado

Cada aluno deve criar um arquivo chamado:

```text
02-glossario.md
```

O arquivo deve conter um glossário com palavras e expressões estudadas na disciplina.

---

# Aula 4 - Sistemas e Computação

## Conceitos

### Sistemas
- Partes
- Tipos

### Computação e Processamento

#### Desktop

#### Web
- Cloud Computing (Computação em Nuvem)
- Aplicações
- Navegadores

### IoT (Internet of Things)

#### Vantagens
- Flexibilidade
- Autonomia
- Agilidade
- Integração de tecnologias

#### Desvantagens
- Segurança
- Dependência da internet

#### Arquiteturas
- Cliente-Servidor
- Ponto-a-Ponto

### Modelos de Serviços em Nuvem

- IaaS
- PaaS
- SaaS

---

# Aula 5 - IoT e Computação em Nuvem

## IoT (Internet das Coisas)

É a conexão de dispositivos físicos à internet para coleta e troca de dados.

### Exemplos
- Geladeiras inteligentes
- Câmeras
- Sensores
- Veículos conectados

---

## Computação em Nuvem

Utilização de recursos computacionais pela internet sem necessidade de infraestrutura própria.

### Principais provedores
- AWS
- Azure
- Google Cloud

### Relação com IoT

A computação em nuvem permite armazenar e processar grandes quantidades de dados gerados pelos dispositivos conectados.

---

## Sistemas Pervasivos

Tecnologias inteligentes presentes em um ambiente específico e que auxiliam o usuário.

### Exemplos
- Automação residencial
- Monitoramento de saúde
- Sensores industriais

---

## Sistemas Ubíquos

Tecnologias integradas ao ambiente de forma quase imperceptível.

### Exemplos
- Assistentes de voz
- Espelhos inteligentes
- Cadeiras com sensores de postura

---

## Comparação

| Característica | Pervasivo | Ubíquo |
|---------------|-----------|---------|
| Visibilidade | Perceptível | Quase invisível |
| Objetivo | Tarefa específica | Experiência do usuário |

---

# Aula 6 - Desenvolvimento Colaborativo

## Boas práticas de desenvolvimento em grupo

### Controle de Versão

#### Git e GitHub
- Controle de versões
- Backup de projetos
- Trabalho colaborativo

---

## Kanban

Ferramenta de gerenciamento de tarefas.

### Exemplo: Trello

Fluxo básico:

```text
TO DO → DOING → DONE
```

### Etapas
- A Fazer (To Do)
- Fazendo (Doing)
- Concluído (Done)

---

## Atividade

Pesquisar:

- Diferença entre técnica e metodologia
- Integração entre Trello e GitHub

---

# Aula 6 - Sistemas Web e Computação em Nuvem

## Sistemas Web

Estudo e desenvolvimento de aplicações acessadas através de navegadores.

---

## Computação em Nuvem

Fornecimento de recursos computacionais pela internet.

---

## Arquitetura Cliente-Servidor

### Infraestrutura

- Ubuntu 22.04
- MySQL
- Firewall
- Gunicorn
- NGINX

### Aplicação

- Python
- Django
- Bootstrap

### Funcionalidades

- CRUD
- Serviços de gestão

---

## Modelos de Serviço

- IaaS
- PaaS

---

## Sistema de Gestão de Pizzaria

### Funcionalidades

- Gestão de Insumos
- Gestão de Usuários
- Gestão de Fornecedores
- Gestão Fornecedor-Insumo
- Gestão Pizza-Insumo
- Gestão de Clientes
- Gestão Cliente-Compra
- Sistema de Conhecimento

---

## CRN

Conteúdo mencionado durante a aula.

---

# Aula 7 - Virtualização e Contêineres

## Virtualização de Máquinas

### Hipervisores Tipo 1 (Bare-Metal)

- ESXi
- Hyper-V
- KVM

### Hipervisores Tipo 2 (Hosted)

- VirtualBox
- VMware Workstation

### Características

- Isolamento em nível de hardware
- Virtual Machine Monitor (VMM)

---

## Máquina Virtual vs Ambiente Virtual (VENV)

| Máquina Virtual | VENV |
|----------------|------|
| Isola hardware e sistema operacional | Isola pacotes e dependências |
| Possui Guest OS | Utiliza o sistema hospedeiro |
| Consome vários GB | Consome poucos MB |
| Reserva RAM e CPU | Sem consumo permanente |

---

## Docker e Contêineres

### Características

- Isolamento em nível de processo
- Compartilhamento do kernel do hospedeiro
- Consistência de ambientes

### Benefícios

- Evita conflitos de versões
- Ambientes descartáveis
- Facilidade de implantação

---

## Estrutura do Primeiro Contêiner

### Código Fonte

```python
app.py
```

### Dockerfile

```dockerfile
FROM python:3.10-slim

WORKDIR /app

COPY app.py .

CMD ["python", "app.py"]
```

### Fluxo

```text
Código Fonte
     ↓
 Dockerfile
     ↓
 Docker Image
     ↓
 Docker Container
```

---

## Distribuição de Contêineres

### Docker Hub

```bash
docker tag meu-app seu-user/meu-app

docker push seu-user/meu-app

docker run seu-user/meu-app
```

### Exportação Local

```bash
docker save -o meu-app.tar meu-app

docker load -i meu-app.tar
```

---

## 📖 Referências

- GitHub
- Docker
- Trello
- AWS
- Azure
- Google Cloud
- Django
- MySQL
- Ubuntu Server

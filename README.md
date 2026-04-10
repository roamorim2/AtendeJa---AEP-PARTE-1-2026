# AtendeJa

Sistema simples de registro e acompanhamento de solicitações públicas desenvolvido em Java para o projeto ESOFT5S.

---

##  Objetivo

O **AtendeJa** permite que cidadãos registrem solicitações de serviços públicos (como iluminação, buracos, limpeza, etc.) e acompanhem o andamento através de um sistema simples em linha de comando.

O sistema busca melhorar a **organização das demandas**, a **transparência no atendimento** e a **comunicação entre população e setor público**.

---

## Funcionalidades

* Criar solicitação
* Listar solicitações
* Buscar por protocolo
* Atualizar status da solicitação
* Registrar histórico com comentários
* Interface simples via terminal (CLI)

---

## Conceitos Aplicados

* Programação Orientada a Objetos (POO)
* Uso de classes (Solicitacao, Categoria, HistoricoStatus, ServicoSolicitacoes)
* Uso de Enum para controle de status
* Lista para armazenamento de dados em memória
* Histórico de alterações para rastreabilidade

---

## Como Executar

### Pré-requisitos:

* Java (JDK 17 ou superior)
* IntelliJ IDEA ou outra IDE

### Passos:

1. Baixar ou clonar o repositório:

```bash
git clone https://github.com/seu-usuario/AtendeJa.git
```

2. Abrir o projeto na IDE

3. Executar a classe:

```bash
Main.java
```

4. Utilizar o menu no terminal:

```
1 - Criar
2 - Listar
3 - Buscar
4 - Atualizar
0 - Sair
```

---

## Estrutura do Projeto

O projeto foi desenvolvido em um único arquivo:

* `Main.java` → Contém todas as classes do sistema:

    * `Solicitacao`
    * `Categoria`
    * `HistoricoStatus`
    * `ServicoSolicitacoes`
    * `Status (enum)`

---

## Observações

* Os dados são armazenados apenas em memória (não há banco de dados)
* O sistema é um protótipo (versão beta) para fins acadêmicos
* Pode ser expandido futuramente com interface gráfica ou banco de dados

---

## Autor

Projeto acadêmico - Engenharia de Software (ESOFT5S)

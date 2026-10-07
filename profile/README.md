# DevSec-DEMOs

Repositório central de projetos, laboratórios e demonstrações práticas de **DevOps + Security**.

A organização reúne os materiais utilizados pelo **M3TechLab** para transformar conceitos de engenharia de software, DevOps e segurança em experimentos práticos.

## O que você encontrará aqui

A organização é dividida principalmente em dois tipos de conteúdo:

### M3TechLab

O **M3TechLab** é o espaço de aprendizado da organização.

Nele estão reunidos:

- materiais de estudo;
- guias de ferramentas;
- referências;
- workshops;
- laboratórios;
- exercícios práticos;
- conexões entre conceitos, ferramentas e experimentos.

A proposta é partir do conceito e chegar à prática:

**Problema → Conceito → Tecnologia → Ferramenta → Laboratório → Experimento → Aprendizado**

### Projetos e aplicações para Labs

A organização também contém projetos de exemplo que podem ser utilizados como base para demonstrações e laboratórios.

Esses projetos permitem experimentar diferentes etapas do ciclo de desenvolvimento e segurança, por exemplo:

- desenvolvimento de aplicações;
- CI/CD;
- SAST;
- SCA;
- Secrets Detection;
- Threat Modeling;
- DAST;
- API Security;
- segurança de containers;
- infraestrutura como código;
- monitoramento;
- testes de segurança;
- Security Chaos Engineering.

Um exemplo é o **NodeGoat**, utilizado como aplicação deliberadamente vulnerável para estudos e demonstrações de segurança de aplicações.

## Como os projetos se conectam

A ideia não é apenas disponibilizar aplicações para executar.

Cada projeto pode servir como um ambiente para responder perguntas como:

> Qual problema estamos tentando identificar?

> Qual conceito de segurança está envolvido?

> Qual controle pode detectar ou reduzir esse problema?

> Como podemos testar esse controle?

> O que aprendemos com o resultado?

Por isso, um mesmo projeto pode ser utilizado em diferentes laboratórios.

Um fluxo possível:

```text
Projeto de exemplo
       ↓
   Arquitetura
       ↓
Threat Modeling
       ↓
      Código
       ↓
 SAST / SCA / Secrets
       ↓
      CI/CD
       ↓
    Deploy
       ↓
   Produção
       ↓
Monitoramento / Detecção
       ↓
    Experimento
       ↓
   Aprendizado
```

## Relação com o M3TechLab

O **DevSec-DEMOs** é a camada prática do M3TechLab.

```text
M3TechLab
   │
   ├── Conceitos
   ├── Livros e referências
   ├── Guias
   ├── Ferramentas
   └── Labs
          │
          ↓
     DevSec-DEMOs
          │
          ├── Projetos de exemplo
          ├── Aplicações para Labs
          ├── Demos
          └── Experimentos
```

O objetivo é permitir que alguém possa sair da teoria e chegar a um ambiente onde possa experimentar.

## Para quem é

O conteúdo é voltado principalmente para:

- estudantes de tecnologia;
- desenvolvedores;
- profissionais de infraestrutura;
- profissionais de segurança;
- pessoas começando em DevOps e DevSecOps;
- entusiastas de tecnologia;
- equipes que precisam de ambientes simples para demonstrações e treinamentos.

Não é necessário conhecer todas as ferramentas para começar.

Os materiais procuram explicar primeiro o **problema e o conceito**, antes de apresentar a ferramenta.

## Filosofia

A organização segue alguns princípios:

### Conceitos antes das ferramentas

Ferramentas mudam.

Os fundamentos permanecem.

Por isso, os Labs procuram explicar o conceito que está por trás de cada tecnologia.

### Aprender fazendo

Sempre que possível, os conteúdos devem levar a algum tipo de experimentação prática.

### Segurança como parte do fluxo

Security não deve ser tratada apenas como uma etapa final.

Ela pode participar de diferentes momentos:

**Requisitos → Arquitetura → Código → Build → Testes → Deploy → Produção → Monitoramento → Feedback**

### Experimentação

Encontrar uma vulnerabilidade ou configurar um controle é apenas parte do processo.

Também é importante testar se os controles realmente funcionam.

### Aprendizado seguro

Os Labs devem ser executados em ambientes controlados e destinados à experimentação.

Aplicações deliberadamente vulneráveis, credenciais de teste e técnicas ofensivas devem ser utilizadas somente em ambientes autorizados.

## Estrutura

A organização pode conter diferentes repositórios, cada um com uma finalidade específica.

Exemplo:

```text
DevSec-DEMOs
│
├── M3TechLab
│   ├── Livros
│   ├── Ferramentas
│   ├── Workshops
│   └── Labs
│
├── NodeGoat
│   └── Aplicação vulnerável para Labs
│
├── Outros projetos
│   └── Aplicações e ambientes para demonstrações
│
└── ...
```

A estrutura pode evoluir conforme novos Labs e projetos forem adicionados.

## Como utilizar

Para estudar um determinado tema, a recomendação é seguir este caminho:

1. Escolha um conceito.
2. Leia o material relacionado no M3TechLab.
3. Identifique uma ferramenta ou técnica relacionada.
4. Escolha um projeto de exemplo.
5. Execute o Lab em ambiente controlado.
6. Observe os resultados.
7. Faça alterações no projeto ou no ambiente.
8. Repita o experimento.
9. Registre o que foi aprendido.

## Exemplos de Labs

Alguns exemplos de atividades que podem ser construídas a partir dos projetos:

### Application Security

- encontrar vulnerabilidades no código;
- identificar dependências vulneráveis;
- detectar secrets;
- comparar diferentes tipos de scanners;
- priorizar findings;
- corrigir vulnerabilidades;
- validar a correção.

### Threat Modeling

- desenhar a arquitetura;
- identificar componentes;
- identificar trust boundaries;
- levantar ameaças;
- utilizar STRIDE;
- definir mitigações;
- revisar o modelo após alterações na aplicação.

### DevOps + Security

- criar um pipeline;
- adicionar testes de segurança;
- observar o feedback do pipeline;
- analisar falhas;
- corrigir problemas;
- automatizar controles.

### Security Chaos Engineering

- formular uma hipótese;
- criar uma condição controlada;
- observar o comportamento do sistema;
- verificar se o controle de segurança funciona;
- identificar falhas;
- corrigir;
- repetir o experimento.

## Aviso

Os projetos desta organização podem incluir aplicações deliberadamente vulneráveis ou configurações inseguras.

Utilize esses projetos **somente em ambientes próprios, de laboratório ou para os quais você tenha autorização**.

Não execute testes de segurança contra sistemas de terceiros sem autorização.

## Licenciamento

Cada repositório pode possuir sua própria licença e suas próprias condições de uso.

Consulte o `README.md` e o arquivo `LICENSE` de cada projeto antes de utilizá-lo, modificá-lo ou redistribuí-lo.

## Objetivo

O objetivo do DevSec-DEMOs é criar um ambiente onde seja possível:

**Entender → Experimentar → Construir → Testar → Medir → Aprender**

Tecnologia muda. Ferramentas mudam.

A capacidade de compreender sistemas, testar hipóteses e aprender com os resultados permanece.

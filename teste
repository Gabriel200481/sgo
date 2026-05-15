# 🏅 Sistema de Gestão das Olimpíadas (SGO)

> Solução robusta para a coordenação integral de eventos olímpicos, abrangendo desde o cadastro de modalidades e alocação de infraestrutura até a gestão de atletas e entrega de resultados oficiais.

<table>
	<tr>
		<td width="800px">
			<div align="justify">
				Este projeto foi desenvolvido para a disciplina de <b>Projeto de Software</b> (4º período). A solução foca na modelagem arquitetural de um sistema crítico para a gestão esportiva, garantindo a integridade das regras de negócio como a representação única de países por modalidade e a prevenção de conflitos em locais de prova. Através de uma abordagem orientada a modelos (PlantUML), o sistema define as bases para uma implementação escalável e resiliente.
			</div>
		</td>
		<td>
			<div>
				<img src="https://joaopauloaramuni.github.io/image/logo_ES_vertical.png" alt="Logo PUC Minas" width="120px"/>
			</div>
		</td>
	</tr>
</table>

---

## 🚧 Status do Projeto

[![Versão](https://img.shields.io/badge/Versão-v1.1.0-blue)](#)
![PlantUML](https://img.shields.io/badge/Modelagem-PlantUML-orange?style=for-the-badge&logo=uml&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-007ec6?style=for-the-badge&logo=openjdk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-336791?style=for-the-badge&logo=postgresql&logoColor=white)

- [x] **Fase 1:** Levantamento de Requisitos e User Stories 
- [x] **Fase 2:** Modelagem de Casos de Uso e Classes
- [x] **Fase 3:** Definição Arquitetural (Pacotes e Componentes)
- [x] **Fase 4:** Planejamento de Infraestrutura (Implantação)
- [x] **Fase 5:** Modelagem Comportamental (Sequência)

---

## 📚 Índice
- [Links Úteis](#-links-úteis)
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura](#-arquitetura)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Histórias de Usuário](#-histórias-de-usuário)
- [Diagramas UML](#-diagramas-uml)
- [Como Gerar as Imagens PNG](#-como-gerar-as-imagens-png)
- [Regras de Negócio](#-regras-de-negócio)
- [Autor](#-autor)
- [Agradecimentos](#-agradecimentos)
- [Licença](#-licença)

---

## 🔗 Links Úteis
* 🧩 **Diagramas PlantUML:** [./codigos/](./codigos/)
* 🖼️ **Imagens dos Diagramas:** [./imagens/](./imagens/)
* 📖 **Documentação Oficial:** [Referência PlantUML](https://plantuml.com/guide)
* 🎓 **Disciplina:** Projeto de Software - PUC Minas

---

## 📝 Sobre o Projeto

O **SGO (Sistema de Gestão das Olimpíadas)** resolve a complexidade logística de coordenar milhares de atletas e centenas de competições simultâneas. O foco principal é a **consistência de dados**: evitar que dois eventos ocorram no mesmo local ao mesmo tempo e garantir que o quadro de medalhas reflita fielmente o desempenho por país.

O projeto foi estruturado para atender aos requisitos da disciplina de Projeto de Software, utilizando o **PlantUML** para garantir que a modelagem possa ser versionada como código.

---

## ✨ Funcionalidades Principais

- 🏟️ **Gestão de Competições:** Cadastro completo de modalidades, horários e cronogramas.
- 🏃 **Inscrição de Atletas:** Validação de nacionalidade única por modalidade (Regra de Negócio 2).
- 📍 **Alocação de Locais:** Prevenção automática de conflitos de horário em arenas (Regra de Negócio 3).
- 🥇 **Controle de Resultados:** Registro oficial de pódio e persistência de vencedores.
- 📊 **Quadro de Medalhas:** Geração de relatórios de desempenho por país (Ouro, Prata e Bronze).

---

## 🛠 Tecnologias Utilizadas

### 🏗️ Modelagem e Design
* **Linguagem de Modelagem:** PlantUML (UML 2.0)
* **Ferramenta de Estilo:** SGO Custom Skin (CSS-like) nos arquivos `.puml`

### 🖥️ Stack Técnica (Referência de Arquitetura)
* **Back-end:** Java 17 (Ambiente sugerido no diagrama de implantação)
* **Banco de Dados:** PostgreSQL 15 (Persistência relacional)
* **Padrões:** MVC, Repository Pattern, Service Layer e Value Objects

---

## 🏗 Arquitetura

O sistema utiliza uma **Arquitetura em Camadas (Layered Architecture)** para garantir a separação entre as regras de negócio e a infraestrutura.

### Detalhamento dos Diagramas

| Diagrama | Finalidade | Link do Arquivo |
| :--- | :--- | :--- |
| **Casos de Uso** | Identifica atores e interações principais do sistema | [./codigos/diagrama-de-caso-de-uso.puml](./codigos/diagrama-de-caso-de-uso.puml) |
| **Classes** | Estrutura estática, entidades e regras de domínio | [./codigos/diagrama-de-classes.puml](./codigos/diagrama-de-classes.puml) |
| **Pacotes** | Organização lógica e dependências entre camadas | [./codigos/diagrama-de-pacotes.puml](./codigos/diagrama-de-pacotes.puml) |
| **Componentes** | Modularização da interface, serviços e repositórios | [./codigos/diagrama-de-componentes.puml](./codigos/diagrama-de-componentes.puml) |
| **Implantação** | Arquitetura física: servidores, rede e banco de dados | [./codigos/diagrama-de-implantacao.puml](./codigos/diagrama-de-implantacao.puml) |
| **Sequência** | Fluxo dinâmico das interações entre atores e camadas | [./codigos/diagrama-de-sequencia.puml](./codigos/diagrama-de-sequencia.puml) |

---

## 📂 Estrutura de Pastas

```text
SGO/
├── README.md                           # Documentação técnica (este arquivo)
├── codigos/                            # Fontes PlantUML (.puml)
│   ├── diagrama-de-caso-de-uso.puml
│   ├── diagrama-de-classes.puml
│   ├── diagrama-de-pacotes.puml
│   ├── diagrama-de-componentes.puml
│   └── diagrama-de-implantacao.puml
│   └── diagrama-de-sequencia.puml
└── imagens/                            # Exportações em PNG dos diagramas
    ├── diagrama-de-caso-de-uso.png
    ├── diagrama-de-classes.png
    ├── diagrama-de-pacotes.png
    ├── diagrama-de-componentes.png
    └── diagrama-de-implantação.png
    └── diagrama-de-sequencia.png
```

---

## 📜 Histórias de Usuário

### US01 – Cadastrar Competição
**Como** Organizador  
**Quero** cadastrar novas competições no sistema  
**Para que** eu possa registrar todas as modalidades e seus detalhes (nome da modalidade, data, horário, local)

**Critérios de Aceitação:**
- O sistema permite inserir nome da modalidade, data, horário e local
- Cada competição é identificada unicamente
- O sistema armazena a lista de atletas inscritos por competição

---

### US02 – Inscrever Atleta
**Como** Atleta  
**Quero** me inscrever em competições específicas do meu interesse  
**Para que** eu possa participar das modalidades desejadas

**Critérios de Aceitação:**
- O atleta pode se inscrever em várias competições
- O sistema valida se o atleta já representa outro país na mesma modalidade
- A inscrição é rejeitada se houver conflito de representação de país
- A inscrição é confirmada quando aprovada

---

### US03 – Alocar Local
**Como** Organizador  
**Quero** alocar locais para as competições garantindo evitar conflitos de horário  
**Para que** cada competição tenha um espaço exclusivo no momento de sua realização

**Critérios de Aceitação:**
- O sistema verifica a disponibilidade do local no horário da competição
- Um local só pode abrigar uma competição por vez
- O sistema identifica e evita conflitos de horário automáticamente
- A alocação é registrada no banco de dados

---

### US04 – Registrar Resultados
**Como** Organizador  
**Quero** registrar os resultados de cada competição após sua realização  
**Para que** o sistema tenha informações sobre os vencedores (1º, 2º e 3º lugares)

**Critérios de Aceitação:**
- O sistema permite registrar o atleta vencedor, segundo e terceiro colocados
- Cada resultado é associado à competição correspondente
- O sistema determina automaticamente as medalhas (ouro, prata, bronze) conforme a posição
- Os resultados são persistidos para posteriores consultas

---

### US05 – Gerar Relatório de Medalhas
**Como** Organizador  
**Quero** gerar relatórios de medalhas por país  
**Para que** eu possa visualizar o desempenho de cada nação com base em ouro, prata e bronze

**Critérios de Aceitação:**
- O sistema agrupa as medalhas por país
- Cada país é identificado pela sigla e nome
- O relatório exibe quantidade de ouro, prata e bronze conquistadas
- O relatório pode ser filtrado por período ou todas as competições

---

## 🖼️ Diagramas UML

### 1. Diagrama de Caso de Uso
Modela os principais casos de uso do sistema e os atores (Atleta e Organizador) que interagem com o SGO.

<img width="800px" height="600px" src="imagens/diagrama-de-caso-de-uso.png" alt="Diagrama de Caso de Uso"/>

---

### 2. Diagrama de Classes
Apresenta a estrutura de dados do sistema com as classes principais (Competição, Atleta, Local, Resultado, País) e seus relacionamentos.

<img width="800px" height="600px" src="imagens/diagrama-de-classes.png" alt="Diagrama de Classes"/>

---

### 3. Diagrama de Pacotes
Organiza o sistema em camadas arquiteturais (Apresentação, Serviço, Domínio, Repositório e Infraestrutura) mostrando as dependências entre pacotes.

<img width="800px" height="600px" src="imagens/diagrama-de-pacotes.png" alt="Diagrama de Pacotes"/>

---

### 4. Diagrama de Componentes
Ilustra os componentes principais do sistema (Interface de Usuário, Módulo de Inscrições, Módulo de Alocação, Módulo de Resultados, Módulo de Relatórios) e como eles interagem.

<img width="800px" height="600px" src="imagens/diagrama-de-componentes.png" alt="Diagrama de Componentes"/>

---

### 5. Diagrama de Implantação
Mostra a arquitetura física do sistema com dispositivos dos usuários, servidores de aplicação, banco de dados e infra de suporte.

<img width="800px" height="600px" src="imagens/diagrama-de-implantacao.png" alt="Diagrama de Implantação"/>

---

### 6. Diagrama de Sequência
Representa o fluxo dinâmico das interações entre os atores (Atleta e Organizador) e as camadas do sistema (Apresentação, Serviço e Dados) para os três principais fluxos operacionais do SGO:

- **Inscrição de Atletas (Regra 2):** O Atleta solicita inscrição ao `SgoController`, que delega ao `InscricaoService`. O serviço valida a representação única por modalidade e, em caso de sucesso, persiste via `IInscricaoRepository`; em caso de conflito de país, retorna erro ao atleta.
- **Alocação de Locais (Regra 3):** O Organizador define um local para uma competição. O `AlocacaoLocalService` verifica conflito de horário e, se disponível, persiste via `ILocalRepository`; caso contrário, emite alerta de conflito.
- **Registro de Resultados (Regra 4):** O Organizador informa o pódio. O `ResultadoService` cria os resultados com as respectivas medalhas e os persiste via `IResultadoRepository`, retornando o quadro de resultados.

<img width="800px" height="600px" src="imagens/diagrama-de-sequencia.png" alt="Diagrama de Sequência"/>

---

## 🔄 Como Gerar as Imagens PNG

### Usando PlantUML Online
1. Acesse https://www.plantuml.com/plantuml/uml/
2. Copie o conteúdo de cada arquivo `.puml` da pasta `codigos/`
3. Cole no editor online
4. Clique em "PNG" para baixar a imagem

### Usando PlantUML CLI (Local)
```bash
# Instalar PlantUML (requer Java)
# Windows (via Chocolatey):
choco install plantuml

# Gerar PNG:
plantuml -png codigos/diagrama-de-caso-de-uso.puml -o ../imagens/

# Gerar todos:
plantuml -png codigos/*.puml -o ../imagens/
```

### Usando Docker
```bash
docker run --rm -v $(pwd)/codigos:/input -v $(pwd)/imagens:/output \
  plantuml/plantuml:latest -png /input/*.puml -o /output
```

---

## 📋 Regras de Negócio

1. **Cadastro de Competições:** O sistema permite o cadastro de competições com nome da modalidade, data, horário, local e lista de atletas inscritos.

2. **Inscrição de Atletas:** Atletas de diferentes países se inscrevem em competições específicas. Cada atleta pode participar de várias competições, mas só pode representar um país em cada modalidade.

3. **Alocação de Locais:** Os locais para as competições são alocados de forma a evitar conflitos de horário. Um local só pode abrigar uma competição por vez.

4. **Controle de Resultados:** Após a realização das competições, os resultados são registrados, determinando o atleta vencedor e os classificados em segundo e terceiro lugares.

5. **Relatórios de Medalhas:** O sistema gera relatórios de medalhas, mostrando o desempenho de cada país com base nas medalhas de ouro, prata e bronze conquistadas.

---

## 👥 Autor

👤 **Gabriel Afonso Infante Vieira**
* 🔗 [LinkedIn](https://www.linkedin.com/in/gabrielvieira2004/)
* 🐙 [GitHub](https://github.com/Gabriel200481)
* 📧 [Email](mailto:gabrielvieira200481@gmail.com)

---

## 🙏 Agradecimentos

- **Engenharia de Software - PUC Minas**
- **Prof. João Paulo Carneiro Aramuni** - Pela orientação na disciplina de Projeto de Software

---

## 📄 Licença

Este projeto é estritamente acadêmico e distribuído sob a Licença MIT.

---

**Última atualização:** Maio de 2026

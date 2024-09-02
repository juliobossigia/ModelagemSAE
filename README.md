# Sistema de Acompanhamento Educacional (SAE)

## Descrição do Projeto
O Sistema de Acompanhamento Educacional (SAE) é uma plataforma desenvolvida para facilitar o registro e acompanhamento do comportamento e desempenho dos alunos do ensino técnico. O sistema permite que docentes e servidores realizem registros sobre os alunos, encaminhem informações para setores específicos e agendem atendimentos com profissionais como psicólogos, assistentes sociais e membros do NAI.

Este projeto está sendo desenvolvido como parte do trabalho da disciplina de Modelagem de Software, abordando técnicas de design de software e incluindo padrões de projeto.
## Estrutura do Projeto

### 1. **Gerência de Configuração com GIT e GitHub**
   - **Repositório**: O repositório do projeto está hospedado no GitHub, facilitando o versionamento e a colaboração entre os desenvolvedores.
   - **Branches**: Utilizamos a estratégia de branching com as seguintes convenções:
     - `main`: Branch principal que contém o código de produção estável.
     - `develop`: Branch de desenvolvimento onde novas funcionalidades.
     - `Interface*`: Branches para o desenvolvimento da prototipagem de interfaces do sistema.
   - **Commits**: Os commits são feitos com mensagens descritivas e concisas, permitindo fácil rastreamento das alterações.
   - **Pull Requests**: Todo o código deve ser revisado via pull requests antes de ser integrado na branch principal.
   - **GitHub Actions**: A integração contínua é gerenciada via GitHub Actions, automatizando testes e builds.

### 2. **Padrões de Projeto**
   - **Diagrama de Classes**: O sistema implementa os padrões Singleton, DAO e MVC, garantindo modularidade e fácil manutenção.
   - **Diagrama de Sequência**: Diagrama de sequência detalhando a interação entre os componentes utilizando os padrões de projeto mencionados.

### 3. **Prototipação com Interfaces**
   - Protótipos de interfaces para o sistema foram criados para facilitar a visualização e o design da experiência do usuário.

### 4. **Plano de Testes**
   - O plano de testes abrange testes unitários, de integração e funcionais para garantir a qualidade e a estabilidade do sistema.

### 5. **Diagrama de Implantação**
   - O diagrama de implantação ilustra a arquitetura do sistema, incluindo servidores, bancos de dados e outros componentes.

## Como Contribuir
1. **Clone o Repositório**
   ```bash
   git clone https://github.com/seu-usuario/SAE.git

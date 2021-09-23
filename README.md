# Sistema de teleatendimento médico para consulta de pacientes via APP/Web

**Objetivos:** Desenvolver um Plano de Negócios para sua *startup* (empresa de tecnologia). Quais requisitos funcionais, requisitos não funcionais e regras de negócios serão necessários para a confecção deste sistema (em detalhes técnicos). Confeccionar os seguintes diagramas: Caso de Uso (descritivo e seu design em 
si), Diagrama de Atividades, Diagrama de Classes, Diagrama de Sequência, Diagrama de 
Componentes e de Implantação. Qual metodologia frente às Normas Internacionais ISO, CMMI, MPS.br - explique como a metodologia funciona no detalhe e justifique sua opção tecnicamente. Gerenciar seu novo projeto, definindo um escopo, redigindo um Termo de Abertura de Projeto, para o Planejamento: Definição de Matriz 
de Papéis de Responsabilidades, Cronograma de atividades e custos, Análise de Riscos e, ao final, listando Lições Aprendidas. Desenvolva o mecanismo de acesso ao banco de dados em linguagem C#. Esse 
mecanismo será o responsável por oferecer acesso a um trecho do banco de dados 
por parte do resto do sistema. Sempre que um trecho do sistema precisar acessar esse trecho do banco de dados, deverá fazê-lo por meio desse mecanismo desenvolvido por sua equipe. Crie um protótipo de interface gráfica com o usuário em ASP .Net que permita que o usuário interaja com os dados modelados por esse trecho do banco de dados. Crie um protótipo de interface gráfica com o usuário em Android que permita que 
o usuário interaja com os dados modelados por esse trecho do banco de dados. Confeccionar o Diagrama Entidade-Relacionamento (DER).

## Requisitos Funcionais
- [ ] **RF-01 Efetuar login**: O paciente deverá ser identificado através de um login e senha para poder realizar uma consulta. Assim como o médico deverá logar para ver quais pacientes passarão nele em ordem de chegada. **Atores**: Usuário. **Prioridade**: Essencial.
- [ ] **RF-02 Efetuar logoff**: Deve ser possivel que o usuario finalize a sua sessão no sistema. **Atores**. Usuário. **Prioridade**: Essencial 
- [ ] **RF-03 Visualizar a consulta agendada**: O paciente deve poder visualizar a consulta que foi agendada. Assim como o medico deve poder visualizar as consultas que foram agendadas para passar nele. **Atores**: Usuário. **Prioridade**: Essencial.
- [ ] **RF-04 Visualizar consultas que já foram finalizadas**: Deve ser possivel ao paciente visualizar as consultas que já foram finalizadas. **Atores**: Usuario. **Prioridade**: Essencial.
- [ ] **RF-05 Visualizar detalhes da consulta**: Tanto ao paciente; quanto ao medico deve ser possivel visualizar detalhes da consulta. **Atores**: Usuário. **Prioridade**: Essencial.
- [ ] **RF-06 Alterar o estado da consulta**: Deve ser possivel ao medico alterar o estado da consulta para: "Em progresso", "Finalizada" ou "Agendada". **Atores**: Medico. **Prioridade**: Essencial.
- [ ] **RF-06 Agendar uma consulta**: Deve ser possivel ao paciente agendar consultas. **Atores**: Paciente. **Prioridade**: Essencial.

## Requisitos não-funcionais
- [ ] **RNF-01 Usabilidade**: O sistema deve fazer uso de uma interface amigável e intuitiva para permitir a utilização por usuários menos experientes.
- [ ] **RNF-02 Usabilidade**: As mensagens de erros devem ser claras e concisas para o entendimento perfeito do usuário do sistema.
- [ ] **RNF-03 Usabilidade**: Um bom tratamento de exceções é imprescindível, de forma a facilitar eventuais manutenções no sistema.
- [ ] **RNF-4 Confiabilidade**: Deve haver consistência e integridade nas informações, o que é garantido pelo uso do sistema de gerenciamento de banco de dados.
- [ ] **RNF-5 Confiabilidade**: O sistema deve estar sempre disponível. Caso seja necessária alguma manutenção no sistema, fazê-lo em uma versão para testes, não disponível para os usuários, e então aplicar as mudanças na versão disponível para os usuários.
- [ ] **RNF-06 Performance**: O espaço disponível em disco para informações deve ser capaz de armazenar todos os dados que forem cadastrados ou atualizados a partir do servidor.
- [ ] **RNF-07 Performance**: É necessario que o tempo de resposta a consultas sejam rápidas.
- [ ] **RNF-08 Segurança**: Todos os usuários, para terem acesso ao sistema, devem informar login e senha de identificação.
- [ ] **RNF-09 Segurança**: Os dados dos usuários só poderão ser acessados por pessoas autorizadas.
- [ ] **RNF-10 Requisitos Externos**: Caberá aos usuários garantir a veracidade de todas as informações sobre os dados cadastrais.
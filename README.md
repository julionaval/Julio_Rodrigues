# Júlio da silva rodrigues
Repositorio Gerencia de projetos software 2024

## Sistema para: Gerenciador de tarefas



# 1. introdução
O Sistema de Gerenciamento de Tarefas foi desenvolvido para otimizar a organização e a execução de atividades, proporcionando uma solução prática e eficiente tanto para o trabalho individual quanto para a colaboração em grupo. Em um mundo cada vez mais dinâmico, a capacidade de gerenciar tarefas de forma eficaz é crucial para aumentar a produtividade e garantir que prazos sejam cumpridos. Com uma interface intuitiva, o sistema visa facilitar o registro e a visualização das tarefas, promovendo um ambiente de trabalho mais estruturado.

Este sistema permite que os usuários configurem perfis personalizados, adaptando as funcionalidades às suas necessidades específicas. Seja para o gerenciamento de projetos em equipe ou para o controle de tarefas pessoais, os recursos disponíveis garantem uma abordagem flexível e acessível. A possibilidade de definir prioridades, categorizar atividades e estabelecer prazos contribui para uma visão clara do progresso das tarefas, permitindo que os usuários se concentrem no que realmente importa.

Além disso, o sistema oferece ferramentas para o acompanhamento contínuo das tarefas, com opções de consulta e relatórios que facilitam a análise de desempenho. Dessa forma, é possível identificar gargalos, ajustar estratégias e promover uma comunicação eficaz entre os membros da equipe. Com o Sistema de Gerenciamento de Tarefas, as organizações podem não apenas cumprir prazos, mas também cultivar uma cultura de responsabilidade e colaboração, resultando em um ambiente produtivo e motivador.

<!---
Comentario
--->
****
# 2. Objetivos e Metas 
O objetivo específico é que o sistema permita 
acompanhar as tarefas que estejam em andamento, 
concluídas, pendentes e arquivadas.
A meta é que todas as tarefas tenham um registro para
que sejam registradas e controladas.

<!---
Comentario
--->


# 3. Metodologia de desenvolvimento
Kanban: Foca na visualização do trabalho em andamento através de quadros que mostram as etapas das tarefas. Isso ajuda a identificar gargalos e priorizar o que deve ser feito a seguir, promovendo um fluxo contínuo de trabalho.
<!---
Descrição -  descrito acima: reescreva em até 2 paragrafos usando uma linguagem informal.
--->

# 4. Papeis e responsabilidades
1. Designer de UX/UI

Criar interfaces intuitivas e amigáveis para o usuário.
Realizar pesquisas com usuários para entender suas necessidades e comportamentos.
Desenvolver protótipos e wireframes para validar conceitos de design.
Colaborar com desenvolvedores para garantir que o design seja implementado corretamente.

2. Testador (QA)

Planejar e executar testes para garantir a qualidade do sistema.
Identificar e reportar bugs e problemas encontrados.
Validar que as funcionalidades atendem aos requisitos definidos.
Colaborar com a equipe de desenvolvimento para resolver problemas detectados.

3. Gerente de Projeto

Planejar e monitorar o progresso do projeto, assegurando que os prazos sejam cumpridos.
Gerenciar recursos e orçamentos do projeto.
Comunicar-se com stakeholders para atualizá-los sobre o status do projeto.
Identificar riscos e desenvolver estratégias de mitigação.

4. Usuários Finais

Fornecer feedback sobre a usabilidade e funcionalidades do sistema.
Participar de testes beta ou sessões de feedback.
Utilizar o sistema conforme as diretrizes para maximizar sua eficácia.

5. Administrador do Sistema

Gerenciar a infraestrutura do sistema e garantir sua disponibilidade.
Implementar e monitorar medidas de segurança.
Fornecer suporte técnico aos usuários.
Gerenciar a integração com outras ferramentas e sistemas.
<!---


Para o contexto de papeis e responsabilidades descrito acima, gere uma tabela em Markdown, colocando os itnes **acima** e escreva em linguagem informal.
--->

# 5. Requisitos

## 5.1. Funcionais

1. Gestão de Tarefas
   
Criar Tarefa: O usuário deve ser capaz de criar novas tarefas, especificando título, descrição, prioridade e data de vencimento.
Editar Tarefa: O usuário deve poder editar as informações de uma tarefa existente.
Excluir Tarefa: O sistema deve permitir que o usuário exclua uma tarefa.
Marcar como Concluída: O usuário deve ter a opção de marcar uma tarefa como concluída.

2. Organização de Tarefas

Listar Tarefas: O sistema deve exibir uma lista de todas as tarefas do usuário, com opções de filtragem por status (pendente, concluída) e prioridade.
Priorizar Tarefas: O usuário deve poder definir e alterar a prioridade das tarefas (alta, média, baixa).
Adicionar Etiquetas/Categorias: O sistema deve permitir que o usuário adicione etiquetas ou categorias às tarefas para melhor organização.

3. Colaboração
Compartilhar Tarefas: O usuário deve poder compartilhar tarefas com outros usuários ou equipes.
Comentários: O sistema deve permitir que os usuários adicionem comentários às tarefas, facilitando a comunicação.
Notificações: O sistema deve enviar notificações para os usuários sobre atualizações em tarefas compartilhadas ou prazos que estão se aproximando.

4. Gerenciamento de Prazos
Definir Datas de Vencimento: O usuário deve poder definir uma data de vencimento para cada tarefa.
Alertas e Lembretes: O sistema deve enviar lembretes automáticos para os usuários sobre tarefas com prazos próximos.
Visualização de Prazos: O usuário deve ter a opção de visualizar as tarefas em uma linha do tempo ou calendário.

5. Relatórios e Estatísticas
Geração de Relatórios: O sistema deve permitir a geração de relatórios sobre o progresso das tarefas e produtividade do usuário.
Estatísticas de Conclusão: O usuário deve poder visualizar estatísticas sobre tarefas concluídas, pendentes e atrasadas.

6. Autenticação e Autorização
Registro de Usuário: O sistema deve permitir que novos usuários se registrem e criem uma conta.
Login/Logout: O usuário deve ser capaz de fazer login e logout de sua conta.
Recuperação de Senha: O sistema deve fornecer um mecanismo para recuperação de senha em caso de esquecimentos.

7. Configurações do Usuário
Perfil do Usuário: O sistema deve permitir que os usuários editem suas informações de perfil.
Preferências de Notificação: O usuário deve poder definir suas preferências de notificação (e-mail, pop-up, etc.).

8. Integrações
Integração com Calendários: O sistema deve permitir a integração com calendários externos (como Google Calendar).
APIs: O sistema deve fornecer APIs para que outras aplicações possam interagir com as funcionalidades do gerenciador de tarefas.
<!---

Para o contexto de requisitos funcionais, crie uma tabela em markdown ampliando a lista acima em mais 5 itens.
--->
## 5.2. Não Funcionais
<!---

Para o contexto de requisitos não funcionais, crie uma tabela em markdown ampliando a lista acima em mais 5 itens.
--->
# 6. Arquitetura e módulos

<!---

--->

# 7. Plano de desenvolvimento

<!---

--->

## 7.1. Lista de recursos tecnológicos

1 acesso aos logs do firewall
2 acesso à rede para analisar o tráfego

# 8. Orçamento e cronograma geral

## 8.1. Orçamento

## 8.2. cronograma geral

# 9. testes

# 10 Qualidade
1. Desempenho
Tempo de Resposta: O sistema deve responder a ações do usuário (como criar, editar ou excluir tarefas) em no máximo 2 segundos.
Capacidade de Carga: O sistema deve suportar até 500 usuários simultâneos sem degradação de desempenho.
Escalabilidade: O sistema deve ser capaz de escalar horizontalmente para acomodar um aumento no número de usuários e dados.

2. Usabilidade
Interface Intuitiva: A interface deve ser fácil de navegar e compreensível para usuários com diferentes níveis de experiência.
Acessibilidade: O sistema deve ser acessível a pessoas com deficiências, seguindo diretrizes de acessibilidade, como WCAG.
Documentação: A documentação do usuário deve ser clara e disponível online, incluindo tutoriais e FAQs.

3. Segurança
Autenticação: O sistema deve suportar autenticação de dois fatores para garantir a segurança dos dados dos usuários.
Criptografia: Todos os dados sensíveis (como senhas e informações pessoais) devem ser armazenados e transmitidos de forma criptografada.
Controle de Acesso: O sistema deve implementar controle de acesso baseado em funções, garantindo que os usuários tenham acesso apenas às funcionalidades e dados relevantes.

4. Manutenibilidade
Código Limpo: O código deve ser bem documentado e seguir padrões de codificação para facilitar a manutenção.
Testabilidade: O sistema deve ser projetado de forma a facilitar a realização de testes automatizados e manuais.
Atualizações: O sistema deve permitir atualizações regulares sem interrupção significativa no serviço.

5. Compatibilidade
Navegadores: O sistema deve ser compatível com os principais navegadores (Chrome, Firefox, Safari, Edge).
Dispositivos: O sistema deve ser responsivo, funcionando bem em dispositivos desktop e móveis.
Integração: O sistema deve ser capaz de se integrar com outras ferramentas populares, como plataformas de comunicação e calendários.

6. Confiabilidade
Tempo de Atividade: O sistema deve garantir uma disponibilidade de 99,9% durante o horário comercial.
Recuperação de Falhas: O sistema deve ter um plano de recuperação de desastres, com backup automático de dados a cada 24 horas.
Tratamento de Erros: O sistema deve fornecer mensagens de erro claras e úteis, guiando o usuário na resolução de problemas

# 11. Implantação

# 12. Riscos e mitigações

<!---
isto é um comentário !
-->
| Riscos | Mitigações |
|--------|------------|
| 1.       |  |
| 2.       |  |
| 3.       |  |

# 13. Cálculo de FPA

# 14. Anexos

## 14.1 Telas do Sistema
![Exercicio-25SET2024](https://github.com/user-attachments/assets/0437e61b-e2c5-4b45-8aba-32ebd34506b7)
![Project_status](https://github.com/user-attachments/assets/bc284d13-5fa3-4fed-ab16-a753b3969d42)
![Task_Status](https://github.com/user-attachments/assets/7e65c6c7-474d-4edf-a40d-de737842a840)
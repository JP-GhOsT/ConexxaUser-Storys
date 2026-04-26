### User Stories para o Produto Connexa

---

#### 1. *Criar Grupo de Estudo*
*Descrição:*  
Como um *aluno*, eu quero criar um grupo de estudo com informações estruturadas para que eu possa organizar melhor os participantes e o objetivo do grupo.

*Critérios de Aceitação:*  
1. O sistema deve permitir que o aluno insira a matéria, objetivo, local (online/presencial) e limite de participantes ao criar o grupo.  
2. O sistema deve validar que todos os campos obrigatórios foram preenchidos antes de criar o grupo.  
3. O sistema deve exibir uma mensagem de confirmação após a criação bem-sucedida do grupo.  

*Prioridade:* Alta  
*Justificativa:* Este é o principal recurso da plataforma e resolve diretamente o problema identificado.

---
#### 2. *Buscar Grupos de Estudo*
*Descrição:*  
Como um *aluno*, eu quero buscar grupos de estudo por matéria e objetivo para que eu possa encontrar grupos relevantes para minhas necessidades.

*Critérios de Aceitação:*  
1. O sistema deve permitir a busca por filtros como matéria, objetivo e local (online/presencial).  
2. O sistema deve exibir os grupos correspondentes aos filtros aplicados em uma lista organizada.  
3. O sistema deve permitir que o aluno visualize os detalhes de um grupo antes de solicitar participação.  

*Prioridade:* Alta  
*Justificativa:* Facilitar a busca por grupos é essencial para atrair e engajar os usuários.

---

#### 3. *Participar de um Grupo*
*Descrição:*  
Como um *aluno*, eu quero solicitar participação em um grupo de estudo para que eu possa colaborar com outros colegas.

*Critérios de Aceitação:*  
1. O sistema deve permitir que o aluno envie uma solicitação de participação para o administrador do grupo.  
2. O sistema deve notificar o administrador do grupo sobre novas solicitações.  
3. O sistema deve exibir o status da solicitação (pendente, aceita, recusada) para o aluno.  

*Prioridade:* Alta  
*Justificativa:* A funcionalidade é essencial para conectar os alunos e promover a colaboração.

---

#### 4. *Gerenciar Grupos Criados*
*Descrição:*  
Como um *aluno*, eu quero gerenciar os grupos que criei para que eu possa aceitar ou recusar solicitações de participação e editar informações do grupo.

*Critérios de Aceitação:*  
1. O sistema deve permitir que o criador do grupo aceite ou recuse solicitações de participação.  
2. O sistema deve permitir a edição das informações do grupo, como objetivo ou limite de participantes.  
3. O sistema deve exibir uma lista de participantes confirmados no grupo.  

*Prioridade:* Média  
*Justificativa:* Embora importante, esta funcionalidade é secundária em relação à criação e busca de grupos.

---

#### 5. *Gerenciar Usuários (Administrador)*
*Descrição:*  
Como um *administrador da plataforma*, eu quero gerenciar os usuários da plataforma para que eu possa garantir o bom funcionamento e a segurança do sistema.

*Critérios de Aceitação:*  
1. O sistema deve permitir que o administrador visualize uma lista de usuários cadastrados.  
2. O sistema deve permitir que o administrador bloqueie ou exclua usuários que violem as regras da plataforma.  
3. O sistema deve registrar todas as ações administrativas para auditoria.  

*Prioridade:* Média  
*Justificativa:* Essencial para manter a integridade da plataforma, mas não impacta diretamente os alunos.

---

#### 6. *Notificações*
*Descrição:*  
Como um *aluno*, eu quero receber notificações sobre atualizações nos grupos para que eu possa acompanhar as atividades em tempo real.

*Critérios de Aceitação:*  
1. O sistema deve enviar notificações para o aluno quando sua solicitação de participação for aceita ou recusada.  
2. O sistema deve notificar os participantes sobre alterações nas informações do grupo (ex.: mudança de local).  
3. O sistema deve permitir que o aluno configure suas preferências de notificação (ex.: e-mail, push).  

*Prioridade:* Média  
*Justificativa:* Melhora a experiência do usuário, mas não é essencial para o funcionamento inicial da plataforma.

---

#### 7. *Desempenho e Escalabilidade*
*Descrição:*  
Como um *administrador da plataforma*, eu quero que o sistema suporte um grande número de usuários simultâneos para que a plataforma funcione sem interrupções.

*Critérios de Aceitação:*  
1. O sistema deve suportar pelo menos 3.000 usuários simultâneos sem degradação de desempenho.  
2. O tempo de resposta para ações como busca de grupos deve ser inferior a 2 segundos.  
3. O sistema deve ser monitorado para identificar e resolver gargalos de desempenho.  

*Prioridade:* Alta  
*Justificativa:* A escalabilidade é crucial para o sucesso da plataforma em longo prazo.

---

#### 8. *Acessibilidade*
*Descrição:*  
Como um *aluno*, eu quero que a plataforma seja acessível para pessoas com deficiência para que todos possam utilizá-la sem barreiras.

*Critérios de Aceitação:*  
1. O sistema deve ser compatível com leitores de tela para alunos com deficiência visual.  
2. O sistema deve permitir navegação completa por teclado.  
3. O sistema deve seguir as diretrizes WCAG 2.1 (nível AA).  

*Prioridade:* Alta  
*Justificativa:* Inclusão é um requisito essencial para atender a todos os usuários.

---

### User Stories Focadas na Experiência de Busca e Descoberta de Grupos

---

#### 1. *Busca por Grupos*
*Descrição:*  
Como um *aluno*, eu quero buscar grupos de estudo por filtros específicos para que eu possa encontrar grupos que atendam às minhas necessidades.

*Critérios de Aceitação:*  
1. O sistema deve permitir a busca por filtros como matéria, objetivo, local (online/presencial) e limite de participantes.  
2. O sistema deve exibir os resultados da busca em uma lista organizada e paginada.  
3. O sistema deve permitir a combinação de múltiplos filtros para refinar os resultados.  

*Prioridade:* Alta  
*Justificativa:* A busca eficiente é essencial para conectar os alunos aos grupos mais relevantes.

---

---

#### 2. *Sugestões de Grupos*
*Descrição:*  
Como um *aluno*, eu quero receber sugestões de grupos com base nos meus interesses para que eu possa descobrir grupos relevantes sem precisar buscar manualmente.

*Critérios de Aceitação:*  
1. O sistema deve exibir sugestões de grupos com base nas matérias e objetivos mais buscados pelo aluno.  
2. O sistema deve atualizar as sugestões automaticamente conforme novos grupos são criados.  
3. O sistema deve permitir que o aluno salve grupos sugeridos para análise posterior.  

*Prioridade:* Média  
*Justificativa:* Facilita a descoberta de grupos, melhorando a experiência do usuário.

---

#### 3. *Visualização de Grupos*
*Descrição:*  
Como um *aluno*, eu quero visualizar os detalhes de um grupo de estudo para que eu possa decidir se ele é adequado para mim.

*Critérios de Aceitação:*  
1. O sistema deve exibir informações detalhadas do grupo, como matéria, objetivo, local, limite de participantes e participantes atuais.  
2. O sistema deve permitir que o aluno visualize o perfil do criador do grupo.  
3. O sistema deve exibir um botão para solicitar participação diretamente na página de detalhes.  

*Prioridade:* Alta  
*Justificativa:* A visualização detalhada é crucial para a tomada de decisão do aluno.

---

#### 4. *Busca por Localização*
*Descrição:*  
Como um *aluno*, eu quero buscar grupos presenciais próximos à minha localização para que eu possa participar de grupos acessíveis.

*Critérios de Aceitação:*  
1. O sistema deve permitir que o aluno insira sua localização ou use o GPS para buscar grupos próximos.  
2. O sistema deve exibir a distância aproximada entre o aluno e os grupos presenciais encontrados.  
3. O sistema deve permitir a combinação de filtros de localização com outros filtros, como matéria e objetivo.  

*Prioridade:* Média  
*Justificativa:* A busca por localização melhora a experiência de alunos que preferem encontros presenciais.

---

#### 5. *Busca por Palavras-chave*
*Descrição:*  
Como um *aluno*, eu quero buscar grupos usando palavras-chave para que eu possa encontrar grupos rapidamente.

*Critérios de Aceitação:*  
1. O sistema deve permitir a busca por palavras-chave no título, descrição ou objetivo dos grupos.  
2. O sistema deve exibir os resultados ordenados por relevância.  
3. O sistema deve destacar as palavras-chave encontradas nos resultados exibidos.  

*Prioridade:* Alta  
*Justificativa:* A busca por palavras-chave é uma funcionalidade básica e esperada pelos usuários.

---

### User Stories com Critérios de Aceitação no Formato Given/When/Then (Gherkin)

---

#### 1. *Busca por Grupos*
*Descrição:*  
Como um *aluno*, eu quero buscar grupos de estudo por filtros específicos para que eu possa encontrar grupos que atendam às minhas necessidades.

*Critérios de Aceitação:*  
- *Cenário 1:* Busca com filtros específicos  
  Given que o aluno está na página de busca,  
  When ele aplica filtros como matéria, objetivo e local,  
  Then o sistema deve exibir uma lista de grupos correspondentes aos filtros aplicados.  

- *Cenário 2:* Lista de resultados organizada  
  Given que o aluno realizou uma busca,  
  When os resultados são exibidos,  
  Then o sistema deve apresentar os grupos em uma lista organizada e paginada.  

- *Cenário 3:* Combinação de múltiplos filtros  
  Given que o aluno deseja refinar sua busca,  
  When ele combina múltiplos filtros,  
  Then o sistema deve exibir apenas os grupos que atendem a todos os critérios selecionados.  

---

#### 2. *Sugestões de Grupos*
*Descrição:*  
Como um *aluno*, eu quero receber sugestões de grupos com base nos meus interesses para que eu possa descobrir grupos relevantes sem precisar buscar manualmente.

*Critérios de Aceitação:*  
- *Cenário 1:* Sugestões baseadas em interesses  
  Given que o aluno possui histórico de buscas ou interesses cadastrados,  
  When ele acessa a página inicial,  
  Then o sistema deve exibir sugestões de grupos relevantes com base nesses dados.  

- *Cenário 2:* Atualização automática de sugestões  
  Given que novos grupos são criados,  
  When esses grupos correspondem aos interesses do aluno,  
  Then o sistema deve atualizar as sugestões exibidas automaticamente.  

- *Cenário 3:* Salvar grupos sugeridos  
  Given que o aluno visualiza um grupo sugerido,  
  When ele decide salvar o grupo,  
  Then o sistema deve permitir que o grupo seja salvo para análise posterior.  

---

#### 3. *Visualização de Grupos*
*Descrição:*  
Como um *aluno*, eu quero visualizar os detalhes de um grupo de estudo para que eu possa decidir se ele é adequado para mim.

*Critérios de Aceitação:*  
- *Cenário 1:* Exibição de informações detalhadas  
  Given que o aluno acessa a página de detalhes de um grupo,  
  When o grupo é exibido,  
  Then o sistema deve mostrar informações como matéria, objetivo, local, limite de participantes e participantes atuais.  

- *Cenário 2:* Visualização do perfil do criador  
  Given que o aluno está na página de detalhes do grupo,  
  When ele deseja saber mais sobre o criador,  
  Then o sistema deve exibir o perfil do criador do grupo.  

- *Cenário 3:* Solicitação de participação  
  Given que o aluno está na página de detalhes do grupo,  
  When ele decide participar do grupo,  
  Then o sistema deve exibir um botão para enviar a solicitação de participação.  

---

#### 4. *Busca por Localização*
*Descrição:*  
Como um *aluno*, eu quero buscar grupos presenciais próximos à minha localização para que eu possa participar de grupos acessíveis.

*Critérios de Aceitação:*  
- *Cenário 1:* Busca por localização  
  Given que o aluno deseja buscar grupos presenciais,  
  When ele insere sua localização ou utiliza o GPS,  
  Then o sistema deve exibir grupos próximos à localização informada.  

- *Cenário 2:* Exibição da distância  
  Given que o aluno realizou uma busca por localização,  
  When os resultados são exibidos,  
  Then o sistema deve mostrar a distância aproximada entre o aluno e os grupos encontrados.  

- *Cenário 3:* Combinação de filtros com localização  
  Given que o aluno deseja refinar sua busca,  
  When ele combina filtros de localização com outros critérios,  
  Then o sistema deve exibir apenas os grupos que atendem a todos os filtros aplicados.  

---

#### 5. *Busca por Palavras-chave*
*Descrição:*  
Como um *aluno*, eu quero buscar grupos usando palavras-chave para que eu possa encontrar grupos rapidamente.

*Critérios de Aceitação:*  
- *Cenário 1:* Busca por palavras-chave  
  Given que o aluno deseja buscar grupos,  
  When ele insere uma palavra-chave no campo de busca,  
  Then o sistema deve exibir grupos que contenham a palavra-chave no título, descrição ou objetivo.  

- *Cenário 2:* Ordenação por relevância  
  Given que o aluno realizou uma busca por palavras-chave,  
  When os resultados são exibidos,  
  Then o sistema deve ordená-los por relevância.  

- *Cenário 3:* Destaque das palavras-chave  
  Given que o aluno visualiza os resultados da busca,  
  When um grupo contém a palavra-chave buscada,  
  Then o sistema deve destacar a palavra-chave nos resultados exibidos.  

---

### Requisitos Importantes Não Incluídos e User Stories

Após análise, alguns requisitos importantes para uma plataforma colaborativa universitária que ainda não foram abordados incluem:

1. *Sistema de Avaliação de Grupos e Participantes*  
   Para garantir a qualidade das interações e promover um ambiente colaborativo.

2. *Sistema de Mensagens Internas*  
   Para facilitar a comunicação direta entre os membros do grupo.

3. *Integração com Calendário*  
   Para organizar reuniões e prazos de forma eficiente.

---

#### 1. *Avaliação de Grupos e Participantes*
*Descrição:*  
Como um *aluno*, eu quero avaliar os grupos e participantes após a conclusão de um objetivo para que eu possa ajudar outros alunos a escolherem grupos de qualidade.

*Critérios de Aceitação:*  
- *Cenário 1:* Avaliação de grupos  
  Given que o aluno participou de um grupo,  
  When o objetivo do grupo é concluído,  
  Then o sistema deve permitir que o aluno avalie o grupo com uma nota e um comentário.  

- *Cenário 2:* Avaliação de participantes  
  Given que o aluno participou de um grupo,  
  When o objetivo do grupo é concluído,  
  Then o sistema deve permitir que o aluno avalie outros participantes com base em critérios como colaboração e pontualidade.  

- *Cenário 3:* Exibição de avaliações  
  Given que um aluno está visualizando os detalhes de um grupo,  
  When o grupo possui avaliações,  
  Then o sistema deve exibir a média das avaliações e os comentários mais relevantes.  

*Prioridade:* Média  
*Justificativa:* Promove a confiança e a qualidade das interações na plataforma.

---

#### 2. *Sistema de Mensagens Internas*
*Descrição:*  
Como um *aluno*, eu quero enviar mensagens diretas para outros membros do grupo para que eu possa me comunicar de forma rápida e eficiente.

*Critérios de Aceitação:*  
- *Cenário 1:* Envio de mensagens  
  Given que o aluno é membro de um grupo,  
  When ele acessa a página do grupo,  
  Then o sistema deve permitir o envio de mensagens diretas para outros membros.  

- *Cenário 2:* Notificações de mensagens  
  Given que o aluno recebeu uma mensagem,  
  When ele acessa a plataforma,  
  Then o sistema deve exibir uma notificação indicando a nova mensagem.  

- *Cenário 3:* Histórico de mensagens  
  Given que o aluno enviou ou recebeu mensagens,  
  When ele acessa a conversa,  
  Then o sistema deve exibir o histórico completo das mensagens trocadas.  

*Prioridade:* Alta  
*Justificativa:* Comunicação eficiente é essencial para o sucesso dos grupos.

---

#### 3. *Integração com Calendário*
*Descrição:*  
Como um *aluno*, eu quero integrar os eventos do grupo ao meu calendário para que eu possa organizar melhor meus compromissos.

*Critérios de Aceitação:*  
- *Cenário 1:* Criação de eventos  
  Given que o aluno é membro de um grupo,  
  When o grupo define uma reunião ou prazo,  
  Then o sistema deve permitir que o evento seja adicionado ao calendário do aluno.  

- *Cenário 2:* Integração com ferramentas externas  
  Given que o aluno utiliza um calendário externo (ex.: Google Calendar),  
  When ele sincroniza sua conta,  
  Then o sistema deve adicionar os eventos do grupo ao calendário externo.  

- *Cenário 3:* Notificações de eventos  
  Given que um evento está próximo,  
  When o aluno acessa a plataforma,  
  Then o sistema deve exibir uma notificação lembrando do evento.  

*Prioridade:* Média  
*Justificativa:* Ajuda os alunos a gerenciarem melhor seu tempo e compromissos.

---

### User Stories Focadas em Segurança, Desempenho e Acessibilidade

---

#### *Segurança*

---

#### 1. *Autenticação Segura*
*Descrição:*  
Como um *aluno*, eu quero que a plataforma utilize autenticação segura para que meus dados pessoais estejam protegidos.

*Critérios de Aceitação:*  
- *Cenário 1:* Login com autenticação de dois fatores  
  Given que o aluno está tentando fazer login,  
  When ele insere suas credenciais corretas,  
  Then o sistema deve solicitar um código de verificação enviado por e-mail ou SMS.  

- *Cenário 2:* Bloqueio após tentativas de login inválidas  
  Given que o aluno insere credenciais incorretas,  
  When ele tenta fazer login mais de 5 vezes consecutivas,  
  Then o sistema deve bloquear temporariamente a conta e notificar o aluno.  

- *Cenário 3:* Criptografia de senhas  
  Given que o aluno cria ou altera sua senha,  
  When a senha é salva no sistema,  
  Then o sistema deve armazená-la de forma criptografada.  

*Prioridade:* Alta  
*Justificativa:* Protege os dados dos usuários e evita acessos não autorizados.

---

#### 2. *Controle de Acesso*
*Descrição:*  
Como um *administrador da plataforma*, eu quero gerenciar permissões de acesso para que apenas usuários autorizados possam realizar ações específicas.

*Critérios de Aceitação:*  
- *Cenário 1:* Permissões de administrador  
  Given que o administrador acessa o painel de controle,  
  When ele tenta realizar ações administrativas,  
  Then o sistema deve verificar suas permissões antes de permitir a ação.  

- *Cenário 2:* Restrições para alunos  
  Given que um aluno tenta acessar uma funcionalidade restrita,  
  When ele não possui as permissões necessárias,  
  Then o sistema deve exibir uma mensagem de erro e negar o acesso.  

- *Cenário 3:* Logs de acesso  
  Given que um usuário realiza ações na plataforma,  
  When a ação é concluída,  
  Then o sistema deve registrar a ação em um log para auditoria.  

*Prioridade:* Alta  
*Justificativa:* Garante que apenas usuários autorizados realizem ações críticas.

---

#### 3. *Proteção contra Ataques*
*Descrição:*  
Como um *administrador da plataforma*, eu quero que o sistema detecte e previna ataques como SQL Injection e XSS para que a plataforma permaneça segura.

*Critérios de Aceitação:*  
- *Cenário 1:* Validação de entradas  
  Given que um usuário insere dados em um formulário,  
  When os dados são enviados,  
  Then o sistema deve validar e sanitizar as entradas para evitar ataques de injeção.  

- *Cenário 2:* Prevenção de scripts maliciosos  
  Given que um usuário insere scripts em campos de texto,  
  When os dados são exibidos,  
  Then o sistema deve impedir a execução de scripts maliciosos.  

- *Cenário 3:* Monitoramento de atividades suspeitas  
  Given que o sistema detecta padrões de uso anormais,  
  When uma possível tentativa de ataque é identificada,  
  Then o sistema deve bloquear temporariamente o acesso e notificar o administrador.  

*Prioridade:* Alta  
*Justificativa:* Protege a integridade da plataforma e os dados dos usuários.

---

#### *Desempenho*

---

#### 4. *Tempo de Resposta Rápido*
*Descrição:*  
Como um *aluno*, eu quero que as páginas carreguem rapidamente para que eu possa usar a plataforma sem atrasos.

*Critérios de Aceitação:*  
- *Cenário 1:* Tempo de carregamento  
  Given que o aluno acessa qualquer página da plataforma,  
  When a página é carregada,  
  Then o tempo de resposta deve ser inferior a 2 segundos.  

- *Cenário 2:* Otimização de imagens  
  Given que a página contém imagens,  
  When as imagens são carregadas,  
  Then o sistema deve utilizar versões otimizadas para reduzir o tempo de carregamento.  

- *Cenário 3:* Cache de conteúdo  
  Given que o aluno acessa a mesma página repetidamente,  
  When o conteúdo não foi alterado,  
  Then o sistema deve carregar os dados do cache local.  

*Prioridade:* Alta  
*Justificativa:* Melhora a experiência do usuário e reduz a taxa de abandono.

---

#### 5. *Escalabilidade*
*Descrição:*  
Como um *administrador da plataforma*, eu quero que o sistema suporte um grande número de usuários simultâneos para que a plataforma funcione sem interrupções.

*Critérios de Aceitação:*  
- *Cenário 1:* Suporte a usuários simultâneos  
  Given que muitos alunos estão acessando a plataforma,  
  When o número de usuários simultâneos atinge 3.000,  
  Then o sistema deve continuar funcionando sem degradação de desempenho.  

- *Cenário 2:* Monitoramento de desempenho  
  Given que o administrador deseja acompanhar o desempenho,  
  When ele acessa o painel de controle,  
  Then o sistema deve exibir métricas como uso de CPU, memória e tráfego.  

*Prioridade:* Alta  
*Justificativa:* Garante a estabilidade da plataforma mesmo em cenários de alta demanda.

---

#### 6. *Compatibilidade com Leitores de Tela*
*Descrição:*  
Como um *aluno com deficiência visual*, eu quero que a plataforma seja compatível com leitores de tela para que eu possa navegar sem barreiras.

*Critérios de Aceitação:*  
- *Cenário 1:* Suporte a leitores de tela  
  Given que o aluno utiliza um leitor de tela,  
  When ele navega pela plataforma,  
  Then o sistema deve fornecer descrições textuais para todos os elementos visuais.  

- *Cenário 2:* Navegação por teclado  
  Given que o aluno utiliza apenas o teclado,  
  When ele navega pela plataforma,  
  Then o sistema deve permitir acesso a todas as funcionalidades sem o uso do mouse.  

- *Cenário 3:* Testes de acessibilidade  
  Given que o sistema é atualizado,  
  When uma nova versão é lançada,  
  Then o sistema deve ser testado para garantir conformidade com as diretrizes WCAG 2.1 (nível AA).  

*Prioridade:* Alta  
*Justificativa:* Garante inclusão e acessibilidade para todos os usuários.

---

#### 7. *Contraste e Legibilidade*
*Descrição:*  
Como um *aluno com baixa visão*, eu quero que a plataforma tenha bom contraste e fontes legíveis para que eu possa ler o conteúdo sem dificuldades.

*Critérios de Aceitação:*  
- *Cenário 1:* Contraste adequado  
  Given que o aluno acessa a plataforma,  
  When ele visualiza o conteúdo,  
  Then o sistema deve garantir um contraste mínimo de 4.5:1 entre texto e fundo.  

- *Cenário 2:* Ajuste de tamanho de fonte  
  Given que o aluno deseja aumentar o tamanho do texto,  
  When ele utiliza as configurações do navegador,  
  Then o sistema deve permitir que o texto seja redimensionado sem prejudicar o layout.  

- *Cenário 3:* Modos de exibição  
  Given que o aluno prefere um modo de exibição específico,  
  When ele ativa o modo escuro ou de alto contraste,  
  Then o sistema deve aplicar o tema escolhido em toda a plataforma.  

*Prioridade:* Média  
*Justificativa:* Melhora a experiência de alunos com baixa visão ou preferências específicas.  

---

### Análise do Backlog

---

#### 1. *Requisitos funcionais importantes que estão AUSENTES*

*Recuperação de senha*: Não há user stories relacionadas à recuperação de senha para alunos ou administradores.
*Gerenciamento de grupos inativos*: Não há funcionalidade para identificar e arquivar grupos inativos ou sem atividade por um período prolongado.

---

#### 2. *Requisitos não-funcionais que não foram cobertos*

- *Segurança*:
  - Não há menção de proteção contra ataques de força bruta além do bloqueio após 5 tentativas de login.
- *Desempenho*:
  - Não há menção de requisitos para otimização de banco de dados
- *Acessibilidade*:
  - Não há requisitos para suporte a múltiplos idiomas.
- *Conformidade legal*:
  - Não há menção de conformidade com leis de proteção de dados, como LGPD ou GDPR.
- *Testabilidade*:
  - Não há menção de requisitos para testes automatizados ou cobertura mínima de testes.

---

#### 3. *Ambiguidades ou sobreposições entre as user stories*
- *"Desempenho e Escalabilidade" e "Escalabilidade"*: Ambas as histórias abordam escalabilidade, mas estão separadas, o que pode causar redundância.
- *"Notificações" e "Sistema de Mensagens Internas"*: Há sobreposição entre notificações e mensagens diretas, especialmente em relação à comunicação entre membros do grupo.
- *"Busca por Localização" e "Busca por Palavras-chave"*: Não está claro se a busca por palavras-chave inclui localização ou se são funcionalidades completamente separadas.
- *"Visualização de Grupos" e "Sugestões de Grupos"*: Ambas mencionam a exibição de detalhes do grupo, mas não está claro se as sugestões incluem os mesmos detalhes.

---

#### 4. *Critérios de aceitação que não são testáveis*
- *"Gerenciar Usuários (Administrador)"*:
  - "O sistema deve registrar todas as ações administrativas para auditoria" não especifica como ou onde essas ações serão registradas.
- *"Sugestões de Grupos"*:
  - "O sistema deve atualizar as sugestões automaticamente conforme novos grupos são criados" não define o intervalo ou condições para atualização.
- *"Proteção contra Ataques"*:
  - "O sistema deve bloquear temporariamente o acesso e notificar o administrador" não especifica o tempo de bloqueio ou o formato da notificação.
- *"Contraste e Legibilidade"*:
  - "O sistema deve garantir um contraste mínimo de 4.5:1 entre texto e fundo" não define como isso será medido ou validado.

---

#### 5. *Sugestões de melhoria para as stories existentes*
- *"Criar Grupo de Estudo"*:
  - Adicionar um critério para permitir a edição de informações do grupo logo após a criação.
  - Especificar validações para o limite de participantes (ex.: número máximo permitido).
- *"Buscar Grupos de Estudo"*:
  - Adicionar critérios para lidar com resultados vazios (ex.: exibir mensagem ou sugestões alternativas).
- *"Participar de um Grupo"*:
  - Adicionar critérios para permitir que o aluno cancele uma solicitação pendente.
- *"Gerenciar Grupos Criados"*:
  - Adicionar critérios para arquivar ou excluir grupos inativos.
- *"Notificações"*:
  - Especificar o tempo máximo para envio de notificações após uma alteração.
- *"Acessibilidade"*:
  - Adicionar critérios para suporte a múltiplos idiomas e legendas em vídeos.
- *"Sistema de Mensagens Internas"*:
  - Adicionar critérios para permitir o bloqueio de mensagens indesejadas.
- *"Tempo de Resposta Rápido"*:
  - Especificar métricas para diferentes tipos de páginas (ex.: páginas com mais dados podem ter tempos de resposta maiores).

---

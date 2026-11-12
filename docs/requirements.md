# Requisitos do Projeto

## 1. Visão Geral

Organic Store (nome fictício criado para o projeto) é um e-commerce de arte voltado à divulgação e comercialização de trabalhos de bandas e artistas independentes do estado de São Paulo, com o propósito de divulgar, difundir e apresentar o cenário independente de arte.

A plataforma busca conectar artistas independentes de todo o estado de São Paulo a consumidores de todo o Brasil, oferecendo produtos que vão além do modelo varejista industrial de larga escala, com itens produzidos em pequenas quantidades e, em determinados casos, exclusivos para comercialização pela plataforma.

O sistema é desenvolvido como um projeto de portfólio. Embora utilize dados fictícios, possui uma estrutura compatível com uma possível aplicação real, sendo planejado para ser completo e funcional e para demonstrar competências técnicas e conhecimentos relacionados ao desenvolvimento de software.

## 2. Objetivos

### 2.1 Objetivo Geral

Construção de uma aplicação completa, funcional e consistente, capaz de demonstrar habilidades técnicas e competências profissionais relacionadas ao desenvolvimento de software.

### 2.2 Objetivos Específicos

Viabilizar a comercialização de produtos, conectar e divulgar artistas independentes, proporcionando de uma experiencia de compra completa para os usuários. Permitindo participação rotativa de artistas e submissão de seus trabalhos na plataforma, por meio de uma seleção estruturada e avaliação dos mesmos.

### 2.3 Objetivos Técnicos 

Implementar de um e-commerce completo. Que contemple: gerenciamento de produtos, usuários e pedidos; integração de serviços externos pertinentes e necessários a operação; autenticação, autorização e controle de acesso; mecanismos de segurança e proteção de dados; e aplicação de práticas de desenvolvimento, testes, documentação e deployment.

## 3. Perfis de Usuário

### 3.1 Cliente

Descrição: Perfil destinado a pessoas que utilizam a loja para consultar produtos, realizar compras e acompanhar seus pedidos.

Funcionalidades:

- Criar e gerenciar uma conta individual.
- Consultar produtos, preços, disponibilidade e condições de compra.
- Realizar pedidos e pagamentos.
- Consultar o histórico de pedidos e seus respectivos estados.
- Consultar informações pertinentes sobre pagamentos, cancelamentos e reembolsos, quando aplicáveis.
- Gerenciar os dados pessoais e endereços necessários à utilização dos serviços.
- Entrar em contato com a loja para solicitar suporte, reportar problemas, enviar sugestões ou registrar outras manifestações.
- Acompanhar o andamento das solicitações encaminhadas à loja.
- Disponibilizar a opção de habilitação de um perfil artístico vinculado à conta existente, sem necessidade de criar uma segunda conta.

Observações:

- A criação da conta não exige automaticamente CPF (Cadastro de Pessoas Físicas) ou CNPJ (Cadastro Nacional da Pessoa Jurídica).
- Determinados dados poderão ser solicitados quando necessários para uma operação específica, observadas as exigências aplicáveis.
- A possibilidade de solicitar um perfil artístico não concede aprovação automática para comercialização de produtos.

### 3.2 Artista

Descrição: Perfil destinado à representação de atividades artísticas interessadas em divulgar e comercializar seus trabalhos por meio da Organic Store.

O perfil artístico poderá representar um artista individual, uma banda, um grupo artístico ou uma marca independente. Uma mesma conta poderá administrar mais de um perfil artístico.

Funcionalidades:

- Criar e gerenciar um ou mais perfis artísticos vinculados à conta existente.
- Cadastrar e atualizar informações sobre a atividade artística, o trabalho desenvolvido e as áreas de atuação.
- Submeter candidaturas para avaliação, incluindo informações e materiais autorais solicitados pela loja.
- Enviar imagens e vídeos curtos dos produtos, conforme os critérios de submissão definidos.
- Consultar o estado de cada candidatura.
- Receber decisões, orientações e feedbacks referentes às etapas de avaliação.
- Entrar em contato com a loja para tratar de questões relacionadas à candidatura, à comercialização e à parceria artística.
- Consultar informações sobre obras aprovadas e produtos comercializados.
- Consultar informações pertinentes sobre vendas e repasses, conforme as permissões concedidas e a formalização da parceria.
- Utilizar cupons de desconto destinados exclusivamente a clientes que possuam perfil artístico habilitado, respeitando as condições de cada promoção.

Observações:

- A criação de um perfil artístico não significa que a candidatura foi aprovada, que existe uma parceria formalizada ou que o perfil está autorizado a comercializar produtos.
- A avaliação será realizada em duas etapas, com responsabilidades distintas para os colaboradores envolvidos.
- Os dados necessários à formalização da parceria, incluindo informações da pessoa física ou jurídica responsável pela contratação e pelos pagamentos, serão solicitados quando necessários.
- A entidade artística representada poderá ser diferente da pessoa física ou jurídica responsável pela formalização comercial.
- A alteração dos dados comerciais não deverá substituir automaticamente as partes identificadas em contratos já formalizados nem apagar o histórico de operações anteriores.

### 3.3 Colaborador e Administrador

Descrição: Perfis internos destinados à operação, ao atendimento, à gestão comercial e à administração da Organic Store.

As permissões serão atribuídas conforme as responsabilidades de cada função. A simples existência de uma conta de colaborador não concederá acesso irrestrito às informações ou funcionalidades do sistema.

Contas de colaboradores e administradores não poderão realizar compras na loja.

#### 3.3.1 Colaborador Geral

Responsabilidade principal: atendimento, manutenção de conteúdo e avaliação inicial de candidaturas artísticas.

Funcionalidades:

- Consultar pedidos e informações operacionais necessárias ao atendimento dos clientes.
- Consultar manifestações enviadas pelos usuários, incluindo problemas, sugestões e elogios.
- Responder às solicitações e acompanhar seu andamento.
- Consultar informações de perfis de clientes e artistas, respeitando as permissões de acesso e as restrições aplicáveis a dados pessoais.
- Criar publicações e atualizar informações do catálogo, conforme as permissões concedidas.
- Avaliar candidaturas artísticas durante a primeira etapa do processo de seleção.
- Aprovar candidaturas para encaminhamento à segunda etapa.
- Registrar decisões e fornecer feedbacks aos candidatos não aprovados.
- Solicitar informações complementares pertinentes à avaliação artística, quando necessário.

Limites de acesso:

- Não poderá acessar indiscriminadamente dados pessoais restritos, como CPF, credenciais de acesso ou informações financeiras particulares.
- Não poderá realizar a aprovação final de uma parceria artística nem habilitar definitivamente um perfil artístico para comercialização.
- Não terá acesso irrestrito a contratos, repasses ou informações financeiras confidenciais.
    
#### 3.3.2 Colaborador Financeiro

Responsabilidade principal: análise de informações comerciais e financeiras relacionadas à formalização e à manutenção das parcerias artísticas.

Funcionalidades:

- Consultar candidaturas encaminhadas à segunda etapa do processo de seleção.
- Revisar os dados fornecidos pelos artistas e pelas pessoas físicas ou jurídicas responsáveis pela formalização da parceria.
- Solicitar correções ou informações adicionais necessárias à análise documental e comercial.
- Registrar decisões e acompanhar as pendências relacionadas à formalização.
- Aprovar ou rejeitar a parceria na etapa final, conforme os critérios definidos pela Organic Store.
- Autorizar a habilitação do perfil artístico para as funcionalidades que dependam da aprovação final.
- Consultar informações financeiras pertinentes às suas atribuições, incluindo vendas, pagamentos e repasses a artistas.
- Consultar registros necessários à conferência de valores, à análise de divergências e ao acompanhamento financeiro das parcerias.
- Registrar e revisar informações relacionadas aos processos financeiros sob sua responsabilidade.

Limites de acesso:

- O acesso a dados pessoais e financeiros deverá limitar-se às informações necessárias para executar suas responsabilidades.
- A aprovação financeira e comercial não deverá permitir alterações irrestritas em configurações administrativas ou nas permissões de outros colaboradores.
- A consulta ou alteração de contratos e registros financeiros deverá respeitar as permissões definidas para a função.

Observação: a aprovação da parceria deverá ser registrada separadamente da aprovação inicial da candidatura. Dessa forma, será possível identificar quem avaliou o trabalho artístico e quem autorizou a formalização comercial.

#### 3.3.3 Administrador

Responsabilidade principal: administração geral do sistema, gestão de contas, permissões e configurações operacionais.

Funcionalidades:

- Gerenciar contas de clientes, artistas e colaboradores, incluindo criação, edição, suspensão, reativação e exclusão, conforme as regras aplicáveis.
- Criar e gerenciar contas adicionais de Colaborador Geral e Colaborador Financeiro.
- Gerenciar permissões de acesso dos colaboradores.
- Consultar e administrar informações operacionais, comerciais e financeiras conforme as responsabilidades administrativas.
- Revisar registros de vendas, pedidos, pagamentos, repasses e contratos, respeitando as exigências de segurança e proteção de dados.
- Revisar candidaturas, conteúdos e formulários enviados por artistas.
- Gerenciar as configurações gerais da loja, incluindo as regras de cupons e descontos.
- Consultar registros de operações administrativas relevantes.
- Investigar inconsistências operacionais e financeiras, conforme as permissões administrativas.

Limites e responsabilidades:

- As operações administrativas críticas deverão manter registros que permitam identificar a conta responsável, a ação realizada e o momento da operação.
- A suspensão ou exclusão de contas não deverá apagar os registros comerciais ou históricos que precisem ser preservados.
- A exclusão de dados pessoais deverá considerar as finalidades do tratamento e as obrigações de conservação aplicáveis.
- O sistema deverá impedir que a remoção ou suspensão de contas deixe a loja sem um administrador ativo.
- As permissões administrativas deverão ser protegidas contra alterações não autorizadas.

Observação: o Administrador terá as funcionalidades dos colaboradores, além das permissões administrativas adicionais. Isso não significa que todas as informações pessoais ou financeiras devam ser exibidas sem restrições: o acesso deverá ser compatível com a finalidade da operação.

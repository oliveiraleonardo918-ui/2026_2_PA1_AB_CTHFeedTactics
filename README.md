# 2026_2_PA1_CTHFeedTactics
Trabalho para disciplina de Projeto Aplicado de Dev Software

# Membros do Grupo
Leonardo Oliveira / 2523546

Lucas Silva / 2422728

João Gabriel de Holanda / 2522687


# Documento do Projeto

https://docs.google.com/document/d/1WfoTo3V6UwHy_UaceGcP7m1p5zpbO11dca_fpcouHd0/edit?usp=drivesdk


<h1> 1. Resumo do Produto — É, Não É, Faz, Não Faz </h1>

<h2> É: </h2>

 - Plataforma de informações direcionada à prevenção de ataques cibernéticos.

 - Direciona usuários para relatos, feeds e conexão com indicadores de comprometimento (IOCs).

 - Plataforma com divisão por indústria e os ofensores direcionados a cada uma.

 - Plataforma unificada de informações sobre ciberataques.


<h2> Não É: </h2>

 - Não é uma plataforma genérica de notícias e alertas de segurança.

 - Não é fórum de troca de informações.

 - Não é vendor-based (não é patrocinada ou direcionada por fabricantes).


<h2> Faz: </h2>

 - Permite que usuários verificados enviem IOCs e metodologias de ataque.

 - Permite que usuários encontrem seu nicho e vejam o que está sendo usado contra empresas similares.

 - Integração com APIs de feeds reputacionais para checagem dos IOCs fornecidos.

 - Permite que usuários verificados acessem informações de contato de outros verificados.


<h2> Não Faz: </h2>

 - Não tem chat dentro da plataforma.

 - Não faz análise dos ataques.

 - Não monta recomendações nativamente.




<h1> 2. Segmento de Cliente </h1>

O CTHFeedTatics atende a um **único segmento de cliente**: profissionais de tecnologia e segurança da informação de empresas de qualquer porte que atuam ou têm responsabilidade sobre a postura de segurança cibernética de suas organizações e que precisam de inteligência de ameaças contextualizada à sua indústria.

Esse segmento inclui analistas de SOC, engenheiros de detecção, incident responders, analistas de threat intelligence, coordenadores e gestores de segurança da informação, CISOs e profissionais de TI que acumulam responsabilidades de segurança em empresas onde não existe uma equipe dedicada. O que unifica esse segmento não é o cargo, mas a necessidade compartilhada de acessar informações setoriais confiáveis sobre ataques cibernéticos direcionados ao seu ramo de atuação.

Dentro da plataforma, esse segmento único pode assumir dois **papéis de permissão** — usuário comum (visualização) e usuário verificado (visualização + publicação de IOCs e acesso a contatos de outros verificados). Esses papéis não representam segmentos distintos: qualquer cliente entra na plataforma como usuário do segmento e pode, mediante processo de verificação, obter permissões adicionais de publicação e networking.


<h1> 3. Mapa de Empatia </h1>

<img width="550" height="350" alt="mapa-da-empatia-exemplo-para-preencher" src="https://github.com/user-attachments/assets/d71716e6-4c8d-49ad-9b4f-3c872efe24f6" />

[CTHFeedTatics_Mapa_Empatia.docx](https://github.com/user-attachments/files/31238880/CTHFeedTatics_Mapa_Empatia.docx)


<h3> O QUE PENSA E SENTE? </h3>

▸ Preocupação constante com a segurança da empresa — sente que pode ser o próximo alvo de um ataque direcionado ao setor. **Certeza**

▸ Ansiedade por não saber quais ameaças estão ativamente direcionadas à sua indústria e frustração por só descobrir tardiamente. **Certeza**

▸ Frustração com a fragmentação das informações — precisa consultar dezenas de fontes diferentes sem garantia de relevância. **Certeza**

▸ Sensação de isolamento — sabe que outras empresas do setor passam pelo mesmo, mas as vezes não tem a divulgação necessária para prevenção. **Certeza**

▸ Responsabilidade de proteger sua organização e desejo de contribuir para a defesa coletiva do setor quando possível. **Certeza**

▸ Receio de compartilhar ou consumir informações sensíveis sem garantia de verificação, curadoria e segurança. **Certeza**


<h3> O QUE ESCUTA? </h3>

▸ Colegas de trabalho comentando sobre incidentes recentes de cibersegurança no setor. **Certeza**

▸ Gestores e diretoria cobrando postura de segurança mais robusta e evidências de monitoramento de ameaças. **Certeza**

▸ Notícias sobre vazamentos de dados e ransomware em grandes portais de TI, geralmente sem detalhes técnicos. **Certeza**

▸ Recomendações de influenciadores e especialistas de cybersecurity em redes sociais e podcasts. **Certeza**

▸ Recomendações para participar de ISACs e comunidades fechadas, mas com barreiras de entrada e custos altos. **Certeza**

▸ Que a colaboração e o compartilhamento de IOCs entre empresas do setor é fundamental para defesa coletiva. **Certeza**


<h3> O QUE VÊ? </h3>

▸ Notícias fragmentadas e genéricas sobre ciberataques em portais de notícias, sem IOCs nem detalhes técnicos. **Certeza**

▸ Concorrentes e empresas do setor sendo atacados publicamente, com informações reportadas tardiamente. **Certeza**

▸ Vendedores de soluções de segurança fazendo marketing agressivo sem contexto real do cenário de ameaças. **Certeza**

▸ Relatórios de threat intelligence pagos e inacessíveis para empresas de pequeno e médio porte. **Certeza**

▸ Feeds de IOCs dispersos em múltiplas plataformas. **Certeza** 

▸ Falta de plataformas colaborativas não-vendor-based para troca de inteligência de ameaças setorial. **Certeza**
 

<h3> O QUE FALA E FAZ? </h3>

▸ Busca informações sobre ameaças em múltiplas fontes diariamente, de forma manual e não estruturada. **Certeza**

▸ Compartilha alertas relevantes internamente com a equipe de TI/Segurança e reporta ao gestor. **Certeza**

▸ Participa de grupos informais de segurança (Telegram, Discord, WhatsApp) para troca rápida de informações. **Certeza**
 
▸ Tenta implementar medidas preventivas com base em informações limitadas e defasadas. **Certeza**

▸ Consulta feeds de reputação e plataformas de threat intel para validar indicadores recebidos em alertas. **Certeza**


<h3> DORES </h3>

▸ Escassez de informações consolidadas, curadas e filtradas por indústria/setor. **Certeza**

▸ Tempo excessivo gasto buscando informações em fontes dispersas, sem garantia de relevância. **Certeza**

▸ Dificuldade em diferenciar alertas relevantes de ruído informacional. **Certeza**

▸ Ausência de um hub centralizado para consumir — e potencialmente publicar — informações de ataques ao setor **Certeza**

▸ Falta de comunicação e colaboração entre empresas de pequeno e médio porte atacadas. **Certeza**

▸ Barreiras de entrada em comunidades existentes (ISACs, CERTs) por custo, formalidade ou processo. **Certeza**

▸ Dificuldade em validar IOCs recebidos via alertas sem integração com feeds reputacionais. **Certeza**


<h3> GANHOS </h3>

▸ Acesso centralizado a informações de ataques cibernéticos filtradas pela sua indústria. **Certeza**

▸ Feed de alertas atualizado com o intuito de informar e prevenir ataques futuros. **Certeza**

▸ Economia de tempo ao não precisar consultar dezenas de fontes diariamente. **Certeza**

▸ Maior confiança na postura de segurança da empresa com informações contextualizadas ao setor. **Certeza**

▸ Capacidade de antecipar ameaças que já atingiram empresas similares na indústria. **Certeza**

▸ Acesso acessível a inteligência de ameaças que antes era restrita a relatórios pagos. **Certeza**

▸ Possibilidade de contribuir ativamente com IOCs e TTPs, participando da defesa coletiva do setor (mediante verificação). **Certeza**

▸ Rede de contatos com profissionais verificados da mesma indústria para troca segura de informações. **Certeza**

▸ Validação automática de IOCs consumidos e submetidos via integração com feeds reputacionais. **Certeza**




<h1> 4. Questionário de Empatia </h1>

Roteiro de entrevista semiestruturada para validação das hipóteses do mapa de empatia. Aplicar individualmente com profissionais de TI e segurança da informação de empresas de diferentes portes, incluindo analistas, engenheiros de detecção, incident responders e gestores de segurança.

1. Com que frequência você busca informações sobre ameaças cibernéticas direcionadas à sua empresa ou setor?
Objetivo: Mapear hábito de consumo de threat intel e frequência da dor.

2. Quais fontes você utiliza hoje para se manter atualizado sobre ataques cibernéticos? (ex: sites, newsletters, redes sociais, grupos)
Objetivo: Entender o ecossistema atual de fontes e identificar gaps.

3. Você sente que as informações que encontra são relevantes para o setor da sua empresa, ou são genéricas demais?
Objetivo: Validar a dor de falta de segmentação por indústria.

4. Quanto tempo por semana você estima gastar buscando informações de segurança em diferentes fontes?
Objetivo: Quantificar a dor de tempo e justificar a proposta de centralização.

5. Você já deixou de tomar uma ação preventiva por falta de informação sobre uma ameaça específica?
Objetivo: Medir impacto real da escassez de informações na postura de segurança.

6. O que te causaria mais ansiedade: não saber que um ataque está acontecendo no seu setor, ou saber mas não ter detalhes técnicos suficientes?
Objetivo: Entender a hierarquia das dores — awareness vs. profundidade.

7. Quando sua empresa sofre ou identifica um incidente, vocês compartilham os IOCs e TTPs com outras organizações do setor? Se sim, como? Se não, por quê?
Objetivo: Validar a dor de falta de canal de compartilhamento e entender barreiras.

8. Você já tentou participar de algum ISAC, CERT ou comunidade de compartilhamento de threat intel? Como foi a experiência?
Objetivo: Mapear experiências anteriores e gaps das soluções existentes.

9. Se existisse uma plataforma que centralizasse alertas e IOCs filtrados por indústria, qual seria a primeira coisa que você buscaria nela?
Objetivo: Identificar a funcionalidade de maior valor percebido.

10. Você confiaria em informações de ataques compartilhadas por outras empresas do mesmo setor em uma plataforma verificada? Qual nível de verificação de identidade você consideraria aceitável?
Objetivo: Validar a premissa de confiança em comunidade verificada e definir requisitos de trust.

11. A integração com APIs de feeds reputacionais para validação automática de IOCs é algo que você usaria ativamente?
Objetivo: Validar a feature de integração com feeds reputacionais.

12. Se tivesse permissão para publicar na plataforma, que tipo de informação você compartilharia primeiro: IOCs técnicos (hashes, IPs, domínios), TTPs (MITRE ATT&CK), contexto do ataque, ou a combinação?
Objetivo: Priorizar o formato e profundidade do conteúdo publicado.

13. Ter acesso às informações de contato de outros profissionais verificados do seu setor seria útil? Em que situação você usaria isso?
Objetivo: Validar o valor da funcionalidade de networking entre verificados.

14. O que te impediria de usar uma plataforma como essa? (ex: custo, complexidade, desconfiança, jurídico, falta de tempo)
Objetivo: Mapear barreiras de adoção e objeções.

15. Como você preferiria receber os alertas da plataforma? (ex: feed no site, e-mail, integração com ferramentas, app mobile) E o que faria você voltar diariamente ou abandoná-la?
Objetivo: Definir canais de entrega de valor e identificar drivers de retenção/churn.

https://docs.google.com/forms/d/e/1FAIpQLSe5T4fkVSonfDt6bbIMu4VQ9eEKwRKl8O6E8LApkbVbHjDVWw/viewform?usp=publish-editor

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


<h1> 5. Orientações de Aplicação </h1>


<h2> 5.1 Formato das Entrevistas </h2>

- Entrevistas individuais de 20 a 30 minutos, preferencialmente por videoconferência ou presencial.

- Mínimo recomendado: 8 a 10 entrevistas com profissionais do segmento em diferentes portes de empresa.

- Buscar diversidade de perfis dentro do segmento (analistas de SOC, engenheiros de detecção, gestores, CISOs) para capturar variações de responsabilidade.

- Gravar (com consentimento) para análise posterior e extração de insights.

- Evitar perguntas fechadas — estimular o entrevistado a elaborar suas respostas.


<h2> 5.2 Análise dos Resultados </h2>

- Após as entrevistas, consolidar respostas em um mapa de afinidade para identificar padrões.

- Comparar as respostas com as hipóteses do mapa de empatia e ajustar onde necessário.

- Priorizar dores recorrentes e ganhos mais desejados para guiar o backlog do produto.

- Usar os insights para refinar o entendimento do segmento e validar (ou invalidar) as premissas do CTHFeedTatics.


<h2> 5.3 Métricas de Validação </h2>

- Taxa de confirmação: % de hipóteses do mapa de empatia confirmadas nas entrevistas.

- Novas dores descobertas: dores mencionadas pelos entrevistados que não estavam no mapa original.

- Intensidade das dores: classificar de 1 a 5 a intensidade de cada dor mencionada.

- Intenção de uso: % de entrevistados que usariam a plataforma se estivesse disponível hoje.

- Intenção de contribuição: % de entrevistados que aceitariam passar por processo de verificação para publicar IOCs.



------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


<h1> 6. Jobs to be Done (JTBD) </h1>

A metodologia Jobs to be Done complementa o mapa de empatia ao mudar o foco de "quem é o cliente" para "qual progresso o cliente está tentando fazer". Em vez de descrever características do usuário, o JTBD descreve o **trabalho** que ele contrata a plataforma para executar em sua vida profissional. Essa abordagem ajuda a orientar decisões de produto pela função a ser cumprida, e não pelas features em si.


<h2> 6.1 Job Statement Principal </h2>

> **Quando** um novo ataque cibernético relevante ao meu setor está circulando ou já atingiu empresas similares à minha, **eu quero** identificar rapidamente os indicadores de comprometimento, as metodologias envolvidas e o contexto do ataque, **para que** eu possa antecipar riscos, ajustar minhas defesas e proteger minha organização antes de ser o próximo alvo.


<h2> 6.2 Jobs Funcionais </h2>

Trabalhos práticos e mensuráveis que o cliente precisa realizar.

- **Monitorar continuamente** o cenário de ameaças específico da sua indústria sem precisar consultar dezenas de fontes dispersas.

- **Identificar rapidamente** IOCs (hashes, IPs, domínios, URLs) e TTPs (MITRE ATT&CK) relevantes ao seu contexto setorial.

- **Validar tecnicamente** os indicadores recebidos por meio de integração com feeds reputacionais antes de aplicá-los nas ferramentas de defesa.

- **Filtrar ruído informacional** e receber apenas alertas relevantes à sua indústria e ao seu contexto operacional.

- **Compartilhar informações** de ataques sofridos ou identificados de forma segura, verificada e sem exposição indesejada (quando verificado).

- **Consultar contatos** de outros profissionais verificados do seu setor para troca direta de informações sensíveis (quando verificado).

- **Reduzir o tempo** gasto na coleta e curadoria manual de inteligência de ameaças.


<h2> 6.3 Jobs Emocionais </h2>

Como o cliente quer se sentir ao realizar o trabalho.

- **Sentir-se preparado** para responder a ameaças que já atingiram empresas similares, em vez de reagir a incidentes sem contexto.

- **Reduzir a ansiedade** causada pela sensação de estar "no escuro" enquanto ataques acontecem no setor.

- **Sentir-se conectado** a uma comunidade profissional que compartilha o mesmo contexto de ameaças, superando o isolamento setorial.

- **Sentir confiança** ao apresentar sua postura de segurança à diretoria, embasado em inteligência de ameaças curada e setorial.

- **Sentir-se relevante** ao contribuir com a defesa coletiva do setor por meio de IOCs e TTPs publicados (quando verificado).


<h2> 6.4 Jobs Sociais </h2>

Como o cliente quer ser percebido pelos outros ao realizar o trabalho.

- **Ser reconhecido** como um profissional atualizado, informado e proativo em relação ao cenário de ameaças da sua indústria.

- **Ser visto pela diretoria** como um agente de valor estratégico que antecipa riscos, e não apenas responde a incidentes.

- **Ganhar reputação** na comunidade de segurança setorial por meio de contribuições verificadas e de qualidade (quando verificado).

- **Ser percebido como parte** de uma rede confiável de profissionais que colabora ativamente para a defesa coletiva do setor.


<h2> 6.5 Job Map — Etapas do Trabalho </h2>

Sequência das etapas que o cliente executa para completar o job principal. O CTHFeedTatics deve reduzir o esforço em cada uma delas.

1. **Definir** — determinar quais tipos de ameaça e indicadores são relevantes ao setor da empresa.

2. **Localizar** — encontrar fontes confiáveis de informação sobre ataques ao setor.

3. **Preparar** — organizar as fontes e criar uma rotina de consulta diária.

4. **Confirmar** — validar tecnicamente os indicadores encontrados (reputação, contexto, aplicabilidade).

5. **Executar** — aplicar os indicadores nas ferramentas de defesa (SIEM, EDR, firewalls, WAFs).

6. **Monitorar** — acompanhar continuamente novos indicadores e evolução das ameaças ao setor.

7. **Modificar** — ajustar defesas e prioridades conforme novas ameaças setoriais surgem.

8. **Concluir** — registrar aprendizados e, quando aplicável, compartilhar descobertas com a comunidade verificada.


<h2> 6.6 Jobs Relacionados e Não Atendidos </h2>

Trabalhos adjacentes que o cliente pode ter, mas que o CTHFeedTatics **explicitamente não pretende executar**, deixando claro o escopo do produto.

- **Análise detalhada de ataques** — o produto não realiza análise técnica dos ataques publicados; entrega os IOCs e TTPs para que o cliente analise.

- **Recomendação de resposta** — não gera prescrições nativas de mitigação; o cliente decide como aplicar a informação.

- **Comunicação síncrona** — não substitui chats, canais de mensageria ou fóruns; oferece o contato dos verificados para conversa fora da plataforma.

- **Substituição de SIEM/SOAR** — não é ferramenta de detecção nem de orquestração; é fonte de inteligência que alimenta essas ferramentas.
-----------------------------------------------------------------------------------------------------------------------------
<h1># 7. Problem-Solution Fit</h1>

O **Problem-Solution Fit (Encaixe Problema-Solução)** demonstra como a proposta do CTHFeedTatics responde diretamente às principais dores identificadas no segmento de clientes. O objetivo é estabelecer uma relação clara entre os problemas enfrentados pelos profissionais de tecnologia e segurança da informação e as soluções oferecidas pela plataforma, verificando se suas funcionalidades entregam valor real e atendem às necessidades identificadas.

## 7.1 Problemas Identificados

Principais problemas enfrentados pelo segmento de clientes que o CTHFeedTatics pretende solucionar.

* **Excesso de ruído e falta de contexto setorial** — profissionais precisam consultar diversas fontes de inteligência e filtrar manualmente alertas genéricos para identificar quais ameaças são realmente relevantes para sua indústria.

* **Dificuldade na validação de indicadores** — IOCs encontrados em grupos, redes sociais e outras fontes informais podem não possuir contexto ou validação suficiente, aumentando a insegurança antes de sua utilização nas ferramentas de defesa.

* **Fragmentação das fontes de inteligência** — informações sobre ataques, IOCs e TTPs encontram-se distribuídas entre diferentes sites, feeds, blogs, redes sociais e comunidades, aumentando o tempo necessário para coleta e curadoria.

* **Isolamento entre profissionais do mesmo setor** — profissionais de empresas que enfrentam ameaças semelhantes possuem poucas formas acessíveis e confiáveis de identificar e entrar em contato com outros especialistas da mesma indústria.

* **Barreiras de acesso às soluções existentes** — relatórios especializados, plataformas comerciais de threat intelligence e comunidades como ISACs podem apresentar custos, processos de entrada ou níveis de formalidade incompatíveis com empresas menores e profissionais individuais.

* **Dependência de informações vendor-based** — parte das informações disponíveis é produzida ou distribuída por fornecedores de soluções de segurança, podendo estar associada à divulgação de produtos e serviços específicos.

## 7.2 Soluções Propostas

Recursos oferecidos pelo CTHFeedTatics para responder aos problemas identificados.

* **Inteligência dividida por indústria** — organização das informações de ameaças de acordo com o setor de atuação, permitindo que o usuário acompanhe ataques, ofensores, IOCs e TTPs relacionados ao seu contexto.

* **Centralização da inteligência de ameaças** — criação de um hub único para consulta de informações que normalmente estariam distribuídas entre diversas fontes, reduzindo o esforço de pesquisa e curadoria manual.

* **Integração com APIs reputacionais** — utilização de feeds reputacionais para realizar a checagem dos IOCs fornecidos à plataforma e oferecer informações adicionais sobre sua reputação.

* **Comunidade verificada** — usuários que passam pelo processo de verificação recebem permissão para publicar IOCs e metodologias de ataque, aumentando a confiabilidade e a responsabilidade das contribuições.

* **Acesso a contatos profissionais** — usuários verificados podem consultar informações de contato de outros profissionais verificados, permitindo que a comunicação direta ocorra externamente sem transformar a plataforma em um serviço de chat.

* **Abordagem agnóstica e comunitária** — a plataforma não é direcionada por fabricantes de ferramentas de segurança e concentra sua proposta de valor na organização e troca de inteligência tática entre profissionais.

## 7.3 Relação Problema–Solução

A correspondência entre os principais problemas identificados e as soluções propostas pode ser estabelecida da seguinte forma:

1. **Excesso de ruído e falta de contexto setorial → Inteligência dividida por indústria.**
   O feed segmentado permite ao profissional concentrar sua atenção nas ameaças relacionadas ao seu setor, reduzindo o volume de informações genéricas que precisa analisar.

2. **Fragmentação das fontes → Centralização da inteligência de ameaças.**
   O CTHFeedTatics reúne informações relevantes em um único ambiente, diminuindo a necessidade de consultar manualmente diversas fontes diariamente.

3. **Dificuldade na validação de indicadores → Integração com APIs reputacionais.**
   A consulta a feeds reputacionais adiciona uma camada de validação técnica aos IOCs disponibilizados, aumentando a confiança nas informações consumidas.

4. **Isolamento setorial → Comunidade verificada e acesso a contatos.**
   O sistema de verificação permite identificar profissionais confiáveis da mesma indústria e estabelecer contato externo para troca de informações mais sensíveis ou específicas.

5. **Barreiras de acesso às soluções existentes → Abordagem comunitária e acessível.**
   A proposta busca tornar a inteligência de ameaças setorial mais acessível a organizações de diferentes portes, sem depender exclusivamente de relatórios comerciais ou comunidades restritas.

6. **Dependência de conteúdo vendor-based → Abordagem agnóstica.**
   O CTHFeedTatics não é orientado por fabricantes específicos e busca priorizar informações de inteligência relevantes ao contexto dos usuários em vez da promoção de ferramentas de segurança.

## 7.4 Valor Entregue ao Cliente

Ao relacionar diretamente os problemas identificados às soluções propostas, o CTHFeedTatics pretende entregar quatro ganhos principais ao cliente:

* **Economia de tempo**, reduzindo a necessidade de pesquisar e filtrar manualmente diversas fontes de threat intelligence.
* **Maior relevância das informações**, priorizando ameaças relacionadas à indústria do usuário.
* **Maior confiança nos indicadores**, utilizando integração com feeds reputacionais e contribuições de usuários verificados.
* **Maior colaboração setorial**, aproximando profissionais que enfrentam ameaças semelhantes e facilitando a troca externa de informações.

## 7.5 Limites da Solução

O Problem-Solution Fit também estabelece quais problemas estão fora do escopo do CTHFeedTatics. A plataforma fornece e organiza inteligência de ameaças, mas não substitui as ferramentas utilizadas para analisar ou responder aos incidentes.

O CTHFeedTatics:

* **não realiza análise detalhada dos ataques** publicados;
* **não gera recomendações nativas de mitigação ou resposta**;
* **não oferece comunicação síncrona ou chat interno**;
* **não substitui ferramentas SIEM, SOAR, EDR, firewalls ou outras soluções de defesa**.

Sua função é atuar como uma fonte centralizada e setorial de inteligência de ameaças que auxilia os profissionais na identificação, validação e compartilhamento de informações relevantes para suas próprias operações de segurança.

_____________________________________________________________________________________________________________________________________________________________________________

# 8. Business Model Canvas

O Business Model Canvas do **CTHFeedTatics** apresenta a estrutura do modelo de negócio da plataforma, relacionando o segmento de clientes atendido, a proposta de valor oferecida, os canais de acesso, as formas de relacionamento, as possíveis fontes de receita, os recursos e atividades necessários para a operação, as principais parcerias e a estrutura de custos.

## 8.1 Segmentos de Clientes

O CTHFeedTatics atende a um **segmento principal de clientes: profissionais de tecnologia e segurança da informação que possuem responsabilidade sobre a postura de segurança cibernética de suas organizações e necessitam de inteligência de ameaças contextualizada à sua indústria**.

Esse segmento inclui:

* Analistas de SOC;
* Analistas de Threat Intelligence;
* Engenheiros de detecção;
* Incident Responders;
* Engenheiros e analistas de segurança;
* Coordenadores e gestores de segurança da informação;
* CISOs;
* Profissionais de TI que acumulam responsabilidades relacionadas à segurança em organizações sem equipes especializadas.

Dentro da plataforma existem dois **papéis de permissão**, que não representam segmentos diferentes:

* **Usuário comum:** pode consultar informações, IOCs, TTPs e conteúdos relacionados às ameaças direcionadas à sua indústria.
* **Usuário verificado:** além da consulta, pode publicar IOCs e metodologias de ataque e acessar informações de contato de outros profissionais verificados.

O elemento que unifica esses usuários é a necessidade de obter informações confiáveis e contextualizadas sobre ameaças que estejam afetando organizações de setores semelhantes.

## 8.2 Propostas de Valor

O CTHFeedTatics oferece uma **plataforma centralizada de inteligência de ameaças organizada por indústria**, permitindo que profissionais de segurança encontrem informações relevantes ao seu contexto sem depender da consulta manual de diversas fontes dispersas.

A plataforma busca entregar:

* **Inteligência segmentada por indústria**, permitindo acompanhar ataques, ofensores, IOCs e TTPs relacionados especificamente ao setor de atuação do usuário.

* **Centralização de informações**, reunindo em um único ambiente dados que normalmente estariam distribuídos entre feeds, blogs, redes sociais, comunidades e outras fontes.

* **Redução do ruído informacional**, priorizando informações relacionadas ao contexto setorial do usuário em vez de apresentar um feed genérico de notícias de segurança.

* **Validação de IOCs**, utilizando integração com APIs e feeds reputacionais para adicionar contexto técnico aos indicadores disponibilizados.

* **Compartilhamento verificado de inteligência**, permitindo que profissionais que passaram pelo processo de verificação contribuam com IOCs e metodologias de ataques identificados.

* **Colaboração entre profissionais da mesma indústria**, possibilitando que usuários verificados encontrem informações de contato de outros profissionais verificados e realizem a comunicação externamente.

* **Independência de fabricantes**, mantendo uma abordagem não-vendor-based, sem direcionar a inteligência apresentada para a promoção de ferramentas ou fornecedores específicos.

A proposta busca reduzir o tempo gasto na coleta e filtragem manual de informações e permitir que o profissional identifique mais rapidamente ameaças que já estejam afetando empresas semelhantes à sua.

## 8.3 Canais

Os principais canais utilizados pelo CTHFeedTatics para entregar sua proposta de valor e alcançar seus usuários são:

* **Plataforma Web**, como principal meio de acesso aos feeds, IOCs, TTPs, informações sobre ofensores e conteúdos segmentados por indústria.

* **Feed personalizado por indústria**, permitindo ao usuário acompanhar informações relacionadas ao seu setor diretamente dentro da plataforma.

* **E-mail**, utilizado para notificações, alertas relevantes, recuperação de conta, confirmação de cadastro e comunicações relacionadas à plataforma.

* **APIs e integrações com feeds reputacionais**, utilizadas para enriquecer e validar os IOCs apresentados aos usuários.

* **Mecanismos de busca e presença digital**, facilitando a descoberta da plataforma por profissionais que procuram informações sobre inteligência de ameaças e segurança setorial.

* **Comunidades e eventos de cybersecurity**, utilizados como canais para divulgação da plataforma e aquisição de profissionais do segmento.

* **Redes profissionais**, especialmente ambientes utilizados por profissionais de tecnologia e segurança para divulgação de conteúdo e networking.

## 8.4 Relacionamentos com os Clientes

O relacionamento com os usuários do CTHFeedTatics é baseado principalmente em **self-service, automação, confiança e colaboração profissional verificada**.

A plataforma estabelece esse relacionamento por meio de:

* **Self-service para consulta de inteligência**, permitindo que o profissional encontre e filtre informações relevantes sem necessidade de atendimento direto.

* **Personalização por indústria**, priorizando conteúdos relacionados ao contexto profissional do usuário.

* **Processo de verificação de usuários**, utilizado para estabelecer maior confiança entre os profissionais autorizados a contribuir com informações.

* **Contribuição comunitária**, permitindo que usuários verificados publiquem IOCs e metodologias de ataque relevantes.

* **Validação automatizada de indicadores**, utilizando integrações externas para adicionar informações reputacionais aos IOCs.

* **Networking profissional**, permitindo que usuários verificados consultem informações de contato de outros profissionais verificados.

* **Suporte ao usuário**, para resolução de problemas relacionados a cadastro, acesso, verificação e utilização da plataforma.

* **Moderação e curadoria**, buscando preservar a qualidade e a confiabilidade das informações disponibilizadas.

O CTHFeedTatics não pretende substituir ferramentas externas de comunicação. O contato entre profissionais ocorre fora da plataforma a partir das informações disponibilizadas aos usuários verificados.

## 8.5 Fontes de Renda

Considerando a proposta de tornar a inteligência de ameaças acessível para organizações de diferentes portes, o modelo de receita do CTHFeedTatics pode combinar acesso gratuito a funcionalidades essenciais com serviços e funcionalidades avançadas.

Possíveis fontes de receita incluem:

* **Modelo freemium**, oferecendo gratuitamente funcionalidades essenciais de consulta e cobrando por recursos profissionais ou avançados.

* **Assinaturas profissionais**, destinadas a usuários ou organizações que necessitem de funcionalidades adicionais, maior capacidade de consulta ou recursos avançados.

* **Planos corporativos**, permitindo que empresas disponibilizem acesso à plataforma para múltiplos profissionais de suas equipes de segurança.

* **Acesso avançado a integrações e APIs**, possibilitando que organizações integrem informações disponibilizadas pelo CTHFeedTatics às suas ferramentas e fluxos internos.

* **Serviços B2B relacionados à inteligência setorial**, desde que não comprometam a independência da plataforma nem transformem o serviço em uma solução direcionada por fabricantes.

As estratégias de monetização devem preservar o princípio **não-vendor-based** do CTHFeedTatics, evitando que fornecedores de segurança possam influenciar a priorização ou apresentação das informações de inteligência.

## 8.6 Recursos-Chave

Para operar e entregar sua proposta de valor, o CTHFeedTatics depende dos seguintes recursos principais:

* **Plataforma Web**, responsável pela disponibilização dos feeds e interação dos usuários.

* **Backend e banco de dados**, responsáveis pelo armazenamento e organização de usuários, setores, ataques, ofensores, IOCs, TTPs e demais informações da plataforma.

* **Sistema de classificação por indústria**, utilizado para relacionar informações de ameaças aos setores relevantes.

* **Integrações com APIs e feeds reputacionais**, necessárias para checagem e enriquecimento dos IOCs.

* **Sistema de autenticação e verificação**, responsável por diferenciar usuários comuns e usuários verificados.

* **Mecanismos de moderação e curadoria**, necessários para manter a qualidade das contribuições realizadas pela comunidade.

* **Infraestrutura em nuvem**, garantindo disponibilidade, armazenamento, processamento e escalabilidade.

* **Equipe de desenvolvimento**, responsável pela criação, manutenção e evolução da plataforma.

* **Conhecimento especializado em cybersecurity e threat intelligence**, necessário para estruturar corretamente os dados e processos relacionados a IOCs, TTPs e inteligência de ameaças.

* **Políticas de segurança, privacidade e confiança**, fundamentais para lidar com informações potencialmente sensíveis e dados de profissionais verificados.

## 8.7 Atividades-Chave

As principais atividades necessárias para o funcionamento do CTHFeedTatics são:

* **Desenvolvimento e evolução da plataforma**, incluindo feeds, filtros, perfis, publicação de informações e integrações.

* **Organização e classificação da inteligência por indústria**, garantindo que as informações sejam apresentadas dentro do contexto setorial adequado.

* **Integração e manutenção de APIs reputacionais**, permitindo consultar e enriquecer os IOCs disponíveis.

* **Gestão do processo de verificação de usuários**, garantindo que permissões adicionais sejam concedidas de maneira controlada.

* **Moderação das contribuições**, buscando reduzir informações incorretas, maliciosas ou de baixa qualidade.

* **Gestão e proteção dos dados**, especialmente informações relacionadas aos usuários verificados e suas formas de contato.

* **Manutenção da infraestrutura e segurança da própria plataforma**, considerando que um serviço relacionado à cybersecurity precisa manter elevados padrões de proteção.

* **Aquisição e retenção de usuários**, por meio da divulgação em comunidades, eventos e canais utilizados por profissionais de segurança.

* **Monitoramento da qualidade das informações**, buscando preservar a relevância e confiabilidade do conteúdo disponibilizado.

## 8.8 Parcerias-Chave

O CTHFeedTatics depende de parceiros capazes de complementar sua infraestrutura e fornecer fontes confiáveis de informação.

As principais categorias de parceiros são:

* **Provedores de feeds reputacionais**, utilizados para consulta e enriquecimento de hashes, endereços IP, domínios, URLs e outros indicadores.

* **Provedores de infraestrutura em nuvem**, responsáveis por hospedagem, armazenamento, banco de dados e disponibilidade da plataforma.

* **Serviços de autenticação e identidade**, quando utilizados para auxiliar o processo de cadastro e verificação.

* **Comunidades e organizações de cybersecurity**, que podem contribuir para divulgação, adoção e construção de uma comunidade profissional.

* **Instituições acadêmicas e grupos de pesquisa em segurança**, que podem colaborar com conhecimento, divulgação e desenvolvimento de práticas relacionadas à inteligência de ameaças.

* **Empresas e equipes de segurança participantes**, cuja contribuição voluntária de IOCs e metodologias de ataque é importante para o crescimento da base comunitária.

* **Eventos e conferências de cybersecurity**, utilizados para divulgação da plataforma e aproximação com profissionais do segmento.

As parcerias devem preservar a independência da plataforma, principalmente em relação a fabricantes de ferramentas de segurança, evitando interferência comercial sobre a inteligência apresentada aos usuários.

## 8.9 Estrutura de Custos

Os principais custos associados ao desenvolvimento e operação do CTHFeedTatics incluem:

* **Desenvolvimento de software**, envolvendo frontend, backend, banco de dados, UX e manutenção da plataforma.

* **Infraestrutura em nuvem**, incluindo hospedagem, banco de dados, armazenamento, processamento e transferência de dados.

* **APIs e feeds reputacionais**, especialmente quando serviços externos adotarem cobrança baseada em quantidade de consultas ou planos de acesso.

* **Segurança da plataforma**, incluindo monitoramento, proteção da infraestrutura, gerenciamento de vulnerabilidades e mecanismos de autenticação.

* **Processo de verificação de usuários**, incluindo ferramentas ou atividades necessárias para confirmar a legitimidade dos profissionais que solicitarem permissões adicionais.

* **Moderação e curadoria**, necessárias para garantir a qualidade das informações publicadas pela comunidade.

* **Equipe técnica e operacional**, incluindo desenvolvimento, infraestrutura, segurança, suporte e administração.

* **Aquisição e retenção de usuários**, envolvendo divulgação, participação em eventos, produção de conteúdo e relacionamento com comunidades profissionais.

* **Custos legais e de compliance**, especialmente relacionados à LGPD, privacidade, armazenamento de informações de contato e termos de utilização.

* **Ferramentas administrativas e operacionais**, necessárias para gestão interna, suporte e acompanhamento do funcionamento da plataforma.

## 8.10 Síntese do Modelo de Negócio

O modelo do CTHFeedTatics pode ser resumido em um ciclo de geração de valor:

**Profissionais e fontes fornecem inteligência de ameaças**

↓

**A plataforma organiza as informações por indústria**

↓

**IOCs são enriquecidos por feeds reputacionais**

↓

**Profissionais encontram ameaças relevantes ao seu contexto**

↓

**As organizações podem antecipar riscos e ajustar suas próprias defesas**

↓

**Usuários verificados contribuem com novos IOCs e metodologias**

↓

**A base de inteligência setorial cresce e beneficia novamente a comunidade**

Dessa forma, o valor da plataforma tende a aumentar conforme cresce a quantidade de informações relevantes e de profissionais verificados participantes, criando um efeito de rede voltado à colaboração e à defesa coletiva entre organizações que enfrentam contextos de ameaça semelhantes.






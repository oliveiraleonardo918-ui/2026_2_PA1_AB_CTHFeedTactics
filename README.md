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

▸ Preocupação constante com a segurança da empresa — sente que pode ser o próximo alvo de um ataque direcionado ao setor.

▸ Ansiedade por não saber quais ameaças estão ativamente direcionadas à sua indústria e frustração por só descobrir tardiamente.

▸ Frustração com a fragmentação das informações — precisa consultar dezenas de fontes diferentes sem garantia de relevância.

▸ Sensação de isolamento — sabe que outras empresas do setor passam pelo mesmo, mas não há canal seguro de comunicação.

▸ Responsabilidade de proteger sua organização e desejo de contribuir para a defesa coletiva do setor quando possível.

▸ Desejo de fazer parte de uma comunidade ativa de inteligência de ameaças da sua indústria, com fonte única e confiável.

▸ Receio de compartilhar ou consumir informações sensíveis sem garantia de verificação, curadoria e segurança.


<h3> O QUE ESCUTA? </h3>

▸ Colegas de trabalho comentando sobre incidentes recentes de cibersegurança no setor.

▸ Gestores e diretoria cobrando postura de segurança mais robusta e evidências de monitoramento de ameaças.

▸ Notícias sobre vazamentos de dados e ransomware em grandes portais de TI, geralmente sem detalhes técnicos.

▸ Relatos informais de ataques em conferências, meetups e eventos de segurança da comunidade.

▸ Recomendações de influenciadores e especialistas de cybersecurity em redes sociais e podcasts.

▸ Recomendações para participar de ISACs e comunidades fechadas, mas com barreiras de entrada e custos altos.

▸ Que a colaboração e o compartilhamento de IOCs entre empresas do setor é fundamental para defesa coletiva.


<h3> O QUE VÊ? </h3>

▸ Notícias fragmentadas e genéricas sobre ciberataques em portais de notícias, sem IOCs nem detalhes técnicos.

▸ Concorrentes e empresas do setor sendo atacados publicamente, com informações reportadas tardiamente.

▸ Vendedores de soluções de segurança fazendo marketing agressivo sem contexto real do cenário de ameaças.

▸ Relatórios de threat intelligence pagos e inacessíveis para empresas de pequeno e médio porte.

▸ Feeds de IOCs dispersos em múltiplas plataformas (Twitter/X, blogs, listas de e-mail, GitHub).

▸ Falta de plataformas colaborativas não-vendor-based para troca de inteligência de ameaças setorial.

▸ Comunidades fechadas e exclusivas que não atendem empresas menores ou profissionais individuais.


<h3> O QUE FALA E FAZ? </h3>

▸ Busca informações sobre ameaças em múltiplas fontes diariamente, de forma manual e não estruturada.

▸ Compartilha alertas relevantes internamente com a equipe de TI/Segurança e reporta ao gestor.

▸ Participa de grupos informais de segurança (Telegram, Discord, WhatsApp) para troca rápida de informações.

▸ Reclama publicamente da falta de informações acessíveis e centralizadas sobre ataques ao seu setor.

▸ Tenta implementar medidas preventivas com base em informações limitadas e defasadas.

▸ Consulta feeds de reputação e plataformas de threat intel para validar indicadores recebidos informalmente.

▸ Documenta ataques internamente e, quando possível, tenta contato direto com pares de outras empresas.


<h3> DORES </h3>

▸ Ansiedade constante diante da possibilidade de sofrer um ciberataque sem aviso prévio ou preparação.

▸ Escassez de informações consolidadas, curadas e filtradas por indústria/setor.

▸ Tempo excessivo gasto buscando informações em fontes dispersas, sem garantia de relevância.

▸ Dificuldade em diferenciar alertas relevantes de ruído informacional e marketing de fornecedores.

▸ Ausência de um hub centralizado para consumir — e potencialmente publicar — informações de ataques ao setor.

▸ Falta de comunicação e colaboração entre empresas de pequeno e médio porte atacadas.

▸ Barreiras de entrada em comunidades existentes (ISACs, CERTs) por custo, formalidade ou processo.

▸ Dificuldade em validar IOCs recebidos informalmente sem integração com feeds reputacionais.


<h3> GANHOS </h3>

▸ Acesso centralizado a informações de ataques cibernéticos filtradas pela sua indústria.

▸ Feed de alertas atualizado com o intuito de informar e prevenir ataques futuros.

▸ Economia de tempo ao não precisar consultar dezenas de fontes diariamente.

▸ Maior confiança na postura de segurança da empresa com informações contextualizadas ao setor.

▸ Capacidade de antecipar ameaças que já atingiram empresas similares na indústria.

▸ Acesso acessível a inteligência de ameaças que antes era restrita a relatórios pagos.

▸ Possibilidade de contribuir ativamente com IOCs e TTPs, participando da defesa coletiva do setor (mediante verificação).

▸ Rede de contatos com profissionais verificados da mesma indústria para troca segura de informações.

▸ Validação automática de IOCs consumidos e submetidos via integração com feeds reputacionais.




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



CTHFeedTactics
Simulação de Respostas ao Questionário de Empatia
4 entrevistas simuladas com profissionais de Security da Accenture
Documento de Pesquisa — Design de Produto
Entrevista 1 — Enzo Durans
Analista SOC N1, Accenture — Triagem de clientes
O que ele VÊ
1. Com que frequência você busca informações sobre ameaças cibernéticas direcionadas à sua empresa ou setor?
Todo dia no início do turno, e ao longo do dia quando dá tempo entre os casos. Como sou N1 de triagem eu atendo vários clientes de setores diferentes, então preciso ter noção geral do que está acontecendo em cada indústria pra priorizar bem os alertas.
2. Quais fontes você utiliza hoje para se manter atualizado sobre ataques cibernéticos?
Twitter/X é a principal, sigo uns 30 pesquisadores. Bleeping Computer e The Hacker News pra notícias gerais. Alguns canais no YouTube tipo Gabriel Pato e alguns em inglês. Grupo de WhatsApp com colegas do SOC. O material interno da Accenture ajuda bastante, tem trilha de threat intel e alertas dos outros times.
3. Você sente que as informações que encontra são relevantes para o setor da sua empresa, ou são genéricas demais?
Genéricas demais. Como faço triagem de vários clientes, sinto muita falta de informação segmentada. Recebo um alerta de um cliente do varejo e outro de um cliente de saúde na mesma hora, e não tenho contexto setorial pra saber qual priorizar. Vejo muita coisa global, mas o contexto brasileiro por indústria é raro.
O que ele OUVE
4. Você já tentou participar de algum ISAC, CERT ou comunidade de compartilhamento de threat intel? Como foi a experiência?
Como N1 não tenho acesso direto a esses fóruns, geralmente é o tech lead ou o cliente que interage. Acompanho o CERT.br pelos alertas públicos. Comunidade brasileira aberta pra analistas mais júnior eu não conheço nenhuma ativa.
5. Ter acesso às informações de contato de outros profissionais verificados do seu setor seria útil?
Bastante. Como N1 eu tenho muita coisa a aprender, e conhecer analistas mais experientes seria valioso pra desenvolvimento profissional. Também usaria pra tirar dúvidas técnicas em investigações que eu me sinta menos seguro.
O que ele PENSA E SENTE
6. O que te causaria mais ansiedade: não saber que um ataque está acontecendo no seu setor, ou saber mas não ter detalhes técnicos suficientes?
Não saber é o pior. Se eu sei que existe eu peço ajuda pro N2 ou pro tech lead, corro atrás. Mas se eu nem sei da existência da ameaça é pior porque não tenho como priorizar direito o alerta que vem.
7. Você confiaria em informações de ataques compartilhadas por outras empresas do mesmo setor em uma plataforma verificada?
Confiaria com verificação séria. E-mail corporativo verificado e LinkedIn confirmado no mínimo. Se tivesse indicador visual mostrando reputação da conta, tipo quantos IOCs já publicou e quantos foram validados, isso ajudaria muito quem é mais júnior como eu a saber em quem confiar mais.
O que ele FALA E FAZ
8. Quanto tempo por semana você estima gastar buscando informações de segurança em diferentes fontes?
Umas 6 a 8 horas por semana. Gostaria de dedicar mais, mas a rotina de triagem é bem puxada com volume alto de alertas.
9. Quando sua empresa sofre ou identifica um incidente, vocês compartilham os IOCs e TTPs com outras organizações do setor?
Internamente entre os times da Accenture sim, tem processo bem estabelecido e a gente contribui com IOCs pra base interna. Externamente é decisão do cliente e do time de threat intel, eu não participo dessa etapa como N1. Publicamente nunca até onde eu sei.
10. A integração com APIs de feeds reputacionais para validação automática de IOCs é algo que você usaria ativamente?
Muito. Hoje quando pego um IOC em algum alerta preciso ir manualmente no VirusTotal e outros pra classificar. Se a plataforma já entrega isso pronto eu ganho tempo enorme no turno e consigo processar mais alertas.
11. Se tivesse permissão para publicar na plataforma, que tipo de informação você compartilharia primeiro?
Provavelmente começaria com IOCs técnicos porque é o que domino mais. Contexto detalhado eu ainda estou aprendendo a escrever com qualidade. Com o tempo, evoluiria pra publicar combinação de IOC mais TTP mais contexto.
DORES
12. Você já deixou de tomar uma ação preventiva por falta de informação sobre uma ameaça específica?
Como N1 minha ação é mais operacional, tipo escalar rápido pro N2 ou classificar corretamente. Mas já vi casos em que descobri depois que existia uma campanha ativa contra o setor de algum cliente e a gente não tinha o contexto pra priorizar corretamente na hora. Aí o alerta acabou ficando na fila mais tempo que deveria.
13. O que te impediria de usar uma plataforma como essa?
Se fosse muito complexa pra quem está começando eu talvez desistisse. Custo alto o cliente não aprovaria. E se tivesse muito jargão sem explicação eu perderia tempo tentando entender antes de conseguir aplicar.
GANHOS
14. Se existisse uma plataforma que centralizasse alertas e IOCs filtrados por indústria, qual seria a primeira coisa que você buscaria nela?
Filtro pelos setores dos clientes que atendo, pra ver os IOCs mais recentes de cada um. Isso me ajudaria muito na hora de priorizar alertas na triagem. Se tivesse contexto explicativo dos ataques em linguagem mais acessível seria ótimo, porque ajuda quem está aprendendo como eu.
15. Como você preferiria receber os alertas da plataforma? E o que faria você voltar diariamente ou abandoná-la?
Feed no site e digest por e-mail pela manhã. Notificação no celular pra alertas críticos dos setores dos meus clientes. Voltaria diariamente se encontrasse conteúdo que me ajudasse a evoluir tecnicamente e a fazer melhor a triagem. Abandonaria se fosse técnico demais sem contexto ou se não trouxesse nada novo.
Entrevista 2 — Enzo Marins
Analista SOC N2, Accenture — Dedicado a cliente automotivo
O que ele VÊ
1. Com que frequência você busca informações sobre ameaças cibernéticas direcionadas à sua empresa ou setor?
Todo dia no início do turno. Automotivo é um setor que vive sob mira de espionagem industrial e ransomware direcionado a linha de produção, então eu preciso estar antenado desde o primeiro café. Durante o turno também acompanho os canais quando aparece algo relevante.
2. Quais fontes você utiliza hoje para se manter atualizado sobre ataques cibernéticos?
Twitter/X é onde eu vivo, sigo pesquisadores de OT e IT security. Bleeping Computer, The DFIR Report, Dark Reading. Alguns canais no Telegram de threat intel em português. Reports da Mandiant e CrowdStrike quando saem os anuais. Também acompanho o Auto-ISAC de longe, mas o acesso é restrito ao cliente. Grupo interno da Accenture no Teams tem uma trilha de threat intel que ajuda.
3. Você sente que as informações que encontra são relevantes para o setor da sua empresa, ou são genéricas demais?
Bem genéricas. O setor automotivo tem particularidades enormes, tipo ataques a fornecedores da cadeia, ataques a linha de produção via OT, roubo de propriedade intelectual. Isso raramente aparece nas fontes abertas. Quando aparece é caso grande tipo o da Toyota parando fábrica, e aí já é tarde.
O que ele OUVE
4. Você já tentou participar de algum ISAC, CERT ou comunidade de compartilhamento de threat intel?
Auto-ISAC é acesso do cliente, eu não uso diretamente. CERT.br eu acompanho os alertas gerais. Comunidade automotiva brasileira específica eu não conheço nenhuma ativa, o que é um problema porque a gente sabe que ataques a montadoras aqui existem.
5. Ter acesso às informações de contato de outros profissionais verificados do seu setor seria útil?
Muito útil. Automotivo é um setor pequeno e fechado no Brasil, conhecer analistas de outras montadoras direto seria ouro. Usaria pra tirar dúvida em investigação ativa, pra confirmar se alguém mais está vendo o mesmo indicador, e pra trocar figurinha em conferência.
O que ele PENSA E SENTE
6. O que te causaria mais ansiedade?
Não saber. Sem awareness eu não posso nem começar a caçar. Se eu sei que existe eu invento um jeito de investigar, mas não saber é ficar de olhos vendados.
7. Você confiaria em informações compartilhadas por outras empresas?
Confiaria com verificação séria. E-mail corporativo verificado, LinkedIn confirmado, e idealmente algum vouching. Reputação da conta baseada no histórico de publicação também. Se qualquer um pudesse publicar sem filtro, viraria ruído em pouco tempo.
O que ele FALA E FAZ
8. Quanto tempo por semana você estima gastar buscando informações?
Umas 10 horas por semana somando tudo. Um pouco mais quando estou de plantão ou quando o cliente pede briefing de ameaças mensal.
9. Quando sua empresa identifica um incidente, vocês compartilham IOCs e TTPs?
Internamente compartilhamos entre os SOCs da Accenture, tem processo bem definido pra isso. Com outras empresas do setor automotivo, quase nada. O cliente é muito restrito sobre o que sai do ambiente, e faz sentido porque tem propriedade intelectual envolvida. Publicamente nunca.
10. Usaria integração com APIs de feeds reputacionais?
Absolutamente. Sem isso a plataforma perde metade do valor pra mim. VirusTotal, AbuseIPDB, AlienVault OTX no mínimo. Se puder incluir GreyNoise e Shodan também, melhor.
11. Que informações compartilharia?
Combinação. IOC solto é meio inútil hoje em dia. Preciso do IOC mais TTP no MITRE mais contexto de como o ataque se desenrolou.
DORES
12. Você já deixou de tomar uma ação preventiva por falta de informação?
Já, mais de uma vez. O que mais me marcou foi uma campanha usando um loader específico contra montadoras que a gente só entendeu depois que apareceu no ambiente. Depois descobri em fórum fechado que colegas de outras montadoras já tinham visto o mesmo padrão semanas antes.
13. O que impediria você de usar a plataforma?
Se fosse cara demais o cliente não aprovaria licença corporativa. Se tivesse muito ruído eu abandonaria rápido. E se o processo de verificação fosse muito burocrático eu ficaria como usuário comum e não contribuiria.
GANHOS
14. O que buscaria primeiro na plataforma?
Filtro automotivo LATAM, últimos 15 dias. Depois olharia TTPs específicos de ataques a cadeia de suprimentos e OT. Se tivesse hashes exportáveis eu jogaria direto no SIEM pra caçada retroativa.
15. Como gostaria de receber os alertas?
Feed no site pra consulta diária, digest matinal por e-mail com highlights do setor, e API pra integrar com SIEM e SOAR. Voltaria todo dia se encontrasse conteúdo que não está em Twitter nem em blog conhecido.
Entrevista 3 — Paulo Sizino
Analista SOC N3 CSIRT, Accenture — Atuação em qualquer cliente com incidente
O que ele VÊ
1. Frequência de busca por informações
O tempo todo. Como N3 CSIRT eu atuo em incidentes ativos de vários clientes e setores diferentes, então threat intel é insumo constante do meu trabalho. Umas 5 a 7 horas do meu dia é isso, entre consumo, análise e produção de intel.
2. Principais fontes
Mandiant Advantage, Recorded Future, MISP interno da Accenture. Reports globais da CrowdStrike, Palo Alto Unit 42, Microsoft Threat Intelligence. GitHub de pesquisadores, MITRE ATT&CK, DFIR Report. Twitter/X pra sinal rápido. Fóruns em russo e chinês eu monitoro com tradutor quando é atribuição de ator específico.
3. Relevância das informações
As pagas são bem específicas, mas ainda com viés global. Pra realidade LATAM tem muito gap. O que me falta mais é o cruzamento setorial em contexto brasileiro.
O que ele OUVE
4. Participação em comunidades
Vários, dependendo do cliente. FS-ISAC pra financeiro, E-ISAC pra energia, Auto-ISAC pra automotivo. Todos com foco EUA e barreiras de entrada. CERT.br pra macro. Comunidades regionais LATAM eu tento fomentar informalmente com colegas de outras empresas em conferência.
5. Contato com outros profissionais
Muito útil, especialmente pra colaboração em investigação ativa. Muitas vezes durante um incidente eu preciso saber se outro CSIRT ou tech lead está vendo o mesmo indicador.
O que ele PENSA E SENTE
6. Maior preocupação
Pra mim é o oposto do que meus analistas mais júnior falariam. Awareness eu tenho de sobra, meu problema é conseguir descer pro nível de IOC e TTP acionável rápido o suficiente pra responder ao incidente.
7. Confiança na plataforma
Confiaria mediante marcação TLP em cada publicação. Verificação de indivíduo mais empresa, vouching por pares e histórico de contribuição. Reputação da fonte precisa ser transparente.
O que ele FALA E FAZ
8. Tempo dedicado
Umas 30 a 35 horas por semana, considerando que threat intel é insumo direto do meu trabalho de resposta.
9. Compartilhamento de inteligência
Internamente entre os SOCs e CSIRTs da Accenture sim. Externamente é caso a caso e depende do NDA do cliente, geralmente vai via ISAC.
10. Integrações
VirusTotal, AbuseIPDB, AlienVault OTX, GreyNoise, Shodan, Censys, PulseDive. E idealmente exportação em STIX/TAXII pra alimentar o MISP direto.
11. Publicação
Combinação sempre. IOC sozinho é ruído. Meu formato preferido é IOC mais TTP no MITRE mais contexto de campanha mais atribuição quando possível.
DORES
12. Falta de informação
Quando faço lições aprendidas e threat hunting proativo, muitas vezes descubro que a informação existia e não foi capturada em tempo. Isso me frustra bastante.
13. Barreiras de adoção
Falta de suporte a STIX/TAXII. Falta de TLP. Ausência de mecanismo pra proteger informação sensível de atribuição. Também não uso plataforma sem API robusta.
GANHOS
14. Principal necessidade
Cruzamento setorial no Brasil e LATAM. Filtro por ator ou família de malware. Busca por hash, IP ou domínio direto pra enrichment durante resposta ativa.
15. Forma de utilização
API e webhook pra integrar com MISP e SIEM. Feed no site pra pesquisa ad-hoc durante incidente. E-mail digest diário pra visão geral do que os pares estão vendo.
Entrevista 4 — Edgar Pedrosa
Gerente SOC, Accenture
O que ele VÊ
1. Frequência
Diariamente, mas de forma diferente dos meus analistas. Eles fazem o operacional, eu consumo relatórios executivos e me foco no que vira decisão de investimento, contratação e postura de defesa.
2. Fontes
Recorded Future e Mandiant. Relatórios trimestrais da Verizon DBIR, CrowdStrike Global Threat Report, IBM X-Force. LinkedIn de outros gerentes e CISOs e os reports internos dos meus tech leads e do time de threat intel da Accenture.
3. Relevância
As pagas são bem específicas. As gratuitas são genéricas. O problema é que meu time todo não tem acesso às plataformas pagas por questão de licenciamento.
O que ele OUVE
4. Comunidades
Como gerente participo indiretamente pelos clientes. FS-ISAC, E-ISAC, Auto-ISAC, dependendo do portfolio. Todos com foco EUA, em inglês, e caros. Pra realidade brasileira falta algo equivalente.
5. Networking
Extremamente útil. Usaria pra networking com outros gerentes de SOC em situações de crise e também pra benchmark de estrutura, custos, contratação e maturidade.
O que ele PENSA E SENTE
6. Principal preocupação
Não saber é pior estrategicamente. Sem detalhe eu ainda ajusto postura genericamente e delego pro tech lead aprofundar. Sem informação nenhuma eu tomo decisão no escuro.
7. Confiança
Confiaria com processo de verificação equivalente aos ISACs. Idealmente verificação de empresa e não só de indivíduo. Precisa ter algum tipo de acordo de confidencialidade ou termo que dê proteção jurídica pra quem publica.
O que ele FALA E FAZ
8. Tempo dedicado
Umas 5 horas eu direto. Mas se somar o tempo do meu time todo, é fácil passar de 100 horas semana coletiva.
9. Compartilhamento
Internamente entre os SOCs e CSIRTs da Accenture sim. Com o cliente sempre. Externamente é decisão do cliente e passa pelo jurídico deles.
10. Integrações
Meu time usa muito. Eu enquanto gerente uso indiretamente, mas é premissa. Se a plataforma não fizesse isso, meu time reclamaria em uma semana e eu não conseguiria justificar a assinatura corporativa.
11. Publicação
A combinação, mas com camada de sanitização forte. Publicaríamos IOCs e TTPs limpos, contexto sem identificar cliente ou volume financeiro.
DORES
12. Falta de informação
Quando a informação chega atrasada, eu perco janela de decisão e a resposta acaba sendo reativa em vez de preventiva.
13. Barreiras de adoção
Preço fora da realidade brasileira. Falta de aderência à LGPD e riscos jurídicos mal tratados. Falta de mecanismo de proteção da confidencialidade do cliente é dealbreaker.
GANHOS
14. O que buscaria primeiro
Visão executiva das ameaças ativas por setor no Brasil na última semana. Depois cruzamento com os setores dos clientes que atendemos pra ver onde priorizar recursos.
15. Forma de utilização
Digest executivo semanal por e-mail, feed do site pra consulta e integração via API pro meu time no operacional. Voltaria se eu conseguisse levar insight único pra minha próxima reunião com liderança e clientes.

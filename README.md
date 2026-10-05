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


## 7.6 Alternativas de Mercado e Posicionamento (Benchmarking)

Embora existam ferramentas e bases de dados consolidadas no ecossistema de segurança cibernética voltadas à consulta de indicadores e inteligência de ameaças, o CTHFeedTatics se diferencia ao endereçar lacunas específicas deixadas por essas soluções, posicionando-se de forma complementar ou alternativa a elas:

**VirusTotal**

* O que é: Plataforma global de análise de arquivos, domínios, IPs e URLs suspeitos utilizando múltiplos motores antivírus e scanners de segurança.

* Onde difere da nossa solução: O VirusTotal é altamente focado na análise técnica pontual de artefatos (análise de arquivos e URLs) e na verificação automatizada por motores. O CTHFeedTatics não faz análise detalhada de ataques e foca na contextualização setorial (quais ofensores atacam determinada indústria) e no networking entre profissionais de um mesmo nicho, indo muito além de uma caixa de pesquisa de hashes.

**ThreatFox (por abuse.ch)**

* O que é: Plataforma comunitária gratuita voltada especificamente para o compartilhamento e descoberta de IOCs de malware (como endereços IP de C2 e payloads).

* Onde difere da nossa solução: O ThreatFox opera como um feed técnico e massivo de indicadores de malware com forte apelo open-source e voltado para analistas técnicos. O CTHFeedTatics introduz a camada de segmentação por indústria e verificação de identidade profissional, permitindo que analistas de um mesmo setor entendam o impacto da ameaça no seu nicho de negócio, além de viabilizar a conexão profissional direta com pares da mesma área.

**AlienVault OTX (Open Threat Exchange - AT&T Cybersecurity)**

* O que é: Uma das maiores redes abertas de inteligência de ameaças baseada em colaboração, onde usuários criam "Pulses" (agrupamentos de IOCs e descrições de campanhas).

* Onde difere da nossa solução: O OTX é uma excelente ferramenta aberta, mas frequentemente sofre com o excesso de ruído e alertas genéricos, exigindo esforço manual intenso de filtragem. Além disso, o OTX possui um ecossistema mais generalista. O CTHFeedTatics resolve esse problema ao propor uma curadoria focada rigidamente na realidade setorial do cliente e em barreiras de verificação que elevam a qualidade e a confiabilidade das interações e publicações corporativas.

## Síntese do Posicionamento:

Enquanto ferramentas como VirusTotal ajudam a "testar o arquivo", o ThreatFox centraliza "o indicador técnico de malware" e o OTX funciona como uma rede global aberta e ampla, o CTHFeedTatics atua no filtro e na tradução contextual desses dados para a realidade de cada indústria, unindo a inteligência setorial à conexão direta entre profissionais, sem a complexidade ou os custos proibitivos de plataformas comerciais fechadas.

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
__________________________________________________________________________________________________________________________________________________
# 9. Canvas de Proposta de Valor

## 9.1 Profissionais de tecnologia e segurança da informação (usuários que consultam, validam e compartilham inteligência de ameaças)

### 9.1.1 Tarefas

* Monitorar continuamente ameaças cibernéticas direcionadas à indústria da organização.

* Encontrar informações sobre ataques que estejam afetando empresas do mesmo setor.

* Identificar rapidamente IOCs, como hashes, endereços IP, domínios e URLs relacionados às ameaças.

* Identificar TTPs e metodologias utilizadas pelos ofensores.

* Filtrar alertas e informações para identificar quais ameaças são realmente relevantes para o contexto da organização.

* Validar tecnicamente IOCs antes de utilizá-los nos processos e ferramentas internas de segurança.

* Acompanhar diferentes fontes de Threat Intelligence para identificar novas ameaças.

* Compartilhar internamente informações relevantes com equipes de TI, segurança e gestores.

* Compartilhar IOCs e metodologias de ataque identificados com outros profissionais do setor, quando possível e mediante verificação.

* Encontrar profissionais verificados de outras organizações do mesmo setor para troca direta de informações quando necessário.

### 9.1.2 Dores

* Informações sobre ameaças estão dispersas entre diferentes feeds, sites, redes sociais, comunidades e relatórios.

* Grande quantidade de alertas genéricos dificulta encontrar ameaças realmente relacionadas à indústria da organização.

* A busca manual em diversas fontes consome tempo e não garante que as informações encontradas sejam relevantes.

* Ataques contra empresas semelhantes podem ser descobertos tardiamente, reduzindo a capacidade de prevenção.

* IOCs encontrados em alertas e fontes externas nem sempre possuem validação ou contexto suficiente.

* A validação de indicadores exige consultas adicionais a feeds e serviços reputacionais.

* Falta um ambiente centralizado para consumir e, quando autorizado, publicar informações sobre ataques relacionados ao setor.

* Existe pouca comunicação e colaboração entre organizações de pequeno e médio porte que enfrentam ameaças semelhantes.

* Comunidades especializadas, como ISACs e CERTs, podem possuir barreiras de entrada relacionadas a custo, formalidade ou processo.

* Relatórios especializados de Threat Intelligence podem ser inacessíveis para organizações de menor porte.

* Parte das informações disponíveis é produzida por fornecedores de segurança e pode estar associada à promoção de produtos e serviços específicos.

### 9.1.3 Ganhos

* Acesso centralizado a informações sobre ataques cibernéticos filtradas pela indústria da organização.

* Feed atualizado de ameaças relevantes ao contexto setorial.

* Economia de tempo ao reduzir a necessidade de consultar diversas fontes diariamente.

* Maior facilidade para identificar IOCs e TTPs relacionados às ameaças relevantes.

* Redução do ruído informacional por meio da segmentação das informações por indústria.

* Maior confiança nos IOCs por meio da integração com feeds reputacionais.

* Capacidade de antecipar ameaças que já estejam afetando empresas semelhantes.

* Acesso mais acessível a inteligência de ameaças que normalmente pode estar restrita a relatórios e serviços pagos.

* Possibilidade de contribuir com IOCs e metodologias de ataque mediante processo de verificação.

* Acesso a uma rede de contatos de profissionais verificados da mesma indústria.

* Maior confiança na postura de segurança da organização por meio de informações contextualizadas ao setor.

### 9.1.4 Produtos

* Plataforma web centralizada de inteligência de ameaças.

* Feed de inteligência segmentado por indústria.

* Informações sobre ataques cibernéticos direcionados a diferentes setores.

* Informações sobre ofensores relacionados às ameaças publicadas.

* Consulta de IOCs, incluindo hashes, endereços IP, domínios e URLs.

* Consulta de TTPs e metodologias utilizadas nos ataques.

* Integração com APIs e feeds reputacionais para checagem e enriquecimento de IOCs.

* Sistema de classificação das informações de ameaças por indústria.

* Sistema de autenticação e verificação de usuários.

* Publicação de IOCs e metodologias de ataque por usuários verificados.

* Acesso às informações de contato de outros profissionais verificados.

* Mecanismos de moderação e curadoria das contribuições realizadas pela comunidade.

### 9.1.5 Aliviadores de ganhos

* Centraliza informações sobre ameaças para reduzir a necessidade de pesquisa manual em múltiplas fontes.

* Reduz o excesso de informações genéricas ao organizar ameaças de acordo com a indústria do usuário.

* Diminui o tempo gasto na coleta e curadoria manual de Threat Intelligence.

* Facilita a identificação de ataques relevantes ao apresentar informações relacionadas a organizações e setores semelhantes.

* Reduz a insegurança sobre IOCs ao adicionar informações provenientes de feeds reputacionais.

* Diminui a necessidade de realizar separadamente parte das consultas reputacionais sobre os indicadores apresentados.

* Reduz a fragmentação ao reunir ataques, ofensores, IOCs e TTPs em um ambiente centralizado.

* Diminui o isolamento entre profissionais ao permitir que usuários verificados encontrem contatos de outros profissionais verificados.

* Reduz as barreiras de acesso à inteligência setorial ao oferecer uma alternativa a comunidades e relatórios especializados mais restritos.

* Diminui a dependência de conteúdo vendor-based por meio de uma abordagem independente de fabricantes específicos.

### 9.1.6 Geradores de ganhos

* Aumenta a velocidade de identificação de ameaças ao apresentar inteligência relacionada diretamente à indústria do usuário.

* Melhora a capacidade de antecipação ao permitir acompanhar ameaças que já atingiram organizações semelhantes.

* Aumenta a eficiência do profissional ao reduzir o tempo dedicado à coleta e filtragem manual de informações.

* Aumenta a relevância da inteligência consumida ao relacionar ataques, ofensores, IOCs e TTPs ao contexto setorial.

* Amplia a confiança nos indicadores ao combinar informações disponibilizadas na plataforma com dados de feeds reputacionais.

* Facilita o acesso a inteligência de ameaças setorial para profissionais e organizações de diferentes portes.

* Estimula a colaboração entre organizações ao permitir que usuários verificados publiquem IOCs e metodologias de ataque.

* Facilita o contato entre profissionais verificados que enfrentam contextos de ameaça semelhantes.

* Permite que informações identificadas em uma organização contribuam para a preparação de outras empresas do mesmo setor.

* Amplia progressivamente a base de inteligência conforme novos IOCs, metodologias e informações relevantes são compartilhados.

* Cria um efeito de rede no qual o crescimento das contribuições e da comunidade verificada aumenta o valor da plataforma para os demais usuários.

__________________________________________________________________________________________________________________________________________________
# Visão do Produto

**Para** profissionais de tecnologia e segurança da informação responsáveis pela postura de segurança cibernética de organizações de diferentes portes, incluindo analistas de SOC, analistas de Threat Intelligence, engenheiros de detecção, Incident Responders, gestores de segurança, CISOs e profissionais de TI com responsabilidades de segurança.

**Que dores** precisam acompanhar ameaças relevantes à sua indústria, identificar IOCs e TTPs e obter informações confiáveis sobre ataques, mas hoje dependem de múltiplas fontes dispersas, alertas genéricos e informações sem contexto setorial, gastando tempo na coleta e validação manual e tendo dificuldade para colaborar com profissionais de outras organizações do mesmo setor.

**O** CTHFeedTatics

**Que benefícios** centraliza inteligência de ameaças e organiza as informações de acordo com a indústria do usuário, reduzindo o ruído informacional e o tempo gasto na busca manual, facilitando a identificação de ameaças relevantes e oferecendo maior confiança nos IOCs por meio de integração com feeds reputacionais, além de possibilitar a contribuição e o contato entre profissionais verificados.

**É uma** plataforma web de inteligência de ameaças cibernéticas segmentada por indústria, voltada à centralização, consulta, validação e compartilhamento de informações sobre ataques, ofensores, indicadores de comprometimento (IOCs) e técnicas, táticas e procedimentos (TTPs).

**Diferente de** portais genéricos de notícias de segurança, feeds dispersos, grupos informais de comunicação, relatórios pagos de Threat Intelligence, comunidades com altas barreiras de entrada e plataformas vendor-based direcionadas por fabricantes de ferramentas de segurança.

**O nosso produto** organiza informações sobre ameaças em feeds segmentados por indústria, permitindo que profissionais encontrem ataques, ofensores, IOCs e TTPs relevantes ao seu contexto, com integração a APIs e feeds reputacionais para checagem dos indicadores. Usuários verificados podem contribuir com IOCs e metodologias de ataque e acessar informações de contato de outros profissionais verificados, fortalecendo a colaboração e a inteligência coletiva entre organizações que enfrentam ameaças semelhantes, sem substituir ferramentas de análise, resposta, SIEM/SOAR ou canais externos de comunicação.
__________________________________________________________________________________________________________________________________________________

# 10. Roadmap Estratégico de Negócio

O Roadmap Estratégico de Negócio do **CTHFeedTatics** organiza, em horizontes de curto, médio e longo prazo, as iniciativas necessárias para transformar a visão do produto em uma plataforma sustentável de inteligência de ameaças setorial. Diferente de um roadmap de produto — que trata de funcionalidades específicas —, este documento foca em **objetivos estratégicos**: entrada em mercado, construção de comunidade, definição de modelo de monetização, parcerias e expansão de canais.

Considerando o uso intensivo de ferramentas de IA generativa, low-code/no-code e infraestrutura em nuvem gerenciada, o horizonte total do roadmap foi comprimido para **seis meses**, divididos em três fases sequenciais. Os prazos incluem os tempos de medição e avaliação da solução diante do mercado.

## 10.1 Visão Aspiracional

Tornar o CTHFeedTatics a **principal referência aberta e não-vendor-based de inteligência de ameaças cibernéticas setorial no Brasil e na América Latina**, reconhecida por profissionais de segurança como o hub de consulta diária para identificar ameaças ativas em seu setor, validar indicadores e colaborar com pares verificados — reduzindo a assimetria informacional entre grandes corporações e organizações de pequeno e médio porte.

## 10.2 Pilares Estratégicos

Grandes áreas de foco que sustentam a visão. Todas as iniciativas do roadmap se ancoram em pelo menos um destes pilares:

1. **Aquisição e ativação de usuários** — atrair profissionais de segurança do segmento-alvo e converter visitantes em usuários ativos recorrentes.

2. **Confiança e verificação** — construir e sustentar a credibilidade da plataforma por meio de curadoria, processo de verificação e mecanismos de reputação de fontes.

3. **Comunidade e efeito de rede** — habilitar contribuições verificadas e networking entre profissionais, criando o ciclo virtuoso descrito na síntese do modelo de negócio.

4. **Integrações e ecossistema técnico** — conectar a plataforma às ferramentas que os usuários já operam (SIEM, SOAR, TIP, feeds reputacionais) via APIs e padrões como STIX/TAXII.

5. **Sustentabilidade e monetização** — validar e implementar modelo de receita que preserve a independência não-vendor-based e permita cobrir custos operacionais.

6. **Compliance e segurança jurídica** — garantir aderência à LGPD, definir políticas de TLP (Traffic Light Protocol) e proteção jurídica para publicação e consumo de IOCs.

## 10.3 Fases do Roadmap

### Fase 1 — Fundação e Validação (Mês 0 a Mês 2)

**Objetivo estratégico:** validar hipóteses centrais da Matriz SCD com um MVP funcional e uma base inicial de usuários engajados no contexto brasileiro.

**Pilares envolvidos:** Aquisição e ativação · Confiança e verificação · Compliance.

**Iniciativas:**

* **Lançamento do MVP web** com feed segmentado por indústria, cadastro básico, consulta de IOCs e TTPs e integração inicial com pelo menos um feed reputacional público (ex.: AbuseIPDB, VirusTotal em plano gratuito).

* **Definição do processo de verificação de usuários** em versão inicial — validação manual por documento profissional, e-mail corporativo ou indicação de verificado existente.

* **Curadoria manual assistida por IA** para popular o feed com informações setoriais durante o período de bootstrapping, enquanto a comunidade ainda não gera volume próprio.

* **Publicação da política de TLP e termos de uso**, definindo regras claras de compartilhamento, responsabilidade sobre conteúdo publicado e tratamento de dados sob a LGPD.

* **Foco geográfico e setorial inicial:** Brasil, com dois a três setores-piloto (ex.: financeiro, varejo, saúde) selecionados a partir das entrevistas realizadas.

* **Aquisição orgânica em comunidades:** divulgação em grupos de segurança brasileiros (LinkedIn, Discord, Telegram), participação em eventos regionais (ex.: BSides locais, meetups de threat intel).

**Métricas de saída da fase:**

* 200 a 500 usuários cadastrados.
* 30 a 50 usuários verificados ativos.
* Pelo menos 100 IOCs setoriais consultáveis na plataforma.
* Taxa de retorno semanal (WAU/MAU) ≥ 30%.
* NPS inicial mensurado com base amostral.

**Hipóteses validadas nesta fase:** dor de fragmentação · valor da segmentação por indústria · viabilidade do processo de verificação inicial.

---

### Fase 2 — Tração e Ecossistema (Mês 2 a Mês 4)

**Objetivo estratégico:** transformar o MVP validado em uma plataforma com tração real, integrações técnicas e primeiros sinais de efeito de rede setorial.

**Pilares envolvidos:** Comunidade e efeito de rede · Integrações e ecossistema técnico · Aquisição e ativação.

**Iniciativas:**

* **Lançamento da API pública de consulta de IOCs** com autenticação por token, permitindo que usuários integrem o CTHFeedTatics aos seus SIEMs e ferramentas de detecção.

* **Suporte a exportação em formatos padrão** (STIX 2.1 e feeds TAXII básicos), removendo uma das lacunas apontadas pelo perfil N3/CSIRT nas entrevistas de aderência.

* **Habilitação da publicação por usuários verificados** com fluxo estruturado (formulário guiado, validação automática do IOC contra feeds reputacionais antes da publicação, atribuição de TLP pelo autor).

* **Diretório de verificados por indústria**, entregando o valor de networking identificado no mapa de empatia — com controles de privacidade e opt-in por parte do verificado.

* **Alertas personalizados e digest por e-mail**, cobrindo uma das lacunas marcadas como "Ausente" na Matriz SCD.

* **Parcerias iniciais** com uma ou duas comunidades brasileiras de segurança (ex.: BSides, CERT.br, capítulos regionais da OWASP) para divulgação cruzada e legitimação.

* **Expansão setorial:** adicionar mais três a quatro indústrias além dos setores-piloto, guiada pela demanda observada na Fase 1.

**Métricas de saída da fase:**

* 1.500 a 3.000 usuários cadastrados.
* 150 a 250 usuários verificados ativos.
* Pelo menos 30% dos IOCs do feed originados por contribuições da comunidade (não apenas curadoria interna).
* Ao menos 20 organizações consumindo a API ativamente.
* Retenção mensal (M1→M2) ≥ 40%.

**Hipóteses validadas nesta fase:** disposição a contribuir mediante verificação · valor real da API para N2/N3 · aceitação de TLP como mecanismo de compartilhamento controlado.

---

### Fase 3 — Sustentabilidade e Expansão (Mês 4 a Mês 6)

**Objetivo estratégico:** consolidar modelo de monetização compatível com a proposta não-vendor-based, iniciar expansão para a América Latina e entregar recursos que sustentem a visão executiva demandada por gestores.

**Pilares envolvidos:** Sustentabilidade e monetização · Comunidade e efeito de rede · Compliance.

**Iniciativas:**

* **Lançamento do modelo freemium**, com camada gratuita robusta (consulta, feed setorial, contribuição verificada) e camada paga voltada a organizações — planos corporativos com múltiplos assentos, cotas ampliadas de API, exportações avançadas e dashboards executivos.

* **Dashboard executivo por indústria**, entregando a visão consolidada demandada pelo perfil gerencial nas entrevistas — indicadores agregados de ameaças ativas no setor, tendências, ofensores recorrentes.

* **Expansão geográfica para LATAM**, começando por países hispano-falantes com contexto de ameaças próximo ao brasileiro (ex.: México, Argentina, Colômbia), com localização de interface e curadoria de conteúdo setorial regional.

* **Parcerias com CSIRTs e CERTs regionais** para troca controlada de indicadores e legitimação institucional em cada mercado.

* **Programa de contribuidores reconhecidos**, sistema de reputação para verificados que consistentemente publicam IOCs de qualidade — abordando o job social de "ganhar reputação na comunidade".

* **Auditoria de compliance LGPD e revisão jurídica** com apoio externo, formalizando a proteção jurídica demandada pelo perfil gerencial.

* **Programa de embaixadores acadêmicos** em universidades brasileiras com cursos de segurança da informação, apoiando aquisição de longo prazo e formação de comunidade.

**Métricas de saída da fase:**

* 5.000 a 10.000 usuários cadastrados.
* 500+ usuários verificados ativos.
* Pelo menos 3 organizações pagantes no plano corporativo (validação de disposição a pagar).
* Presença de conteúdo setorial em ao menos 2 países além do Brasil.
* Custo de aquisição por usuário verificado (CAC) mensurado e estável.

**Hipóteses validadas nesta fase:** disposição a pagar por camada corporativa · valor real da visão executiva para gestores · viabilidade da expansão LATAM sem perder foco setorial.

## 10.4 Visão Consolidada do Roadmap

| Horizonte | Foco Estratégico | Entregas-Chave | Pilares Dominantes |
|---|---|---|---|
| **Curto prazo** (Mês 0–2) | Fundação e Validação | MVP web · verificação inicial · curadoria assistida por IA · TLP e LGPD básicos · foco Brasil, 2–3 setores | Aquisição · Confiança · Compliance |
| **Médio prazo** (Mês 2–4) | Tração e Ecossistema | API pública · STIX/TAXII · publicação por verificados · diretório de contatos · alertas personalizados · parcerias com comunidades | Comunidade · Integrações · Aquisição |
| **Longo prazo** (Mês 4–6) | Sustentabilidade e Expansão | Freemium e planos corporativos · dashboard executivo · expansão LATAM · parcerias com CSIRTs · reputação de contribuidores · compliance auditado | Monetização · Comunidade · Compliance |

## 10.5 Validação Contínua e Adaptação

O roadmap deve ser revisado a cada fase com base em:

* **Métricas quantitativas** de aquisição, ativação, retenção e contribuição definidas em cada fase.
* **Feedback qualitativo** dos usuários verificados via entrevistas periódicas e questionário estruturado (reaproveitando o roteiro da Seção 4).
* **Sinais de mercado**: surgimento de concorrentes, mudanças regulatórias (ex.: evolução da LGPD, marco civil da IA), incidentes setoriais de grande impacto que alterem a demanda por certos verticais.

A vantagem competitiva do CTHFeedTatics — segmentação setorial, contexto brasileiro/LATAM e independência de fabricantes — é **temporária**. Concorrentes globais podem regionalizar suas ofertas, e plataformas vendor-based podem tentar replicar o modelo comunitário. O roadmap deve, portanto, ser tratado como documento vivo, ajustado a cada ciclo com base em evidência.

## 10.6 Ecossistema e Parcerias

A construção de valor sustentável do CTHFeedTatics depende de um ecossistema ativo. As categorias de parceria priorizadas ao longo das três fases são:

* **Provedores de feeds reputacionais** (Fase 1–2) — VirusTotal, AbuseIPDB, AlienVault OTX, MISP público.
* **Comunidades brasileiras de segurança** (Fase 1–2) — BSides, CERT.br, OWASP, capítulos regionais.
* **CSIRTs e CERTs governamentais e setoriais** (Fase 3) — para legitimação institucional e troca controlada.
* **Instituições acadêmicas** (Fase 3) — programas de embaixadores e pesquisa aplicada.
* **Provedores de infraestrutura em nuvem** (todas as fases) — parceria comercial que preserve independência editorial.

Todas as parcerias devem ser avaliadas pelo critério **não-vendor-based**: nenhuma parceria pode conceder ao parceiro influência sobre a priorização, apresentação ou curadoria da inteligência exibida aos usuários.

# 11. Proto-Personas e Jornadas do Usuário

Como o CTHFeedTactics ainda está em fase de descoberta — com as quatro entrevistas exploratórias já realizadas, porém sem validação estatística ampla —, as representações abaixo são tratadas como **proto-personas**: versões iniciais e hipotéticas, ancoradas nos artefatos anteriores do projeto (Segmento de Cliente, Mapa de Empatia, JTBD, Business Model Canvas e Problem-Solution Fit), que serão refinadas conforme o volume de entrevistas aumentar.

Cada proto-persona foi construída a partir de um perfil profissional distinto identificado no documento de Análise de Aderência: analista N1, analista N2 de investigação, engenheiro CSIRT/N3 e gestor de SOC. Elas compartilham o mesmo segmento de cliente definido na Seção 2, mas diferem em profundidade da dor, ferramentas usadas e resultados esperados da plataforma.

## 11.1 Proto-Personas

### Proto-Persona 1 — Enzo, o analista N1 apagando incêndio

**Nome representativo:** Enzo, o analista N1 apagando incêndio
**Nome descritivo:** Analista de SOC Nível 1 (Triagem de Alertas)

**Dados demográficos:** 22–28 anos. Formação técnica ou superior em andamento em áreas de TI/Segurança. Baseado em capital brasileira. Trabalha em regime de turnos (24x7) em SOC terceirizado ou interno.

**Comportamentos e hábitos:**

* Consome informações de threat intel em fragmentos ao longo do turno — LinkedIn, Twitter/X, grupos de Telegram e Discord de segurança.
* Depende de playbooks e runbooks para tomar decisão em cada alerta.
* Escala para N2/N3 quando o alerta parece relevante mas falta contexto.
* Prefere respostas rápidas, formato digest, informação já mastigada.

**Necessidades e objetivos:**

* Priorizar alertas com base em contexto setorial ("isso está atingindo empresas parecidas com a minha agora?").
* Reduzir tempo de triagem por alerta.
* Ganhar autonomia para decidir se um alerta escala ou fecha, sem depender só de N2.
* Aprender sobre TTPs e ofensores ativos no setor durante o próprio trabalho.

**Frustrações e dores:**

* Alertas genéricos sem contexto setorial travam a decisão.
* Excesso de fontes dispersas — não dá tempo de consultar tudo durante o turno.
* Threat intel paga é inacessível na função dele; conteúdo grátis é raso ou vendor-based.
* Sensação de estar sempre reagindo, nunca antecipando.

**Canais e ferramentas:**

* SIEM (Sentinel, Chronicle, Splunk, XSIAM ou similar) no dia a dia.
* Slack/Teams internos para escalação.
* Web pelo desktop de trabalho; celular pessoal para leitura fora do turno.
* Grupos de Telegram/Discord de comunidade de segurança.

**Citação representativa:**
*"Chegou o alerta, eu tenho 15 minutos pra decidir se escalo ou fecho. Preciso saber se isso já bateu no meu setor hoje."*

---

### Proto-Persona 2 — Marina, a analista N2 de investigação

**Nome representativo:** Marina, a analista N2 de investigação
**Nome descritivo:** Analista de SOC Nível 2 (Investigação e Detection Engineering)

**Dados demográficos:** 26–35 anos. Superior completo em áreas de TI/Segurança, geralmente com certificações intermediárias (Security+, CySA+, BTL1 ou equivalente). Baseada em capital brasileira, muitas vezes remoto. Trabalha em SOC interno de empresa média/grande ou em MSSP.

**Comportamentos e hábitos:**

* Investiga alertas escalados pelo N1 e conduz análises de incidentes de média complexidade.
* Escreve e ajusta regras de detecção com base em TTPs observados no setor.
* Acompanha relatórios de threat intel semanais e mensais quando o tempo permite.
* Mantém um "caderno de notas" pessoal de IOCs e comportamentos recorrentes por vertical.

**Necessidades e objetivos:**

* Obter inteligência aplicável à investigação em andamento — IOCs enriquecidos, TTPs mapeados no MITRE ATT&CK, contexto do ofensor.
* Correlacionar padrões observados no ambiente com o que outras empresas do setor estão vendo.
* Reduzir tempo de investigação por caso.
* Melhorar suas regras de detecção com base em inteligência setorial.

**Frustrações e dores:**

* Informação genérica não ajuda a decidir se um comportamento é campanha ativa ou ruído.
* Falta de recorte setorial obriga a filtrar manualmente relatórios globais.
* IOCs sem contexto (TLP, ofensor, data, alvo) exigem retrabalho antes de aplicar.
* Dependência de comunidades informais para conseguir contexto rápido — não escala.

**Canais e ferramentas:**

* SIEM, EDR, TIP (quando existe), MISP (às vezes).
* Ferramentas de OSINT (Shodan, Censys, VirusTotal, urlscan).
* MITRE ATT&CK Navigator.
* Comunidades técnicas (BSides, Discord, canais fechados).

**Citação representativa:**
*"Se eu souber que essa TTP já foi vista em outros três casos do meu setor esse mês, muda completamente como eu escrevo a regra."*

---

### Proto-Persona 3 — Paulo, o engenheiro CSIRT que quer dado integrável

**Nome representativo:** Paulo, o engenheiro CSIRT que quer dado integrável
**Nome descritivo:** Analista Sênior de CSIRT / Threat Intelligence Engineer

**Dados demográficos:** 30–42 anos. Superior completo, frequentemente com pós-graduação em segurança da informação. Certificações avançadas (GCIH, GCTI, GCFA, OSCP ou equivalentes). Baseado em capital brasileira, atua em CSIRT interno de grande empresa, setor financeiro, energia ou governo.

**Comportamentos e hábitos:**

* Consome inteligência estruturada, prefere STIX/TAXII a leitura de blog post.
* Automatiza ingestão de feeds em TIP interno (MISP, OpenCTI) e correlaciona com SIEM/SOAR.
* Contribui com IOCs e TTPs para comunidades fechadas (ISACs setoriais, grupos entre CSIRTs).
* Avalia fontes por reputação, cobertura setorial e frescor dos indicadores.

**Necessidades e objetivos:**

* Ingerir inteligência setorial via API/STIX/TAXII sem intervenção manual.
* Validar automaticamente reputação e contexto de IOCs antes de aplicar em regras de bloqueio.
* Compartilhar IOCs e TTPs de incidentes locais de forma controlada (TLP:AMBER, TLP:GREEN) com pares do setor.
* Manter cobertura setorial brasileira/LATAM, que os feeds globais entregam mal.

**Frustrações e dores:**

* Feeds globais têm baixa relevância setorial local — muito ruído, pouco sinal.
* ISACs brasileiros têm barreiras de entrada (custo, formalidade, vínculo institucional).
* Plataformas vendor-based influenciam curadoria conforme o portfólio do fornecedor.
* Falta de padrões (STIX/TAXII, TLP) em plataformas emergentes inviabiliza integração.

**Canais e ferramentas:**

* TIP (MISP, OpenCTI), SIEM, SOAR, EDR.
* APIs, scripts Python de automação, cron jobs de ingestão.
* GitHub para compartilhar sigmas, YARA e detections.
* Comunidades fechadas (Signal, canais restritos, ISACs).

**Citação representativa:**
*"Se não tem API decente e STIX/TAXII, não entra no meu pipeline. Ponto."*

---

### Proto-Persona 4 — Edgar, o gestor de SOC responsável pelo risco

**Nome representativo:** Edgar, o gestor de SOC responsável pelo risco
**Nome descritivo:** Coordenador/Gerente de SOC (Gestão e Reporting Executivo)

**Dados demográficos:** 35–50 anos. Superior completo, geralmente MBA ou pós em gestão de segurança. Certificações de gestão (CISSP, CISM, CRISC) além das técnicas. Baseado em capital brasileira, responde à diretoria de segurança (CISO) ou de TI.

**Comportamentos e hábitos:**

* Consome inteligência de forma consolidada — dashboards, digest semanal, relatórios executivos.
* Prioriza decisões de investimento e priorização de defesa com base em risco setorial.
* Aciona jurídico e compliance antes de aprovar compartilhamento externo de IOCs.
* Cobra da equipe métricas de MTTR, cobertura de detecção e ameaças ativas no setor.

**Necessidades e objetivos:**

* Ter visão consolidada de ameaças ativas no seu setor no Brasil e LATAM.
* Demonstrar postura de segurança embasada em inteligência para diretoria e conselho.
* Compartilhar IOCs com pares setoriais sem gerar exposição jurídica ou violação de LGPD.
* Reduzir custo total de inteligência sem comprometer qualidade.

**Frustrações e dores:**

* Relatórios pagos caros, com pouco recorte para o mercado brasileiro/LATAM.
* Falta de segurança jurídica para compartilhamento de IOCs de incidentes internos.
* Ausência de visão executiva consolidada — analistas trazem dados, mas ele precisa traduzir.
* Fornecedores empurram inteligência atrelada a produto, o que enviesa a análise de risco.

**Canais e ferramentas:**

* Dashboards executivos, relatórios de compliance.
* E-mail e reuniões com CISO, diretoria e jurídico.
* Consultorias jurídicas para revisão de compartilhamento externo.
* Fóruns executivos setoriais (associações, câmaras).

**Citação representativa:**
*"Não basta a informação ser boa. Ela precisa ser algo que eu consiga levar pra diretoria e algo que eu possa compartilhar sem virar processo."*

---

### Proto-Persona 5 — Rafael, o profissional de TI que também cuida da segurança

**Nome representativo:** Rafael, o profissional de TI generalista  
**Nome descritivo:** Analista de Infraestrutura/TI com responsabilidades de segurança

**Dados demográficos:** 27–40 anos. Formação técnica ou superior em TI, Redes, Sistemas de Informação ou áreas relacionadas. Trabalha em empresa de pequeno ou médio porte, normalmente sem SOC próprio e sem equipe dedicada de Threat Intelligence.

**Comportamentos e hábitos:**

* Divide seu tempo entre infraestrutura, suporte, redes, administração de sistemas e segurança.
* Não acompanha feeds especializados de Threat Intelligence continuamente porque não possui tempo nem equipe dedicada.
* Busca informações principalmente quando surge uma notícia relevante, um alerta interno ou um incidente em outra empresa do mesmo setor.
* Utiliza fontes gratuitas, grupos profissionais, portais de tecnologia e ferramentas de reputação para investigar indicadores quando necessário.
* Prefere informações resumidas, contextualizadas e diretamente relacionadas à realidade da empresa.

**Necessidades e objetivos:**

* Saber rapidamente quais ameaças estão atingindo empresas do mesmo setor.
* Identificar IOCs relevantes sem precisar compreender ou operar plataformas complexas de Threat Intelligence.
* Reduzir o tempo gasto pesquisando informações em diferentes fontes.
* Obter contexto suficiente para saber quando uma ameaça merece atenção imediata.
* Encontrar profissionais mais especializados do mesmo setor quando precisar de orientação ou troca de informação.

**Frustrações e dores:**

* Não possui equipe especializada para acompanhar continuamente o cenário de ameaças.
* Muitas plataformas de segurança são complexas ou voltadas a organizações com estruturas maiores.
* Informações encontradas em notícias normalmente não possuem IOCs ou detalhes técnicos úteis.
* Feeds públicos podem apresentar grande volume de dados sem indicar o que realmente importa para sua indústria.
* Relatórios comerciais de Threat Intelligence podem ser caros demais para empresas menores.
* Muitas vezes descobre ameaças relevantes somente depois que outras organizações já foram afetadas.

**Canais e ferramentas:**

* Plataforma web pelo computador de trabalho.
* E-mail para alertas e comunicação.
* Firewall, antivírus/EDR e ferramentas básicas de monitoramento.
* LinkedIn, Telegram, WhatsApp e comunidades profissionais.
* VirusTotal, AbuseIPDB e outras ferramentas gratuitas de consulta quando necessário.

**Citação representativa:**

*"Eu não preciso acompanhar todas as ameaças do mundo. Preciso saber quais delas podem atingir a minha empresa e o que já está acontecendo no meu setor."*

## 11.2 Jornadas do Usuário

As três jornadas abaixo representam situações em que o CTHFeedTactics entrega valor para diferentes perfis de usuários. Embora algumas ações ocorram em ferramentas externas utilizadas pelos profissionais, a **plataforma web do CTHFeedTactics é o principal ponto de acesso às informações**, permitindo consultar o feed setorial, pesquisar IOCs e TTPs, visualizar informações sobre ataques e ofensores, validar indicadores e, para usuários verificados, publicar informações e acessar recursos adicionais.

Cada etapa apresenta a ação realizada pelo usuário, seu sentimento durante a atividade e o principal ponto de contato com o CTHFeedTactics.

---

### Jornada 1 — Enzo (Analista N1): consulta e triagem contextualizada de alerta

**Persona:** Enzo, o analista N1 apagando incêndio  
**Objetivo:** Utilizar a plataforma web do CTHFeedTactics para obter rapidamente contexto sobre um IOC identificado durante a triagem de um alerta e decidir se o caso deve ser escalado.

**1. Receber um alerta e identificar um IOC suspeito**

**Descrição:** Durante o turno no SOC, Enzo recebe um alerta no SIEM contendo um hash, endereço IP, domínio ou URL suspeita. O indicador não possui contexto suficiente para permitir uma decisão imediata.

**Sentimento do usuário:** "Preciso descobrir rapidamente se isso é realmente relevante."

**Touchpoint:** SIEM da organização (fora da plataforma).

---

**2. Acessar o site do CTHFeedTactics**

**Descrição:** Enzo abre o CTHFeedTactics pelo navegador e realiza login. Ao entrar, visualiza a página inicial com o feed de inteligência relacionado à indústria cadastrada em seu perfil.

Antes mesmo de pesquisar o IOC, ele pode verificar se existem ataques, campanhas ou ofensores recentemente associados ao seu setor.

**Sentimento do usuário:** "Quero encontrar a informação sem precisar abrir várias fontes diferentes."

**Touchpoint:** Plataforma Web → Login → Página Inicial / Feed Setorial.

---

**3. Pesquisar o IOC na plataforma**

**Descrição:** Enzo utiliza a barra de busca do site para pesquisar diretamente o IOC identificado no SIEM. A plataforma apresenta resultados relacionados ao indicador, incluindo ocorrências registradas, ataques associados e informações disponíveis sobre sua reputação.

**Sentimento do usuário:** "Preciso de uma resposta objetiva para saber se continuo investigando."

**Touchpoint:** Plataforma Web → Busca de IOC.

---

**4. Consultar contexto setorial e informações relacionadas**

**Descrição:** Na página de resultados, Enzo verifica se o IOC apareceu recentemente em ataques direcionados à sua indústria. Ele pode acessar informações relacionadas ao ataque, ao ofensor e às TTPs registradas.

Os filtros da plataforma permitem restringir os resultados por indústria, tipo de IOC ou período.

**Sentimento do usuário:** "Se esse indicador apareceu recentemente no meu setor, o alerta ganha muito mais importância."

**Touchpoint:** Plataforma Web → Resultados da Busca → Filtros → Página de Detalhes do IOC/Ataque.

---

**5. Verificar a reputação do IOC**

**Descrição:** Dentro da página do indicador, Enzo consulta as informações obtidas por meio das integrações com feeds reputacionais utilizadas pelo CTHFeedTactics. Isso fornece uma camada adicional de contexto antes de sua decisão.

**Sentimento do usuário:** "Agora tenho uma segunda fonte para confirmar se esse indicador é realmente suspeito."

**Touchpoint:** Plataforma Web → Página do IOC → Informações de Reputação.

---

**6. Tomar a decisão de triagem**

**Descrição:** Com o contexto obtido no CTHFeedTactics, Enzo retorna ao SIEM e decide se deve escalar o alerta para um analista mais experiente ou encerrar a ocorrência conforme os procedimentos internos da organização.

Quando necessário, utiliza as informações encontradas na plataforma como referência para justificar sua decisão.

**Sentimento do usuário:** "Tenho contexto suficiente para tomar uma decisão e seguir para o próximo alerta."

**Touchpoint:** CTHFeedTactics → SIEM / sistema interno de tickets.

---

### Jornada 2 — Paulo (CSIRT / Threat Intelligence Engineer): acompanhamento e integração da inteligência setorial

**Persona:** Paulo, o engenheiro CSIRT que quer dado integrável  
**Objetivo:** Utilizar inicialmente a plataforma web para avaliar a qualidade e relevância da inteligência disponibilizada pelo CTHFeedTactics e, posteriormente, integrar os IOCs relevantes ao pipeline interno da organização.

**1. Acessar o site e visualizar o feed da indústria**

**Descrição:** Paulo acessa a plataforma web e realiza login. Na página inicial, encontra o feed de ameaças organizado de acordo com a indústria de sua organização.

Ele utiliza o feed para verificar rapidamente ataques recentes, ofensores observados, IOCs e TTPs relacionados ao seu setor.

**Sentimento do usuário:** "Antes de integrar qualquer fonte, quero saber se os dados realmente são relevantes para o meu ambiente."

**Touchpoint:** Plataforma Web → Página Inicial / Feed Setorial.

---

**2. Explorar ameaças e indicadores disponíveis**

**Descrição:** Paulo navega pelas publicações e utiliza filtros para visualizar ameaças por indústria, período, tipo de indicador e outros critérios disponíveis.

Ao abrir uma publicação, consulta os IOCs associados, TTPs, contexto do ataque, informações do ofensor e dados reputacionais disponíveis.

**Sentimento do usuário:** "Se o conteúdo tiver pouco ruído e bom contexto, pode valer a pena incorporar essa fonte ao nosso processo."

**Touchpoint:** Plataforma Web → Feed → Filtros → Página de Detalhes do Ataque/IOC.

---

**3. Pesquisar indicadores específicos**

**Descrição:** Para avaliar a cobertura da plataforma, Paulo pesquisa IOCs que sua equipe já conhece e compara as informações disponíveis no CTHFeedTactics com as fontes atualmente utilizadas pela organização.

Isso permite avaliar a qualidade, atualidade e relevância setorial dos dados antes de realizar qualquer integração automática.

**Sentimento do usuário:** "Quero saber se essa plataforma acrescenta alguma coisa ao que já consumimos."

**Touchpoint:** Plataforma Web → Busca Global → Página do IOC.

---

**4. Acessar os recursos de integração**

**Descrição:** Após considerar o conteúdo útil, Paulo acessa pelo próprio site a área destinada às integrações da conta verificada. Nessa seção, consulta a documentação disponível e gera as credenciais necessárias para utilizar os recursos de API ou exportação disponibilizados pela plataforma.

**Sentimento do usuário:** "A interface web precisa tornar a configuração simples, mesmo que depois o consumo seja automatizado."

**Touchpoint:** Plataforma Web → Perfil/Configurações → Integrações / API.

---

**5. Configurar a integração com o ambiente interno**

**Descrição:** Paulo utiliza as informações e credenciais obtidas no site para configurar a ingestão dos IOCs relevantes no ambiente interno da organização.

Quando os recursos estiverem disponíveis na evolução da plataforma, essa integração poderá utilizar API e formatos estruturados como STIX/TAXII para alimentar ferramentas como MISP, OpenCTI, SIEM ou SOAR.

**Sentimento do usuário:** "Quero que a inteligência chegue ao pipeline sem depender de pesquisa manual todos os dias."

**Touchpoint:** CTHFeedTactics Web → API/Integração → TIP, SIEM ou SOAR da organização.

---

**6. Retornar ao site para acompanhar contexto e ajustar o consumo**

**Descrição:** Mesmo após automatizar parte do consumo, Paulo continua utilizando o site para consultar publicações completas, investigar ataques específicos, verificar contexto que não aparece diretamente no IOC e ajustar os filtros ou configurações utilizadas pela integração.

**Sentimento do usuário:** "A automação traz os indicadores, mas o site continua sendo onde encontro o contexto."

**Touchpoint:** Plataforma Web → Feed Setorial → Busca → Configurações de Integração.

---

### Jornada 3 — Edgar (Gestor de SOC): acompanhamento setorial e compartilhamento controlado de inteligência

**Persona:** Edgar, o gestor de SOC responsável pelo risco  
**Objetivo:** Utilizar a plataforma web para acompanhar o cenário de ameaças da indústria e, após um incidente, compartilhar IOCs relevantes com outros profissionais por meio de uma publicação realizada como usuário verificado.

**1. Acessar a plataforma para acompanhar ameaças do setor**

**Descrição:** Edgar acessa periodicamente o site do CTHFeedTactics para visualizar o feed relacionado à indústria de sua organização.

Ele observa ataques recentes, ofensores recorrentes, indicadores publicados e tendências que possam ser relevantes para as prioridades de segurança da equipe.

**Sentimento do usuário:** "Preciso entender o que está acontecendo no nosso setor sem analisar dezenas de fontes diferentes."

**Touchpoint:** Plataforma Web → Página Inicial / Feed Setorial.

---

**2. Consultar detalhes de uma ameaça relevante**

**Descrição:** Ao identificar uma publicação importante, Edgar acessa sua página de detalhes para verificar o contexto do ataque, os IOCs associados, as TTPs registradas e outras informações disponibilizadas.

Esses dados podem posteriormente servir de apoio para discussões internas sobre prioridades de defesa e riscos.

**Sentimento do usuário:** "Preciso transformar essas informações em algo que faça sentido para minha equipe e para a gestão."

**Touchpoint:** Plataforma Web → Feed → Página de Detalhes do Ataque.

---

**3. Identificar informações que podem contribuir para a comunidade**

**Descrição:** Após a organização concluir a resposta a um incidente, Edgar e sua equipe identificam IOCs e informações técnicas que poderiam ser úteis para outras empresas do mesmo setor.

Antes da publicação, avaliam internamente quais dados podem ser compartilhados sem expor informações sensíveis da organização.

**Sentimento do usuário:** "Podemos ajudar outras empresas, mas precisamos controlar exatamente o que será divulgado."

**Touchpoint:** Processo interno da organização + consulta às regras e políticas disponíveis no CTHFeedTactics.

---

**4. Acessar a área de publicação do site**

**Descrição:** Como usuário verificado, Edgar entra no CTHFeedTactics e acessa a área destinada à criação de uma nova publicação.

A interface web apresenta um formulário estruturado para inserir informações relacionadas ao ataque, incluindo setor afetado, IOCs e metodologias ou TTPs identificadas.

**Sentimento do usuário:** "Quero publicar somente o necessário, de maneira organizada e rápida."

**Touchpoint:** Plataforma Web → Área do Usuário Verificado → Nova Publicação.

---

**5. Inserir os IOCs e revisar as informações**

**Descrição:** Edgar adiciona os indicadores que podem ser compartilhados e descreve o contexto necessário para que outros profissionais compreendam sua relevância.

Antes da publicação, os IOCs podem ser consultados nos feeds reputacionais integrados à plataforma, permitindo identificar possíveis inconsistências ou informações já existentes.

**Sentimento do usuário:** "Quero ter certeza de que as informações estão corretas antes de disponibilizá-las para outros profissionais."

**Touchpoint:** Plataforma Web → Formulário de Publicação → Validação de IOCs.

---

**6. Publicar e acompanhar a informação no feed**

**Descrição:** Após revisar os dados, Edgar confirma a publicação. O conteúdo passa a integrar a base de inteligência da plataforma e pode ser apresentado aos usuários de acordo com seu contexto setorial e as regras de acesso aplicáveis.

Posteriormente, Edgar pode retornar ao site para visualizar a publicação e acompanhar as informações disponíveis na plataforma.

**Sentimento do usuário:** "Nossa experiência agora pode ajudar outras organizações do setor a identificar a mesma ameaça mais cedo."

**Touchpoint:** Plataforma Web → Publicação → Feed Setorial.

---

### Jornada 4 — Rafael: monitoramento diário de ameaças relevantes à empresa

**Persona:** Rafael, o profissional de TI generalista  
**Objetivo:** Utilizar o site do CTHFeedTactics como fonte rápida de acompanhamento de ameaças relevantes à indústria da empresa, sem precisar consultar diversas fontes externas todos os dias.

**1. Acessar o CTHFeedTactics no início do expediente**

**Descrição:** Rafael abre a plataforma web durante sua rotina diária e realiza login. Como sua conta já possui a indústria da empresa cadastrada, a página inicial apresenta prioritariamente conteúdos relacionados ao seu setor.

**Sentimento do usuário:** "Quero saber se aconteceu alguma coisa importante antes de começar o resto do trabalho."

**Touchpoint:** Plataforma Web → Login → Página Inicial.

---

**2. Visualizar o feed personalizado por indústria**

**Descrição:** Rafael percorre o feed setorial e identifica ataques, campanhas, ofensores, IOCs ou TTPs registrados recentemente contra organizações semelhantes à sua.

A plataforma reduz a quantidade de informações genéricas e apresenta principalmente aquilo que possui relação com o setor cadastrado.

**Sentimento do usuário:** "Isso é muito mais fácil do que abrir cinco sites diferentes."

**Touchpoint:** Plataforma Web → Feed Setorial.

---

**3. Identificar uma ameaça potencialmente relevante**

**Descrição:** Uma publicação informa que empresas do mesmo setor estão sendo alvo de uma nova campanha. Rafael abre a publicação para verificar os detalhes disponíveis.

**Sentimento do usuário:** "Se empresas parecidas com a nossa estão sendo atacadas, preciso olhar isso com atenção."

**Touchpoint:** Plataforma Web → Feed → Publicação de Ataque.

---

**4. Consultar IOCs e TTPs associados**

**Descrição:** Na página do ataque, Rafael verifica os endereços IP, domínios, hashes e demais indicadores associados, além das TTPs registradas.

Ele também consulta as informações reputacionais adicionadas pelas integrações da plataforma.

**Sentimento do usuário:** "Agora consigo verificar se algo disso já apareceu na nossa rede."

**Touchpoint:** Plataforma Web → Página do Ataque → IOCs / TTPs / Reputação.

---

**5. Comparar os indicadores com o ambiente da empresa**

**Descrição:** Rafael consulta suas próprias ferramentas de segurança, logs, firewall ou EDR para verificar se algum dos indicadores apresentados pelo CTHFeedTactics apareceu no ambiente da empresa.

**Sentimento do usuário:** "Até agora não encontramos nada, mas pelo menos sei exatamente o que procurar."

**Touchpoint:** CTHFeedTactics → Ferramentas internas da organização.

---

**6. Salvar ou compartilhar a ameaça com a equipe**

**Descrição:** Caso considere a publicação importante, Rafael copia o link da página ou salva a informação para consulta posterior e compartilha o alerta com colegas ou gestores responsáveis.

**Sentimento do usuário:** "Agora a equipe sabe o que deve observar."

**Touchpoint:** Plataforma Web → Compartilhar/Salvar → Comunicação interna.

---

**7. Retornar periodicamente ao feed**

**Descrição:** O CTHFeedTactics passa a integrar sua rotina de consulta. Rafael retorna ao site para verificar novas ameaças relacionadas à indústria sem precisar manter uma rotina manual em diversas fontes externas.

**Sentimento do usuário:** "Tenho um ponto central para acompanhar o que realmente interessa à nossa empresa."

**Touchpoint:** Plataforma Web → Feed Setorial.

---

### Jornada 5 — Marina: localizar e entrar em contato com outro profissional verificado

**Persona:** Marina, analista N2 de investigação  
**Objetivo:** Encontrar, por meio da plataforma web, um profissional verificado da mesma indústria que possa fornecer contexto adicional sobre uma ameaça observada em diferentes organizações.

**1. Investigar uma ameaça com contexto insuficiente**

**Descrição:** Durante uma investigação, Marina identifica um conjunto de IOCs e comportamentos suspeitos. O CTHFeedTactics mostra que indicadores semelhantes já foram associados a ataques em outras empresas de sua indústria, mas as informações disponíveis não esclarecem completamente o comportamento observado.

**Sentimento do usuário:** "Existe alguma coisa acontecendo no setor, mas ainda está faltando contexto."

**Touchpoint:** Plataforma Web → Busca → Página do IOC/Ataque.

---

**2. Consultar publicações relacionadas**

**Descrição:** Marina utiliza a plataforma para localizar publicações relacionadas aos mesmos IOCs, TTPs ou ofensor e percebe que parte das informações foi compartilhada por usuários verificados.

**Sentimento do usuário:** "Talvez alguém que já tenha visto isso consiga confirmar o padrão."

**Touchpoint:** Plataforma Web → Resultados Relacionados → Publicações.

---

**3. Acessar o diretório de profissionais verificados**

**Descrição:** Marina abre a área de profissionais verificados e aplica filtros para localizar usuários associados à mesma indústria ou área profissional.

A plataforma apresenta somente as informações de contato disponibilizadas pelos próprios usuários conforme suas configurações de privacidade.

**Sentimento do usuário:** "Quero encontrar alguém relevante, não simplesmente uma lista enorme de pessoas."

**Touchpoint:** Plataforma Web → Diretório de Verificados → Filtro por Indústria.

---

**4. Analisar o perfil profissional**

**Descrição:** Marina abre o perfil de um profissional verificado e consulta as informações disponibilizadas, como função, setor de atuação e formas de contato autorizadas.

Ela verifica se aquele profissional parece ter relação com o tipo de ameaça que está investigando.

**Sentimento do usuário:** "Esse perfil parece trabalhar com exatamente o tipo de problema que estou vendo."

**Touchpoint:** Plataforma Web → Perfil de Usuário Verificado.

---

**5. Obter o contato do profissional**

**Descrição:** Como usuária verificada, Marina acessa a forma de contato disponibilizada pelo profissional e decide iniciar uma conversa externamente.

O CTHFeedTactics não oferece chat interno; sua função é facilitar a descoberta do profissional e disponibilizar o contato autorizado.

**Sentimento do usuário:** "A plataforma me levou até a pessoa certa sem tentar virar mais um aplicativo de mensagens."

**Touchpoint:** Plataforma Web → Perfil Verificado → Informação de Contato.

---

**6. Realizar a troca de informações fora da plataforma**

**Descrição:** Marina entra em contato pelo canal disponibilizado, como e-mail ou outra forma autorizada, e troca informações técnicas respeitando as políticas e procedimentos das organizações envolvidas.

**Sentimento do usuário:** "Agora consigo confirmar se o comportamento que estamos vendo também ocorreu em outra organização."

**Touchpoint:** Ferramenta externa de comunicação.

---

**7. Utilizar o novo contexto na investigação**

**Descrição:** Com as informações adicionais obtidas, Marina retorna à investigação interna e compara os novos dados com os eventos observados em seu ambiente.

Quando adequado, ela também pode voltar ao CTHFeedTactics para consultar ou contribuir com informações complementares.

**Sentimento do usuário:** "A informação da comunidade ajudou a transformar um indicador isolado em contexto útil."

**Touchpoint:** Comunicação externa → CTHFeedTactics → Ferramentas internas de investigação.

---

### Jornada 6 — Rafael: configurar o perfil e personalizar o feed por indústria

**Persona:** Rafael, o profissional de TI generalista  
**Objetivo:** Configurar seu perfil no primeiro acesso para que o CTHFeedTactics priorize automaticamente informações relacionadas à indústria de sua organização.

**1. Criar uma conta na plataforma**

**Descrição:** Rafael acessa o CTHFeedTactics pela primeira vez e realiza seu cadastro utilizando as informações necessárias para criar uma conta.

Após concluir o cadastro, ele realiza login e é direcionado para a configuração inicial do perfil.

**Sentimento do usuário:** "Quero começar a usar a plataforma sem precisar configurar dezenas de coisas."

**Touchpoint:** Plataforma Web → Cadastro → Login.

---

**2. Informar sua área profissional**

**Descrição:** Rafael informa sua função ou área de atuação para contextualizar seu perfil profissional dentro da plataforma.

Essa informação também poderá ser utilizada posteriormente caso ele solicite verificação da conta.

**Sentimento do usuário:** "Isso ajuda a plataforma a entender o tipo de informação que pode ser útil para mim."

**Touchpoint:** Plataforma Web → Configuração de Perfil → Informações Profissionais.

---

**3. Selecionar a indústria da organização**

**Descrição:** Rafael seleciona o setor econômico no qual sua empresa atua.

A indústria escolhida passa a ser utilizada como principal referência para organização e priorização do conteúdo apresentado.

**Sentimento do usuário:** "O que realmente importa para mim são ameaças contra empresas parecidas com a nossa."

**Touchpoint:** Plataforma Web → Perfil → Seleção de Indústria.

---

**4. Visualizar o feed personalizado**

**Descrição:** Após salvar as informações, Rafael retorna à página inicial e percebe que o feed passa a priorizar ataques, IOCs, TTPs e ofensores relacionados à indústria selecionada.

**Sentimento do usuário:** "Agora faz sentido. Não estou vendo apenas um monte de notícias de segurança."

**Touchpoint:** Plataforma Web → Página Inicial → Feed Setorial.

---

**5. Alterar a configuração quando necessário**

**Descrição:** Caso mude de empresa ou passe a trabalhar com outro setor, Rafael pode retornar às configurações do perfil e atualizar sua indústria.

**Sentimento do usuário:** "Posso ajustar o perfil se meu contexto profissional mudar."

**Touchpoint:** Plataforma Web → Perfil → Configurações de Indústria.

---

### Jornada 7 — Marina: pesquisar e correlacionar um IOC durante uma investigação

**Persona:** Marina, analista N2 de investigação  
**Objetivo:** Pesquisar um indicador identificado durante uma investigação e descobrir se ele está relacionado a outras ameaças ou ataques registrados na plataforma.

**1. Identificar um IOC suspeito**

**Descrição:** Durante uma investigação interna, Marina identifica um endereço IP, domínio, hash ou URL que ainda não possui contexto suficiente para determinar sua relevância.

**Sentimento do usuário:** "Tenho o indicador, mas ainda não sei o que ele significa."

**Touchpoint:** SIEM / EDR / Ferramentas internas de investigação.

---

**2. Pesquisar o IOC no CTHFeedTactics**

**Descrição:** Marina acessa a barra de busca da plataforma e insere o indicador encontrado.

O sistema retorna as informações relacionadas ao IOC disponíveis na base.

**Sentimento do usuário:** "Quero saber se alguém já viu isso antes."

**Touchpoint:** Plataforma Web → Busca Global → Pesquisa de IOC.

---

**3. Consultar ocorrências relacionadas**

**Descrição:** Marina verifica se o indicador aparece associado a ataques, campanhas, ofensores ou publicações anteriores.

Ela observa especialmente ocorrências registradas contra organizações da mesma indústria.

**Sentimento do usuário:** "Se esse indicador já apareceu em ataques semelhantes, ele se torna muito mais importante."

**Touchpoint:** Plataforma Web → Página do IOC → Conteúdo Relacionado.

---

**4. Consultar informações reputacionais**

**Descrição:** Marina verifica os dados fornecidos pelas integrações com feeds reputacionais disponíveis na página do IOC.

Essas informações complementam o contexto apresentado pela comunidade.

**Sentimento do usuário:** "Agora tenho mais de uma fonte apoiando minha análise."

**Touchpoint:** Plataforma Web → Página do IOC → Reputação.

---

**5. Retornar à investigação**

**Descrição:** Com o novo contexto, Marina retorna às ferramentas internas e compara as informações encontradas com os eventos registrados no ambiente da organização.

**Sentimento do usuário:** "Agora consigo decidir se esse indicador realmente merece aprofundamento."

**Touchpoint:** CTHFeedTactics → Ferramentas internas de investigação.

---

### Jornada 8 — Enzo: entender uma TTP observada em um alerta

**Persona:** Enzo, o analista N1 apagando incêndio  
**Objetivo:** Consultar informações sobre uma técnica ou comportamento identificado durante a triagem de um alerta para entender se ele está associado a ameaças relevantes ao setor.

**1. Receber um alerta com comportamento suspeito**

**Descrição:** Durante a triagem, Enzo encontra um alerta associado a uma técnica ou comportamento que não reconhece completamente.

**Sentimento do usuário:** "Eu sei que isso pode ser suspeito, mas preciso de contexto rapidamente."

**Touchpoint:** SIEM → Alerta de Segurança.

---

**2. Pesquisar a técnica na plataforma**

**Descrição:** Enzo acessa o CTHFeedTactics e pesquisa pela técnica ou TTP relacionada ao comportamento observado.

**Sentimento do usuário:** "Quero saber onde isso já apareceu."

**Touchpoint:** Plataforma Web → Busca → TTP.

---

**3. Consultar ameaças associadas**

**Descrição:** A plataforma apresenta ataques, ofensores e publicações relacionadas à técnica pesquisada.

Enzo verifica se existem ocorrências recentes contra organizações da mesma indústria.

**Sentimento do usuário:** "Se isso estiver sendo usado contra empresas do meu setor, o alerta muda de prioridade."

**Touchpoint:** Plataforma Web → Página da TTP → Ameaças Relacionadas.

---

**4. Consultar os IOCs vinculados**

**Descrição:** Enzo verifica se as publicações relacionadas possuem IOCs que possam ser comparados com o alerta recebido.

**Sentimento do usuário:** "Talvez exista algum indicador que confirme o que estou vendo."

**Touchpoint:** Plataforma Web → TTP → Publicações → IOCs.

---

**5. Decidir sobre o escalonamento**

**Descrição:** Com o contexto adicional, Enzo retorna ao processo de triagem e decide se o alerta deve ser escalado para investigação mais aprofundada.

**Sentimento do usuário:** "Agora tenho uma justificativa melhor para escalar ou encerrar."

**Touchpoint:** CTHFeedTactics → SIEM / Sistema de Tickets.

---

### Jornada 9 — Paulo: analisar um ofensor ativo contra sua indústria

**Persona:** Paulo, o engenheiro CSIRT que quer dado integrável  
**Objetivo:** Investigar um grupo ou ofensor mencionado em uma ameaça para compreender sua atividade recente contra organizações do mesmo setor.

**1. Identificar um ofensor relevante**

**Descrição:** Paulo encontra no feed uma publicação relacionada a um grupo ou agente de ameaça que recentemente atacou uma organização de sua indústria.

**Sentimento do usuário:** "Quero saber se isso é um caso isolado ou parte de uma campanha maior."

**Touchpoint:** Plataforma Web → Feed Setorial → Publicação.

---

**2. Acessar a página do ofensor**

**Descrição:** Paulo seleciona o nome do ofensor e acessa uma página que reúne as informações relacionadas disponíveis na plataforma.

**Sentimento do usuário:** "Quero reunir o histórico antes de começar a procurar em fontes separadas."

**Touchpoint:** Plataforma Web → Página do Ofensor.

---

**3. Consultar ataques associados**

**Descrição:** Paulo analisa as publicações e ataques relacionados ao ofensor, observando principalmente datas, setores afetados e contexto disponível.

**Sentimento do usuário:** "Preciso entender o padrão de atuação desse grupo."

**Touchpoint:** Plataforma Web → Ofensor → Ataques Relacionados.

---

**4. Examinar IOCs e TTPs utilizados**

**Descrição:** Paulo consulta os indicadores e metodologias associados às atividades registradas.

**Sentimento do usuário:** "Essas informações podem ser comparadas diretamente com o nosso ambiente."

**Touchpoint:** Plataforma Web → Ofensor → IOCs / TTPs.

---

**5. Utilizar as informações internamente**

**Descrição:** Paulo utiliza o contexto obtido como referência para revisar investigações, cobertura de detecção ou outras atividades internas da organização.

**Sentimento do usuário:** "Agora tenho uma visão mais clara do que procurar."

**Touchpoint:** CTHFeedTactics → Ferramentas internas de Threat Intelligence / CSIRT.

---

### Jornada 10 — Rafael: receber um alerta sobre uma nova ameaça setorial

**Persona:** Rafael, o profissional de TI generalista  
**Objetivo:** Ser informado quando uma ameaça relevante à indústria de sua organização for disponibilizada na plataforma.

**1. Configurar o recebimento de alertas**

**Descrição:** Rafael acessa suas preferências e habilita notificações relacionadas à indústria cadastrada em seu perfil.

**Sentimento do usuário:** "Não quero precisar abrir a plataforma o tempo todo para descobrir se aconteceu alguma coisa."

**Touchpoint:** Plataforma Web → Perfil → Preferências de Notificação.

---

**2. Receber uma notificação**

**Descrição:** Quando uma nova ameaça relevante é registrada, Rafael recebe uma notificação pelos canais disponibilizados pela plataforma, como e-mail.

**Sentimento do usuário:** "Isso parece relevante para nossa empresa."

**Touchpoint:** CTHFeedTactics → E-mail / Notificação.

---

**3. Acessar a publicação**

**Descrição:** Rafael utiliza o link recebido para abrir diretamente a publicação relacionada à ameaça.

**Sentimento do usuário:** "Quero entender rapidamente o que aconteceu."

**Touchpoint:** E-mail → Plataforma Web → Publicação.

---

**4. Consultar os indicadores disponíveis**

**Descrição:** Rafael verifica os IOCs, TTPs e informações de contexto associadas à ameaça.

**Sentimento do usuário:** "Agora sei exatamente o que preciso verificar no nosso ambiente."

**Touchpoint:** Plataforma Web → Publicação → IOCs / TTPs.

---

**5. Compartilhar internamente quando necessário**

**Descrição:** Caso considere a ameaça relevante, Rafael encaminha a informação para os responsáveis internos pela segurança.

**Sentimento do usuário:** "É melhor a equipe saber disso antes que apareça alguma coisa."

**Touchpoint:** CTHFeedTactics → Comunicação interna da organização.

---

### Jornada 11 — Marina: salvar ameaças para uma investigação posterior

**Persona:** Marina, analista N2 de investigação  
**Objetivo:** Salvar publicações relevantes encontradas durante uma investigação para consultá-las posteriormente sem precisar repetir a pesquisa.

**1. Encontrar uma publicação relevante**

**Descrição:** Durante uma pesquisa, Marina encontra uma ameaça que possui informações potencialmente relacionadas ao caso que está investigando.

**Sentimento do usuário:** "Isso pode ser útil depois, mas ainda preciso verificar outras coisas."

**Touchpoint:** Plataforma Web → Busca → Publicação.

---

**2. Salvar a publicação**

**Descrição:** Marina utiliza a opção de salvar a publicação em sua conta.

**Sentimento do usuário:** "Assim não preciso tentar encontrar isso novamente."

**Touchpoint:** Plataforma Web → Publicação → Salvar.

---

**3. Continuar a investigação**

**Descrição:** Marina continua pesquisando outros IOCs, TTPs e ofensores sem perder a referência encontrada anteriormente.

**Sentimento do usuário:** "Posso continuar explorando sem abrir vinte abas."

**Touchpoint:** Plataforma Web → Busca / Feed.

---

**4. Acessar os itens salvos**

**Descrição:** Posteriormente, Marina abre a área de conteúdos salvos e encontra a publicação armazenada.

**Sentimento do usuário:** "Aqui está exatamente o que eu precisava recuperar."

**Touchpoint:** Plataforma Web → Perfil → Itens Salvos.

---

**5. Utilizar a referência na investigação**

**Descrição:** Marina compara as informações da publicação com os dados coletados durante sua investigação.

**Sentimento do usuário:** "Agora consigo juntar as diferentes partes da investigação."

**Touchpoint:** CTHFeedTactics → Ferramentas internas de investigação.

---

### Jornada 12 — Edgar: solicitar a verificação de sua conta

**Persona:** Edgar, o gestor de SOC responsável pelo risco  
**Objetivo:** Solicitar a verificação de sua conta para obter acesso às funcionalidades reservadas aos profissionais verificados.

**1. Utilizar a plataforma como usuário comum**

**Descrição:** Edgar começa utilizando o CTHFeedTactics para consultar ameaças e inteligência relacionada à sua indústria.

Ele percebe que determinadas funcionalidades de contribuição e networking exigem uma conta verificada.

**Sentimento do usuário:** "Se queremos contribuir com informações, precisamos validar nossa identidade profissional."

**Touchpoint:** Plataforma Web → Perfil / Recursos para Verificados.

---

**2. Iniciar a solicitação de verificação**

**Descrição:** Edgar acessa sua conta e seleciona a opção de solicitar verificação.

**Sentimento do usuário:** "Quero entender exatamente o que a plataforma precisa para verificar meu perfil."

**Touchpoint:** Plataforma Web → Perfil → Solicitar Verificação.

---

**3. Fornecer as informações necessárias**

**Descrição:** Edgar envia as informações profissionais solicitadas pelo processo de verificação, seguindo os critérios definidos pela plataforma.

**Sentimento do usuário:** "São informações profissionais, então quero saber como elas serão utilizadas."

**Touchpoint:** Plataforma Web → Formulário de Verificação.

---

**4. Acompanhar a solicitação**

**Descrição:** Após enviar os dados, Edgar pode visualizar o status do processo enquanto aguarda a análise.

**Sentimento do usuário:** "Pelo menos sei que a solicitação está sendo analisada."

**Touchpoint:** Plataforma Web → Perfil → Status da Verificação.

---

**5. Obter a conta verificada**

**Descrição:** Quando a solicitação é aprovada, a conta passa a apresentar o status de usuário verificado e libera as funcionalidades correspondentes.

**Sentimento do usuário:** "Agora podemos participar de forma mais ativa da comunidade."

**Touchpoint:** Plataforma Web → Perfil Verificado.

---

### Jornada 13 — Marina: controlar a privacidade de suas informações profissionais

**Persona:** Marina, analista N2 de investigação  
**Objetivo:** Definir quais informações de contato outros usuários verificados poderão visualizar em seu perfil.

**1. Acessar as configurações de privacidade**

**Descrição:** Após obter a verificação da conta, Marina acessa as configurações relacionadas às informações profissionais disponíveis em seu perfil.

**Sentimento do usuário:** "Quero participar da comunidade sem expor mais informações do que o necessário."

**Touchpoint:** Plataforma Web → Perfil → Privacidade.

---

**2. Revisar as informações disponíveis**

**Descrição:** Marina verifica quais dados profissionais podem ser apresentados a outros usuários verificados.

**Sentimento do usuário:** "Preciso saber exatamente o que outras pessoas conseguem visualizar."

**Touchpoint:** Plataforma Web → Privacidade → Informações de Contato.

---

**3. Escolher quais dados compartilhar**

**Descrição:** Marina seleciona quais formas de contato deseja disponibilizar aos demais profissionais verificados.

**Sentimento do usuário:** "Quero ser encontrada, mas ainda manter controle sobre meus dados."

**Touchpoint:** Plataforma Web → Configurações de Privacidade.

---

**4. Salvar as preferências**

**Descrição:** A plataforma registra as configurações escolhidas e passa a aplicá-las ao perfil da usuária.

**Sentimento do usuário:** "Agora sei que somente as informações que autorizei estarão disponíveis."

**Touchpoint:** Plataforma Web → Perfil → Salvar Configurações.

---

**5. Alterar as preferências futuramente**

**Descrição:** Marina pode retornar às configurações sempre que quiser modificar ou remover uma informação de contato.

**Sentimento do usuário:** "Posso mudar de ideia sem perder o controle do perfil."

**Touchpoint:** Plataforma Web → Perfil → Privacidade.

---

### Jornada 14 — Edgar: publicar inteligência com classificação de compartilhamento

**Persona:** Edgar, o gestor de SOC responsável pelo risco  
**Objetivo:** Publicar informações sobre uma ameaça identificada pela organização indicando claramente as condições de compartilhamento do conteúdo.

**1. Identificar informações compartilháveis**

**Descrição:** Após um incidente, Edgar e sua equipe separam IOCs e informações técnicas que podem ser compartilhados sem expor dados sensíveis da organização.

**Sentimento do usuário:** "Precisamos contribuir, mas sem divulgar informações que deveriam permanecer internas."

**Touchpoint:** Processo interno da organização.

---

**2. Criar uma nova publicação**

**Descrição:** Como usuário verificado, Edgar acessa a área de publicação e começa a registrar as informações disponíveis.

**Sentimento do usuário:** "Quero que o conteúdo seja útil para outras organizações."

**Touchpoint:** Plataforma Web → Nova Publicação.

---

**3. Adicionar contexto, IOCs e TTPs**

**Descrição:** Edgar informa os indicadores, metodologias observadas e o contexto necessário para compreender a ameaça.

**Sentimento do usuário:** "Um IOC sozinho não explica praticamente nada."

**Touchpoint:** Plataforma Web → Formulário de Publicação.

---

**4. Definir as condições de compartilhamento**

**Descrição:** Antes de concluir a publicação, Edgar seleciona a classificação de compartilhamento aplicável às informações disponibilizadas.

**Sentimento do usuário:** "As pessoas precisam saber claramente até onde essa informação pode circular."

**Touchpoint:** Plataforma Web → Nova Publicação → Classificação de Compartilhamento.

---

**5. Revisar e publicar**

**Descrição:** Edgar revisa o conteúdo e confirma a publicação após verificar se não existem informações que deveriam permanecer restritas.

**Sentimento do usuário:** "Agora posso compartilhar com mais confiança."

**Touchpoint:** Plataforma Web → Revisão → Publicar.

---

### Jornada 15 — Paulo: exportar inteligência para utilização em ferramentas externas

**Persona:** Paulo, o engenheiro CSIRT que quer dado integrável  
**Objetivo:** Exportar informações estruturadas da plataforma para utilizá-las em ferramentas de Threat Intelligence da organização.

**1. Encontrar um conjunto relevante de indicadores**

**Descrição:** Paulo utiliza filtros e buscas para localizar IOCs relacionados à indústria e às ameaças que sua equipe acompanha.

**Sentimento do usuário:** "Esses indicadores são relevantes, mas não quero copiá-los um por um."

**Touchpoint:** Plataforma Web → Feed / Busca → Filtros.

---

**2. Selecionar os dados necessários**

**Descrição:** Paulo identifica quais informações deseja utilizar em suas ferramentas internas.

**Sentimento do usuário:** "Quero levar apenas o que realmente interessa ao nosso ambiente."

**Touchpoint:** Plataforma Web → Resultados → Seleção de Dados.

---

**3. Escolher um formato de exportação**

**Descrição:** Quando disponível, Paulo escolhe um formato estruturado suportado pela plataforma, como STIX.

**Sentimento do usuário:** "Se os dados já vêm estruturados, economizo bastante trabalho manual."

**Touchpoint:** Plataforma Web → Exportar → Formato Estruturado.

---

**4. Importar os dados na ferramenta interna**

**Descrição:** Paulo utiliza o arquivo ou conjunto de dados exportado para alimentar uma ferramenta de Threat Intelligence utilizada pela organização.

**Sentimento do usuário:** "Agora essa inteligência pode entrar no nosso fluxo normal de trabalho."

**Touchpoint:** CTHFeedTactics → TIP / MISP / OpenCTI.

---

**5. Consultar o contexto no site quando necessário**

**Descrição:** Caso precise de informações adicionais, Paulo retorna à publicação original no CTHFeedTactics para consultar contexto que não esteja presente diretamente no indicador exportado.

**Sentimento do usuário:** "Os dados estruturados ajudam na automação, mas o contexto continua sendo importante."

**Touchpoint:** Ferramenta interna → CTHFeedTactics → Publicação.

---

### Jornada 16 — Enzo: filtrar o feed para encontrar ameaças recentes

**Persona:** Enzo, o analista N1 apagando incêndio  
**Objetivo:** Utilizar filtros para localizar rapidamente ameaças recentes relacionadas ao contexto de um alerta em análise.

**1. Acessar o feed setorial**

**Descrição:** Durante a triagem de um alerta, Enzo abre o CTHFeedTactics para verificar se existe alguma campanha recente relacionada à sua indústria.

**Sentimento do usuário:** "Não tenho tempo para percorrer dezenas de publicações."

**Touchpoint:** Plataforma Web → Feed Setorial.

---

**2. Aplicar filtro por período**

**Descrição:** Enzo limita os resultados às publicações mais recentes para verificar ameaças ativas ou registradas recentemente.

**Sentimento do usuário:** "O que aconteceu nos últimos dias é muito mais relevante para esse alerta."

**Touchpoint:** Plataforma Web → Feed → Filtro por Período.

---

**3. Aplicar filtros adicionais**

**Descrição:** Quando necessário, Enzo combina filtros relacionados à indústria, tipo de IOC ou outros critérios disponíveis.

**Sentimento do usuário:** "Quanto menos ruído eu tiver, mais rápido consigo tomar uma decisão."

**Touchpoint:** Plataforma Web → Feed → Filtros.

---

**4. Abrir uma publicação relevante**

**Descrição:** Entre os resultados reduzidos, Enzo identifica uma ameaça compatível com o comportamento observado no alerta.

**Sentimento do usuário:** "Isso parece muito parecido com o que estou vendo."

**Touchpoint:** Plataforma Web → Resultados Filtrados → Publicação.

---

**5. Utilizar o contexto na triagem**

**Descrição:** Enzo utiliza as informações encontradas para auxiliar sua decisão dentro do processo interno da organização.

**Sentimento do usuário:** "Consegui encontrar a informação sem perder tempo navegando pelo feed inteiro."

**Touchpoint:** CTHFeedTactics → SIEM / Sistema de Tickets.

---

### Jornada 17 — Marina: acompanhar novas informações sobre uma ameaça já investigada

**Persona:** Marina, analista N2 de investigação  
**Objetivo:** Retornar a uma ameaça pesquisada anteriormente para verificar se novos indicadores ou informações foram adicionados.

**1. Recuperar uma publicação anteriormente consultada**

**Descrição:** Marina acessa uma ameaça que havia sido utilizada em uma investigação anterior.

**Sentimento do usuário:** "Quero saber se apareceu alguma coisa nova desde a última vez."

**Touchpoint:** Plataforma Web → Histórico / Itens Salvos → Publicação.

---

**2. Verificar a atualização das informações**

**Descrição:** Marina observa se novos IOCs, TTPs ou informações de contexto foram adicionados à publicação ou relacionados à ameaça.

**Sentimento do usuário:** "Uma campanha pode mudar rapidamente; os indicadores antigos não contam toda a história."

**Touchpoint:** Plataforma Web → Publicação → Informações Atualizadas.

---

**3. Consultar novas publicações relacionadas**

**Descrição:** Marina verifica outros conteúdos que passaram a ser associados à mesma ameaça ou ofensor.

**Sentimento do usuário:** "Talvez outras organizações tenham identificado novas partes da campanha."

**Touchpoint:** Plataforma Web → Publicação → Conteúdo Relacionado.

---

**4. Comparar com a investigação anterior**

**Descrição:** Marina compara as novas informações com os dados registrados anteriormente por sua equipe.

**Sentimento do usuário:** "Agora consigo verificar se alguma coisa mudou desde nossa última análise."

**Touchpoint:** CTHFeedTactics → Ferramentas internas.

---

**5. Atualizar o contexto interno**

**Descrição:** Quando necessário, Marina registra internamente os novos indicadores ou informações consideradas relevantes.

**Sentimento do usuário:** "Nossa investigação continua atualizada sem precisar começar tudo de novo."

**Touchpoint:** Ferramentas internas de investigação.

---

### Jornada 18 — Edgar: obter uma visão executiva das ameaças do setor

**Persona:** Edgar, o gestor de SOC responsável pelo risco  
**Objetivo:** Consultar uma visão consolidada das ameaças relacionadas à sua indústria para apoiar discussões de prioridade e risco com a gestão.

**1. Acessar a visão consolidada da indústria**

**Descrição:** Edgar entra na plataforma e acessa uma área que reúne informações agregadas sobre ameaças relacionadas ao seu setor.

**Sentimento do usuário:** "Não preciso de cada IOC individual para conversar com a diretoria."

**Touchpoint:** Plataforma Web → Dashboard Setorial.

---

**2. Consultar ameaças recentes**

**Descrição:** Edgar observa quais ameaças e ofensores aparecem com maior frequência no período selecionado.

**Sentimento do usuário:** "Quero entender quais problemas estão realmente se repetindo no setor."

**Touchpoint:** Plataforma Web → Dashboard → Ameaças Recentes.

---

**3. Analisar tendências**

**Descrição:** Edgar compara informações agregadas para identificar aumento ou redução de determinadas atividades relacionadas à indústria.

**Sentimento do usuário:** "Isso ajuda a distinguir um incidente isolado de uma tendência."

**Touchpoint:** Plataforma Web → Dashboard → Tendências.

---

**4. Acessar detalhes quando necessário**

**Descrição:** Quando uma ameaça chama atenção, Edgar abre as publicações relacionadas para consultar informações técnicas adicionais.

**Sentimento do usuário:** "Se alguém perguntar de onde esse risco está vindo, preciso conseguir aprofundar."

**Touchpoint:** Dashboard → Publicação → Detalhes.

---

**5. Utilizar as informações em discussões internas**

**Descrição:** Edgar utiliza a visão consolidada como apoio para conversas sobre prioridades de segurança e acompanhamento do cenário de ameaças.

**Sentimento do usuário:** "Agora consigo apresentar o cenário de forma mais clara sem transformar a reunião em uma análise técnica de IOC."

**Touchpoint:** CTHFeedTactics → Processo interno de gestão.

---

### Jornada 19 — Paulo: contribuir com novos IOCs para uma publicação existente

**Persona:** Paulo, o engenheiro CSIRT que quer dado integrável  
**Objetivo:** Adicionar informações complementares sobre uma ameaça que já possui registros na plataforma, evitando criar conteúdo duplicado.

**1. Pesquisar a ameaça**

**Descrição:** Após identificar novos indicadores durante uma investigação, Paulo pesquisa a campanha ou ofensor relacionado no CTHFeedTactics.

**Sentimento do usuário:** "Antes de criar alguma coisa nova, quero saber se isso já está registrado."

**Touchpoint:** Plataforma Web → Busca.

---

**2. Encontrar uma publicação existente**

**Descrição:** Paulo identifica uma publicação que descreve a mesma ameaça observada por sua equipe.

**Sentimento do usuário:** "Isso parece ser exatamente a mesma atividade."

**Touchpoint:** Plataforma Web → Resultados → Publicação.

---

**3. Comparar os indicadores**

**Descrição:** Paulo compara os IOCs já registrados com aqueles encontrados pela organização e percebe que possui informações adicionais.

**Sentimento do usuário:** "Temos indicadores que ainda não aparecem aqui."

**Touchpoint:** Plataforma Web → Publicação → IOCs.

---

**4. Adicionar informações complementares**

**Descrição:** Como usuário verificado, Paulo utiliza o fluxo disponível para contribuir com novos indicadores ou contexto relacionado à ameaça.

**Sentimento do usuário:** "É melhor complementar o que já existe do que fragmentar a mesma campanha em várias publicações."

**Touchpoint:** Plataforma Web → Publicação → Contribuir.

---

**5. Revisar a contribuição**

**Descrição:** Paulo verifica os dados adicionados e confirma que não incluiu informações internas ou sensíveis.

**Sentimento do usuário:** "Quero contribuir sem expor nossa organização."

**Touchpoint:** Plataforma Web → Revisão da Contribuição.

---

**6. Disponibilizar as novas informações**

**Descrição:** Após a conclusão do processo aplicável, os novos dados passam a complementar a inteligência relacionada à ameaça.

**Sentimento do usuário:** "Agora outras equipes conseguem enxergar uma parte maior dessa campanha."

**Touchpoint:** Plataforma Web → Publicação Atualizada.

---

### Jornada 20 — Marina: reportar uma informação incorreta ou suspeita

**Persona:** Marina, analista N2 de investigação  
**Objetivo:** Sinalizar uma publicação ou indicador potencialmente incorreto para preservar a confiabilidade das informações disponíveis na plataforma.

**1. Encontrar uma inconsistência**

**Descrição:** Durante uma investigação, Marina percebe que determinado IOC ou informação apresentada em uma publicação parece incompatível com outras evidências disponíveis.

**Sentimento do usuário:** "Isso parece errado e alguém pode acabar utilizando essa informação."

**Touchpoint:** Plataforma Web → Publicação / Página do IOC.

---

**2. Revisar o contexto disponível**

**Descrição:** Antes de realizar qualquer ação, Marina verifica a publicação completa e as informações reputacionais disponíveis para confirmar que não interpretou o dado de forma incorreta.

**Sentimento do usuário:** "Quero ter certeza antes de sinalizar alguma coisa."

**Touchpoint:** Plataforma Web → Publicação → IOC → Reputação.

---

**3. Utilizar a opção de reportar**

**Descrição:** Marina seleciona a opção de reportar ou sinalizar o conteúdo e informa brevemente o motivo pelo qual considera a informação problemática.

**Sentimento do usuário:** "A plataforma precisa saber que esse dado merece revisão."

**Touchpoint:** Plataforma Web → Publicação → Reportar.

---

**4. Enviar o reporte para análise**

**Descrição:** O reporte é encaminhado ao processo de moderação ou curadoria da plataforma para avaliação.

A publicação não é automaticamente considerada incorreta apenas porque recebeu um reporte.

**Sentimento do usuário:** "Agora alguém pode revisar isso antes que o problema se espalhe."

**Touchpoint:** Plataforma Web → Reporte → Moderação.

---

**5. Continuar a investigação com cautela**

**Descrição:** Enquanto a informação é analisada, Marina evita utilizá-la como única referência e continua buscando contexto em outras informações disponíveis.

**Sentimento do usuário:** "Até isso ser esclarecido, é melhor tratar esse indicador com cautela."

**Touchpoint:** CTHFeedTactics → Ferramentas internas de investigação.

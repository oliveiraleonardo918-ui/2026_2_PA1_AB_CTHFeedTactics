# 2026_2_PA1_CTHFeedTactics
Trabalho para disciplina de Projeto aplicado de Dev Software

# Membros do Grupo
Leonardo Oliveira / 2523546

Lucas Silva / 2422728

João Gabriel de Holanda / 2522687



# Documento do Projeto



https://docs.google.com/document/d/1WfoTo3V6UwHy_UaceGcP7m1p5zpbO11dca_fpcouHd0/edit?usp=drivesdk

<h1> 1. Resumo do Produto — É, Não É, Faz, Não Faz </h1>

<h2 >É: </h2>

 • Plataforma de informações direcionada à prevenção de ataques cibernéticos.
 
 • Direciona usuários para relatos, feeds e conexão com indicadores de comprometimento (IOCs).
 
 • Plataforma com divisão por indústria e os ofensores direcionados a cada uma.
 
 • Plataforma unificada de informações sobre ciberataques.


<h2> Não É: </h2>

 • Não é uma plataforma genérica de notícias e alertas de segurança.
 
 • Não é fórum de troca de informações.
 
 • Não é vendor-based (não é patrocinada ou direcionada por fabricantes).


<h2> Faz: </h2>

 • Permite que usuários verificados enviem IOCs e metodologias de ataque.
 
 • Permite que usuários encontrem seu nicho e vejam o que está sendo usado contra empresas similares.
 
 • Integração com APIs de feeds reputacionais para checagem dos IOCs fornecidos.
 
 • Permite que usuários verificados acessem informações de contato de outros verificados.


<h2> Não Faz: </h2>

 • Não tem chat dentro da plataforma.

 • Não faz análise dos ataques.
 
 • Não monta recomendações nativamente.




<h1> 2. Personas </h1>

<h2> 2.1 Usuário Comum </h2>
Profissional de TI ou segurança da informação que busca se manter informado sobre ameaças ao seu setor. Tem acesso somente à visualização de alertas, feeds e IOCs publicados. Não publica conteúdo na plataforma.

<h2> 2.2 Usuário Verificado </h2>
Analista de segurança, incident responder ou CISO de uma empresa que passou pelo processo de verificação da plataforma. Além de consumir informações, pode publicar IOCs, metodologias de ataque e tem acesso às informações de contato de outros verificados da sua indústria.





<h1> 3. Mapa de Empatia </h1>


<img width="550" height="350" alt="mapa-da-empatia-exemplo-para-preencher" src="https://github.com/user-attachments/assets/d71716e6-4c8d-49ad-9b4f-3c872efe24f6" />

[CTHFeedTatics_Mapa_Empatia.docx](https://github.com/user-attachments/files/31238880/CTHFeedTatics_Mapa_Empatia.docx)


<h2> — Usuário Comum </h2>

<h3> O QUE PENSA E SENTE? </h3>

▸ Preocupação constante com a segurança da empresa — sente que pode ser o próximo alvo.

▸ Ansiedade por não saber quais ameaças estão ativamente direcionadas à sua indústria.

▸ Frustração com a fragmentação das informações — precisa consultar dezenas de fontes diferentes.

▸ Sensação de estar 'no escuro' enquanto ataques acontecem em empresas similares.

▸ Desejo de ter uma fonte única, confiável e atualizada de inteligência de ameaças.

▸ Receio de que a empresa não esteja preparada para responder a um ataque sofisticado.


<h3> O QUE ESCUTA? </h3>

▸ Colegas de trabalho comentando sobre incidentes recentes de cibersegurança.

▸ Gestores e diretoria cobrando postura de segurança mais robusta.

▸ Notícias sobre vazamentos de dados e ransomware em grandes portais de TI.

▸ Que empresas do mesmo setor sofreram ataques com TTPs semelhantes.

▸ Recomendações de influenciadores e especialistas de cybersecurity em redes sociais e podcasts.

▸ Que a colaboração e o compartilhamento de IOCs entre empresas é fundamental para defesa coletiva.


<h3> O QUE VÊ? </h3>

▸ Notícias fragmentadas e genéricas sobre ciberataques em portais de notícias.

▸ Concorrentes e empresas do setor sendo atacados publicamente.

▸ Vendedores de soluções de segurança fazendo marketing agressivo sem contexto real.

▸ Relatórios de threat intelligence pagos e inacessíveis para empresas menores.

▸ Feeds de IOCs dispersos em múltiplas plataformas (Twitter/X, blogs, listas de e-mail).

▸ Dashboards internos de segurança sem contexto externo do cenário de ameaças.


<h3> O QUE FALA E FAZ? </h3>

▸ Busca informações sobre ameaças em múltiplas fontes diariamente de forma manual.

▸ Compartilha alertas relevantes internamente com a equipe de TI/Segurança.

▸ Participa de grupos informais de segurança (Telegram, Discord, WhatsApp).

▸ Reclama da falta de informações acessíveis e centralizadas sobre ataques ao seu setor.

▸ Tenta implementar medidas preventivas com base em informações limitadas e defasadas.

▸ Assina newsletters de segurança e acompanha blogs especializados.


<h3> DORES </h3>

▸ Ansiedade constante diante da possibilidade de sofrer um ciberataque sem aviso prévio.

▸ Escassez de informações consolidadas e filtradas por indústria/setor.

▸ Tempo excessivo gasto buscando informações em fontes dispersas e não curadas.

▸ Dificuldade em diferenciar alertas relevantes de ruído informacional.

▸ Falta de contexto — sabe que existem ameaças, mas não entende quais são direcionadas ao seu setor.

▸ Ausência de um canal confiável que agregue feeds, IOCs e alertas em um só lugar.


<h3> GANHOS </h3>

▸ Acesso centralizado a informações de ataques cibernéticos filtradas pela sua indústria.

▸ Feed de alertas atualizado com o intuito de informar e prevenir ataques futuros.

▸ Economia de tempo ao não precisar consultar dezenas de fontes diariamente.

▸ Maior confiança na postura de segurança da empresa com informações contextualizadas.

▸ Capacidade de antecipar ameaças que já atingiram empresas similares no setor.

▸ Acesso gratuito ou acessível a inteligência de ameaças que antes era restrita a relatórios pagos.




<h2> — Usuário Verificado </h2>

<h3> O QUE PENSA E SENTE? </h3>

▸ Frustração por não ter um canal adequado para compartilhar IOCs e TTPs de ataques sofridos.

▸ Sentimento de isolamento — sabe que outras empresas passam pelo mesmo, mas não há comunicação.

▸ Responsabilidade de proteger sua organização e desejo de contribuir para a defesa coletiva do setor.

▸ Preocupação com a falta de colaboração entre empresas de pequeno e médio porte.

▸ Aspiração de fazer parte de uma comunidade ativa de inteligência de ameaças da sua indústria.

▸ Receio de compartilhar informações sensíveis sem garantia de verificação e segurança.


<h3> O QUE ESCUTA? </h3>

▸ Que compartilhar informações sobre ataques é crucial para a defesa coletiva.

▸ Pressão interna para melhorar a detecção e a resposta a incidentes.

▸ Relatos informais de ataques em conferências, meetups e eventos de segurança.

▸ Que faltam canais seguros e verificados para troca de informações entre empresas.

▸ Recomendações para participar de ISACs, mas encontra barreiras de entrada e custos altos.

▸ Feedbacks da comunidade sobre a importância de feeds setoriais de threat intelligence.


<h3> O QUE VÊ? </h3>

▸ Ataques sendo reportados tardiamente pela mídia, sem IOCs ou detalhes técnicos.

▸ Falta de plataformas colaborativas não-vendor-based para troca de inteligência de ameaças.

▸ Empresas do mesmo setor sendo atingidas por TTPs similares de forma recorrente.

▸ Relatórios de threat intel que não refletem a realidade local ou setorial.

▸ Comunidades fechadas e exclusivas que não atendem empresas menores.

▸ Plataformas que exigem investimento alto ou são voltadas apenas para grandes corporações.


<h3> O QUE FALA E FAZ? </h3>

▸ Analisa IOCs e TTPs dos ataques que investiga durante a rotina de resposta a incidentes.

▸ Busca compartilhar descobertas com a comunidade de segurança, mas encontra poucos canais.

▸ Participa de conferências e eventos de segurança para networking e troca de experiências.

▸ Consulta feeds de reputação e plataformas de threat intel para validar indicadores.

▸ Tenta contato direto com profissionais de outras empresas do setor para trocar informações.

▸ Documenta ataques internamente, mas raramente publica externamente por falta de canal adequado.


<h3> DORES </h3>

▸ Falta de um hub centralizado para publicar e consumir informações de ataques cibernéticos.

▸ Falta de comunicação e colaboração entre empresas de pequeno e médio porte atacadas.

▸ Dificuldade em validar IOCs recebidos informalmente sem integração com feeds reputacionais.

▸ Ausência de uma plataforma segura para divulgar ataques sofridos sem exposição indesejada.

▸ Barreiras de entrada em comunidades existentes de compartilhamento de inteligência (ISACs, CERTs).

▸ Sensação de que informações valiosas se perdem porque não existe onde publicá-las.


<h3> GANHO S</h3>

▸ Plataforma para divulgar e receber IOCs verificados com validação via APIs reputacionais.

▸ Rede de contatos com profissionais verificados da mesma indústria.

▸ Contribuição ativa para a defesa coletiva do setor contra ameaças comuns.

▸ Acesso a informações de ataques específicos que atingiram empresas similares.

▸ Validação automática de IOCs submetidos via integração com feeds reputacionais.

▸ Plataforma segmentada por indústria que garante relevância das informações consumidas.




<h1> 4. Questionário de Empatia </h1>
  
  

<h2> — Usuário Comum </h2>
Roteiro de entrevista semiestruturada para validação das hipóteses do mapa de empatia do usuário comum. Aplicar individualmente com profissionais de TI e segurança de diferentes portes de empresa.

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

7. Se existisse uma plataforma que centralizasse alertas e IOCs filtrados por indústria, qual seria a primeira coisa que você buscaria nela?
Objetivo: Identificar a funcionalidade de maior valor percebido.

8. Você confiaria em informações de ataques compartilhadas por outras empresas do mesmo setor em uma plataforma verificada?
Objetivo: Validar a premissa de confiança em comunidade verificada.

9. O que te impediria de usar uma plataforma como essa? (ex: custo, complexidade, desconfiança, falta de tempo)
Objetivo: Mapear barreiras de adoção e objeções.

10. Como você preferiria receber os alertas da plataforma? (ex: feed no site, e-mail, integração com ferramentas, app mobile)
Objetivo: Definir canais de entrega de valor.

https://docs.google.com/forms/d/e/1FAIpQLSe5T4fkVSonfDt6bbIMu4VQ9eEKwRKl8O6E8LApkbVbHjDVWw/viewform?usp=publish-editor


<h2> — Usuário Verificado </h2>
Roteiro de entrevista semiestruturada para validação das hipóteses do mapa de empatia do usuário verificado. Aplicar com analistas de segurança, incident responders e CISOs que já lidam com resposta a incidentes.

1. Quando sua empresa sofre um ciberataque, vocês compartilham os IOCs e TTPs com outras organizações? Se sim, como? Se não, por quê?
Objetivo: Validar a dor de falta de canal de compartilhamento e entender barreiras.

2. Você sente que existe isolamento entre empresas do mesmo setor quando se trata de resposta a ameaças?
Objetivo: Medir a percepção de isolamento e necessidade de comunidade.

3. Quais barreiras você encontra para trocar informações de ameaças com outras empresas? (ex: confiança, jurídico, falta de canal, tempo)
Objetivo: Identificar bloqueios concretos ao compartilhamento de inteligência.

4. Você já tentou participar de algum ISAC, CERT ou comunidade de compartilhamento de threat intel? Como foi a experiência?
Objetivo: Mapear experiências anteriores e gaps das soluções existentes.

5. Se você pudesse publicar IOCs e metodologias de ataque em uma plataforma setorial verificada, que tipo de informação você compartilharia primeiro?
Objetivo: Entender o tipo de conteúdo de maior valor para o usuário produtor.

6. Qual nível de verificação de identidade você consideraria aceitável para confiar nos IOCs publicados por outros usuários?
Objetivo: Definir requisitos de trust e verificação da comunidade.

7. A integração com APIs de feeds reputacionais para validação automática de IOCs é algo que você usaria ativamente?
Objetivo: Validar a feature de integração com feeds reputacionais.

8. Ter acesso às informações de contato de outros profissionais verificados do seu setor seria útil? Em que situação você usaria isso?
Objetivo: Validar o valor da funcionalidade de networking entre verificados.

9. Quais informações sobre um ataque seriam mais úteis para você: IOCs técnicos (hashes, IPs, domínios), TTPs (MITRE ATT&CK), contexto do ataque, ou a combinação?
Objetivo: Priorizar o formato e profundidade do conteúdo publicado.

10. O que faria você voltar à plataforma diariamente? O que te faria abandoná-la?
Objetivo: Identificar drivers de retenção e churn.

https://docs.google.com/forms/d/e/1FAIpQLSf_-ANEmRsCD-Q4VGm9P6bM4IumPztNB7xrNUgXI3KgCuclRQ/viewform?usp=publish-editor

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



<h1> 5. Orientações de Aplicação </h1>


<h2>5.1 Formato das Entrevistas</h2>

• Entrevistas individuais de 20 a 30 minutos, preferencialmente por videoconferência ou presencial.

• Mínimo recomendado: 5 entrevistas por persona (total de 10 entrevistas).

• Gravar (com consentimento) para análise posterior e extração de insights.

• Evitar perguntas fechadas — estimular o entrevistado a elaborar suas respostas.


<h2>5.2 Análise dos Resultados</h2>

• Após as entrevistas, consolidar respostas em um mapa de afinidade para identificar padrões.

• Comparar as respostas com as hipóteses dos mapas de empatia e ajustar onde necessário.

• Priorizar dores recorrentes e ganhos mais desejados para guiar o backlog do produto.

• Usar os insights para refinar as personas e validar (ou invalidar) as premissas do CTHFeedTatics.


<h2>5.3 Métricas de Validação</h2>

• Taxa de confirmação: % de hipóteses dos mapas de empatia confirmadas nas entrevistas.

• Novas dores descobertas: dores mencionadas pelos entrevistados que não estavam nos mapas originais.

• Intensidade das dores: classificar de 1 a 5 a intensidade de cada dor mencionada.

• Intenção de uso: % de entrevistados que usariam a plataforma se estivesse disponível hoje.






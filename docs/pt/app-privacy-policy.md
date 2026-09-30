# Política de Privacidade

_Última atualização: 16 de abril de 2026_

## 1. Âmbito

Esta Política de Privacidade aplica-se à aplicação móvel LUNIA ("a App") disponível em iOS e Android, e a todos os serviços de backend relacionados. Descreve como recolhemos, utilizamos, armazenamos e protegemos os seus dados pessoais, incluindo dados de saúde de categoria especial. O website LUNIA (lunia.health) e o registo de acesso antecipado são regidos por uma Política de Privacidade separada.

## 2. Responsável pelo Tratamento

Virtuous Conviction Lda. (a operar como LUNIA Health)
Rua do Porto, n.º 37, 4925-347 Viana do Castelo, Portugal
NIF: 517 193 787
Email: hello@lunia.health
Encarregado de Proteção de Dados (DPO): Jorge Daniel Araújo — hello@lunia.health

## 3. Dados que Recolhemos

A LUNIA recolhe dados nas seguintes categorias:

| Categoria | Dados e finalidade |
|---|---|
| **Conta e Autenticação** | Email, número de telefone (opcional), ID de utilizador, tokens JWT, método de autenticação — para criação de conta e sessão. |
| **Perfil e Onboarding** | Nome de exibição, faixa etária, sintomas primários, estado emocional, fase hormonal, frequência de check-in, preferência de idioma — para personalização do serviço. |
| **Diário de Sintomas e Saúde** | Registos de sintomas (18 códigos com severidade), estado emocional por entrada, notas em texto livre, data e fonte da entrada — para acompanhamento de padrões de saúde. |
| **Dados de Wearables e Biométricos** | Sono (minutos totais, fases), frequência cardíaca, passos diários, fluxo menstrual, minutos de mindfulness, contagem de afrontamentos e suores noturnos — via Apple HealthKit / Google Health Connect. Requer consentimento explícito. |
| **Conversas e Interação com IA** | Mensagens de chat (utilizador + respostas IA), modo de conversa, referências RAG, metadados de deteção de red-flag, metadados de filtro de output — para funcionamento da companheira IA. |
| **Timeline Extraída por IA** | Sintomas extraídos de conversas, referências temporais, fatores contextuais, score de confiança IA, status de confirmação — para análise automatizada de padrões de saúde. |
| **Relatórios Clínicos** | Tipo de relatório, respostas a entrevistas, narrativa de padrões gerada por IA, perguntas sugeridas, exportação PDF (link com 48h de validade) — para preparação de consultas médicas. |
| **Telemetria Comportamental (Tempo)** | Intervalos de interação, taxas de conclusão, transições de ecrã, velocidade de escrita, embedding comportamental — rastreia ritmo, NUNCA conteúdo. Requer consentimento opt-in. |
| **Fórum Comunitário** | Publicações, modo anónimo, score de moderação IA, redação automática de PII, denúncias — para suporte comunitário entre pares. |
| **Subscrição e Faturação** | Plano de subscrição, datas de faturação, processamento de pagamento via Stripe — a LUNIA NÃO armazena números de cartão de crédito. |
| **Dados de Dispositivo e Técnicos** | Sistema operativo, versão da app, locale, dimensões de ecrã, modelo do dispositivo, tipo de rede — requer consentimento opt-in. |
| **Identificador de Dispositivo (Prevenção de Abuso)** | Um único identificador de dispositivo fornecido pelo sistema operativo (ANDROID_ID no Android, identifierForVendor no iOS), recolhido quando cria conta ou inicia sessão. Nunca é guardado tal como nos é dado: é imediatamente convertido num código irreversível com uma chave secreta do servidor, e apenas esse código é conservado, pelo que não pode ser revertido nem cruzado com os registos de qualquer outro serviço. Usamo-lo para um único fim — perceber quando uma conta suspensa regressa com um email novo — ao abrigo do nosso interesse legítimo em manter a comunidade segura (RGPD art. 6.º, n.º 1, al. f)). Não é usado para publicidade, estatísticas nem para a seguir entre aplicações, e não é combinado com o modelo do telemóvel, o tamanho do ecrã ou qualquer outro atributo para criar um perfil do seu dispositivo. Conservado durante 12 meses após a última utilização do dispositivo, sendo depois eliminado automaticamente. |
| **Localização** | Localização aproximada (país, região) derivada da rede — utilizada apenas para orientação de saúde específica por região e conformidade regulatória. Requer consentimento explícito opt-in. |
| **Consultas a APIs de Investigação Externa** | Termos de pesquisa anonimizados enviados para bases de dados científicas externas (PubMed, arXiv, bioRxiv, CrossRef) para recuperar literatura revista por pares para respostas da IA. Nenhum dado de saúde pessoal é transmitido; as consultas são anonimizadas antes do envio. Requer consentimento opt-in. |
| **Consultas à API de Nutrição** | Consultas de alimentação e nutrição anonimizadas enviadas ao Spoonacular para funcionalidades de orientação nutricional. As consultas são anonimizadas antes do envio. Requer consentimento opt-in. |

## 4. Como Obtemos o Seu Consentimento

Quando utiliza a app LUNIA pela primeira vez, pedimos o seu consentimento explícito antes de recolher quaisquer dados. O nosso sistema de consentimento é granular — escolhe exatamente que categorias de dados podemos processar:

- Dados de Saúde Essenciais — registo de sintomas, dados do ciclo, conversas com IA (necessário para o funcionamento da app)
- Analytics — estatísticas de utilização anónimas
- Experiência Adaptativa — acompanhamento de tempo comportamental
- Informação do Dispositivo — versão do SO, modelo, tamanho de ecrã
- Notificações — entrega e timing inteligente de notificações push
- Saúde via Wearables — sincronização Apple HealthKit / Google Health Connect
- Localização — localização aproximada para orientação específica por região e conformidade
- APIs de Investigação Externa — consultas anonimizadas ao PubMed, arXiv, bioRxiv, CrossRef para respostas da IA baseadas em literatura
- API de Nutrição — consultas anonimizadas ao Spoonacular para funcionalidades de orientação nutricional

Pode alterar qualquer consentimento a qualquer momento em Perfil → Definições de Privacidade. A retirada do consentimento interrompe a recolha futura de dados para essa categoria.

## 5. Fornecedores de Serviços Terceiros

Partilhamos dados com os seguintes fornecedores:

- Hetzner Cloud (Alemanha, UE) — infraestrutura de backend, todos os dados do servidor
- Anthropic Claude API (EUA) — processamento de conversas IA, com Cláusulas Contratuais Padrão e consentimento explícito
- Stripe (EUA/UE) — processamento de pagamentos
- Google Firebase (EUA) — base de dados website e analytics
- Apple HealthKit / Google Health Connect — dados de saúde permanecem no dispositivo + nossos servidores
- Expo EAS (EUA) — compilação e atualizações da app

## 6. Processamento por Inteligência Artificial

As tuas conversas com a Luni são processadas por inteligência artificial fornecida pela Anthropic PBC (EUA), ao abrigo de Cláusulas Contratuais Padrão da UE. A Anthropic não utiliza as tuas conversas para treinar os seus modelos e elimina-os no prazo máximo de 30 dias.

As tuas mensagens são enviadas à Anthropic para gerar respostas. Não são enviados dados de perfil de saúde estruturados (condições, medicações, sintomas), email, telefone ou identificadores de conta.

Para mais informações: https://www.anthropic.com/privacy

## 7. Onde os Seus Dados São Armazenados

Dispositivo móvel: Perfil, sintomas, histórico de chat e dados comportamentais são armazenados localmente no seu dispositivo usando armazenamento encriptado (iOS Keychain / Android Keystore para credenciais; AsyncStorage para preferências não sensíveis). Servidores europeus: Os dados do backend são armazenados em servidores Hetzner Cloud na Alemanha (UE). Os seus dados de saúde nunca saem da União Europeia, salvo se consentir no processamento IA externo.

## 8. Segurança

Implementamos as seguintes medidas de segurança: encriptação AES-256-GCM em repouso para campos sensíveis; autenticação JWT com tokens de acesso de curta duração armazenados no keychain seguro do dispositivo; rate limiting em todos os endpoints da API; nenhum dado de saúde nos logs da aplicação; conversas IA encriptadas antes da persistência em base de dados; containers sem root para todos os serviços de backend; sanitização de input e filtragem de output nas respostas da IA.

## 9. Retenção de Dados

Dados de conta: até à eliminação da conta. Conversas de onboarding: 30 dias após conclusão. Entradas do diário de sintomas: até à eliminação da conta ou pedido da utilizadora. Histórico de chat: até à eliminação da conta. Dados de wearables: cache local; sincronização com servidor até eliminação. Dados comportamentais Tempo: até retirada de consentimento ou eliminação de conta. Relatórios clínicos: até eliminação da conta; links PDF expiram após 48h. Publicações no fórum: até eliminação pela utilizadora ou moderação. Registos de auditoria de consentimento: mantidos indefinidamente (exigência regulamentar RGPD). Códigos de identificador de dispositivo (prevenção de abuso): 12 meses após a última utilização do dispositivo, sendo depois eliminados automaticamente.

## 10. Os Seus Direitos

Ao abrigo do RGPD, tem direito a:

- Direito de Acesso (Art. 15.º) — solicitar cópia legível dos seus dados pessoais (PDF) em Conta → Ver os meus dados. Responderemos no prazo de um mês.
- Direito de Retificação (Art. 16.º) — corrigir dados inexatos ou incompletos. Pode editar os dados de perfil diretamente na app; para dados extraídos por IA, contacte hello@lunia.health.
- Direito ao Apagamento (Art. 17.º) — eliminar a sua conta e todos os dados associados em Perfil → Eliminar Conta. A eliminação propaga-se em 72 horas.
- Direito à Limitação do Tratamento (Art. 18.º) — desativar categorias de consentimento individuais a qualquer momento em Perfil → Definições de Privacidade.
- Direito à Portabilidade dos Dados (Art. 20.º) — exportar os seus dados em formato JSON estruturado, transferível para outro serviço, em Conta → Exportar os meus dados.
- Direito de Oposição (Art. 21.º) — opor-se ao tratamento dos seus dados pessoais baseado em interesse legítimo, incluindo moderação automática de conteúdos e análise de padrões. Contacte hello@lunia.health para exercer este direito.
- Direito a Não Ficar Sujeita a Decisões Individuais Automatizadas (Art. 22.º) — a LUNIA utiliza IA para extrair padrões de sintomas e gerar sugestões, mas estes são apenas auxiliares informativos, não constituem decisões médicas ou jurídicas. Pode solicitar revisão humana de quaisquer dados extraídos por IA.
- Direito de Reclamação (Art. 77.º) — tem direito a apresentar reclamação a uma autoridade de controlo. Em Portugal, a autoridade competente é a Comissão Nacional de Proteção de Dados (CNPD): geral@cnpd.pt, www.cnpd.pt, Av. D. Carlos I, 134 — 1.º, 1200-651 Lisboa.
- Direito a Indemnização (Art. 82.º) — em caso de danos materiais ou imateriais resultantes de violação do RGPD, tem direito a obter indemnização do responsável pelo tratamento ou subcontratante. Contacte hello@lunia.health ou recorra aos tribunais portugueses.
- Direito a Retirar o Consentimento (Art. 7.º, n.º 3) — pode retirar o seu consentimento a qualquer momento, sem afetar a licitude do tratamento efetuado com base no consentimento previamente concedido.

Para exercer qualquer destes direitos, contacte hello@lunia.health. Responderemos no prazo de um mês (prorrogável até três meses em casos complexos, com notificação prévia).

## 11. Privacidade de Menores

A app LUNIA foi concebida para mulheres adultas. Não recolhemos conscientemente dados de menores de 16 anos. Se descobrirmos que recolhemos dados de um menor de 16 anos, eliminaremos imediatamente esses dados.

## 12. Aviso Médico

A LUNIA é uma companheira informativa de bem-estar. NÃO fornece diagnósticos médicos, prescrições ou recomendações de tratamento. A informação fornecida pela companheira IA (Luni) destina-se apenas a fins educativos. A LUNIA não substitui aconselhamento médico profissional. Em caso de emergência, ligue para o 112 (número europeu de emergência) ou SNS 24 (808 24 24 24 em Portugal).

## 13. Notificação de Violação de Dados

Em caso de violação de dados pessoais que represente um risco para os seus direitos e liberdades, iremos: notificar a Comissão Nacional de Proteção de Dados (CNPD) no prazo de 72 horas; notificar as utilizadoras afetadas sem demora injustificada se a violação representar risco elevado; documentar a violação, os seus efeitos e as medidas corretivas tomadas.

## 14. Transferências Internacionais

Os seus dados são principalmente armazenados e processados na União Europeia (Hetzner Cloud, Alemanha). As transferências para fora da UE (Stripe, Firebase, Anthropic, Expo — todos nos EUA) são protegidas por Cláusulas Contratuais Padrão ou pelo Quadro de Privacidade de Dados UE-EUA. Os dados de saúde (categoria especial Art. 9.º RGPD) só são transferidos para fora da UE com o seu consentimento explícito e salvaguardas apropriadas.

## 15. Cookies

A app móvel LUNIA não utiliza cookies. O armazenamento local de dados utiliza AsyncStorage (dados não sensíveis) e o keychain seguro do dispositivo (credenciais e tokens). O website lunia.health utiliza cookies conforme descrito nas Definições de Cookies.

## 16. Contacto

Para questões sobre esta Política de Privacidade, contacte-nos em hello@lunia.health.

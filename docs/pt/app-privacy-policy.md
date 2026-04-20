# Política de Privacidade — App LUNIA

**Última Atualização: 16 de abril de 2026**

## 1. Âmbito

Esta Política de Privacidade aplica-se à aplicação móvel LUNIA ("a App") disponível em iOS e Android, e a todos os serviços de backend relacionados. Descreve como recolhemos, utilizamos, armazenamos e protegemos os seus dados pessoais, incluindo dados de saúde de categoria especial. O website LUNIA (lunia.health) e o registo de acesso antecipado são regidos por uma Política de Privacidade separada.

## 2. Responsável pelo Tratamento

LUNIA Health  
[DENOMINAÇÃO SOCIAL — a confirmar]  
[MORADA REGISTADA — a confirmar]  
NIF: [NIF — a confirmar]  
Email: hello@lunia.health  
Contacto de Proteção de Dados: hello@lunia.health

## 3. Dados que Recolhemos

A LUNIA recolhe dados nas seguintes categorias:

| Categoria | Dados | Finalidade |
|---|---|---|
| **Conta e Autenticação** | Email, número de telefone (opcional), ID de utilizador, tokens JWT, método de autenticação | Criação de conta e sessão |
| **Perfil e Onboarding** | Nome de exibição, faixa etária, sintomas primários, estado emocional, fase hormonal, frequência de check-in, preferência de idioma | Personalização do serviço |
| **Diário de Sintomas e Saúde** | Registos de sintomas (18 códigos com severidade), estado emocional por entrada, notas em texto livre, data e fonte da entrada | Acompanhamento de padrões de saúde |
| **Dados de Wearables e Biométricos** | Sono (minutos totais, fases), frequência cardíaca, passos diários, fluxo menstrual, minutos de mindfulness, contagem de afrontamentos e suores noturnos — via Apple HealthKit / Google Health Connect | Correlação biométrica (opt-in, consentimento explícito) |
| **Conversas e Interação com IA** | Mensagens de chat (utilizador + respostas IA), modo de conversa, referências RAG, metadados de deteção de red-flag, metadados de filtro de output | Funcionamento da companheira IA |
| **Timeline Extraída por IA** | Sintomas extraídos de conversas, referências temporais, fatores contextuais, score de confiança IA, status de confirmação | Análise automatizada de padrões de saúde |
| **Relatórios Clínicos** | Tipo de relatório, respostas a entrevistas, narrativa de padrões gerada por IA, perguntas sugeridas, exportação PDF (link com 48h de validade) | Preparação de consultas médicas |
| **Telemetria Comportamental (Tempo)** | Intervalos de interação, taxas de conclusão, transições de ecrã, velocidade de escrita, embedding comportamental — rastreia ritmo, NUNCA conteúdo | Adaptação de UX (opt-in) |
| **Fórum Comunitário** | Publicações, modo anónimo, score de moderação IA, redação automática de PII, denúncias | Suporte comunitário entre pares |
| **Subscrição e Faturação** | Plano de subscrição, datas de faturação, processamento de pagamento via Stripe — a LUNIA NÃO armazena números de cartão de crédito | Gestão de subscrição |
| **Dados de Dispositivo e Técnicos** | Sistema operativo, versão da app, locale, dimensões de ecrã, modelo do dispositivo, tipo de rede | Suporte técnico e compatibilidade (opt-in) |
| **Localização** | Localização aproximada (país, região) derivada da rede | Orientação de saúde específica por região e conformidade regulatória (opt-in) |
| **Consultas a APIs de Investigação Externa** | Termos de pesquisa anonimizados enviados para PubMed, arXiv, bioRxiv, CrossRef | Respostas da IA baseadas em literatura — nenhum dado de saúde pessoal transmitido (opt-in) |
| **Consultas à API de Nutrição** | Consultas de alimentação e nutrição anonimizadas enviadas ao Spoonacular | Funcionalidades de orientação nutricional (opt-in) |

## 4. Como Obtemos o Seu Consentimento

Quando utiliza a app LUNIA pela primeira vez, pedimos o seu consentimento explícito antes de recolher quaisquer dados. O nosso sistema de consentimento é granular — escolhe exatamente que categorias de dados podemos processar:

1. **Dados de Saúde Essenciais** — registo de sintomas, dados do ciclo, conversas com IA *(necessário para o funcionamento da app)*
2. **Analytics** — estatísticas de utilização anónimas
3. **Experiência Adaptativa** — acompanhamento de tempo comportamental
4. **Informação do Dispositivo** — versão do SO, modelo, tamanho de ecrã
5. **Notificações** — entrega e timing inteligente de notificações push
6. **Saúde via Wearables** — sincronização Apple HealthKit / Google Health Connect
7. **Localização** — localização aproximada para orientação específica por região e conformidade
8. **APIs de Investigação Externa** — consultas anonimizadas ao PubMed, arXiv, bioRxiv, CrossRef para respostas da IA baseadas em literatura
9. **API de Nutrição** — consultas anonimizadas ao Spoonacular para funcionalidades de orientação nutricional

Pode alterar qualquer consentimento a qualquer momento em **Perfil → Definições de Privacidade**. A retirada do consentimento interrompe a recolha futura de dados para essa categoria.

## 5. Fornecedores de Serviços Terceiros

Partilhamos dados com os seguintes fornecedores:

| Fornecedor | Localização | Finalidade |
|---|---|---|
| Hetzner Cloud | Alemanha, UE | Infraestrutura de backend, armazenamento de todos os dados do servidor |
| Anthropic Claude API | EUA | Processamento de conversas IA (Cláusulas Contratuais Padrão + consentimento explícito) |
| Stripe | EUA / UE | Processamento de pagamentos |
| Pinecone | EUA | Pesquisa vetorial RAG, apenas embeddings |
| Google Firebase | EUA | Base de dados do website e analytics |
| Apple HealthKit / Google Health Connect | Dispositivo | Dados de saúde permanecem no dispositivo + servidores EU |
| Expo EAS | EUA | Compilação e atualizações da app |

## 6. Processamento por IA

As suas conversas com a Luni são processadas com inteligência artificial. Na nossa configuração padrão, o processamento IA ocorre em servidores europeus (Hetzner Cloud, Alemanha) usando os nossos modelos de IA auto-alojados. Para certas funcionalidades ou quando o nosso serviço IA primário não está disponível, os seus dados de conversa podem ser processados pela Anthropic (Claude API), sediada nos Estados Unidos. Neste caso, os seus dados são protegidos por Cláusulas Contratuais Padrão e pelo acordo de processamento de dados da Anthropic. Pode retirar o consentimento para processamento IA externo a qualquer momento nas suas definições de perfil.

## 7. Onde os Seus Dados São Armazenados

- **Dispositivo móvel**: Perfil, sintomas, histórico de chat e dados comportamentais são armazenados localmente no seu dispositivo usando armazenamento encriptado (iOS Keychain / Android Keystore para credenciais; AsyncStorage para preferências não sensíveis).
- **Servidores europeus**: Os dados do backend são armazenados em servidores Hetzner Cloud na Alemanha (UE). Os seus dados de saúde nunca saem da União Europeia, salvo se consentir no processamento IA externo.

## 8. Segurança

Implementamos as seguintes medidas de segurança:

- Encriptação AES-256-GCM em repouso para campos sensíveis
- Autenticação JWT com tokens de acesso de curta duração armazenados no keychain seguro do dispositivo
- Rate limiting em todos os endpoints da API
- Nenhum dado de saúde nos logs da aplicação
- Conversas IA encriptadas antes da persistência em base de dados
- Containers sem root para todos os serviços de backend
- Sanitização de input e filtragem de output nas respostas da IA

## 9. Retenção de Dados

| Categoria de Dados | Período de Retenção |
|---|---|
| Dados de conta | Até à eliminação da conta |
| Conversas de onboarding | 30 dias após conclusão |
| Entradas do diário de sintomas | Até à eliminação da conta ou pedido da utilizadora |
| Histórico de chat | Até à eliminação da conta |
| Dados de wearables | Cache local; sincronização com servidor até eliminação |
| Dados comportamentais Tempo | Até retirada de consentimento ou eliminação de conta |
| Relatórios clínicos | Até eliminação da conta; links PDF expiram após 48h |
| Publicações no fórum | Até eliminação pela utilizadora ou moderação |
| Registos de auditoria de consentimento | Mantidos indefinidamente (exigência regulamentar RGPD) |

## 10. Os Seus Direitos

Ao abrigo do RGPD, tem direito a:

- **Direito de Acesso (Art. 15.º)** — solicitar cópia dos seus dados pessoais
- **Direito de Retificação (Art. 16.º)** — corrigir dados inexatos
- **Direito ao Apagamento (Art. 17.º)** — eliminar a sua conta e todos os dados associados em **Perfil → Eliminar Conta**. A eliminação propaga-se em 72 horas
- **Direito à Limitação do Tratamento (Art. 18.º)** — desativar categorias de consentimento individuais a qualquer momento
- **Direito à Portabilidade dos Dados (Art. 20.º)** — exportar os seus dados em formato legível por máquina em **Perfil → Exportar os Meus Dados**
- **Direito de Oposição a Decisões Automatizadas (Art. 22.º)** — a LUNIA utiliza IA para extrair padrões de sintomas, mas estes são apenas auxiliares informativos, não decisões médicas

Para exercer qualquer destes direitos, contacte hello@lunia.health. Pode também apresentar reclamação junto da Comissão Nacional de Proteção de Dados (CNPD) em www.cnpd.pt.

## 11. Privacidade de Menores

A app LUNIA foi concebida para mulheres adultas. Não recolhemos conscientemente dados de menores de 16 anos. Se descobrirmos que recolhemos dados de um menor de 16 anos, eliminaremos imediatamente esses dados.

## 12. Aviso Médico

A LUNIA é uma companheira informativa de bem-estar. NÃO fornece diagnósticos médicos, prescrições ou recomendações de tratamento. A informação fornecida pela companheira IA (Luni) destina-se apenas a fins educativos. A LUNIA não substitui aconselhamento médico profissional. Em caso de emergência, ligue para o 112 (número europeu de emergência) ou SNS 24 (808 24 24 24 em Portugal).

## 13. Notificação de Violação de Dados

Em caso de violação de dados pessoais que represente um risco para os seus direitos e liberdades, iremos:

- Notificar a Comissão Nacional de Proteção de Dados (CNPD) no prazo de 72 horas após termos conhecimento da violação
- Notificar as utilizadoras afetadas sem demora injustificada se a violação representar risco elevado para os seus direitos e liberdades
- Documentar a violação, os seus efeitos e as medidas corretivas tomadas

## 14. Transferências Internacionais

Os seus dados são principalmente armazenados e processados na União Europeia (Hetzner Cloud, Alemanha). As transferências para fora da UE (Stripe, Firebase, Anthropic, Pinecone, Expo — todos nos EUA) são protegidas por Cláusulas Contratuais Padrão ou pelo Quadro de Privacidade de Dados UE-EUA. Os dados de saúde (categoria especial Art. 9.º do RGPD) só são transferidos para fora da UE com o seu consentimento explícito e salvaguardas apropriadas.

## 15. Cookies

A app móvel LUNIA não utiliza cookies. O armazenamento local de dados utiliza AsyncStorage (dados não sensíveis) e o keychain seguro do dispositivo (credenciais e tokens). O website lunia.health utiliza cookies conforme descrito na sua Política de Cookies separada.

## 16. Contacto

Para questões sobre esta Política de Privacidade, contacte-nos em hello@lunia.health. Prazo de resposta: até 30 dias.

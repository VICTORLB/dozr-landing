# Dozr Launch Strategy

Data: 2026-05-17

## Diagnostico

Dozr esta em bom ponto para pre-lancamento. O produto ja tem uma proposta clara: um app privado para iPhone que ajuda pessoas a lembrar medicamentos, vitaminas e suplementos, registrar em um toque e acompanhar aderencia.

O que ja esta forte:

- Landing page bilingue com lista de espera via Netlify Forms.
- Posicionamento de privacidade: sem conta, dados no dispositivo, offline.
- Produto com loop diario claro: lembrete, registro, progresso, streak.
- Modelo freemium simples: ate 5 itens gratis, Pro com itens ilimitados e historico completo.
- Paginas legais publicadas: politica de privacidade e termos.
- Precos definidos: BRL 8,90 mensal / BRL 49,90 anual e USD 4.99 mensal / USD 29.99 anual.

Principais riscos antes do lancamento:

- A landing page fala em lista de espera, mas ainda nao existe uma oferta forte de entrada alem de "avisar quando lancar".
- As provas sociais parecem genericas para um app ainda em pre-lancamento; use depoimentos reais de beta testers assim que possivel.
- A configuracao de App Store ainda tem placeholders em `eas.json`, entao submissao e distribuicao precisam ser fechadas antes do plano de lancamento.
- O app pede permissao de notificacao cedo. Isso deve ser testado com usuarios reais, porque permissao recusada mata o valor central do produto.
- O posicionamento mistura "medicamentos" e "suplementos". Para o primeiro lancamento, suplementos/vitaminas tende a ser um angulo mais leve e menos regulatorio; medicamentos entra como caso de uso secundario com disclaimer.

## Posicionamento Recomendado

Mensagem principal:

> Nunca mais esqueca seus suplementos, vitaminas e remedios. Dozr lembra voce no horario certo, registra em um toque e mostra sua consistencia sem criar conta nem enviar seus dados para a nuvem.

Promessa curta:

> Lembretes privados para sua rotina de suplementos e medicamentos no iPhone.

Angulos de copy:

- Privacidade: "Sem conta. Sem nuvem. Seus dados ficam no iPhone."
- Simplicidade: "Cadastre uma vez. Receba lembretes todos os dias. Marque com um toque."
- Habito: "Veja seu streak crescer e acompanhe sua aderencia."
- Controle: "Historico visual para entender sua rotina nos ultimos dias."

Evite prometer:

- Resultado de saude.
- Aderencia clinica garantida.
- Diagnostico, tratamento ou recomendacao medica.

## Publicos Prioritarios

1. Pessoas que tomam suplementos diariamente

Esse deve ser o publico inicial mais facil. Dores: esquecem creatina, omega 3, vitamina D, multivitaminico, manipulados, probioticos. Canais: Instagram, TikTok, Reddit, comunidades fitness, creators de wellness.

2. Pessoas com rotinas simples de remedios

Bom para App Store Search e conteudo SEO. Dores: anticoncepcional, remedio continuo, alergia, ansiedade, vitaminas prescritas. Use linguagem cuidadosa: app de organizacao, nao app medico.

3. Biohackers e usuarios de stack

Podem justificar Pro mais cedo porque ultrapassam 5 itens. Dores: varios suplementos, horarios diferentes, controle de consistencia. Canais: X, Reddit, comunidades de produtividade, longevidade e fitness.

## Oferta de Pre-Lancamento

Troque "entre na lista para ser avisado" por uma oferta com motivo:

> Entre na lista privada e receba acesso antecipado pelo TestFlight, preco anual de fundador no lancamento e um guia simples para montar sua rotina diaria de suplementos.

Sugestao de incentivo:

- Primeiros 100 inscritos: 3 meses de Pro gratis ou desconto anual fundador.
- Beta testers: acesso TestFlight + pedido explicito de feedback.
- Lead magnet simples: "Checklist de rotina diaria de suplementos sem esquecer horarios".

Campos da lista:

- Email.
- Idioma ou pais.
- Caso de uso: suplementos, medicamentos, ambos.
- Quantidade aproximada de itens na rotina: 1-3, 4-5, 6+.

Isso ajuda a validar o limite gratuito de 5 itens e identificar usuarios com maior chance de pagar.

## Canais ORB

| Tipo | Canal | Acao | Meta |
| --- | --- | --- | --- |
| Owned | Landing page `dozr.app` | Melhorar oferta da waitlist e capturar caso de uso | 200-500 emails antes do lancamento |
| Owned | Email | Sequencia de 4 emails para inscritos | Ativar beta e gerar downloads no dia 1 |
| Owned | App Store | ASO com keywords de suplementos, vitaminas e medication reminder | Conversao organica continua |
| Owned | Conteudo SEO | 5 paginas/artigos focados em long-tail | Trafego evergreen |
| Rented | TikTok/Reels | Videos curtos demonstrando dor e solucao | 20-50 posts em 30 dias |
| Rented | X/Threads/LinkedIn pessoal | Build in public do primeiro app | Autoridade e primeiras conversas |
| Rented | Reddit | Posts uteis em comunidades relevantes, sem spam | Feedback e primeiros beta users |
| Borrowed | Microcriadores fitness/wellness | 10 convites para testar e gravar rotina | Prova social real |
| Borrowed | Comunidades iOS/indie hacker | Compartilhar construcao e lancamento | Usuarios early adopter |
| Borrowed | Product Hunt | Usar apenas se houver assets e audiencia minima | Pico de atencao internacional |

## Cronograma de 6 Semanas

### Semana -6: Fundacao

- Fechar App Store Connect, bundle, assinaturas, RevenueCat e TestFlight.
- Instalar analytics minimo na landing: eventos de page view, submit da waitlist e clique em App Store quando existir.
- Ajustar landing para oferta de acesso antecipado, nao apenas aviso.
- Criar formulario com segmentacao de caso de uso.
- Preparar 5 screenshots reais do app em iPhone.

Meta: landing pronta para capturar demanda e TestFlight quase pronto.

### Semana -5: Validacao

- Convidar 20 pessoas manualmente para beta.
- Pedir que cada beta tester cadastre sua rotina real e use por 7 dias.
- Fazer 5 entrevistas rapidas de 15 minutos.
- Medir: permissao de notificacao aceita, itens cadastrados, retorno no dia seguinte, registros feitos.

Meta: encontrar as 3 frases reais que usuarios usam para descrever a dor.

### Semana -4: Conteudo Base

- Publicar 3 posts SEO:
  - "Como lembrar de tomar suplementos todos os dias"
  - "App para lembrar remedios no iPhone: o que observar"
  - "Como montar uma rotina simples de vitaminas e suplementos"
- Criar 10 videos curtos:
  - Dor: "Comprei suplementos e esqueco metade da semana."
  - Demo: cadastro, notificacao, check-in, streak.
  - Privacidade: dados no iPhone, sem conta.
- Comecar postagens build in public 3 vezes por semana.

Meta: gerar trafego e conversas antes do lancamento.

### Semana -3: Prova Social

- Coletar depoimentos reais de beta testers.
- Trocar cards genericos da landing por comentarios reais, mesmo que pequenos.
- Montar press kit: icone, screenshots, descricao curta, descricao longa, video demo de 20-30s.
- Fazer outreach para 20 microcriadores ou perfis pequenos de fitness, rotina, saude preventiva, produtividade e iOS.

Meta: 3 depoimentos reais e 3 parceiros dispostos a postar.

### Semana -2: Aquecimento

- Enviar email "beta fechado abrindo".
- Abrir TestFlight para parte da lista.
- Publicar comparativos leves:
  - planilha/notas vs Dozr;
  - alarme comum vs lembrete com historico;
  - app com conta vs app privado.
- Preparar todos os posts do dia do lancamento.

Meta: 100 usuarios em beta ou lista com intencao clara.

### Semana -1: Lancamento Pronto

- Submeter build final para review da App Store.
- Validar paywall, compras, restore e limites do plano free.
- Preparar email de lancamento em PT e EN.
- Preparar pagina com badge da App Store assim que o link estiver disponivel.
- Criar lista de pessoas para avisar manualmente no dia.

Meta: nada critico pendente no dia do lancamento.

## Dia do Lancamento

Manha:

- Atualizar landing: trocar waitlist por botao da App Store.
- Enviar email para toda a lista.
- Publicar post principal com video demo.
- Mandar mensagens manuais para beta testers pedindo review honesto na App Store.

Meio do dia:

- Publicar 2 videos curtos: demo e dor do usuario.
- Responder todos os comentarios em ate 1 hora.
- Pedir aos primeiros usuarios que reportem problemas.

Fim do dia:

- Publicar resultado parcial: downloads, aprendizados, proximas melhorias.
- Enviar follow-up para quem abriu email e nao clicou.
- Registrar bugs e feedbacks em uma lista priorizada.

Metricas do dia 1:

- Downloads.
- Conversao landing -> App Store.
- Conversao App Store -> install.
- Usuarios que adicionaram primeiro item.
- Permissao de notificacao aceita.
- Primeiro check-in feito.
- Compras ou trials iniciados, se houver.

## Plano de 30 Dias Pos-Lancamento

Semana 1:

- Corrigir atritos encontrados no onboarding e permissao de notificacao.
- Enviar email "como configurar sua primeira rotina".
- Publicar 1 video por dia mostrando casos de uso.
- Pedir reviews para usuarios ativos apos 3 dias de uso.

Semana 2:

- Publicar artigo "Como eu lancei meu primeiro app iOS".
- Criar pagina SEO para "app de lembrete de suplementos".
- Testar 2 variantes de headline na landing.
- Fazer outreach para mais 20 microcriadores.

Semana 3:

- Criar conteudo sobre stacks com mais de 5 itens, puxando para Pro.
- Testar oferta anual fundador.
- Publicar changelog com melhorias feitas a partir do beta.

Semana 4:

- Avaliar funil completo:
  - landing -> email;
  - email -> download;
  - install -> primeiro item;
  - primeiro item -> notificacao;
  - notificacao -> check-in;
  - 5 itens -> paywall;
  - paywall -> compra.
- Decidir o proximo foco: aquisicao, retencao ou monetizacao.

## Sequencia de Email

Email 1: Confirmacao da lista

Assunto: Voce esta na lista do Dozr

Corpo:

Obrigado por entrar na lista. O Dozr esta sendo criado para uma coisa simples: ajudar voce a lembrar suplementos, vitaminas e remedios sem cadastro, sem nuvem e sem complicacao.

Antes do lancamento, vou convidar um pequeno grupo para testar pelo TestFlight. Se voce entrar, quero especialmente saber se os lembretes, o registro em um toque e o historico realmente encaixam na sua rotina.

Email 2: Convite beta

Assunto: Quer testar o Dozr antes da App Store?

Corpo:

Estou abrindo um grupo pequeno de beta testers no iPhone. A ideia e simples: voce cadastra sua rotina real, usa por alguns dias e me diz onde o app ainda atrapalha.

Se quiser participar, responda este email com quantos suplementos ou medicamentos voce toma por dia.

Email 3: Lancamento

Assunto: Dozr ja esta disponivel para iPhone

Corpo:

O Dozr chegou a App Store. Ele ajuda voce a configurar sua rotina uma vez, receber lembretes no horario certo e registrar cada dose com um toque.

O plano gratis permite ate 5 itens. Para rotinas maiores, o Dozr Pro libera itens ilimitados e historico completo.

Email 4: Pos-lancamento

Assunto: Como montar sua primeira rotina no Dozr

Corpo:

Comece simples: cadastre os itens que voce toma todos os dias, escolha os horarios e aceite as notificacoes. Depois de alguns dias, o historico comeca a mostrar onde sua rotina esta funcionando e onde voce costuma esquecer.

## Posts Prontos

Post build in public:

> Estou lancando meu primeiro app iOS: Dozr.
>
> Ele nasceu de uma dor simples: comprar suplementos, montar uma rotina e esquecer no meio da semana.
>
> O app lembra no horario certo, registra em um toque e mostra seu streak. Sem conta. Sem nuvem. Dados no iPhone.
>
> Estou abrindo a lista de acesso antecipado: https://dozr.app/pt/

Post de dor:

> Se voce toma creatina, vitamina D, omega 3 ou qualquer suplemento diario, o problema raramente e comprar.
>
> O problema e lembrar todo dia.
>
> Estou criando o Dozr para resolver isso no iPhone: lembrete, check-in e historico privado.

Post de privacidade:

> Apps de saude nao deveriam exigir que voce mande sua rotina pessoal para a nuvem.
>
> No Dozr, seus dados ficam no iPhone. Sem conta. Sem feed. Sem painel web.
>
> So lembretes, registro e historico para sua rotina.

## App Store ASO

Titulo:

Dozr: Lembrete de Suplementos

Subtitulo:

Vitaminas, remedios e rotina

Keywords iniciais:

suplementos,vitaminas,remedio,lembrete,medicamento,rotina,habito,aderencia,pilula,saude

Descricao curta:

Dozr ajuda voce a lembrar suplementos, vitaminas e medicamentos no iPhone. Configure sua rotina, receba notificacoes, registre cada dose com um toque e acompanhe sua consistencia. Sem conta. Seus dados ficam no dispositivo.

## Product Hunt

Use Product Hunt apenas se voce tiver:

- Versao em ingles bem revisada.
- Video demo curto.
- Pelo menos 100 pessoas para avisar no dia.
- 10-20 apoiadores que entendem o produto antes do lancamento.
- Tempo para responder comentarios durante todo o dia.

Copy:

Name: Dozr

Tagline: Private supplement and medication reminders for iPhone

Description:

Dozr helps iPhone users remember supplements, vitamins and medications with precise reminders, one-tap logging, streaks and offline adherence history. No account required. Your data stays on your device.

## Checklist Antes de Anunciar

- App Store Connect configurado sem placeholders.
- RevenueCat com produtos reais `monthly` e `annual`.
- Compras, restore e paywall testados em build real.
- TestFlight com pelo menos 20 usuarios.
- Landing com evento de conversao funcionando.
- Link da App Store pronto.
- Screenshots reais para App Store e redes sociais.
- Politica de privacidade e termos revisados para compras e dados locais.
- Disclaimer claro: Dozr nao oferece aconselhamento medico.
- Plano de resposta para bugs no dia 1.

## Metas Realistas Para Primeiro Lancamento

Pre-lancamento:

- 200 emails qualificados.
- 30 beta testers.
- 10 conversas reais com usuarios.
- 3 depoimentos aproveitaveis.

Primeiros 7 dias:

- 300-1000 downloads, dependendo da audiencia propria.
- 40%+ dos usuarios adicionando pelo menos 1 item.
- 60%+ aceitando notificacoes entre usuarios que completam onboarding.
- 20+ reviews na App Store.
- Primeiras compras Pro, mesmo que poucas.

## Proxima Acao Recomendada

A prioridade agora nao e postar mais; e transformar a waitlist em validacao.

Nos proximos 7 dias:

1. Ajuste a landing para vender acesso antecipado e beneficio de fundador.
2. Convide 20 beta testers manualmente.
3. Grave um video demo de 20 segundos.
4. Colete feedback sobre permissao de notificacao e primeiro cadastro.
5. Use as palavras dos beta testers para reescrever headline, App Store e posts.

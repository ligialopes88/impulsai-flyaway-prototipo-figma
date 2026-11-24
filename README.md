# ImpulsAI x Flyaway — Protótipo Figma

Trabalho "Da Ideia à Experiência: Projetando e Prototipando uma Interface Digital com Figma" (Design de Interação e Interface UX/UI, UniFECAF).

## Objetivo do produto

O ImpulsAI Painel é o app em que a dona de uma agência de viagens ativa, acompanha e controla o agente de IA que atende seus clientes no WhatsApp, direto do celular. Ela vê o CRM e as conversas, assume um atendimento quando quiser e devolve ao agente depois. O caso de uso é a Flyaway, agência de viagens boutique: a assistente virtual Sofia recebe o pedido de cotação, coleta rota, datas, passageiros e bagagem e passa o atendimento para uma consultora.

O desafio de UX é fazer uma usuária sem perfil técnico ativar o agente em poucos minutos e confiar no que ele diz em seu nome.

## Fluxo principal

1. **Cadastro:** conta criada com o mínimo de campos (onboarding 1 de 2).
2. **Conectar WhatsApp:** autorização do número oficial pela Meta, sem QR code (onboarding 2 de 2).
3. **Painel:** resumo do dia, com atendimentos, pedidos de cotação e conversas que precisam da equipe.
4. **Conversas:** lista com etiqueta de status (Agente atendendo, Precisa de você, Resolvida).
5. **Conversa aberta:** leitura do que o agente disse e botão Assumir atendimento.
6. **Conversa assumida:** responder ao cliente ou Devolver ao agente.

O protótipo tem 6 telas mobile, em moldura de celular Android (390 px), que são a entrega principal, e uma versão web complementar com 3 telas (1440 px: conectar WhatsApp, painel e conversas). Para navegar, abra o protótipo em modo apresentação a partir do ponto de partida "Fluxo principal (mobile Android)".

## Decisões de design

- **API oficial do WhatsApp no lugar de QR code:** evita o risco de bloqueio do número pela Meta e a dificuldade de escanear a própria tela do celular.
- **Mobile-first:** a dona da agência e as consultoras acompanham conversas pelo telefone; a versão web adapta as telas principais ao computador.
- **Uma ação principal por tela**, fixa na base e ao alcance do polegar (Lei de Hick).
- **Barra de abas inferior** com Painel e Conversas, padrão conhecido (Lei de Jakob).
- **Controle da usuária:** Assumir atendimento sempre visível e Devolver ao agente depois.
- **Identidade ImpulsAI:** fundo off-white #F6F5F1, texto #121212, verde-limão #C6F432 só como cor de energia (nunca como texto sobre fundo claro), DM Sans, Instrument Serif itálico e DM Mono.
- **Acessibilidade:** meta WCAG AA, alvos de toque de 44 px, texto mínimo de 16 px e status sempre com ícone e texto.

## Limitações conhecidas

- O foco do trabalho é a interface. A conexão real com o WhatsApp (número de teste da Meta) serve apenas como demonstração do agente.

## Uso de IA

- **Figma:** protótipo, design system e fluxo navegável.
- **IA:** o design foi desenvolvido com a ajuda do Claude (Anthropic), em ideação, estrutura, revisão e textos. As decisões e a conferência final são minhas. Os prompts usados estão na seção 1.6 do documento teórico.

## Links

- Protótipo Figma: (adicionar link público: Share > Anyone with the link can view)
- Parte teórica: (adicionar link do documento "Da Ideia à Experiência — ImpulsAI")
- Vídeo pitch: (adicionar link público ou não listado)

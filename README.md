# Resumo de Podcast para Ouvintes Ocupados

Bem-vindo ao projeto que faz parte da masterclass - **Do Conceito à Realidade: Crie seus próprios produtos de IA com ChatGPT** oferecida pelo Dr. Jorge Valverde-Rebaza (detalhes [AQUI](https://visibilia.net.br/masterclass-ia-generativa-crie-produtos-genai-chatgpt/)). Neste projeto, você criará um aplicativo LLM que resume um episódio de podcast, identifica convidados do podcast, identifica os principais destaques analisando o conteúdo do mesmo, e muito mais!

## **Problema**

Sou um grande fã de podcasts e adoro podcasts por serem uma forma de obter *insights* profundos sobre diferentes tópicos, incluindo negócios, tecnologia, e inclusive saúde. Os podcasts ajudam a aprender com a experiência vivida de pessoas em todo o mundo. Mas o tempo é limitado e acabo ouvindo apenas alguns deles! Estou inscrito em vários podcasts interessantes que lançam 1-2 episódios por semana e o problema é que é difícil identificar um episódio que me agrade. Embora muitos episódios forneçam notas de apresentação, links adicionais e carimbos de data/hora, tais informações terminam sendo pouco úteis para realmente entender os aspectos únicos do podcast e determinar se vou querer ouvi-los! Como posso tornar esse processo de descoberta mais interessante e eficiente?

## **Solução**

Pode-se gerar um boletim informativo personalizado toda semana que resuma cada episódio de podcast lançado naquela semana. Incluiria informações sobre o convidado no episódio, os principais tópicos discutidos, bem como alguns destaques. Para fazer isso possível, deve-se coletar uma lista de feeds RSS do usuário e, periodicamente, processar os episódios mais recentes para gerar o boletim informativo. Isso funciona como um resumo da semana, fornecendo ao usuário o nível certo de detalhes que lhe permitira decidir quais episódios são atraentes e devem ser ouvidos.

## **Abordagem**

Dividiremos a abordagem para construir este produto em três partes -

- **Parte 1:** usar um modelo de Speech to Text da OpenAI chamado Whisper para transcrever o podcast.

- **Parte 2:** usar um LLM da OpenAI para construir a funcionalidade de extração de informações para obter insights do podcast.

- **Parte 3:** usar o chatGPT da OpenAI como seu assistente de codificação para criar e implantar um front-end que permita aos usuários experimentar a funcionalidade de ponta a ponta

Por meio deste projeto, nosso objetivo é entender como podemos abordar a construção e a implantação de aplicativos LLM que agregam valor aos usuários. Também forneceremos ideias para extensões interessantes e funcionalidades adicionais em várias partes do projeto.

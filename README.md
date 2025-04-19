# Desafio_Microsoft_Copilot_Studio
Criar um Copilot em branco
Depois de entrar ou se inscrever no Copilot Studio, você acessa a Home page. Selecione Criar na navegação à esquerda.
Na página Criar, selecione Novo agente.
Use o chat para descrever seu agente, usando as perguntas fornecidas para orientação.
Mantenha sua descrição simples por enquanto, mas certifique-se de incluir informações sobre o que seu agente ajuda os usuários a fazer e qual estilo e tom de conversa ele usa. O Copilot Studio usa suas respostas para preencher os detalhes em nome, descrição, instruções e conhecimento que definem seu agente.
Por exemplo: Seu nome é Tutor de Agente Amigável. Você ajuda os usuários a aprender a criar agentes. Você deve falar com os usuários como um professor gentil e paciente.
Adicionar uma imagem para representar seu agente.
Selecione o ícone do agente na barra superior.
Selecione Alterar ícone.
Escolha uma imagem do seu dispositivo. O arquivo de imagem deve estar no formato PNG e ter menos de 30 KB.
Selecione Salvar.
Depois de ter um nome, ícone, descrição e instruções, seu agente estará pronto. Selecione Criar. É exibida a página Visão geral de seu agente.
Agora você tem um agente que pode começar a testar! Você pode conversar com seu agente no bate-papo Testar seu agente.

Customizar um tópico
Abra seu agente da lista na página de agentes. Para melhor visibilidade, feche o painel Testar seu agente por enquanto.
Na barra do menu superior, selecione Tópicos.
Selecione Adicionar um tópico e escolha Em branco.
Um nó de Gatilho é exibido em uma tela da criação de tópicos em branco.
Selecione o ícone Mais (...) do nó Gatilho e selecione Propriedades. O painel Em Propriedades de Intenção Reconhecida será exibido.
No painel Em Propriedades de Intenção Reconhecida, selecione a área Frases. O painel secundário Frases é exibido.
Em Adicionar frases, insira uma frase de gatilho para seu tópico.
Seu agente precisa de 5 a 10 frases de gatilho para treinar a IA para entender as respostas de seus clientes. Para adicionar mais frases de gatilho:
Selecione o ícone Adicionar ao lado do campo de texto e insira a frase desejada.
Cole um conjunto de frases de gatilho, cada uma em uma linha separada, e selecione Enter.
Digite um conjunto de frases de gatilho, pressionando Shift+Enter após cada uma para colocá-la em uma linha separada e selecione Enter.
Você pode incluir a pontuação em uma frase de gatilho, mas é melhor usar frases curtas em vez de frases longas.
Selecione Detalhes na barra de ferramentas para abrir o painel Detalhes do tópico.
Adicione detalhes do tópico do seu agente:
Insira um nome para identificar o tópico, como "Horário da loja". A página Tópicos lista todos os tópicos definidos no agente, por esse nome.
Se desejar, insira um nome de exibição para mostrar ao cliente quando o agente não puder determinar qual tópico corresponde à mensagem do cliente.
Se quiser, use o campo Descrição para descrever o objetivo do tópico para você e para outros criadores de agentes da sua equipe. Os clientes nunca veem descrições de tópicos.
Selecione Salvar na barra de menu superior para salvar seu tópico.

Personalizar uma mensagem de erro de tópico

Condições e comportamentos do tópico do sistema
Esta lista descreve os tópicos do sistema disponíveis e revela o que os aciona.
Início da conversa
    • Cumprimenta os usuários e apresenta o agente e seus recursos.
    • É acionado quando um agente interage pela primeira vez com um usuário em uma conversa.
Melhora da conversa,
    • Cria respostas generativas a partir de fontes de dados externas.
    • É acionado quando o agente não consegue encontrar uma correspondência para a consulta do usuário.
Fim da conversa
    • Confirma com os clientes que sua dúvida foi respondida.
    • Gatilhos de um redirecionamento. Chame esse tópico dos seus tópicos personalizados quando estiver pronto para encerrar uma conversa.
Escalonar
    • Informa os clientes se eles precisam falar com um humano.
    • Aciona quando "falar com o agente" é correspondido ou Escalar evento do sistema é chamado.
      Por exemplo, os nós Pergunta podem ser configurados para escalar se não receberem uma resposta válida do cliente.
Fallback
    • Informa aos usuários que não foi possível corresponder a um tópico e pede que tentem novamente.
    • É acionado quando o agente não consegue corresponder a pergunta ou mensagem do usuário a um tópico.
Vários Tópicos Correspondentes
    • Solicita que os usuários escolham o tópico pretendido e define uma variável de sistema para identificar o tópico acionado.
    • Acionado quando a mensagem de um usuário se aproxima de vários tópicos.
Se Houver Erro
    • Informa aos clientes que ocorreu um erro.
      A mensagem inclui um código de erro, o ID da conversa e o carimbo de data/hora do erro, que pode ser usado posteriormente para depuração. Se a conversa estiver ocorrendo no painel Teste agente, uma mensagem de erro detalhada será incluída para ajudar o agente autor a diagnosticar o problema. Saiba como solucionar erros.
    • Acionado quando ocorre um erro durante a conversa.
Redefinir Conversa
    • Redefine a conversa limpando valores de variáveis e forçando o agente a usar o conteúdo agente publicado mais recentemente.
    • Gatilhos com um redirecionamento.
Entrar
    • Orienta os clientes a se inscreverem quando a autenticação do usuário é habilitada. Saiba como adicionar autenticação de usuário aos tópicos.
    • Acionado no início da conversa quando os usuários são obrigados a entrar ou quando a conversa chega a um nó que usa variáveis de autenticação.

Aumentar e diminuir a qualidade da resposta com GenAI
Selecione a página Tópicos e abra um tópico. Descubra onde deseja usar respostas generativas.
Selecione o ícone de adição para abrir o menu do novo nó.
Em Avançado, selecione Respostas generativas.
Um novo nó chamado Criar respostas generativa é adicionado ao seu tópico. Para acessar o painel Propriedades, selecione ..., em seguida, Propriedades do nó.
       Você pode especificar e configurar suas novas fontes de dados:
        ◦ Pesquise dados públicos ou use uma Pesquisa Personalizada do Bing para obter respostas generativas
        ◦ Conectar seus dados ao Azure OpenAI para resposta generativas (versão preliminar)
        ◦ Use documentos carregados para respostas generativas
        ◦ Usar conteúdo no conteúdo do SharePoint para respostas generativas
        ◦ Use uma fonte de dados personalizado para respostas generativas

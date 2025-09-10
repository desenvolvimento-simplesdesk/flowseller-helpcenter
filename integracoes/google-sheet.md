# 📊 Google Sheet

_Tempo estimado de leitura: 5 min_ :hourglass\_flowing\_sand:

A integração do Planilhas Google permite enviar dados, obter dados, obter uma linha aleatória e gerar galerias dinâmicas a partir do Planilhas Google.

### Conectando a Simplesdesk ao Google Sheets

1. &#x20;**Vá para Menu > Configurações > Integrações e Clique em Conectar**

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

2. &#x20;A partir daqui, você precisa _escolher a conta_ associada à Planilha Google e aceitar/permitir a conexão da Simplesdesk com sua conta Google.

![](<../.gitbook/assets/image (55).png>)![](<../.gitbook/assets/image (56).png>)

\
**3.** Depois de conectar sua Planilha Google, você obterá a janela de integração como esta imagem abaixo. **Clique em Gerir**

<figure><img src="../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

\*Observe que você pode desconectar as planilhas do Google com a Simplesdesk a qualquer momento pressionando o botão.

4. Agora clique em **Adicionar**

<figure><img src="../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

5. Após, dê um nome para a Planilha que você vai integrar, não precisa ser igual ao nome da planilha  em seu Google Drive / Google Sheets

Após digitar o nome, abra o seu Google Drive em uma guia no seu navegador, encontre a planilha que deseja integrar, abra, em seguida copie o link da planilha (URL) e cole o link na Simplesdesk

<figure><img src="../.gitbook/assets/image (61).png" alt="" width="394"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

### Integração do Google Sheets em ação

Agora você aprenderá como usar a integração do Google Sheets.

#### Como encontrar as ações do Google Sheets

Para poder usar a integração do Google Sheets, você precisa usá-la em um fluxo.

No seu menu, vá para **Fluxos** . Assim que chegar à visão geral dos fluxos, pressione o botão superior direito **Adicionar fluxo** .

Ao chegar ao editor de fluxo, você pode pressionar o bloco de mensagem com o qual inicia> selecionar Ação> Google Sheets(Planilhas do Google). Dê uma olhada abaixo em como encontrar a integração das planilhas do Google

<figure><img src="../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

### Que tipo de ações a integração do Google Sheets oferece?

Existem várias opções para escolher ao selecionar a integração com o Google Sheets.&#x20;

Tudo depende das suas necessidades. Abaixo estão as opções que oferecemos suporte atualmente:

* Enviar dados para o Google Sheets
* Obter linha (valor) do Google Sheets
* Atualizar linha da Planilha Google
* Limpar linha (valor) no Google Sheets
* Obtenha uma linha aleatória no Google Sheets
* Crie uma galeria dinâmica com o Google Sheets

<div align="center"><figure><img src="../.gitbook/assets/image (67).png" alt="" width="228"><figcaption></figcaption></figure></div>

<figure><img src="../.gitbook/assets/image (68).png" alt="" width="375"><figcaption></figcaption></figure>

### Configurando sua Planilha Google

Antes de usar qualquer uma das ações acima, você precisa criar uma planilha do Google com algumas informações predefinidas.

Digamos que você queira capturar dados do assinante, como nome, e-mail e número de telefone.&#x20;

Em seguida, exporte para uma planilha do Google. Para isso, precisamos criar alguns cabeçalhos dentro da própria Planilha Google para onde podemos exportar os dados.

Crie uma planilha do Google como “Dados do Assinante”.

Em seguida, crie os cabeçalhos para cada coluna. Usaremos nome completo, ID de usuário, e-mail e número de telefone

<figure><img src="../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

Agora que preparamos a Planilha Google, é hora de exportar os dados do nosso bot do Messenger para esta planilha.

### FATO IMPORTANTE!

Sempre que você conectar sua Planilha Google na Simplesdesk você precisa levar em consideração que sempre que alterar o nome da planilha ou planilha você precisará refazer aquela ação da Planilha Google.

{% hint style="warning" %}
A integração está configurada para funcionar com o nome da planilha em vez do id. Portanto, alterar isso fará com que a integração pare de funcionar.
{% endhint %}

Portanto, se você alterar qualquer um dos nomes, lembre-se de que precisará refazer a ação da Planilha Google dentro do seu construtor de fluxo.

### Enviar dados para o Planilhas Google

Depois de coletar todas as informações, podemos usar a ação do Planilhas Google **Enviar dados** .

Escolha a ação (Enviar dados para o Google Sheets) e selecione o nome da planilha para a qual deseja exportar os dados. A próxima etapa é selecionar a planilha.

Agora combine os dados do bot Simplsdesk que você coletou com os títulos das colunas do Google. Você pode selecionar qualquer um dos campos personalizados, dados de assinantes ou dados de bot. Está tudo disponível para você exportar.

<figure><img src="../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

Depois que o assinante tiver passado pelo seu fluxo e você usar a ação **Enviar dados** do Google Sheets no final desse fluxo, todos os dados deverão ter sido exportados assim

<figure><img src="../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

Muito fácil e simples de fazer, certo?

### Obter linha (valor)

Em vez de exportar dados para uma Planilha Google, também podemos fazer o contrário.&#x20;

Obter dados de uma planilha do Google e exibir essas informações no bot/conversa para o assinante ver.

Digamos que seu cliente tenha um food truck e mude de local algumas vezes por semana. Ele deseja poder fornecer sua localização atual aos clientes quando eles solicitarem a localização.&#x20;

Em vez de ter que atualizar o bot todas as vezes, você pode simplesmente deixar seu cliente atualizar sua planilha do Google.

Cada vez que ele muda de local, ele apenas atualiza isso na Planilha Google e o bot do Messenger buscará o local mais recente.

Para poder fazer isso você precisa criar dois campo de informação(Variável do botfield) . Um campo de informação(Variável do botfiel) é usado como valor de pesquisa dentro da planilha, enquanto o outro armazenará a localização daquele food truck.&#x20;

Neste caso, criaremos:

* Localização atual
* Endereço atual

O campo de bot Localização Atual precisará ter o mesmo valor na coluna com o mesmo nome em sua Planilha Google. Portanto, neste caso damos o mesmo valor do campo de informação(Variável do botfield) “ **Localização Atual** “

Depois de criar isso, crie sua planilha Google com os mesmos títulos e preencha as informações. Deveria ficar assim;

<figure><img src="../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

Então, tudo o que você precisa fazer dentro do seu construtor de fluxo é ir para > **Planilhas Google** > **Obter linha** > **Selecionar planilha** > **Folha de Calculo** > **Selecionar coluna de pesquisa** > **Mapear dados de planilhas para o bot do Messenger** .

A coluna de pesquisa será o local atual, pois esse valor permanece constante. Então você escolhe essas colunas e define a pesquisa como deve ser igual a. Aqui você insere seu campo de informação(Variável do botfield) **Current Location** (Local Atualizado).

Como fizemos abaixo:

<figure><img src="../.gitbook/assets/image (74).png" alt="" width="563"><figcaption></figcaption></figure>

Agora seu cliente tem a localização mais recente de seu food truck dentro do bot do Messenger sem tocá-lo. A solução perfeita!

### Obtendo linha aleatória

Semelhante à obtenção de dados de linha, também podemos obter uma linha aleatória que nos é apresentada. Isso é ótimo para gerar combinações dinâmicas.

Um exemplo poderia ser a criação de um bot do Messenger para fornecer nomes de meninos e meninas para bebês.

Teremos uma Planilha Google com 3 colunas:

* Pesquisa de valor
* Nomes de meninas
* Nomes de meninos

Parece assim;

<figure><img src="../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

Então, para que isso funcione, pediremos ao assinante que escolha se gostaria de ouvir o nome de um menino ou de uma menina. Usaremos um bloco de entrada do usuário para isso, para que possamos armazenar o valor em um campo personalizado. Isso nos permitirá escolher um nome aleatório na coluna dos meninos ou nas meninas.

A próxima etapa é determinar o valor de pesquisa. Para isso, utilizaremos a coluna **Lookup Value** . como queremos gerar uma resposta/valor aleatório, agora precisaremos fornecer um intervalo para pesquisar na planilha.

Isso será parecido com isto;

<figure><img src="../.gitbook/assets/image (76).png" alt="" width="563"><figcaption></figcaption></figure>

A partir daqui, a resposta é salva no campo personalizado do assinante e você pode exibi-la diretamente na conversa.

### Atualizar linha do Planilhas Google

Outra ótima ação com a integração do Google Sheets é a capacidade de atualizar uma linha se você já tiver valores armazenados. Digamos que você queira fornecer uma lista de assinantes para seu cliente como uma maneira fácil de ele ter uma boa visão geral de seus assinantes.

Portanto, para novos assinantes, você teria exportado alguns dados como Nome, UserId.

Agora, quando eles optam por um leadmagnet, programa de fidelidade, você pode querer capturar seu e-mail e/ou número de telefone também. Em vez de criar uma nova linha com essas informações, você pode simplesmente atualizar aquela que já possui para aquele assinante.

Então, vamos dar uma olhada nos dados do assinante com informações básicas

<figure><img src="../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

Como você pode ver, atualmente só temos o nome e o ID do usuário. O ID do usuário é importante porque será o seu valor de pesquisa quando quiser atualizar os dados do assinante. Esta é a coluna que nunca mudará, pois o ID do usuário é exclusivo desse assinante.

Assim, depois de capturar os dados adicionais do assinante, como número de telefone e e-mail, podemos selecionar a ação do Google Sheets **Atualizar Linha.**

<figure><img src="../.gitbook/assets/image (79).png" alt="" width="542"><figcaption></figcaption></figure>

Dessa forma, você sempre terá sua Planilha Google atualizada com as informações mais recentes coletadas do seu bot.

Ele irá preencher ou atualizar as informações que não existiam antes.

<figure><img src="../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

### Limpar linha na planilha do Google

Assim como a linha de atualização, também podemos limpar uma linha no Google Sheets. É praticamente o mesmo processo. Por exemplo, se você deseja excluir da sua planilha assinantes que cancelaram a assinatura do seu bot na conversa.

Você escolhe a ação **Planilhas Google** -> **Limpar linha** . O mesmo princípio se aplica. Você seleciona sua planilha e sua planilha. Em seguida, escolha sua coluna de pesquisa. Neste caso, como mencionado anteriormente, esse será o ID do usuário, pois este permanece constante.

<figure><img src="../.gitbook/assets/image (81).png" alt="" width="563"><figcaption></figcaption></figure>

### Crie galerias dinâmicas

Este recurso foi atualizado e simplificado, ao mesmo tempo que fornece recursos muito mais poderosos.&#x20;

### Conclusão

A integração da Simplesdeske com o Google Sheets ajuda você de várias maneiras a automatizar a exportação e importação de seus dados de e para o Google Sheets. Oferece muita flexibilidade e mais recursos são adicionados regularmente.

Se isso acontecer esta documentação será atualizada para ajudá-lo a entender os novos recursos, para que você possa implementá-los facilmente.

Se você tiver alguma dúvida, informe-nos dentro do WhatsApp do Suporte para que possamos ajudá-lo com qualquer problema que possa ter.

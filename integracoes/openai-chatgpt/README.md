---
description: Melhore o atendimento ao cliente com OpenAI ChatGPT
---

# 🧠 OpenAI ChatGPT

_Tempo estimado de leitura: 1 min_ :hourglass\_flowing\_sand:

Simplesdesk integrou-se ao ChatGPT para permitir que as empresas melhorem o atendimento ao cliente e, ao mesmo tempo, economizem drasticamente custos e recursos humanos.

As empresas podem treinar o ChatGPT para responder a quaisquer perguntas dos clientes relacionadas aos seus negócios. Um chatbot permite que as empresas respondam instantaneamente aos seus clientes, 24 horas por dia, resultando em maior satisfação do cliente. Além disso, é uma solução económica, reduzindo a necessidade de recursos humanos adicionais nas operações de apoio ao cliente.

A chave para criar um chatbot excelente para o seu negócio é criar um bom prompt (Informações Comerciais). O cérebro do seu chatbot é o seu prompt. Sua solicitação deve ser clara e bem escrita.

## Conecte OpenAI a Simplesdesk

#### **1. Obtenha sua chave API OpenAI** [**AQUI**](https://openai.com/api/) **.**

Clique em Log in em seguida > **API Platform**

<figure><img src="../../.gitbook/assets/WhatsApp Image 2025-05-19 at 11.32.00.jpeg" alt=""><figcaption></figcaption></figure>

Caso você ainda não tenha uma conta na OpenAI clique em **Sign up (Cadastrar)**

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### **1.2. Verifique sua** conta

Após a inscrição, você receberá um e-mail da OpenAI para confirmar sua conta. Abra este e-mail e clique no link de verificação. Esta etapa ajuda a garantir a segurança da sua conta.

#### **1.3. Faça login na sua** conta

Agora que sua conta foi verificada, volte ao site da OpenAI e clique no botão “Log In”. Digite o nome de usuário e a senha que você usou para se inscrever.

#### **1.4. Navegue até a seção API**

**‍ Após** fazer login, no canto superior direito da tela você verá um ícone com o nome da sua conta ao Lado uma Engrenagem (Configurações/ Settings). Clique nele para abrir o menu suspenso de Configurações no lado esquerdo. ([https://platform.openai.com/settings/organization/api-keys](https://platform.openai.com/settings/organization/api-keys))

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

**1.5. Gere uma nova chave API**

**‍ Agora que** você está na seção de chaves de API, deverá ver um botão "Criar nova chave secreta". Clique nesse botão para gerar uma nova chave de API.

<figure><img src="../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

Uma caixa aparecerá solicitando que você nomeie sua chave secreta de API. É uma boa ideia ter chaves diferentes para aplicativos e sites diferentes, portanto, certifique-se de nomeá-lo com algo que você lembrará para que serve quando olhar para ele um dia no futuro.

Depois de inserir um nome para sua chave, clique no botão “Criar chave secreta”.

<figure><img src="../../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

#### **1.6. Salve sua chave API**

A seguir, você verá sua chave secreta que foi gerada. Certifique-se de copiar sua chave secreta e colá-la em qualquer aplicativo necessário.

É muito importante que você copie esta chave e salve-a em algum lugar seguro, pois não será possível recuperá-la novamente por motivos de segurança. Você precisará dessa chave para autenticar seus aplicativos com os serviços da OpenAI.

<figure><img src="../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

#### **1.7. Configure o faturamento**

A OpenAI cobra pelo uso de sua API com base no uso, portanto, se você ainda não configurou um método de pagamento para faturamento, precisará fazê-lo. Caso contrário, a chave API que você acabou de criar não funcionará.

Para configurar o faturamento, clique em Faturamento no menu esquerdo e clique em Métodos de pagamento. Vá em **Settings > Billing > Payment methods**

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

A seguir, você verá a tela de formas de pagamento. Clique em Adicionar forma de pagamento.

<figure><img src="../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

Uma caixa aparecerá onde você poderá inserir seu cartão de crédito e detalhes de cobrança. Clique em Enviar depois de inserir suas informações.

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

#### **1.8. Defina limites de uso**

Agora que você configurou o faturamento, faz sentido definir limites de uso para que você possa controlar quanto gasta por mês na API.

Basta clicar em Limites de uso no menu esquerdo e inserir os valores dos limites de uso rígidos e flexíveis. Em seguida, clique em Salvar.

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

#### **1.9. Certifique-se de seguir** as diretrizes

Como observação final, certifique-se de se familiarizar com a política de casos de uso e os termos de uso da OpenAI. Estas regras ajudam a garantir que a tecnologia seja utilizada de forma responsável.

E aí está! Você está pronto para começar a usar os poderosos serviços de aprendizado de máquina da OpenAI. Lembre-se de manter sua chave de API segura.

### 2. **Vá em Simplesdesk > Configurações > Integrações > OpenAI**

<figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

### 3. Clique no botão **Conectar** e forneça sua **API KEY** .

<figure><img src="../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

## **Acionando um fluxo**

Para saber como acionar um fluxo usando IA, consulte Gatilhos de IA .

## **Transferir uma conversa para um humano**

Implementamos um gatilho de IA integrado que interrompe automaticamente a automação do bot e transfere uma conversa para um humano quando o usuário deseja falar com um agente humano.

## **Prioridade da automação (Hierarquia da plataforma)**

Depois de conectar o Google Gemini a Simplesdesk, seu chatbot se comunicará automaticamente usando IA sempre que um usuário enviar uma mensagem para seu chatbot. Nenhuma ação é necessária de sua parte.

E a plataforma Simplesdesk respeitará sua hierarquia, priorizando sempre as configurações na seguinte ordem:

1 – Respostas Automatizadas.\
2 – Fluxo de diálogo\
3 – OpenAI\
4 – Google Gemini

**Desativar o acionamento automático do ChatGPT**

Cada vez que um usuário envia uma mensagem ao seu chatbot, ele usará automaticamente o ChatGPT para responder à mensagem do usuário. Talvez você queira trabalhar apenas com ações OpenAI no construtor de fluxo. Você pode desabilitar esse comportamento acessando **Configurações** -> **Integrações** -> **OpenAI** e desabilitando a opção **Automatizar Respostas** .

Azul claro está ativado

<figure><img src="../../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

Cinza claro estará desativado

<figure><img src="../../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

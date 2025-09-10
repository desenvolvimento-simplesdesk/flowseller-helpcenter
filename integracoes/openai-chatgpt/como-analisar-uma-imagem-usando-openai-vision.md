# Como analisar uma imagem usando OpenAI Vision

### Visão geral <a href="#block-d7d234b5-ef02-4987-b1a1-3496c8f3d1f0" id="block-d7d234b5-ef02-4987-b1a1-3496c8f3d1f0"></a>

Nesta documentação, você aprenderá como usar o OpenAI Vision para analisar imagens. Este recurso permite que as empresas obtenham insights a partir de imagens enviadas ao seu chatbot.

### Detalhes principais <a href="#block-5bbaa0fb-6d96-4127-b060-56806c28ceaa" id="block-5bbaa0fb-6d96-4127-b060-56806c28ceaa"></a>

* **Conecte OpenAI na seção Integração (Configurações >> Integração >> OpenAI ChatGPT)**
* **Em seu fluxo, colete a imagem do seu usuário e analise-a com OpenAI Vision usando a ação OpenAI.**

### Como configurar <a href="#block-86dd861b-9d0e-4a33-a1e0-6ec35adad726" id="block-86dd861b-9d0e-4a33-a1e0-6ec35adad726"></a>

1. **Conecte a integração OpenAI se ainda não a conectou. Por favor, leia esta** [**documentação**](./)
2. **Crie um fluxo onde você coletará imagens do seu usuário (usando Obter Dados do Usuário)**

<figure><img src="../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

**Analise a imagem com OpenAI Vision.**

<figure><img src="../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

É recomendável incluir uma instrução condicional em seu fluxo para verificar se a resposta OpenAI tem algum valor após usar a ação OpenAI para gerar dados. Isso permitirá que você determine se a ação OpenAI foi executada com sucesso.

<figure><img src="../../.gitbook/assets/image (6) (1).png" alt=""><figcaption></figcaption></figure>

**Caso de uso avançado**

**Este recurso poderoso permite que você analise uma imagem enviada aleatoriamente ao seu chatbot, independentemente de você estar usando seu próprio fluxo de resposta padrão personalizado ou se o OpenAI ChatGPT lida com sua resposta padrão.**

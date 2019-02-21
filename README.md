<h1>Treino de Tweepy</h1>

Eu uso o GitHub para armazenar os códigos de projetos que eu faço. Nesse repositório você encontra exercícios que eu já fiz para treinar raspagem de dados usando a API do Twitter.

Para acessar a API, usei minhas credenciais em um arquivo separado que não subi para o repositório. Para definir as credenciais, rode o seguinte o código antes:

<pre><code>import json<br>
twitter_credentials = {}<br>
twitter_credentials['consumer_key'] = 'DIGITE AQUI SEU CONSUMER KEY'<br>
twitter_credentials['consumer_secret'] = 'DIGITE AQUI SEU CONSUMER SECRET'<br>
twitter_credentials['access_token'] = 'DIGITE AQUI SEU ACCESS TOKEN'<br>
twitter_credentials['access_token_secret'] = 'DIGITE AQUI SEU ACCESS TOKEN SECRET'<br>
with open('credenciais_twitter.json', 'w') as secret_info:<br>
  json.dump(twitter_credentials, secret_info, indent=4, sort_keys=True)<br></code></pre>
  
Para iniciar o Notebook com data rate expandido:
<code>jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000000</code>

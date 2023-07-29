

# Mel - Chatbot 

<br>

<p align = "center" id = "project">
<h2>
  ⚡ 🤖  - 
</h2>
</p>

<br>
<h2 id = "techs">
  
  🚀  Tecnologias
  
</h2>

- Python (Version: 3.10) ;

- Rasa open source machine learning framework (Version: 3.8);

- Docker;


## 🛠 Funcionamento e instalação 

- Para funcionar e rodar a Iago é só seguir o passo a passo:

1 - Realizar a instalação do Docker no site oficial:

```sh

https://www.docker.com/ 

```
<br>

Logo em seguida starta o docker na sua máquina;

<br>

2 - Realizar o clone do projeto realizando nesse comando:

```sh

git clone -b 


```

3 - Entrar no diretório do projeto pelo terminal e buildar o shell script com esse comando:

```sh

sh build.sh

```

Todas as instalações de programas e dependências serão instalados no Docker.

<br>



<br>


# Rasa Server API

## curl localhost:5005/model/parse -s -d '{"text":"oi"}'
```
/conversations/<conversation_id>/messages          POST                           add_message
/conversations/<conversation_id>/tracker/events    POST                           append_events
/webhooks/rest                                     GET                            custom_webhook_RestInput.health
/webhooks/rest/webhook                             POST                           custom_webhook_RestInput.receive
/model/test/intents                                POST                           evaluate_intents
/model/test/stories                                POST                           evaluate_stories
/conversations/<conversation_id>/execute           POST                           execute_action
/domain                                            GET                            get_domain
/                                                  GET                            hello
/model                                             PUT                            load_model
/model/parse                                       POST                           parse
/conversations/<conversation_id>/predict           POST                           predict
/conversations/<conversation_id>/tracker/events    PUT                            replace_events
/conversations/<conversation_id>/story             GET                            retrieve_story
/conversations/<conversation_id>/tracker           GET                            retrieve_tracker
/status                                            GET                            status
/model/predict                                     POST                           tracker_predict
/model/train                                       POST                           train
/conversations/<conversation_id>/trigger_intent    POST                           trigger_intent
/model                                             DELETE                         unload_model
/version
```
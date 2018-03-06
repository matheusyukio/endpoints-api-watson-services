# endpoints-api-watson-services
## Language services
### NLU
#### https://gateway.watsonplatform.net/natural-language-understanding/api/v1/
##### 3
##### Analyze
POST | GET /analyze
features: concepts, categories, emotion, entities, keywords, metadata, relations, semantic_roles, sentiment   
##### Manage models
##### Custom Model from WKS
List Models
GET /models<br>
##### Delete a Custom Model
DELETE /models/{model_id}

### NLC
#### https://gateway.watsonplatform.net/natural-language-classifier/api
##### 5
##### Classify
POST /v1/classifiers/{classifier_id}/classify
##### Create classifier
POST /v1/classifiers
##### Delete classifier
DELETE /v1/classifiers/{classifier_id}
##### Get information about a classifier
GET /v1/classifiers/{classifier_id}
##### List classifiers
GET /v1/classifiers

### Conversation

### Language Translator
#### https://gateway.watsonplatform.net/language-translator/api
##### 7
##### Translate
POST /v2/translate
GET /v2/translate
##### Identifiable languages
GET /v2/identifiable_languages
##### Identify language
GET /v2/identify
POST /v2/identify
##### List models
GET /v2/models
##### Create model
POST /v2/models
##### Delete model
DELETE /v2/models/{model_id}
##### Get model details
GET /v2/models/{model_id}

### Personality Insights
#### https://gateway.watsonplatform.net/personality-insights/api
##### 1
##### Get profile
POST /v2/profile

### Tone Analyzer
#### https://gateway.watsonplatform.net/tone-analyzer/api/v3
##### 2
##### Analyze general tone
GET /v3/tone
POST /v3/tone
##### Analyze customer engagement tone
POST /v3/tone_chat

## Speech services
### Speech to Text
#### HTTP API Endpoint https://stream.watsonplatform.net/speech-to-text/api
#### WebSocket API Endpoint wss://stream.watsonplatform.net/speech-to-text/api
##### 44
##### Get models
##### Get a model
#### WebSockets
##### Recognize audio
#### Sessionless
##### Recognize audio
##### Recognize multipart
#### Sessions
##### Create a session
##### Get status
##### Observe result
##### Recognize audio
##### Recognize multipart
##### Delete a session
#### Asynchronous
##### Register a callback
##### Unregister a callback
##### Create a job
##### Check jobs
##### Check a job
##### Delete a job
#### Custom language models
##### Create a custom language model
##### List custom language models
##### List a custom language model
##### Train a custom language model
##### Reset a custom language model
##### Upgrade a custom language model
##### Delete a custom language model
#### Custom corpora
##### Add a corpus
##### List corpora
##### List a corpus
##### Delete a corpus
#### Custom words
##### Add custom words
##### Add a custom word
##### List custom words
##### List a custom word
##### Delete a custom word
#### Custom acoustic models
##### Create a custom acoustic model
##### List custom acoustic models
##### List a custom acoustic model
##### Train a custom acoustic model
##### Reset a custom acoustic model
##### Upgrade a custom acoustic model
##### Delete a custom acoustic model
#### Custom audio resources
##### Add an audio resource
##### List audio resources
##### List an audio resource
##### Delete an audio resource

### Text to Speech
#### HTTP API Endpoint https://stream.watsonplatform.net/text-to-speech/api
#### WebSocket API Endpoint wss://stream.watsonplatform.net/text-to-speech/api
##### 15
##### Get voices
GET /v1/voices
##### Get a voice
GET /v1/voices/{voice}
##### Synthesize audio
GET /v1/synthesize
POST /v1/synthesize
##### Get pronunciation
GET /v1/pronunciation
##### Create a custom model
POST /v1/customizations
##### Update a custom model
POST /v1/customizations/{customization_id}
##### List custom models
GET /v1/customizations
##### List a custom model
GET /v1/customizations/{customization_id}
##### Delete a custom model
DELETE /v1/customizations/{customization_id}
##### Add custom words
POST /v1/customizations/{customization_id}/words
##### Add a custom word
PUT /v1/customizations/{customization_id}/words/{word}
##### List custom words
GET /v1/customizations/{customization_id}/words
##### List a custom word
GET /v1/customizations/{customization_id}/words/{word}
##### Delete a custom word
DELETE /v1/customizations/{customization_id}/words/{word}

## Data Insights services
### Discovery

### Discovery News

## Vision services
### Visual Recognition
#### https://gateway-a.watsonplatform.net/visual-recognition/api
##### 7
##### Classify images
GET /v3/classify
POST /v3/classify
##### Detect faces
GET /v3/detect_faces
POST /v3/detect_faces
##### Create a classifier
POST /v3/classifiers
##### Retrieve a list of custom classifiers
GET /v3/classifiers
##### Retrieve classifier details
GET /v3/classifiers/{classifier_id}
##### Update a classifier
POST /v3/classifiers/{classifier_id}
##### Delete a classifier
DELETE /v3/classifiers/{classifier_id}

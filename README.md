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

### Text to Speech

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

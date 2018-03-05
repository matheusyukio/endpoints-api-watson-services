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

### Tone Analyzer

## Speech services
### Speech to Text

### Text to Speech

## Data Insights services
### Discovery

### Discovery News

## Vision services
### Visual Recognition

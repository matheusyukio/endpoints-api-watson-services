# endpoints-api-watson-services
## Language services
### NLU
#### https://gateway.watsonplatform.net/natural-language-understanding/api/v1/
##### Analyze
POST | GET /analyze
features: concepts, categories, emotion, entities, keywords, metadata, relations, semantic_roles, sentiment   
##### Manage models
Custom Model from WKS
List Models: GET /models<br>
Delete a Custom Model: DELETE /models/{model_id}

### NLC
#### https://gateway.watsonplatform.net/natural-language-classifier/api
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

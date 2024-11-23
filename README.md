# Erste Definition of Done vom 23.11.2024
- Feature-Branch wurde mittels Pull Request symbolisch auf dev gemerged via semi-linear Merge. 
- dev und release sind noch nicht vonnöten.
- Grundlegender kurzer Funktionstest erfolgte auf der Produktionsumgebung.

Die folgenden Aspekte will ich in meinem Showcase perspektivisch umsetzen.

API
- Authentification with OAuth oder Bearer
- Caching mit nem Redis
- Python Backend für Statistiken
- Prometheus und Graphana
- API Versioning
- Rate Limiting
- Statuscodes
- Fehlerbehandlung
- Sicherheit via TLS, CORS, Input Validation
- Swagger
- Automatisierte Postman Tests
- Logging: Protokollierung aller API-Anfragen und -Antworten, um Fehler besser nachverfolgen zu können.
- Deployment mittels Docker in n K8 Cluster auf GCP oder AWS
- Serverless?
- Rest, GraphQL, GRPC, EDA
- Healthchecks
- Factories zum Erstellen von DTOs damit man Dependency Injection besitzt

Pagination
- 

Application Insights, alternativ Datadog oder so was, ggf. auch ELK Stack: Elasticsearch + Logstash + Kibana und ggf. Opentelemetry


Architektur:
- Mappers, wenn man bspw. eine Bewerbung reingibt, will man die auch zu ner ChatNachricht konvertieren können fürs create / bzw. eine Factory

- Issues von Github

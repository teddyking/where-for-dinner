# Accelerator Log

## Options
```json
{
  "cacheName" : "cache-where-for-dinner",
  "cacheType" : "redisCache",
  "dbName" : "db-where-for-dinner",
  "dbType" : "mysql",
  "dynamicCache" : true,
  "dynamicCacheClass" : "redis-unmanaged",
  "dynamicDBClass" : "mysql-unmanaged",
  "dynamicDatabase" : true,
  "dynamicMsgBroker" : true,
  "dynamicMsgBrokerClass" : "msgbroker-crossplane-where-for-dinner",
  "enableCloudEvents" : false,
  "enableSecurity" : false,
  "includeBuildToolWrapper" : true,
  "msgBrokerType" : "rabbitmq",
  "msgbrokerName" : "msgbroker-where-for-dinner",
  "numRabbitMQClusterNodes" : 1,
  "projectName" : "where-for-dinner",
  "serviceNamespace" : "service-instances",
  "workloadNamespace" : "my-apps"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ engine.transformations[0].validated.delegate (Let)
┃ ┃ ┃ Debug Adding symbol secureProfile with value 'secure'
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, InvokeFragment, Combo, Provenance)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Exclude
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[0].delegate (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [**/templates/**, **/icons/**, **/.git/**, **/deployment/**]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/templates/workloads.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml matched [**/templates/workloads.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"dynamicMsgBrokerClass":"msgbroker-crossplane-where-for-dinner","dynamicCacheClass":"redis-unmanaged","artifactVersion":"0.0.1-beta","dbName":"db-where-for-dinner","dynamicMsgBroker":true,"dbType":"mysql","enableCloudEvents":false,"enableSecurity":false,"cacheName":"cache-where-for-dinner","includeBuildToolWrapper":true,"dynamicCache":true,"msgbrokerName":"msgbroker-where-for-dinner","numRabbitMQClusterNodes":1,"dynamicDBClass":"mysql-unmanaged","secureProfile":"secure","artifactId":"where-for-dinner","dynamicDatabase":true,"serviceNamespace":"service-instances","msgBrokerType":"rabbitmq","projectName":"where-for-dinner","workloadNamespace":"my-apps","cacheType":"redisCache"}
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input13942725357033769048, --data-values-file, /tmp/accelerator-options16443447177095928624.json, --output-files, /tmp/ytt-output18338837638261466568]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'templates/workloads.yaml' matched 'templates/workloads.yaml' with groups {g0=templates/workloads.yaml} and was rewritten to 'config/developer/workloads.yaml'
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[3] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[3].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Condition (#bsGitRepository != null) evaluated to false
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#msgBrokerType == 'rabbitmq' && !#dynamicMsgBroker) evaluated to false
┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#msgBrokerType == 'rabbitmq' && #dynamicMsgBroker) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/dyanmicRabbitMQCluster.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml matched [**/dyanmicRabbitMQCluster.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [**/dyanmicRabbitMQCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[3].delegate.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/dyanmicRabbitMQCluster.yaml' matched 'templates/dyanmicRabbitMQCluster.yaml' with groups {g0=templates/dyanmicRabbitMQCluster.yaml} and was rewritten to 'config/service-operator/dyanmicRabbitMQCluster.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#dbType == 'mysql' && !#dynamicDatabase) evaluated to false
┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#dbType == 'mysql' && #dynamicDatabase) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[5].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[5].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/dynamicMySqlInstance.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml matched [**/dynamicMySqlInstance.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [**/dynamicMySqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[5].delegate.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/dynamicMySqlInstance.yaml' matched 'templates/dynamicMySqlInstance.yaml' with groups {g0=templates/dynamicMySqlInstance.yaml} and was rewritten to 'config/service-operator/dynamicMySqlInstance.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#msgBrokerType == 'rabbitmq') evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[6].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[6].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/rmqResourceClaim.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml matched [**/rmqResourceClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[6].delegate.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"dynamicMsgBrokerClass":"msgbroker-crossplane-where-for-dinner","dynamicCacheClass":"redis-unmanaged","artifactVersion":"0.0.1-beta","dbName":"db-where-for-dinner","dynamicMsgBroker":true,"dbType":"mysql","enableCloudEvents":false,"enableSecurity":false,"cacheName":"cache-where-for-dinner","includeBuildToolWrapper":true,"dynamicCache":true,"msgbrokerName":"msgbroker-where-for-dinner","numRabbitMQClusterNodes":1,"dynamicDBClass":"mysql-unmanaged","secureProfile":"secure","artifactId":"where-for-dinner","dynamicDatabase":true,"serviceNamespace":"service-instances","msgBrokerType":"rabbitmq","projectName":"where-for-dinner","workloadNamespace":"my-apps","cacheType":"redisCache"}
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input8766162614498597215, --data-values-file, /tmp/accelerator-options8427934071696770268.json, --output-files, /tmp/ytt-output5977845591901462014]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[6].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/rmqResourceClaim.yaml' matched 'templates/rmqResourceClaim.yaml' with groups {g0=templates/rmqResourceClaim.yaml} and was rewritten to 'config/app-operator/rmqResourceClaim.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[7] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#dbType == 'mysql') evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[7].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[7].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/mysqlResourceClaim.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml matched [**/mysqlResourceClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[7].delegate.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"dynamicMsgBrokerClass":"msgbroker-crossplane-where-for-dinner","dynamicCacheClass":"redis-unmanaged","artifactVersion":"0.0.1-beta","dbName":"db-where-for-dinner","dynamicMsgBroker":true,"dbType":"mysql","enableCloudEvents":false,"enableSecurity":false,"cacheName":"cache-where-for-dinner","includeBuildToolWrapper":true,"dynamicCache":true,"msgbrokerName":"msgbroker-where-for-dinner","numRabbitMQClusterNodes":1,"dynamicDBClass":"mysql-unmanaged","secureProfile":"secure","artifactId":"where-for-dinner","dynamicDatabase":true,"serviceNamespace":"service-instances","msgBrokerType":"rabbitmq","projectName":"where-for-dinner","workloadNamespace":"my-apps","cacheType":"redisCache"}
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input8842678976883248792, --data-values-file, /tmp/accelerator-options8137939525038756524.json, --output-files, /tmp/ytt-output106535758529879236]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[7].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/mysqlResourceClaim.yaml' matched 'templates/mysqlResourceClaim.yaml' with groups {g0=templates/mysqlResourceClaim.yaml} and was rewritten to 'config/app-operator/mysqlResourceClaim.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[8] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#enableCloudEvents) evaluated to false
┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[9] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#enableSecurity) evaluated to false
┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[10] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#enableSecurity) evaluated to false
┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[11] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#cacheType == 'redisCache' && !#dynamicCache) evaluated to false
┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[12] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#cacheType == 'redisCache' && #dynamicCache) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[12].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[12].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/dynamicRedisInstance.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml matched [**/dynamicRedisInstance.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [**/dynamicRedisInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[12].delegate.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"dynamicMsgBrokerClass":"msgbroker-crossplane-where-for-dinner","dynamicCacheClass":"redis-unmanaged","artifactVersion":"0.0.1-beta","dbName":"db-where-for-dinner","dynamicMsgBroker":true,"dbType":"mysql","enableCloudEvents":false,"enableSecurity":false,"cacheName":"cache-where-for-dinner","includeBuildToolWrapper":true,"dynamicCache":true,"msgbrokerName":"msgbroker-where-for-dinner","numRabbitMQClusterNodes":1,"dynamicDBClass":"mysql-unmanaged","secureProfile":"secure","artifactId":"where-for-dinner","dynamicDatabase":true,"serviceNamespace":"service-instances","msgBrokerType":"rabbitmq","projectName":"where-for-dinner","workloadNamespace":"my-apps","cacheType":"redisCache"}
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input17483610973109830592, --data-values-file, /tmp/accelerator-options12010060029275654865.json, --output-files, /tmp/ytt-output10283988767231307368]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[12].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/dynamicRedisInstance.yaml' matched 'templates/dynamicRedisInstance.yaml' with groups {g0=templates/dynamicRedisInstance.yaml} and was rewritten to 'config/service-operator/dynamicRedisInstance.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[13] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#cacheType == 'redisCache') evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[13].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[13].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/redisResourceClaim.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml matched [**/redisResourceClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [**/redisResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[13].delegate.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"dynamicMsgBrokerClass":"msgbroker-crossplane-where-for-dinner","dynamicCacheClass":"redis-unmanaged","artifactVersion":"0.0.1-beta","dbName":"db-where-for-dinner","dynamicMsgBroker":true,"dbType":"mysql","enableCloudEvents":false,"enableSecurity":false,"cacheName":"cache-where-for-dinner","includeBuildToolWrapper":true,"dynamicCache":true,"msgbrokerName":"msgbroker-where-for-dinner","numRabbitMQClusterNodes":1,"dynamicDBClass":"mysql-unmanaged","secureProfile":"secure","artifactId":"where-for-dinner","dynamicDatabase":true,"serviceNamespace":"service-instances","msgBrokerType":"rabbitmq","projectName":"where-for-dinner","workloadNamespace":"my-apps","cacheType":"redisCache"}
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input15396068631479323514, --data-values-file, /tmp/accelerator-options8622843316014620947.json, --output-files, /tmp/ytt-output6282672964001543730]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[13].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/redisResourceClaim.yaml' matched 'templates/redisResourceClaim.yaml' with groups {g0=templates/redisResourceClaim.yaml} and was rewritten to 'config/app-operator/redisResourceClaim.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[14] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[14].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[14].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[14].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[14].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[14].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/setupTests.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[0].sources[14].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[15] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[15].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-api-gateway/where-for-dinner-api-gateway.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-availability/where-for-dinner-availability.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-notify/where-for-dinner-notify.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search/where-for-dinner-search.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-search-proc/where-for-dinner-search-proc.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/where-for-dinner-ui/where-for-dinner-ui.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/where-for-dinner-db-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/where-for-dinner-messaging-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/where-for-dinner-system.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/DynamicServiceProvisioning.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/DinnerHighLevelArch.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KnativeEventing.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/where-for-dinner.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dyanmicRabbitMQCluster.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicMySqlInstance.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/dynamicRedisInstance.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/knEventing.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisInstance.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/redisResourceClaim.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/java/com/java/example/tanzu/wherefordinner/DinnerAPIGatewayApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-api-gateway/src/main/resources/application.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/Availability.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/entity/AvailabilityWindow.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/function/AvailabilitySink.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityRepository.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/repository/AvailabilityWindowRepository.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/java/com/java/example/tanzu/wherefordinner/resources/AvailabilityResource.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/META-INF/spring.factories didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/application.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-h2.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-mysql.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/main/resources/schema-postgresql.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-availability/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerAvailabilityApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/LocalRandomSearcher.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-crawler/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerCrawlerApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/EmailMessageConfigProperties.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/config/PublisherConfiguration.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/functions/AvailabilitySink.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/EmailPublisher.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/LoggerPublisher.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/java/com/java/example/tanzu/wherefordinner/publisher/Publisher.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-notify/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerNotifyApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/OAuth2BindingsPropertiesProcessor.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/config/WebSecurityConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/entity/Search.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/functions/SearchSupplier.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/repository/SearchRepository.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/java/com/java/example/tanzu/wherefordinner/resources/SearchResource.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/META-INF/spring.factories didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-h2.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-mysql.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/main/resources/schema-postgresql.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/SpringBaseTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerResApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/java/com/java/example/tanzu/wherefordinner/repository/SearchRepositoryTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search/src/test/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/DeclarativeClientConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/config/StaticDiningAvailability.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/exchange/CrawlerClient.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/functions/Search.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/Availability.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/model/SearchCriteria.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/SearchProcessor.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/HashCache.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/MemoryHashCache.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/processor/cache/RedisHashCache.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/Searcher.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/CrawlerSearcher.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/java/com/java/example/tanzu/wherefordinner/searcher/impl/LocalRandomSearcher.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-search-proc/src/test/java/com/java/example/tanzu/wherefordinner/WhereForDinnerSearchProcApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.env didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/httpproxy.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/nginx.conf didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package-lock.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/package.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/favicon.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/manifest.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/public/robots.txt didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/App.test.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/Availability.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningNames.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearch.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningSearches.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/DiningTypes.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/SearchDefForm.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/TimeWindow.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/images/delete.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/index.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/logo.svg didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-for-dinner-ui/src/reportWebVitals.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug where-for-dinner-ui/src/setupTests.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[0].sources[16] (Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1] (UniquePath)
┃ ┗ ┗ ┗ ┗ Debug Multiple representations for path 'README.md', will use the one appearing last 
┗ ╺ engine.transformations[1] (UniquePath)
```

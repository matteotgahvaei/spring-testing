# Spring Testing sample project

Here we are exploring the different possibilities offered by some test frameworks.
PLEASE NOTE: There is no complete test coverage, this is the purpose of this sample project.

## topics
* spring boot
* spring boot test
* testing
	* unit tests
	* integration tests
	* contract tests
* spring testing
* mockito
* assertj
* spring cloud contract

---

## Related repos

* [spring-testing-contracts-stubs](https://github.com/bygui86/spring-testing-contracts-stubs)

---

## links
[DONE]
* theory
	* https://www.martinfowler.com/articles/mocksArentStubs.html
* tests separation
	* https://www.testwithspring.com/lesson/running-integration-tests-with-maven/
* unit/integration testing
	* https://www.baeldung.com/spring-boot-testing
	* https://www.baeldung.com/injecting-mocks-in-spring
	* https://www.baeldung.com/spring-boot-testresttemplate
	* spring @restclienttest
		* https://www.baeldung.com/restclienttest-in-spring-boot
		* https://objectpartners.com/2013/01/09/rest-client-testing-with-mockrestserviceserver/
		* https://www.dontpanicblog.co.uk/2016/07/16/resttemplatebuilder-and-restclienttest-in-spring-boot-1-4-0/
		* https://examples.javacodegeeks.com/enterprise-java/spring/using-mockrestserviceserver-test-rest-client/
	* feign client
		* https://stackoverflow.com/questions/34397570/mock-an-eureka-feign-client-for-unittesting
		* https://www.blazemeter.com/blog/Rest-API-testing-with-Spring-Cloud-Feign-Clients
	* https://www.baeldung.com/integration-testing-in-spring
	* https://www.baeldung.com/spring-webappconfiguration
	* https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-testing.html
* contract testing
	* https://martinfowler.com/articles/consumerDrivenContracts.html
	* https://www.baeldung.com/spring-cloud-contract
	* https://cloud.spring.io/spring-cloud-contract/
	* https://spring.io/guides/gs/contract-rest
	* https://cloud.spring.io/spring-cloud-contract/single/spring-cloud-contract.html
	* multiple base classes
		* https://cloud.spring.io/spring-cloud-contract/single/spring-cloud-contract.html#maven-different-base
	* dsl
		* https://cloud.spring.io/spring-cloud-contract/single/spring-cloud-contract.html#contract-dsl
	* multiple contracts in one file
		* https://cloud.spring.io/spring-cloud-contract/single/spring-cloud-contract.html#_multiple_contracts_in_one_file
	* pushing to repo
		* https://cloud.spring.io/spring-cloud-contract/single/spring-cloud-contract.html#maven-pushing-stubs-to-scm
	* pulling from repo
		* https://cloud.spring.io/spring-cloud-contract/single/spring-cloud-contract.html#scm-stub-downloader
* maven properties
	* https://books.sonatype.com/mvnref-book/reference/resource-filtering-sect-properties.html

[IN-PROGRESS]


[TODO]
* unit/integration testing
	* https://docs.spring.io/spring/docs/current/spring-framework-reference/testing.html
	* https://dzone.com/articles/how-to-mock-spring-bean-version-2
	* feign client
		* https://github.com/velo/feign-mock
* contract testing
	* multiple consumers
		* https://cloud.spring.io/spring-cloud-contract/single/spring-cloud-contract.html#_stubs_per_consumer
	* stub runner for messaging
		* https://cloud.spring.io/spring-cloud-contract/single/spring-cloud-contract.html#stub-runner-for-messaging
* wiremock
	* http://wiremock.org/docs/stubbing/
	* https://www.youtube.com/watch?v=x3MvZ8DFrpE&feature=youtu.be
* cloud-native
	* https://www.infoq.com/articles/test-java-microservices-service-mesh
* mock-server
	* http://www.mock-server.com/
	* https://github.com/jamesdbloom/mockserver
* spock
	* ?
* junit5
	* https://www.baeldung.com/junit-5
	* https://www.infoq.com/articles/deep-dive-junit5-extensions?utm_source=infoqEmail&utm_medium=SpecialNL_EditorialContent&utm_campaign=08272018_SpecialNL&forceSponsorshipId=1656

---

## Repos
* https://github.com/spring-cloud-samples/spring-cloud-contract-samples/
	* https://github.com/spring-cloud-samples/spring-cloud-contract-samples/tree/master/consumer
	* https://github.com/spring-cloud-samples/spring-cloud-contract-samples/tree/master/producer
* https://github.com/hamvocke/spring-testing
* https://github.com/importsource/spring-cloud-contract
* https://github.com/paolocarta/spring-cloud-contract-demo

---

## Issues
* https://github.com/spring-projects/spring-boot/issues/6541
* https://moelholm.com/2016/10/22/spring-boot-separating-tests/
* https://stackoverflow.com/questions/47979589/spring-data-jpa-generate-id-on-database-side-only-before-create
* https://stackoverflow.com/questions/35232827/spring-boot-test-ignores-logging-level
* https://github.com/spring-cloud/spring-cloud-netflix/issues/1482
* https://www.concretepage.com/questions/535
* https://www.mkyong.com/java/jackson-2-convert-java-object-to-from-json/
* https://stackoverflow.com/questions/43093968/enablefeignclients-and-feignclient-fail-on-autowiring-feigncontext-nosuchbea

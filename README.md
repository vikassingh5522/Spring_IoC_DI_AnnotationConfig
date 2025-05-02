

Role in the Example:

Demonstrates Dependency Injection by receiving a MessageService instance via constructor injection.

The @Component annotation marks it as a Spring bean for annotation-based configuration.

The @Autowired annotation on the constructor enables automatic dependency injection for annotation-based configuration.

For XML-based configuration, the dependency is injected via the <constructor-arg> tag in applicationContext.xml.

For Java-based configuration, the dependency is injected programmatically in AppConfig.java.

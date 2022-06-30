# JMS
Create The Project
 Maven Project
Add the artenis client dependency
   <dependency>
			<groupId>org.apache.activemq</groupId>
			<artifactId>artemis-jms-client-all</artifactId>
			<version>2.6.4</version>
		</dependency>

Create jndi.properties
java.naming.factory.initial=org.apache.activemq.artemis.jndi.ActiveMQInitialContextFactory
connectionFactory.ConnectionFactory=tcp://localhost:61616
queue.queue/myQueue=myQueue

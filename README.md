# JMS
1. Create The Project <br>
 Maven Project
2. Add the artenis client dependency <br>
   <dependency>
			<groupId>org.apache.activemq</groupId>
			<artifactId>artemis-jms-client-all</artifactId>
			<version>2.6.4</version>
		</dependency>

3. Create jndi.properties <br>
java.naming.factory.initial=org.apache.activemq.artemis.jndi.ActiveMQInitialContextFactory
connectionFactory.ConnectionFactory=tcp://localhost:61616
queue.queue/myQueue=myQueue

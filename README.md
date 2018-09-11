# RestWithLogger-Junit

Mock Vs Spy::
--------------
Mock: Both can be used to mock methods or fields. The difference is that in mock, you are creating a complete mock or fake object while in spy, there is the real object and you just spying or stubbing specific methods of it.

When using mock objects, the default behavior of the method when not stub is do nothing. Simple means, if its a void method, then it will do nothing when you call the method or if its a method with a return then it may return null, empty or the default value.

While in spy objects, of course, since it is a real method, when you are not stubbing the method, then it will call the real method behavior. If you want to change and mock the method, then you need to stub it.

Maven Dependencies for PowerMockito:
--------------------------------------
		<!-- https://mvnrepository.com/artifact/org.mockito/mockito-all -->
		<dependency>
		    <groupId>org.mockito</groupId>
		    <artifactId>mockito-all</artifactId>
		    <version>1.10.19</version>
		    <scope>test</scope>
		</dependency>
		<!-- https://mvnrepository.com/artifact/junit/junit -->
		<dependency>
		    <groupId>junit</groupId>
		    <artifactId>junit</artifactId>
		    <version>4.12</version>
		    <scope>test</scope>
		</dependency>
		<!-- https://mvnrepository.com/artifact/org.powermock/powermock-module-junit4 -->
		<dependency>
		    <groupId>org.powermock</groupId>
		    <artifactId>powermock-module-junit4</artifactId>
		    <version>1.6.1</version>
		    <scope>test</scope>
		</dependency>
		<!-- https://mvnrepository.com/artifact/org.powermock/powermock-mockito-release-full -->
		<dependency>
		    <groupId>org.powermock</groupId>
		    <artifactId>powermock-mockito-release-full</artifactId>
		    <version>1.6.4</version>
		    <type>pom</type>
		    <scope>test</scope>
		</dependency>

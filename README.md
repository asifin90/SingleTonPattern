# Singleton Design Pattern

Singleton is a design pattern false into category of creational design pattern.

It is one of the simplest design pattern. It is used for applications like logging, device drivers, registry settings, database operation etc when we dont want to create instance again and again.

Concept of this design pattern is to create an instance  and that same instance is provided throughout the application without creating instance again and again.

We need this design pattern where we need to create instance only once and reuse that instance in all application areas like implementing log messages, Database operations, Common error mechanism etc...

For example, we created logger project,will do one time setting like create file name for log, path for storing logs. In this case if we create object for each child method we need to avoid creating logger instance to avoid creating multiple copied of log file for same operation.  
 





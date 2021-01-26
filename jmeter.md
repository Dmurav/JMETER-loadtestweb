Директория main/java — утилиты, классы JMeter Function, классы для Java Request (пример JavaTest и SleepTest) 
— программный код, с помощью которого можно создавать нагрузку

Директория test/java - jUnit-тесты для jUnit Request
Директория test/jmeter - каталог, который будет использоваться плагином jmeter-maven-plugin, в нем можно создавать ещё подкаталоги

Каталог /src/test/jmeter используется для хранения jmx-файлов (скриптов jmeter), 
property-файлов (файлов настройки), дополнительных скриптов, например, groovy-скриптов.

mvn jmeter:gui
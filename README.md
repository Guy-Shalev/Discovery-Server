This project contains three folders:

Discovery-Server

Service-Log

Service-Shuffle

INSTRUCTIONS
=============
1. Open all three projects in Intellij and run them as independent instances.
2. To call "service-shuffle", send HTTP Post request to "localhost:8082/shuffle/" with parameter name "number" and a value between 1 to 1000 ( for example http://localhost:8082/shuffle?number=9).
3. Enjoy the shuffled array that is returned.

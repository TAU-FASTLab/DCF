# DCF
DATA COLLECTION FRAMEWORK

DCF allows users to define variables for receiving data from multiple type of data adapters (orion-ld/fiware, MQTT, opc-ua) or legacy database and storing received data within the program where data can be processed and analyzed using user defined logic functions. Results from these operations can be sent to endpoints designated by users (MQTT, orion-ld/fiware). GUI is also included for logic operation and variable defining, GUI also can be used to view retrieved database data and monitor results from defined logic operations.

Note: in the component video, the DCF version that was used was a non containerized version, in the manual documentation and normal circumstances, the DCF component will be containerized, thus the server address parameters for orion and mongodb will be different if orion and mongodb are containerized by docker alongside DCF

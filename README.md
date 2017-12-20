# JAX-WS Testing

## Apache CXF

### Creating a WSDL from Java

Run the following:

    /opt/apache-cxf-3.2.1/bin/java2ws -wsdl -s src/main/java/ -classdir build/classes/java/main/ -cp build/classes/java/main/ -o src/main/resources/wsdl/data_access.wsdl com.aidanns.data.wsdl.DataAccessService

# WSDLRepo

## WSDL
WSDL stands for Web Service Descriptive Language. It is an XML format which describes about a service.It specifies end points,methods,request and response parameters etc of a web service.

## Basic skeleton of a WSDL file:

**<definitions>**
	definition of wsdl
	includes namespaces
   **<types>**
      import Schema definition being used
   **</types>**

   <message>
      Message Structure
   </message>

   <portType>
      <operation>
         Operation being performed along with parameters 
      </operation>
   </portType>

   <binding>
      binding definiton
   </binding>

   <service>
      service definition
   </service>
</definitions>

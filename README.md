#HDI Container for synonym access from another HDI Containter

## Content
Eight tables taken from SAP Netweaver EPM Content (Sales Order Model)

##How to build schema
1. clone the repo to DevX (XSA WebIDE)
2. Build the DB module
3. Goto HRTT, connect to the HDI Container created in 2., open SQL Console and execute call 
	"Insert_data"
4. In case you want to deploy it with a different schema name: build the project, download the mtar, copy to server, deploy it via xs deploy and an explicit schema name via mta-extension. A sample mta-extension file that can be adapted is included as syn-prov-hdi.mtaext, just remove the line "service-name..." and define a schema name.

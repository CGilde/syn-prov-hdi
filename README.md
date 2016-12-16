#HDI Container for synonym access from another HDI Containter

## Content
Eight tables taken from SAP Netweaver EPM Conten (Sales Order Model)

##How to build schema
1. clone the repo to DevX (XSA WebIDE)
2. Build the DB module
3. Goto HRTT, connect to the HDI Container created in 2., open SQL Console and execute call 
	"Insert_data"
4. Optional: in case you want to deploy it with a different schema name: build the project, download the mtar, copy to server, deploy it via xs deploy (details in How To guide)
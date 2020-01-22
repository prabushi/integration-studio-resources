# Steps to install schema generation feature for salesforce connector into Integration Studio 7.0.0.

- Install [wso2esb-tooling-connector-salesforce-dynamicschema-generation-p2-1.0.1-SNAPSHOT.zip](https://github.com/prabushi/integration-studio-resources/blob/master/salesforce-connector-dynamic-schema-generation/dynamic-schema/repository/main/target/wso2esb-tooling-connector-salesforce-dynamicschema-generation-p2-1.0.1-SNAPSHOT.zip)

	Follow,
	 1. Help -> Install New Software... -> Add... -> Archive..., and select the p2 location.
	 2. Install the p2 and restart Integration Studio to get the new feature.

- Then install [wso2esb-tooling-main-p2-7.0.0-SNAPSHOT.zip](https://drive.google.com/file/d/1AvC5xQargZJ-Dej7CinJMtLST_Ohp_iG/view?usp=sharing)

	Follow,
	 1. Help -> Install New Software... -> Add... -> Archive..., and select the p2 location.
	 2. Install the p2 and restart Integration Studio to get the update.
	
	Please note, installing via p2 update will not work if there are new updates installed after 22-01-2020. In such cases, you can follow as below.

	- Rename [org.wso2.developerstudio.visualdatamapper.diagram jar](https://github.com/prabushi/integration-studio-resources/blob/master/salesforce-connector-dynamic-schema-generation/visual.diagram.jar/org.wso2.developerstudio.visualdatamapper.diagram_7.0.0.201910041013.jar) with the name of the jar inside IntegrationStudio/plugins directory, and replace with it.
		If you have multiple org.wso2.developerstudio.visualdatamapper.diagram jars after updating Integration Studio, make sure to rename the jar with the largest timestamp.

	- Restart integration Studio

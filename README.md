After both source packages have been deployed. Once translate the customField__c of the customObject__c in Salesforce. Then pull the CustomObjectTranslation via the CLI.

Following error will occur:
```
Retrieving v57.0 metadata from user@salesforce.com.develop using the v56.0 SOAP API
ERROR running force:source:retrieve:  Metadata API request failed: Component conversion failed: Unexpected child metadata [/Users/nils/repository/salesforce/sfdx-translation-bug/package-a-app/main/default/objectTranslations/customObject__c-es/customField__c.fieldTranslation-meta.xml] found for parent type [CustomObjectTranslation]

```
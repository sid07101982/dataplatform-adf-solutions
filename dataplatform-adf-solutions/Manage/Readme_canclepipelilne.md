# Parametes accepted by pipeline 
    subscription        : subscription where datafactory is
    resourcegroup       : datafactory resource group

#Instructions
 
-   Use lookup in pipeline to get alet config located in all environments at <datalake-container/config/alert/alert.json> to get subscription and resourcegroup
-   You would need datafactory managed identity to be added as contributor to datafactory



# Implementing alerting tips
-   This can be used to break off from for-loop in case of any error.


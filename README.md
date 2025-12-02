##########################################  
# DISCLAIMER  
# ============  
# Your implementation may differ. Test in non-impacting environment first and derive code relevant to your environment  
# donot run directly in any environment which impacts users  
# make relevant changes  
# Also stated in the azure-pipeline-build-deploy.yml  
##########################################  
1)	ADF DevOps Organization  
    * Create ADF DevOps Organization  
    * Create Repo  
    * Grant Dev Team and Approvers access  
  
3)	Create Managed Id  
In DevOps, Create Service Connection possibly one per environment  
Associate Service Connection with Managed ID  
Grant ADF Contributor at resource Group level  

4)	In ADF, Associate Data Factory to Repo  
![ADF Integration](https://github.com/anishkutti/adf_azure_devops/blob/main/images/1.png)
  
5)	Release Flow  

![ADF Integration Flow ](https://github.com/anishkutti/adf_azure_devops/blob/main/images/2.png)
  
Please note: The code is demo code only

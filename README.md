# This repo will be used as a sample project for Azure Artifacts

**Azure Web App service:**

Note: You must set the app settings as below to disable all file caching:
WEBSITE_DYNAMIC_CACHE=0
WEBSITE_LOCAL_CACHE_OPTION=Never




**Post-deployment inline script in the Release pipeline**

cp -rf /home/site/wwwroot/package/* /home/site/wwwroot/

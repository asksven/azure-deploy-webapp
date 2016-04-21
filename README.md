Click here and you will be taken to the portal to enter the parameters (requires a mouse).

<!-- 
# This does not work because github.pwc.com is not publicly accessible -> the portal can not grab the json file
#
#<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fgithub.pwc.com%2Fdigital-service-delivery%2Farm-templates%2Fraw%2Fmaster%2Fwebapp-github%2Fazuredeploy.json" target="_blank">
#    <img src="http://azuredeploy.net/deploybutton.png"/>
#</a>
#
#<a href="http://armviz.io/#/?load=https://github.pwc.com/digital-service-delivery/arm-templates/raw/master/webapp-github/azuredeploy.json" target="_blank">
#    <img src="http://armviz.io/visualizebutton.png"/>
#</a>
#
# for that reason we use public github for demo purposes
#
-->

We link to a public repo so that the Azure portal can fetch the json file:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fasksven%2Fcloud-provisioning%2Fmaster%2Fazure-cli-webapp%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/asksven/cloud-provisioning/master/azure-cli-webapp/azuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

# Parameters for demo:

- SITENAME: ````<some fancy name>````
- HOSTINGPLANNAME: ````free````
- SITELOCATION: ````West Europe````
- SKU: ````Free````
- WORKERSIZE: ````0````
- REPOURL: ````<link to a public repo>````
- BRANCH: ````master````




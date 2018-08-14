# DLWorkspace deployment using ARM Template

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fdlworkspace%2Fdlworkspace-deployment%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fdlworkspace%2Fdlworkspace-deployment%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>

## DLWorkspace Overview

Deep Learning Workspace (DLWorkspace) is an open source toolkit that allows AI scientists to spin up an AI cluster in turn-key fashion (either in a public cloud such as Azure, or in an on-perm cluster). It has been used in daily production for Microsoft internal groups (e.g., Microsoft Cognitive Service, SwiftKey, Bing Relevance, etc...). Once setup, the DLWorkspace provides web UI and/or restful API that allows AI scientist to run job (interactive exploration, training, inferencing, data analystics) on the cluster with resource allocated by DL Workspace cluster for each job (e.g., a single node job with a couple of GPUs with GPU Direct connection, or a distributed job with multiple GPUs per node). DLWorkspace also provides unified job template and operating environment that allows AI scientists to easily share their job and setting among themselves and with outside community. DLWorkspace out-of-box supports all major deep learning toolkits (TensorFlow, CNTK, Caffe, MxNet, etc..), and supports popular big data analytic toolkit such as hadoop/spark.

For more information about the DLWorkspace toolkit, visit https://github.com/Microsoft/DLWorkspace/tree/master
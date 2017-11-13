#node-red-contrib-japanese-analytics
===================================

Node-RED nodes for Text Analytics API in Microsoft Cognitive Services APIs 

このノードは、MicrosoftのCognitive ServicesのText Analytics APIを使用し、言語判定、日本語のキーワード抽出・感情分析を行います。
そのため、このノードを利用するためには、Microsoft Azureのアカウントが必要となります。

Microsoft Cognitive Services are Cognitive APIs on Azure.
Currently this npm package supports the following APIs on west-US region.
Text Analytics API　also support Japanese.

## Install
Run the following npm command in your Node-RED environment.
```
cd ~/.node-red
npm install -g node-red-contrib-japanese-analytics
```

## Usage
To use the node, launch Node-RED (see running Node-RED for help getting started).

Show node property and input subscription key from Azure portal.

##Revision History
- 1.0.0 
	- Initial release

## Microsoft Cognitive Services website
https://www.microsoft.com/cognitive-services

## Examples using Cognitive Services nodes
- MachineEye using Computer Vision API: http://www.instructables.com/id/MachineEye/?ALLSTEPS
- Node-RED Docker image for Azure nodes: https://hub.docker.com/r/dwaiba/azureiot-nodered/

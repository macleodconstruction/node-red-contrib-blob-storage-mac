# node-red-contrib-azure-blob-storage-aleph

node-red-contrib-azure-blob-storage is a <a href="http://nodered.org" target="_new">Node-RED</a> node that allows you to work with Azure Blob Storage. You can create and delete Containers and also blob files.


#### Azure Blob Storage

Node-Red node to connect to Azure Blob Storage


Ex: 'msg.payload' -> filename that you need to upload. Ex: filename.txt

- Use `msg.payload` to send a file to save on Azure Blob Storage.

- This file must be in the same folder of Node-RED user directory - typically `~/.node-red`


## Installation

```
npm install -g node-red-contrib-blob-storage-mac
```


### References
You can read more about Azure Storage [here](https://docs.microsoft.com/en-us/azure/storage/).

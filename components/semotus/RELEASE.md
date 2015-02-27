## 0.1.19
* Return whether message processing actually has changes
## 0.1.18
* Supports preServerCall and postServerCall in controller
## 0.1.17
* Now synchronize objects whether referenced or not to avoid problems with ignored objects getting updated later.
* Support for transient objects which don't transmit to client
* Support for {toClient: true/false, toServer: true/false, name: template-name} in lieu of name on template.create
## 0.1.16
* Proper handling of boolean null values
* Proper handling of promises for server calls (could not have chained thens before) 
## 0.1.13
* Did not handle case of setting an array to [] and then repopulating it with the identical results
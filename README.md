#### hybris-multiple-env-config 
The main objectif is to manage Hybris configuration ( local.properties, localextensions.xml ...) between diffrent environments, so instead of changing the configuration each time we change the environment, the build.xml contains a set of tasks for making a copy of properties from one common file and one environment specific file and merge them to create a complete local.properties file and for for other content. This is approch is based on ant apache , All what you need is to include build.xml && in config_templatein your config folder as showed in this following screenshot.

- Copy build.xml and config_template to your Config Folder

![Alt text](https://raw.githubusercontent.com/elaissoussi/hybris-multiple-env-config/master/multiple-config.PNG)

 
- Once the configs is included, your need to adapt your need to add folder for each environment inside env folder and add your specifique local.properties and localextenions.xml and  exectute ant -Denv= the name of your target environement

![Alt text](https://raw.githubusercontent.com/elaissoussi/hybris-multiple-env-config/master/build.PNG)

####### enjoy

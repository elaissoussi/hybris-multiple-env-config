#### hybris-multiple-env-config 
The main objectif behinde this configuration is to manage the difference between the configuration of each environment, so instead of change the the configuration each time we change the environement manually , this ant task make a copy of properties from one common file and one environment specific file and merge them to create a complete local.properties file and aloso for other content.This is approch is based on ant apache so, you need to include build.xml in youer config folder.
### copy build.xml and config_template to your Config Folder
![Alt text](https://raw.githubusercontent.com/elaissoussi/hybris-multiple-env-config/master/multiple-config.PNG)

###To test , you can  exectute ant -Denv= the name of your target environement
![Alt text](https://raw.githubusercontent.com/elaissoussi/hybris-multiple-env-config/master/build.PNG)

####### enjoy

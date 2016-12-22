#### hybris-multiple-env-config 
The main object behinde this configuration is to manage the difference between each environment and 
make a copy properties from one common file and one environment specific file and merge them to create a complete local.properties file.
This is approch is based on ant apache so, you need to include build.xml in youer config folder.

### copy build.xml and config_template to your Config Folder
![Alt text](https://raw.githubusercontent.com/elaissoussi/hybris-multiple-env-config/master/multiple-config.PNG)

### exectute ant -Denv= Your target environement
![Alt text](https://raw.githubusercontent.com/elaissoussi/hybris-multiple-env-config/master/build.PNG)

#### enjoy

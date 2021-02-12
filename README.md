# Device registration utility

## How to run
* Add the csv in dataFolder
* Update the properties file from resources folder
* Build the code
* Run `java -Dtype=Finger -Denv.user=dev -DbaseUrl=https://guinea-sandbox.mosip.net -cp target/DeviceRegister-0.0.1-SNAPSHOT-jar-with-dependencies.jar  com.mosip.io.Runner`
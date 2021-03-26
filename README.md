# cucumber-junit

for Android to run:

mvn test mvn test -DplatformName="Android" -DUDID=<your udid> -DdeviceName=<YOUR device name> -DsystemPort=<any local port> -DchromeDriverPort=<any port>

for ios:

mvn test -DplatformName="iOS" -DUDID=<your udid> -DdeviceName=<YOUR device name> -DwdaLocalPort=<any local port> -DwebkitDebugProxyPort=<any port>

default:
mvn test->this will run ios

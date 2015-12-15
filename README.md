# Build
*  mvn clean package

# Test
* mvn clean package
* mvn jetty:run
* browse to http://localhost:8080/ to see the result.

# Deploy
* Be sure to update version in pom.xom
* /usr/local/share/googleAppEngine/appengine-java-sdk/bin/appcfg.sh --oauth2 update target/ROOT
* If there are OAUTH2 errors, delete mv ~/.appcfg_oauth2_tokens_java and retry.

# Test deployment
* https://appengine.google.com/a/greening.org
* Select Versions
* Click on Live URI for the version you uploaded

# Confirm deployment
* https://appengine.google.com/a/greening.org
* Select the new version
* Click Make Default

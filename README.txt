Build:
  mvn clean package

Test:
  mvn clean package
  mvn jetty:run
  browse to http://localhost:8080/ to see the result.

Deploy:
  Be sure to update version in pom.xom
  /usr/local/share/googleAppEngine/appengine-java-sdk-1.2.2/bin/appcfg.sh update target/ROOT

Login to the correct Google app engine account
  https://appengine.google.com/a/greening.org

Test deployment
  https://appengine.google.com/a/greening.org
  -Select Versions
  Click on Live URI for the version you uploaded

Confirm deployment
  https://appengine.google.com/a/greening.org
  Select the new version
  Click Make Default

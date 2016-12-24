1.http4 install
  feature:install camel-http4
2.jetty9 install 
  feature:install camel-jetty9

3.feature:list | grep camel-http4
  ->installed camel-http4 
  ->installed camel-jetty9
4.deploy

5.curl
  ->http://localhost/yahoo



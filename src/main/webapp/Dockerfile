# FROM gcr.io/google_appengine/java-compat
#FROM  gcr.io/google_appengine_labs/jetty9_compat
#FROM gcr.io/google_appengine_qa/jetty9-compat:ludo
FROM gcr.io/google_appengine_qa/jetty9-compat:githubhead
 #FROM appengine-mvn-opensource
RUN apt-get update && apt-get install -y fortunes


ADD . /app

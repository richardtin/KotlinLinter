FROM circleci/android:api-29

RUN echo $' \n\
systemProp.http.proxyHost=${PROXY_HOST}\n\
systemProp.http.proxyPort=${PROXY_PORT}\n\
systemProp.http.proxyUser=${PROXY_USER}\n\
systemProp.http.proxyPassword=${PROXY_PASSWORD}\n\
systemProp.https.proxyHost=${PROXY_HOST}\n\
systemProp.https.proxyPort=${PROXY_PORT}\n\
systemProp.https.proxyUser=${PROXY_USER}\n\
systemProp.https.proxyPassword=${PROXY_PASSWORD}\n\
systemProp.jdk.http.auth.tunneling.disabledSchemes=""' >> ~/.gradle/gradle.properties

COPY . /usr/src/app
WORKDIR /usr/src/app

RUN chmod +x gradlew

CMD ["./gradlew tasks"]
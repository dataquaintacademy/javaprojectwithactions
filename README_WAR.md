Simple Java WAR example

This folder contains a minimal Maven-based Java web application that builds a .war file.

Build:

```bash
mvn package
```

The built WAR will be at `target/simple-war-1.0-SNAPSHOT.war`.

Run in a servlet container (e.g., Tomcat): drop the WAR into the `webapps/` folder and start Tomcat. The app's root shows `index.jsp`; click "Say Hello" to hit the servlet at `/hello`.

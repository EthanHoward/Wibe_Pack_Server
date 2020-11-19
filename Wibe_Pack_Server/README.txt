you may have to change memory allocation within the Start.bat file,
right click and open with notepad and you'll see two java arguments
-Xmx2G and -Xms2G
-Xmx is the limiter so it will only ever use the number set in -Xmx
-Xms is the starting allocation , the amount that is set to the server when it starts
based on the settings you may have to change your _JAVA_OPTIONS in Path, google Change _JAVA_OPTIONS and change the -Xmx at a number e.g 1024m 2G, 4G etc.
Don't start minecraft_server.1.7.10.jar , ensure you start forge or the Start.bat file

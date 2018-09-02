## Welcome!
This github repository contains the original ftc_app from https://github.com/ftctechnh/ftc_app.git 
with a few modifications to the build system. The idea is that instead of rebuilding the entire app, 
we use the HTTP Api of OnBotJava to upload the code from our Android TeamCode Project to the phone
and compile the code on the phone just as if we where using OnBotJava.
# Why
1. We can reduce the build time down to only a couple of seconds vs 30 seconds or more
2. Teams can now store code locally on they're computer and track it with git rather than relying on the phone for sourcecode storage
3. Teams can now seamlessly switch between developing on AndroidStudio and developing with OnBotJava directly

# RelevantSocialPlatforms

#pre requirement
1. install java 11

#to compile 
javac -d bin/ src/com/parminder/utils/*.java src/com/parminder/main/*.java src/com/parminder/parser/*.java src/com/parminder/bo/*.java -classpath lib/jsoup-1.12.1.jar:lib/org.json-20130603.jar 

#to run

java -Dfile.encoding=UTF-8 -classpath /home/parminder/projetcs/RelevantSocialPlatforms/bin:/home/parminder/projetcs/RelevantSocialPlatforms/lib/jsoup-1.12.1.jar:/home/parminder/projetcs/RelevantSocialPlatforms/lib/org.json-20130603.jar com.parminder.main.RelevantSocialPlatforms url

# replvae url withreal url
example 

java -Dfile.encoding=UTF-8 -classpath /home/parminder/projetcs/RelevantSocialPlatforms/bin:/home/parminder/projetcs/RelevantSocialPlatforms/lib/jsoup-1.12.1.jar:/home/parminder/projetcs/RelevantSocialPlatforms/lib/org.json-20130603.jar com.parminder.main.RelevantSocialPlatforms https://www.instagram.com/fashiongrunge/

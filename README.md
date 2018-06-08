# public-rep
Add jar to git respository:
mvn install:install-file -DgroupId=GROUPID -DartifactId=ARTIFACTID -Dversion=VERSION -Dfile=PATH -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=PATH_TO_EXTRACT_JAR  -DcreateChecksum=true

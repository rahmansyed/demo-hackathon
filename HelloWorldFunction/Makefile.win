build-HelloWorldFunctionUberJar:
	@ mvn clean package
	@ if not exist $(ARTIFACTS_DIR)\lib mkdir $(ARTIFACTS_DIR)\lib
	@ xcopy .\target\HelloWorld*.jar $(ARTIFACTS_DIR)\lib\ /Y

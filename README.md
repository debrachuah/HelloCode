# HelloCode
Continuous Delivery With Microsoft Azure and Visual Studio Team Services

Step 12:

Set the MSBuild Arguments field as:

/p:DeployOnBuild=true /p:WebPublishMethod=Package /p:PackageAsSingleFile=true /p:SkipInvalidConfigurations=true /p:PackageLocation="$(build.stagingDirectory)"

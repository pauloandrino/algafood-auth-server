# Generating symmetric key 
keytool -genkeypair -alias algafood -keyalg RSA -keypass 123456 -keystore algafood.jks -storepass 123456 -validity 3650


# Listing keys
keytool -list -keystore .\algafood.jks

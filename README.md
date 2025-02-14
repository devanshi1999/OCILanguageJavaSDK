# OCILanguageJavaSDK
java sdk example for oci language using api key

1.	Download the private key file generated from browser.
2.	Create a config file under .oci in home i.e. mkdir  ~/.oci then vi config
3.	Inside this .oci/config file add these info about API key
  a.	**[DEFAULT/SOME-PROFILE-NAME] (make sure to add square brackets [])

  b.	user = <user-id>
  
  c.	fingerprint = <fingerprint>
  
  d.	tenancy = <tenant-id>
  
  e.	region = <region>
  
  f.	key_file = /Users/path/to/private/key/file**
  
5.	Once you have this ready, download and unzip the attached zip
6.	Open the project on some IDE
7.	Open main class AiServiceLanguageExample
8.	Make necessary changes to following lines
  a.	**Line 29/30 – update config profile name with the name you gave above
  b.	Update compartment id, source and target language code in Line 44 to 46**
  c.	Run the class
  d.	You should get some output


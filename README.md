# OCILanguageJavaSDK

Download the private key file generated from browser.

Create a config file under .oci in home i.e. mkdir  ~/.oci then vi config

Update this .oci/config file to look something like this - Update with the your values

    [DEFAULT/SOME-PROFILE-NAME]
    user = ocid1.user.oc1..aaaaaaaat6swf75jm7hfpdbnp7sqs5rh2hyi3jojqxsdzasqbim575lexgta
    fingerprint = 86:14:2c:78:b6:34:33:b2:28:0f:9a:ca:83:9d:d9:56
    tenancy = ocid1.tenancy.oc1..aaaaaaaahp7giiq4smoqb5hmqnz5xmplfwuyfpovxivy22qczlrlgkzns7qq
    region = us-ashburn-1
    key_file = /Users/devanshisingh/customTesting/loadtest.pem
   
Open main class AiServiceLanguageExample

Make necessary changes to following lines

**Line 29/30 – update config profile name with the name you gave above**

**Update compartment id, source and target language code in Line 44 to 46**

Run the class

You should get some output


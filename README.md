# Azure204-Developing-Solutions-for-Microsoft-Azure

### Steps to deploy application through Cloud Shell or Bash in Azure portal
1. `mkdir newDirName` - make directory
2. `cd newDirName` - change to the new directory
3. `git clone https://github.com/sophialai123/happybirthday.git` - clone any repos from github
4. `az webapp up --location westeurope --name happybirthdaystevent --html` - az webapp up + the location + your website name
5. if it is successful -- open the url to check 
 ```
   {
  "URL": "http://happybirthdaystevent.azurewebsites.net",
  "appserviceplan": "sophia852686_asp_4776",
  "location": "westeurope",
  "name": "happybirthdaystevent",
  "os": "Windows",
  "resourcegroup": "sophia852686_rg_1142",
  "runtime_version": "-",
  "runtime_version_detected": "-",
  "sku": "FREE",
  "src_path": "//home//lai//wtHTML//happybirthday"
}
   ```
6.   `code index.html` - to change any code in the `Bash` and save
7.   redeploy again -- repeat step 4

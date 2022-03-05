# DenizenScriptPluginManager
Handles creating full spigot plugins that run scripts

## Initial Setup

**NOTE:** These steps only have to be performed once.  
These steps involve setting up an access token for this repo to have permission to create other repos.

1. Fork this repository using the button in the top right corner:  
![image](https://user-images.githubusercontent.com/29823405/156869754-1976f33e-5362-4bca-83e7-71f5a13f0e25.png)

2. Create a non-expiring personal access token with "repo" access following GitHub's guide:  
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token  
Save this access token for later! Don't share this token with anyone.  
**NOTE:** If you set an expiration time on this token, you will have to replace it once it has expired.

3. In your newly forked repository, click into the Settings tab and find Secrets -> Actions:  
![image](https://user-images.githubusercontent.com/29823405/156869804-7d851861-063f-4855-86db-a4a83bdebfe7.png)

4. Click "New repository secret" in the top right of this page:  
![image](https://user-images.githubusercontent.com/29823405/156869953-30fd687c-02a5-4000-970c-762be657bdb4.png)

5. Paste your personal access token into the "Value" box and name it `TOKEN` in all caps, then click "Add secret":  
![image](https://user-images.githubusercontent.com/29823405/156871660-8d79388c-cb85-435c-ac7d-4dd42960319d.png)

You are all set up! You do not have to repeat these steps unless your token was made with an expiration.

## Usage

Once this repo is set up, usage is very simple. At the top of this repo click the "Actions" tab.

...
# Initial installation

If you have completed the AWX image deployment on Cloud Platform, the following steps is for you to start use it quikly:

## Preparation

1. Get the **Internet IP address** of Cloud Server from your Cloud Platform Console
2. Check you **inbound of Security Group Rule** of Cloud Console to ensure the **TCP:80** is allowed
3. Make a domain resolution if you want to use domain for this application

## Metabase Installation Wizard

1. Using local Chrome or Firefox to visit the URL http://domain name or http://Internet IP, you will enter the configuration interface of AWX
   ![](https://libs.websoft9.com/Websoft9/DocsPicture/en/awx/awx-login-websoft9.png)

2. The Adminitrator console of AWX...
   ![](https://libs.websoft9.com/Websoft9/DocsPicture/en/awx/awxui-websoft9.png)

3. Then start to create:Credentials,Inventories,Project for one Template, use the Template for deployment job

   > Refers to the [AWX Documentation](https://docs.ansible.com/ansible-tower/) to know more

## FAQ

#### I can't visit the start page of Metabase?

Your TCP:80 of Security Group Rules is not allowed so there no response from Chrome or Firefox

#### The first time loading is slow?

Yes, AWX takes nearly a minute to load and runs smoothly after loading.
#  Hosting a Static Website in Azure Cloud with CI/CD using Github Actions and Custom Domain (Free) 👨‍💻

<img src="https://media.giphy.com/media/PAqjdPkJLDsmBRSYUp/giphy.gif" >

To Start with This Project You need some prerequisites and resources
Read this post I clearly Explained : [Read here](https://urlis.net/jq048)

###  **Step 1**: Create a new Repository on GitHub and upload your Website Source code to it

<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/repo.png" >

___

### **Step 2**: Log in to your Azure Portal and Search for a Static web app in the search bar **>>** Click on it


<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/search.png" >

___

### **Step 3**: Creating a static website in Azure 


➜ Go to Static Web app hit create

<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/create.png" >

➜ Choose the Subscription or leave it default then Create a new resource group and Enter a name for the webapp and Choose hosting plan as free , like this


<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/create1.png"  >


➜ Then in  Deployment details,Choose the source as Github and then authorize and link your github account , then choose the repository and branch what we create in      your github      


<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/create2.png"  >


➜ Then hit Review+ create >> Create.

➜  It takes less than 2 mins to deploy ,after deployment it shows go to resource .then click go to resource and it shows all the data of your static web app
    and the default URL for your web app , like this


<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/Dm%20details.png"  >


#### ➜ Output : (With Default Domain)

<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/default%20domain.png"  >

___

### **Step 4** : Adding Custom Domain

Go to your static web app **>>** Custom Domain


<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/Custom%20Dm1.png" height="300" >


#### Refer this link to how to add a custom domain : [Watch here](https://www.youtube.com/watch?v=SpQgKfJ87fE&ab_channel=MicrosoftDeveloper)

___


### **Step 5**: CI/CD with Github Actions

Lets see how it works , By default while creating your webapp using github as deployment model it enables github ACTIONS CI/CD and .gitworkflows which contains all CI/Cd changes we made to your site

<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/workflows.png" >

Make changes in your source code and commit it >> then go to the actions of the repository to see the status , It takes less two two mins to commit change in your actual web app.

🟢 ➜ Changes Done 
--
🟡 ➜ Changes in Progress
--

#####  Github Actions

<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/actions.png" >

___

#### ➜ Output : (With Custom Domain)


<img src="https://github.com/Raghul-M/Azure-Static-Website-Hosting/blob/main/Images/Project%20Images/final.png"  >

___










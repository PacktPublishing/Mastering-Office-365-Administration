


# Mastering Office 365 Administration
This is the code repository for [Mastering Office 365 Administration](https://www.packtpub.com/virtualization-and-cloud/mastering-office-365-administration?utm_source=github&utm_medium=repository&utm_campaign=9781787288638), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
In today's world, every organization aims to migrate to the cloud to become more efficient by making full use of the latest technologies. Office 365 is your one-stop solution to making your organization reliable, scalable, and fast.

The book will start with an overview of Office 365 components, and help you learn how to use the administration portal, and perform basic administration. Then this book covers common management tasks such as managing users, admin roles, groups, securing Office 365, and enforcing compliance. In the next set of chapters, you will learn topics such as managing Skype for Business Online, Yammer, OneDrive for Business, and Microsoft Teams. In the final section of the book, you will learn how to perform reporting and monitor Office 365 service health.

By the end of this book, you will be able to implement enterprise-level services with Office 365 based on your organization's needs.
## Instructions and Navigation
All of the code is organized into folders. For example, Chapter07.

The code will look like the following:
```
if (([string]::IsNullOrEmpty($Office365Username) -eq $false) -and ([string]::IsNullOrEmpty($Office365Password) -eq $false))
{
    $SecureOffice365Password = ConvertTo-SecureString -AsPlainText $Office365Password -Force

    #Build credentials object
    $Office365Credentials  = New-Object System.Management.Automation.PSCredential $Office365Username, $SecureOffice365Password
}
```

The topics in this book assume that you have some knowledge of Office 365 and have used it as an end user. We assume that you know what the main components are in Office 365. We also assume that you are not already an advanced administrator of Office 365 who is looking for a book entirely comprising master's-level topics and techniques. Although, in some chapters, some techniques are of the master's level, most range from basic to advanced skills.

In order to perform the techniques in this book, we suggest setting up an Office 365 tenant that you can play around with before applying your newly acquired skills to your actual organizational tenant.

You can sign up for a free 30-day trial tenant at https://products.office.com/en-us/business/compare-more-office-365-for-business-plans. We highly recommend signing up for the E3 or E5 subscription and making yourself the global administrator (this happens automatically if you sign up with your info). You may also want to set up multiple users at different administration levels to test them out. You get 25 user licenses with every trial. You will also need PowerShell, SharePoint Online PowerShell, and Exchange PowerShell in order to execute the scripts.

## Related Products
* [PowerShell for Office 365](https://www.packtpub.com/networking-and-servers/powershell-office-365?utm_source=github&utm_medium=repository&utm_campaign=9781787127999)

* [Microsoft Office 365 – Exchange Online Implementation and Migration - Second Edition](https://www.packtpub.com/networking-and-servers/microsoft-office-365-exchange-online-implementation-and-migration-second-edit?utm_source=github&utm_medium=repository&utm_campaign=9781784395520)

* [Getting Started with Dynamics 365 Customer Engagement [Video]](https://www.packtpub.com/game-development/getting-started-dynamics-365-customer-engagement-video?utm_source=github&utm_medium=repository&utm_campaign=9781788292887)
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781787288638">https://packt.link/free-ebook/9781787288638 </a> </p>
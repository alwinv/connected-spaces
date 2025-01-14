---
author: alwinv
description: Learn how to install Dynamics 365 Connected Spaces Preview
ms.author: alwinv
ms.date: 11/06/2020
ms.topic: article
title: Install Dynamics 365 Connected Spaces Preview
ms.reviewer: v-brycho
---

# Install Dynamics 365 Connected Spaces Preview

[!INCLUDE[banner](includes/banner.md)]

After you have created an Azure Active Directory tenant for Microsoft Dynamics 365 Connected Spaces Preview, you can 
install Dynamics 365 Connected Spaces.

>[!NOTE]
>To install Connected Spaces, you must sign in with the global adminstrator account for your Azure Active Directory tenant, or with an account that has the System Administrator security role.

1. [Go to the Connected Spaces setup page](https://go.microsoft.com/fwlink/?linkid=2143957).

2. Read through the [Terms of Use](https://go.microsoft.com/fwlink/?linkid=2128595), and then when you’re ready, select **Install**.

     ![Install button.](media/install-connected-store.PNG "Install button")
    
    Installing Connected Spaces can take 30 to 60 minutes. You’ll see a progress indicator showing where you are in the installation process. During this time, setup installs the Connected Spaces solutions in the selected environment. It also installs the Contoso Sample Store that you can use to explore the web app by using sample data. 
    
    By default, setup creates a new trial (subscription-based) environment. If you want to install Connected Spaces in a different environment, select an environment from the **Choose environment** list. The list only shows environments that are enabled for installing Dynamics 365 applications. [Learn more about environments](/power-platform/admin/environments-overview).
    
    ![Drop-down list of enabled environments.](media/enabled-environments.PNG "Drop-down list of enabled environments")
        
    If the setup process fails, you’ll see the following message:
   
    ![Installation failed message.](media/install-failed-message.PNG "Installation failed message")
    
    If this happens, try installing again.
    

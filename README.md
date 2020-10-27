Reset Azure AD (Office 365) users password
==========================================

            

ResetPassword.png

 

This runbook takes the users name (financeuser@contoso.com) and a credential asset name that has access to Azure AD to reset the users password. It then resets the password and writes out the users alternative email address and the temporary password. This
 could be extended by using the send office 365 email runbook from https://gallery.technet.microsoft.com/scriptcenter/Send-Mail-Office-365-c8679aef to email the users the new password.


![Image](https://github.com/azureautomation/reset-azure-ad-(office-365)-users-password/raw/master/resetpassword.png)


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.

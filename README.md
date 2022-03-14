# azcopy

•	As we are scheduling project/applications  to run end to end On Cloud we have to Automate the File Copy Process from OnPrime to Azure Cloud so we come up the "AzCopy Automation"

•	"AzCopy Automation" is a Process which does  below tasks   
                         A. Generate the Parameter File for the any given source and 
                         B. Do Preprocessing of the given source Files 
                         C. Segregate  the Source Files according to the Modules of the Sources  and Copy 
                         D. Run AzCopy Commands to Sync/Copy the Files from OnPrime to Azure Cloud .

•	The Code for Step A is Specific to given Source and Code for Step B , C , D is Generic Code  with Configuration Changes we can reuse the code for any given Source .

•	  what is AzCopy :
                     The AzCopy is a  tool that allows you to copy and move data to and from Azure storage Account .
                     Its Command Line Utility , but still we can automate AzCopy by Running the AzCopy Commands in Shell Script  with some Configuration Changes .

•	 How to install AzCopy :
                    Its very easy to install AzCopy go Link https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10 and download the Zip/tar file appropriate for the Operating Systems .
                    Once you unzip / untar you have AzCopy executable File which can be placed in your working folder or directory .
•	  AzCopy Authentication  :
                    Before we perform any tasks ( copy/sync/download ) with AzCopy , it is necessary to authenticate AzCopy to your Azure Storage first.
                    There are two ways to authenticate AzCopy to your Azure storage accounts 
                     1 . Azure Active Directory Authentication 
                     2. Shared Access Signature Authentication .
                           The most common method to authenticate AzCopy is via Azure AD. When using Azure AD, you have several options.
                           Some of these options are:
                          A1 : Interactive Login - User is prompted to log in using the browser.
                          A2: Service Principal + password - For non-interactive login. Recommended for automation and scripting.
                          A3 : Service Principal + certificate - For non-interactive login. Recommended for automation and scripting.
                     

•

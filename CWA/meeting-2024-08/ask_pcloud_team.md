Dear pCloud Support Team,

I am writing to request assistance with accessing and uploading files to my pCloud account via the WebDAV interface. Despite following the available instructions, I have encountered issues with authentication and have been unable to successfully connect.

Here are the specific details of the problem:

1. **WebDAV URL and Authentication:**
   I attempted to access the WebDAV interface using the URL format `https://ewebdav.pcloud.com/<code>`. However, I consistently receive a "401 Unauthorized" error when trying to authenticate. It appears that the required username and password are not my pCloud account credentials. I am unsure how to obtain the correct credentials for WebDAV access.

2. **DVC Push Error:**
   I am using Data Version Control (DVC) to manage and push files to the WebDAV remote. The command `dvc push` fails with the following error message:
   ```
   ERROR: unexpected error - received 401 (Unauthorized): Client error '401 Unauthorized' for url 'https://ewebdav.pcloud.com/<code>/files/md5/00'
   ```

3. **Access via Browser and WebDAV Client:**
   Attempts to access the WebDAV server directly through a web browser and other WebDAV clients have also resulted in the same 401 Unauthorized error.

I would greatly appreciate guidance on the following points:
- The correct procedure to obtain the WebDAV URL for accessing a specific folder within my pCloud account.
- How to properly authenticate WebDAV access, including the correct username and password format or method; it seems that it's not the user name (my email) and password of my paid pCloud account.
- Any specific settings or permissions required to enable WebDAV access to my pCloud files.

Thank you very much for your support and assistance. I look forward to your prompt response.

Best regards,

My pCloud Account Email: okatsn@gmail.com


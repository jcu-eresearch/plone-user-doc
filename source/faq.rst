Frequently Asked Questions - FAQ
================================

The title bar is hiding my logo
-------------------------------

The title bar layout applies to all eSpaces and is designed for improve accessibilty. If your logo is 
hidden or obscured as shown below, eSpaces recommends reducing the number of first level items in your 
eSpace and keeping the titles short and descriptive.   

.. image:: images/hidden_logo.png
   :alt: My logo is obscured
   :align: center
   :scale: 50%
   
Our suggestion is to group content into separate logical areas. The top level navigation items
in an eSpace also represent the menu on mobile devices and thus should be kept to a minimum. 
Following these suggestions will aid in the usability and presentation of your site and ensure 
your logo is visible.

Transferring files
------------------

Uploading Multiple Files and Folders (Windows)
----------------------------------------------

We recommend you use Cyberduck

1. Go to http://cyberduck.io/ and download Cyberduck.
2. Open the setup file you downloaded. Install Cyberduck.
3. Launch Cyberduck from desktop or start menu.
4. Click onto the 'Open Connection' button on the toolbar.

.. image:: images/cyberduck-openconnection.png
   :alt: Open Connection

.. image:: images/cyberduck-settings.png
   :alt: Cyberduck Settings
   :align: right

5. In the pop-up window, enter your connection details as shown at the right.

   a. Select 'WebDAV (HTTP/SSL)' from the top drop-down menu.
   b. Server:   espaces.edu.au
   c. Port:     443
   d. Uncheck 'Anonymous Login'
   e. Username: 

      i. On your eSpace site, click on 'Sharing'
      ii. You will see a list of users, including your name. You username is displayed next to your name. It is a long alphanumeric string.   

   f. Password 

      i.   On your eSpace site, under your username, top right hand corner, click on Preferences
      ii.  Click on the Password tab.
      iii. Click 'Generate new password'.
   
   g. Path: "/<your eSpace Id>/" Obtain this from the url. e.g. https://espaces.edu.au/jay-test/
   
6. Click onto 'Connect' and your home folder should appear.
7. Now, drag and drop files to and from your desktop to this window, the folder on the site you've just connected to.
8. To save this connection, click onto the 'Bookmark' menu, and then 'New Bookmark'.  Enter and confirm any details you need and your bookmark is ready for easy access.


Uploading Multiple Files and Folders (Mac)
------------------------------------------

1. Using the Cyberduck client. See setup instructions under 'Uploading Multiple Files and Folders (Windows)' just above here.

2. Using the Finder client (for Mac OSX 10.4 or later).

   a. In the Finder, click onto the Go menu, and choose Connect to Server.
   b. Server Address: "https://espaces.edu.au/<your eSpace Id>" Just like your eSpace url
   c. If your system prompts you to verify the server's certificate, click Continue.
   d. At the authorisation prompt, enter your credentials and click OK.

      Username: 
         i. On you eSpace site, click on 'Sharing'
         ii. You will see a list of users, including your name. You username is displayed next to your name. It is a long alphanumeric string.   
   
      Password: 
         i.   On your eSpace site, under your username, top right hand corner, click on Preferences
         ii.  Click on the Password tab.
         iii. Click 'Generate new password'.
         iv.  Your new password is displayed in the 'Info' bar.
   
   e. You can now access your site from your computer, and copy files just as you would to anywhere else on your computer.

3. Older OSX Versions Details. It is recommended that you download and use Goliath - http://www.webdav.org/goliath/ 
   
Uploading Multiple Files and Folders (Linux)
--------------------------------------------

1. Gnome-based Systems Typically, Ubuntu and Debian operate with the Gnome desktop environment; follow these instructions if they suit your system.

   a. Click onto the Places menu, and choose Connect to Server.
   b. Under Service Type select either WebDAV (HTTPS) or WebDAV (HTTP) if you don't have the former.
   c. Enter the following details:
       i.  Server: espaces.edu.au
       ii. Port: 443
       iii. Folder: "<your eSpace Id>" e.g: https://espaces.edu.au/<your eSpace Id>
       iv. User Name: 
            1. On you eSpace site, click on 'Sharing'
            2. You will see a list of users, including your name. You username is displayed next to your name. It is a long alphanumeric string.   

   d. Check 'Add bookmark' if you want to save this location for later (and enter a bookmark name).
   e. When the Enter Password prompt appears, enter your site password.  You can choose to remember the password, if you so wish.
       i.   On your eSpace site, under your username, top right hand corner, click on Preferences
       ii.  Click on the Password tab.
       iii. Click 'Generate new password'.
       iv.  Your new password is displayed in the 'Info' bar.

   f. The WebDAV folder should appear under your Places menu, and on the Desktop as well.  Drag and drop files into this location to copy them to your site.

2. Other Linux Variations Linux distributions vary widely, but on any system with a command line, you can follow these instructions.

   The command line tool 'cadaver' is a WebDAV client. 
   
   a. Install this program using something like yum install cadaver or apt-get install cadaver
   b. Then connect using the command: cadaver https://espaces.edu.au:443/<your eSpace Id> just like your url
   c. If you are prompted to accept the certificate, enter y for yes.
   d. Enter your site credentials when prompted.
      User Name: 
      i.  On you eSpace site, click on 'Sharing'
      ii. You will see a list of users, including your name. You username is displayed next to your name. It is a long alphanumeric string.   

      Password:
       i.   On your eSpace site, under your username, top right hand corner, click on Preferences
       ii.  Click on the Password tab.
       iii. Click 'Generate new password'.
       iv.  Your new password is displayed in the 'Info' bar.

   e. This tool operates in a similar fashion to FTP or SFTP with get, put and ls commands.  Enter help for more information.

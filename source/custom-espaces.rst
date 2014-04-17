All about |project-name|
************************

|project-name| is an intuitive web platform for research collaboration and data
sharing.

Researchers can easily create eSpaces – web-based sites – that allow content,
files, and pages to be stored securely, with the flexibility of access via the
web and mobile devices. The system also provides granular permissions, allowing
a range of types of security. This makes |project-name| perfect for spanning a
range of researcher needs:

* Public-facing research portfolios
* Project pages
* Secure collaborative environments
* ...anything in between.

Use |project-name| as an access point for data and file storage, to discuss and
collaborate around content, and more. |project-name| provides simple methods of
uploading files and annotating them with comments between users.


Working with |project-name|
===========================

Getting started
---------------

Make sure you have perused the documentation on :ref:`logging-in` and have
authenticated to |project-name|.  The following documentation covers the basics
of configuring your eSpace - your self-contained web portal for your research
or your research group's collaboration.  For all other information about
content management and other |project-name| functionality, see
:ref:`adding-and-editing-content`.

Creating an eSpace
------------------

#. After logging in, the first thing to do is create your eSpace.
   Click on ``Create an eSpace`` on the top menu.

#. Complete the information on the form, including the following:

+-------------+-----------------------------------------------------+
| Metadata    | Description                                         |
+=============+=====================================================+
| Space ID    | This is the unique name that identifies your space. |
|             | It forms part of your eSpace URL, so ensure you use |
|             | a meaningful ID that describes your eSpace and is   |
|             | easy for users to remember.                         |
+-------------+-----------------------------------------------------+
| Space Title | The textual title of an eSpace, displayed in web    |
|             | search results and in eSpace listings.              |
+-------------+-----------------------------------------------------+

#. Click on ``Create`` and wait a moment as your eSpace is created.
   Once finished, the page will reload and you'll be able to get started!


Editing an eSpace
-----------------

After logging in to |project-name|, and having created an eSpace, you can add some
customisations. The following details highlight what changes can be made
to an eSpace itself.  For more information about managing other content,
see :ref:`adding-and-editing-content` and :ref:`managing-content`.

#. On the home page of your eSpace, click on the ``Edit`` tab.

   .. image:: /images/editeSpace.png
      :alt: Edit an eSpace
      :align: center
      :scale: 50%

   If your eSpace has a *default page* set as the display view, an information
   bar will be displayed that shows you are editing the view and not the eSpace
   itself (also called the *container*).  Click on the ``go here`` link to
   proceed with these instructions.

#. Complete the fields that you see to customise options and
   control the appearance of your site. Some fields add functionality to your
   eSpace, such as added analytics support.

   +----------------------+------------------------------------------------------------------+
   | Metadata             | Description                                                      |
   +======================+==================================================================+
   | Title                | The text title of your eSpace. You specified this                |
   |                      | when you created the eSpace, but can modify it at any time.      |
   +----------------------+------------------------------------------------------------------+
   | Summary              | Add text to describe the purpose of your eSpace.                 |
   +----------------------+------------------------------------------------------------------+
   | Custom Logo          | Click on *Choose File* to upload a logo. This replaces the       |
   |                      | default logo.                                                    |
   +----------------------+------------------------------------------------------------------+
   | Custom Logo Size     | Select a size for your custom logo. The logo will automatically  |
   |                      | be scaled according to your selection.                           |
   +----------------------+------------------------------------------------------------------+
   | Analytics Type       | If you wish to use Analytics, you can choose either              |
   |                      | Google Analytics Universal or Classic, depending on the required |
   |                      | settings. See :ref:`analytics-configuration` for details.        |
   +----------------------+------------------------------------------------------------------+
   | Analytics Identifier | Your unique identifier supplied by the Analytics provider.       |
   +----------------------+------------------------------------------------------------------+
   | Theme                | Select a theme to enable a different look and feel. This will    |
   |                      | change the overall appearance for all users using your Space.    |
   +----------------------+------------------------------------------------------------------+

#. Click on ``Save`` to finalise the changes. You can return and modify any of
   these settings at any time.


Sharing an eSpace
-----------------

eSpaces are made for sharing, either with colleagues at a local institution
or across institutions within Australia.  You can choose whether you'd like
to collaborate with associates across your entire eSpace or just inside part
of it.  To do this:

#. Ask your colleagues to log in to eSpaces at https://espaces.edu.au.
   You can send them the link to the documentation about :ref:`logging-in`
   to help them through the process.

   .. note::

       Because of the way that cross-instutional accounts work, your associates
       must log in first before you can share with them.

       Your colleagues will need to let you know they've completed this step so
       you know when to proceed.

#. After each of your colleagues have logged in once, eSpaces will now know
   about their accounts.  Once this has happened, you can continue following
   instructions for :ref:`sharing-your-content`.

#. If you'd like to share with the same people later, you can search and share
   with them immediately as they are already known to eSpaces.


Deleting an eSpace
------------------

In case you decide that you no longer require your eSpace, ensure that you have
a backup of any information that was previously stored there, and `contact us
<https://www.espaces.edu.au/contact-info>`_ with your request.  We'll confirm
this request with any other administrators that are also part of your eSpace.

This process may take a little while to enact.  Please also remember that if
you have had any information publicly accessible that web search engines and
other third parties likely have taken copies of the information since it was
made available.

.. _analytics-configuration:

Analytics configuration
-----------------------

An eSpace provides the opportunity for visitor tracking, via integrated
analytics configuration.  This means that eSpace administrators can keep
track of page activity, site views, visitor locations, and more, depending on
the capabilities of the analytics provider.

At present, configuration for Google Analytics is available; support for other
web analytical providers will be added in the near future.


Google Analytics
~~~~~~~~~~~~~~~~

To add support for Google Analytics to an eSpace:

#. Visit `Google Analytics <http://www.google.com.au/analytics/>`_ and
   follow the instructions in the `Google Analytics help centre
   <https://support.google.com/analytics/>`_.

#. Once you have created your account, and created a Google Analytics
   profile, the system will provide a ``Tracking ID``:

   .. image:: /images/google-analytics-trackingid.png
      :alt: Google Analytics Tracking ID
      :align: center
      :scale: 50%

#. Copy this tracking ID onto your computer's clipboard, or else
   write it down for reference.

#. Access the eSpace to be configured, following the instructions in
   `Editing an eSpace`_ and configure the ``Analytics`` fields accordingly:

   Analytics Type
      should be selected as ``Google Analytics (Universal)`` for all new
      profiles.
   Analytics Identifier
      should be completed by either pasting in or manually enter the Tracking
      ID previously recorded above.

#. Click ``Save`` at the bottom of the page.  Statistics typically take 24 hours
   to begin appearing in your Google Analytics profile.


Other providers
~~~~~~~~~~~~~~~

If eSpaces does not support a web analytics provider that you require, please
get in touch and our team will look at adding it as an option.


Finding an eSpace
=================

This page displays all eSpaces that you have access to and is visible
after logging in.  Click onto the ``Find an eSpace`` link on the top navigation
to see this listing.

.. image:: /images/findspace.png
   :alt: Find an eSpace
   :align: center
   :scale: 50%

.. note::

   This page only displays eSpaces with top-level access.
   It is possible for collaborators to grant access to individual areas
   within a given eSpace, but not the home level.  If this is the case,
   you will need to access the links you have been given directly.

Seeing my eSpaces
=================

This page displays all eSpaces that you have created or else have been marked
as a 'creator' on.  After logging in, click on the *My eSpaces* link on the 
top navigation to see this listing.

.. image:: /images/myspace.png
   :alt: My eSpaces
   :align: center
   :scale: 50%


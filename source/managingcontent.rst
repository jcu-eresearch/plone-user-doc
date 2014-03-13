.. _managing-content:

Managing your content
*********************

What is a workflow?
===================

.. note::

   Workflows play an important role in your portal's security and control who
   can see a document.


Workflows and document publishing
---------------------------------

A workflow is a process that your document passes through before it becomes 
available to others via the portal. This process ensures that content posted
meets standards set by your administrator.

When an item is first created, its state is **Private**. Most users will
require their documents be reviewed before they are published, requiring a 
section or site administrator to be part of the workflow.

.. image:: images/statedropdown.png
   :alt: State Drop Down Menu
   :align: right
   
Changes to a piece of content's workflow state (and thus its visibility) are 
controlled via the State *drop-down menu*, visible when you are viewing that 
piece of content. It is this menu that will also show you the current state 
of your content. If you click onto the ``Advanced`` link in this menu whilst 
looking at a folder, you can change multiple items at the same time. 

At each point in the workflow your document will have a different state. 
These states are listed below.

+--------------------+---------------------------------------------------------------------------------------------------------+
| State              | Description                                                                                             |
+====================+=========================================================================================================+
| Private            | * These items are only visible and editable by their owners and site managers with administrator access |
|                    | * You can still share this content with certain people through the ``Sharing`` tab.                     |
|                    | * Content in this state need to be published before being visible on the Internet.                      |
+--------------------+---------------------------------------------------------------------------------------------------------+
| Pending (submitted | * This content has been submitted for review through workflow and is awaiting a decision                |
| for publication)   | * A site or section administrator with Review rights needs approve this.                                |
|                    | * It can be accessed in the same way as other Private content                                           |
+--------------------+---------------------------------------------------------------------------------------------------------+
| Published          | * These items are available to all site visitors                                                        |
|                    | * They appear in the navigation tree, and are accessible through search                                 |
+--------------------+---------------------------------------------------------------------------------------------------------+


Reviewing content
=================

.. note::

   If you have the right permissions, you'll have the ability to review content
   for yourself and other users.

The review list is shown on your dashboard when you have ``review authorisation``
permissions and there are items to review. The review list contains items that
have been submitted by for review.

.. image:: images/review_list.png
   :alt: Review list
   :align: center

If you don't see this on your dashboard, you can add it easily -- it's called a
``Review list portlet``.

Reviewing an item
-----------------

Click the content link to open the item.

At this point you have the following choices for this item:

Reject the item
^^^^^^^^^^^^^^^

Reject the item by selecting ``Send back`` from the ``State`` drop-down menu.

* You would reject the item if you feel that it is not appropriate for the 
  site, or if it requires more work.
* This returns the item to the ``Private`` state.
* If you want to add comments describing why the document was rejected, 
  click onto the ``Advanced`` option in the State menu first before rejecting 
  it. Enter your comments here and select ``Reject`` to change the document's 
  state.

Approve the item
^^^^^^^^^^^^^^^^

Approve the item by selecting ``Publish`` from the ``State`` drop-down menu.

* This changes the content into the Published state.
* The content is now publicly available on the Internet.
* Keep in mind that you may need to adhere to organisational policies and/or 
  procedures when publishing documents publicly. The publishing process is 
  your responsibility and your username is associated with all publications.

Edit the item
^^^^^^^^^^^^^

As the reviewer, you have permission to edit the document yourself. You can make
any changes that are necessary and then approve the item.

Do nothing
^^^^^^^^^^

If you’re not sure whether this item is suitable or not, you can just leave it
as it is.

This will leave the document in its pending state for the time being. Keep in
mind that it will eventually need to be either approved, edited or rejected.
You may wish to seek advice from another site administrator or reviewer
about the content.


Editing a published document
============================

.. note::
  Editing published content is another important process in content management.

In order to make an edit to a previously published document, there are two 
choices, depending on who you are:

Authors
-------

* The author can choose ``Retract`` from the State drop-down menu, which moves 
  the document back into the ``Private`` state.
* The author then makes the change and saves the document which adds it back 
  to the review list.
* It must be approved by the reviewer/manager and to be published again.

Managers
--------

* Any site administrator can edit any document or content.
* Upon editing content, it is republished without the need to go through the 
  workflow process again.


Adding an updated version of a file
===================================

**A common task is updating a given file or image with a fresh version.**

In order to upload a newer version of a file, you will need to edit that item.

#. Choose the item from the **contents view tab** in your folder, and then 
   click the **Edit** tab.

.. image:: images/edit_image.png
   :alt: Editing an image
   :align: center

#. Only the fields with a red box are required, as when you create the content
   originally.

#. To update your file, click the **Replace with new file** radio button, and
   click the **Browse** button to select the new version of the file.

#. Click the Save button to commit your changes. 

.. _sharing-your-content:

Granting access to your content
===============================

**Sometimes you'll want to give access to individuals rather than the whole
Internet.**

You can choose to share your document with with a particular person.
Descriptions for how to set up each of these permissions are listed below.

Types of permissions
--------------------

First, make sure you're aware of which permissions you are granting individuals
or groups of users.

==========           ========================================================
Permission           Description
==========           ========================================================
Can add              Allows new content objects to be created in this folder,
                     granting access to the ``Add new`` menu. This has no
                     effect on non-folder content.
Can edit             Allows editing of existing content, granting access to
                     the ``Edit`` tab against content.
Can review           Allows the user to publish and review content, granting
                     access to extra controls in the ``State`` menu.
Can view             Allows the user to see private content. Use this
                     permission to grant access to specific folders and
                     content areas on a portal.
==========           ========================================================


To share with other users
-------------------------

.. note::

   The creation of groups for sharing is not supported by eSpaces.

.. image:: images/sharing_page.png
   :alt: The Sharing page
   :align: center
   :width: 500px

* Browse to the piece of content that you'd like to share, or browse
  to the folder that surrounds the content if you'd like to grant
  access to the entire folder.

* Click on the **Sharing** tab 
  
* Search for a name by typing it into the search box and clicking the
  **Search** button. You can also search for partial names, email addresses,
  or user IDs as well.

* When the appropriate entry appears, select the permissions in the same
  row to grant different types of access.  You should refer to `Types of
  permissions`_ mentioned above if you're unsure what each permission does.

* Click the **Save** button to save the changes.

Inheriting permissions
^^^^^^^^^^^^^^^^^^^^^^

The ``Inherit permissions from higher level`` checkbox means that the current
content item or folder will have the same permissions as the parent folder.
This means that the permissions are inherited **downwards** from higher levels.

You may wish to enable or disable this functionality depending on your security
requirements.  For example, if you want one specific area to have customised
security, then you may want to disable this option.  Alternatively, if you want
security to automatically apply from the higher-level folder, leave this
enabled.

To enable or disable this functionality:

* Select or deselect the checkbox on the Sharing page.

* Click the **Save** button to save the changes.


Enabling next/previous folder navigation
========================================

**To make viewing the contents of a large folder more intuitive you may wish to
enable the next/previous navigation feature. This is a simple task in the Plone
environment.**

To add next/previous navigation:

* Browse to the folder you wish to apply navigation to.

* Click the **Edit** tab.

* Click the **Settings** tab.

* Enable the checkbox marked **Enable next previous navigation**.

* Click the **Save** button.


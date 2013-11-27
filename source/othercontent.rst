Using other types of content
****************************

Adding images
=============
**You can upload images to your site for inclusion in your Pages or for separate display.**

Images may be added by selecting image from the **add new**  menu on the portal menu bar.

.. image:: images/add_new_menu1.png
   :alt: Add new menu
   :align: center

If the image is of type . **gif** , **.jpg**  or **.png** , it should be 
viewable in the web browser and the image will not need to be downloaded 
separately. The metadata for an image is very much the same as any other 
type of document.


Adding and editing events
=========================
**You can create events on your portal for others to see.**

In order to add an event to the calendar, select **event**  from the Add 
New drop-down menu.

.. image:: images/add_new_menu1.png
   :alt: Add new menu
   :align: center

The following metadata items are required. Although not required, **Location** 
is a useful bit of information to include.

+-----------------+--------------------------------------------------------+
| Metadata item   | Description                                            |
+=================+========================================================+
| Title           | A short description of the event                       |
+-----------------+--------------------------------------------------------+
| Description     | More details about the event                           |
+-----------------+--------------------------------------------------------+
| Location        | Where the event is going to be held                    |
+-----------------+--------------------------------------------------------+
| Event starts    | Date/time in the format                                |
+-----------------+--------------------------------------------------------+
| Event ends      | Date/time in the format                                |
+-----------------+--------------------------------------------------------+
| Attendees       | List of people who are to be attending                 |
+-----------------+--------------------------------------------------------+
| Event URL       | A web address related to the event                     |
+-----------------+--------------------------------------------------------+
| Contact Details | Various details about whom to contact about the event. |
+-----------------+--------------------------------------------------------+


Adding and editing News items
=============================

**You can also add and edit News items on the portal.**

.. image:: images/add_new_menu1.png
   :alt: Add new menu
   :align: right

News items are created in the same way as other documents, but will appear
under the News tab or portlet once the item is published. The type of display
will depend on your portal's configuration.

To create a News item, click **News item**  from the add item menu on the 
Plone bar.

Enter the information for the content and click the **Save** button.

.. note::

   only **Title**  and **Body**  text are required.

+---------------+--------------------------------------------------------+
| Metadata item | Description                                            |
+===============+========================================================+
| Title         | A short descriptive title                              |
+---------------+--------------------------------------------------------+
| Summary       | A paragraph long description of the document           |
+---------------+--------------------------------------------------------+
| Body Text     | The main text of the document.                         |
+---------------+--------------------------------------------------------+
| Image         | An image to appear as part of the news item. Click the |
|               | browse button to choose the image                      |
+---------------+--------------------------------------------------------+
| Image Caption | The text that will appear under the image              |
+---------------+--------------------------------------------------------+


Adding Links
============

**You can create links within your portal. These act essentially as bookmarks or favourites to other web pages or sites.**

Links can also be added into Plone. When a user clicks onto a given link, they'll be automatically taken to the target of the link. 

.. note::
   if the user has access to edit a given Link, then they'll be taken to a view explaining the link.

To add a link, choose **Link**  from the **Add new**  menu.

.. image:: images/add_new_menu1.png
   :alt: Add new link
   :align: center

Add the metadata.  Only **Title** and **URL** are required.  To finish, click the 
**Save** button.

+-------------+-------------------------------------------------------------+
| Metadata    | Description                                                 |
+=============+=============================================================+
| Title       | A short description of the link                             |
+-------------+-------------------------------------------------------------+
| Description | A longer description of the links.Can be a few sentences in |
|             | length                                                      |
+-------------+-------------------------------------------------------------+
| URL         | The complete url for the link                               |
+-------------+-------------------------------------------------------------+


Organise your content using folders
===================================
**Folders are typically used to structure your physical content into a 
logical fashion; you can use them on your portal too.**

You can create folders within your folder in order to store your content in a 
logical fashion, making it easy for others to find your files.

To add a new folder, navigate to the place where you want the folder to be created and 
choose **folder** from the **Add New** drop-down menu.

.. image:: images/add_new_menu1.png
   :alt: Add new folder
   :align: center

The metadata for folders is very simple. Just add a **Title**  and a 
**Description** for the folder. You can now add content into this folder, 
like you would on your normal computer desktop!


Publishing a folder
-------------------

You can choose to make this folder public if you would like to share the data
within it. This can be changed later if necessary.

The same workflow associated with normal content applies to folders, so have 
a look at :ref:`creating-public-content` to see how.

Adding a Collection
===================

**A collection is a bit like a saved search - it allows you to display a list of contents from
the site that matches some pre-specified criteria.**

For example, you might be interested in

- New content - all content created on the site in the last 7 days
- About to expire content - all content with an expiration date with the next 7 days
- Your content - all content created on the site by you.

To add a collection, simply select the Collection type from the **add new** menu. You need to 
give the collection a Title and add *Search Terms*. Once your are satisfied with the results, click *Save*.

In the example below, The collection displays all content created in the last 7 days. Use the combo 
to add different search criteria. A preview of the results will be displayed. 

.. image:: images/collection_criteria.png
   :alt: Collection criteria
   :align: center
   
The search criteria for the collection can be based on any of the meta-data associated with content.
Some of these are listed below but there are more:

- Title
- Tag - the keywords used to describe an item
- Creation Date - time and date an item was created
- Creator - user who created the content
- Review State - the contents workflow state e.g. published or private
- Expiration Date - the time and date the content will no longer be available
- Location - where in the site the content resides


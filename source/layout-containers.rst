Folder display options
======================

Display View
------------

Within |project-name|, site structure is developed using folders, some of
which can be nested inside of each other and moved around as required.  How each
folder appears to a visitor or site user depends on what content items are
inside that folder and how the folder's display view is configured.  
For instance, a folder with a number of images inside could be displayed as a
gallery; a folder with files could list those files; or a folder with a page 
inside can be customised to display a home-page instead of an automated list.

|project-name| provides several different manners in which to display the
contents within a folder. The standard views are listed below.

.. note::
   Keed in mind that the top-level of any site is also a folder, and has 
   the same configurability for display.

+-------------------------+----------------------------------------------------+
| Folder view             | Description                                        |
+=========================+====================================================+
| Summary view            | Lists the title and description of the content     |
+-------------------------+----------------------------------------------------+
| Tabular view            | Lists the content items in a table format          |
+-------------------------+----------------------------------------------------+
| Thumbnail view          | Lists images in thumbnail form and other items     |
|                         | below the thumbnail gallery.                       |
+-------------------------+----------------------------------------------------+
| Standard view           | Lists all content items in the folder and gives    |
|                         | title, description, creator and date details in    |
|                         | a compact format.                                  |
+-------------------------+----------------------------------------------------+
| All content             | Displays the underlying main text from all content |
|                         | items inside the folder. For example, if you have  |
|                         | a folder with several Page items, then the folder  |
|                         | would then display the full text of each of these  |
|                         | pages, one after the other.                        |
+-------------------------+----------------------------------------------------+
| Content item as default | Lets you set a particular item as the home page    |
|                         | (``default view``) for this folder. See            |
|                         | :ref:`default-view` for more information.          |
+-------------------------+----------------------------------------------------+

Determining the current view
----------------------------

In order to determine the current view for a given folder:

#. Browse to the given folder you would like to change.

#. Click the ``Display`` drop-down menu.

#. Note the highlighted view in the menu listing.  This is the current 
   view configuration.


Changing the view
-----------------

In order to change the view of a given folder:

#. Browse to the given folder you would like to change.

#. Click the ``Display`` drop-down menu, and choose the different view you
   would like to apply.

   .. image:: images/display_view.png
      :alt: Folder display menu
      :align: center
      :width: 300px

#. The page will reload and display the new style of view.  Other visitors to
   the content item will see this change immediately.

Each type of folder view can easily be changed as required, especially in order
to try out other appearances.

Deselecting a default view
--------------------------

If a folder has a default view configured, you can de-select this by
simply selecting another `Display View`_.  If you'd like the default
appearance for a folder to be restored, choose ``Summary view``.


.. _default-view:

Change the home page for a folder
=================================

By default, |project-name| displays a list of the contents of all folders and
a brief description. In order to change this view, you will need to create a
new page and set the folder to use this page as the default view for the
folder.

.. note::
   If you're ever curious or unsure about how a folder is configured for
   display, click the ``Display`` drop-down menu and note the selection.
   This explains whether a folder is configured as an automated listing or
   with a default view set.

#. After logging in to the portal, click into the folder you'd like to change.
   Make sure you've already created a page to set as its default view.

#. Click :menuselection:`Display --> Select a content item as default view`.

.. image:: images/selectcontentitem.png
   :alt: select_content_item
   :align: center

#. Select the item that you would like to be displayed as the default page of
   the folder and click the **Save**  button.

#. You should now be able to see the page appear as the default view for the
   folder. Keep in mind that you will need to publish this page for other
   users to see it.

.. _sorting-a-folder:

Sorting a folder
================

.. only:: folder_sorting

   Sorting manually
   ----------------

The contents of a given folder are displayed in numerous ways across the site,
including in navigation portlets, as top-level tabs, and in folder listings
displayed on pages.  There will come times where the ordering is incorrect and
you'd like to change this.  To manually adjust ordering:

#. Browse to the folder that contains the content to be reordered.

#. Click onto the ``Contents`` link.

#. Click and drag the handle at the far-left of any content item up and down to
   reorder the content.  Note how your cursor changes into an up-down arrow
   when hovering over the handle.  The content can be ordered in any fashion
   you would like.

#. Once finished, click your browser's reload button, or browse to another
   folder where a listing appears.  Notice how the order has now adjusted to
   suit your changes.

#. Repeat as required if the ordering isn't quite right

   .. note::
       If there are many content items in the folder, the ``Contents`` view may
       paginate the listing into groups.  If this is the case, you can view the
       complete listing using the ``Show all items`` link at the bottom of the
       page.


.. only:: folder_sorting

   Sorting based on criteria
   -------------------------

   |project-name| provides a helpful view for re-ordering the contents of folders,
   and allows sorting on a number of different criteria, including title,
   modification date, and more.

   .. note::
      Remember that folder ordering is not automatically applied. You will need to
      follow this process whenever the order should be updated.

   To access the sorting view:

   #. Browse to the folder that you wish to re-order.  Ensure you are looking at
      the ``View`` tab, which will be the main folder view.

   #. Click to :menuselection:`Actions --> Sort folder` to access the sorting
      controls.

      .. image:: images/sort_folder.png
         :alt: Sort folder menu
         :align: center

   #. Choose the criteria you wish to sort on, including enabling the reverse sorting
      option, if so desired.

   #. Click ``Sort`` to complete the process.

   #. Inspect the results in the contents listing.  To re-order contents,
      click back to the ``View`` tab and start again.


Enabling next/previous folder navigation
========================================

To make viewing the contents of a large folder more intuitive, you may wish to
enable the ability for users to skip forwards and backwards through a folder's
contents.  This is called the **Next/Previous Navigation** feature and enabling
this for a folder displays controls to jump to the next or previous page when
looking at a folder's contents.

To add enable next/previous navigation:

#. Browse to the folder you wish to apply navigation to.

#. Click the ``Edit`` tab.

#. Click the ``Settings`` tab.

#. Enable the checkbox marked ``Enable next previous navigation``.

#. Click the ``Save`` button.


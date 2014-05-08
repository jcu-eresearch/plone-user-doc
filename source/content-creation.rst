.. _adding-and-editing-content:

Adding and editing content
**************************

|project-name| is built to be a fully-featured :term:`Content Management System
(CMS)`, meaning that users are able to add and edit content directly via the
web.  Within |project-name|, all content management is done in-place, unlike
some other content management systems which require you to use an
administration interface or similar. Simply put, where you put the content is
where it will appear and exist.


Creating new content items
==========================

|project-name| stores content as individual objects that can be accessed by a
site visitor.  Essentially, as a user, you create a content item and it is
stored by |project-name|. For example, you may wish to store a web page that
someone can view, an image that could be included in a page, or a file that can
be downloaded.  There are several ways of creating content on |project-name| -
the most commonly used method is via the web interface.

What kind of content can I post?
--------------------------------

Before getting started, take a moment to become familiar with the different
types of content that the site can hold. The following lists the basic types
that |project-name| can store.


.. include:: introduction.rst
   :start-after: .. content-start
   :end-before: .. content-end


Special types
-------------

|project-name| also features several content types that perform specialised
tasks.  These include:

Collection
    A grouping of other content. Similar to a saved search, in that content of
    a certain type is grouped together. Collections can only be added by an
    administrator.

.. only:: forms

    Form Folder
        A special folder that is used to build a form. Form folders can have
        fields, data capture tools, and special pages added to them.  Forms
        are especially useful for making a site interactive.


.. _creating-new-content:

Creating new content
--------------------

.. note::

    In order to create new content on |project-name|, your user account requires
    specific permissions in the area of the site you wish to add the content.
    Depending on the site's security configuration, you may already have this
    access or may need to request it from your site administrator.

    To determine whether you have access, browse to the area that you wish to add
    content. If you can see the ``Add new`` drop-down menu, permission has been
    granted.

Follow the steps below to create a new content item.

#. Ensure that you are logged in.

#. Browse to the location you wish to create the new content item.

   For example, if you would like to create a new Page in a section called
   **About Us**, then you would browse to the **About Us** section in order to
   create it there.

#. Locate the :menuselection:`Add new` drop-down menu and click it. You will
   see a list of content types that you can choose:

   .. image:: images/add_new_menu.png
      :alt: Add new menu
      :align: center

#. Choose the appropriate type of content you wish to create.

#. Fill in the fields on the creation page.  Note that some fields may be
   marked as required.

#. Click the ``Save`` button to create the content. This may take a moment as
   your content is created.

#. The page will reload and display your new content item.


.. _editing:

Editing existing content items
==============================

You can edit any item that you have created or that you have been granted
access to.  Editing most types of content will track historical changes,
allowing you to jump back to any point in the content's history and either view
that old version or restore it.

.. important::
   File and Image content items will not track previous versions, due to
   the potential for significant storage required.

To edit a content item:

#. Browse to the content item you wish to edit.

#. Click on the ``Edit`` tab.

.. image:: images/edit_button_on_toolbar.png
   :alt: Edit Button on Toolbar
   :align: center

#. Edit the content item, changing the relevant fields that displayed.

#. For most content items, you have the ability to add comments in the ``Change
   Note`` field.  If you add a description of your changes, they will be
   recorded against the content item's history, which can assist if you ever
   need to revert these changes.

#. Click the ``Save`` button to commit the modifications.

#. The page will reload and display your modified content item.


Uploading a file
================

You can upload any files accessible on your local computer to |project-name|,
including files that might be located on a network share drive.

The instructions below describe the steps to add a pre-existing file to the
site. The steps are similar for other types of content, such as images.

.. image:: images/add_file.png
   :alt: Adding a file
   :align: center

#. Browse to the location you wish to upload one or more files.

#. Click :menuselection:`Add new --> File`, following the same process as
   creating other content.

#. Add relevant file metadata, and browse for a file to upload.  Adding extra
   information as a title and description will make the file easily
   discoverable and improve its appearance in navigation and listings.

#. Click the ``Save`` button to upload the file to the site.

#. The page will reload and display the uploaded file, and show how it can be
   downloaded later.

If you have multiple files to upload, it is possible to connect to
|project-name| using WebDAV using the instructions in
:ref:`transferring-files`.

.. image:: images/download_file.png
   :alt: Download the file
   :align: center

The resulting page shows what visitors to the page will see, including extra
details such as the file's type, size and date modified.

Adding images
=============

Images can be uploaded to |project-name| for inclusion in your Pages or for
separate display in collections, such as photo albums or image galleries.

#. Follow the same process for `Uploading a file`_, except that rather than
   choosing the ``File`` content type, use :menuselection:`Add new --> Image`.

   .. image:: images/add_new_menu1.png
      :alt: Add new menu
      :align: center

#. All other steps are the same as the above process and the metadata required
   matches that required for **File** content.

Once created, if the image is a browser-compatible format (GIF, JPEG, or PNG)
then it will be displayed on content view pages. The image can now be inserted
into Page content using the visual editor.

Uploading an updated version of a file or image
===============================================

A common task is updating a given file or image with a fresh version. The
process follows the same methods as :ref:`editing`.

.. important::
   File and Image content items will not track previous versions, due to
   the potential for significant storage required.  This means that by
   uploading a new version of a file you will permanently replace the older
   copy.


#. Browse to the content item you wish to edit.

#. Click on the ``Edit`` tab.

   .. image:: images/edit_image.png
      :alt: Editing an image
      :align: center

#. Only the marked fields are required, as was the case when you created the content
   originally. Note that fields are already populated with the existing
   content metadata.

#. To update your file, click the ``Replace with new`` button, and
   click the ``Browse`` button to select the new version of the file.

#. Click the ``Save`` button to commit your changes and replace the file.


Organise your content using folders
===================================

Folders are typically used to structure your content items in a
logical, structured fashion, much as you would use them on a computer's desktop
or hard drive.  |project-name| supports creating any number of folders, and
these can be nested or organised in any fashion that fits best.  To add a new
folder:

#. Browse to the location you wish to create the folder. This might involve
   *traversing* down several levels of folders to find the right spot for your
   folder.

#. Click :menuselection:`Add new --> Folder`, following the same process as
   creating other content.

   .. image:: images/add_new_menu1.png
      :alt: Add new folder
      :align: center

#. Enter the relevant metadata for the folder; a title that will be displayed
   in navigation and a description for explaining what the folder contains.

#. Click the ``Save`` button to finish the creation process.


You can now add content into this folder, including folders as well, following the
:ref:`creating-new-content` process.


.. _setting-the-document-metadata:

Setting the document metadata
=============================

.. important::

    Document metadata is very important because users and visitors to the site
    need to be able to easily locate and identify your content.

    Appropriate titles and rich descriptions will improve the appearance of
    your pages and content, and will improve searchability both on the site,
    and if the content is public, via search engines.

Each item on |project-name| has specific properties, called *metadata*. This
metadata is displayed in various fashions on the site, such as titles being
displayed as a heading when viewing a page and in navigation, and descriptions
allowing documents to be found easily via searches.  As you experiment with
managing content, you will notice how changing metadata fields affect the
display of content on the site.

If you've gone ahead and created content or edited existing content, you've
already experienced modifying metadata.  Although it's a fancy word, *metadata*
just means data about the content that you've created.


Types of metadata
-----------------

.. note::

    Keep in mind that metadata will vary from one content type to
    another.

In general, however, the most common metadata consist of the following:

Title
    The title of the item, which is displayed in the title, as a heading, in
    navigation and listings.
Description
    A short description of the content, which will be displayed as a subtitle
    on content, as well as being used in searches and search engine metadata.
Body text
    Rich text which can be crafted to be displayed on the content item. For
    content types such as Page, News Item, and Event, this will feature as the
    main content on the page. It is possible to cut and paste content in from
    other documents and applications. Note that not all content types have this
    field.
Change note
    A textual note that describes changes that are being made to a given
    content item at one particular time. Making change notes enables you to
    easily ascertain what happened to a content item, when it happened, and who
    performed the action.


.. _setting-advanced-metadata-properties:

Setting advanced metadata properties
====================================

You can control your content even further with advanced metadata properties.

In order to control various aspects of how your content interacts with
|project-name|, there are many other metadata aspects that can be modified.
To see the complete overview of what metadata can be modified for a given
content item:

#. Browse to the content item you wish to modify.

#. Click on the ``Edit`` tab to access the edit interface.

#. Look for these collapsed tabs on the page:

   .. image:: images/metadata_tabs.png
      :alt: Extra tabs
      :align: center
      :width: 150px

The extra metadata items are described below. Keep in mind that some of these
aspects won't appear on all content types, or might appear under different tabs
for certain content types.

Categorisation
--------------

Tags
    Categories that the given content it should be associated with. Content
    associated with the same tags can be found via search. Tags will also be
    displayed when viewing the content item.
Related items
    Associate one item to other content that exists on the site.  Related items
    will be displayed when viewing the content item.
Location
    A textual location string associated with the content. This will be
    displayed beneath the content item's metadata when viewed.
Language
    Specify the language that the content item has been written in or for.  By
    default, content on |project-name| will default to English.  Note this is
    a metadata-only field and has no effect on the actual text of the content.


Dates
-----

Publishing Date
    Configure a publishing date to hide the content from navigation until the
    date and time has passed. For instance, use this for a news item that
    should be visible after a certain time. Also known as the *Effective Date*.
Expiration Date
    Configure to hide the content from navigation once the date and time has
    passed. For instance, use this for a news item that should only be visible
    until a certain time.


Creators
--------

Creators
    A line-by-line list of user IDs (or full names, if no user exists) of
    creators for the given content item. The principal creator - the user
    listed first - will be displayed in the content item's byline as ``by
    [user's name]``.
Contributors
    A line-by-line list of names of contributors to this piece of content.
    Contributors are displayed in the content item's byline.
Rights
    A statement of copyright or other information regarding the content object.
    Rights are displayed in the content item's byline.

Settings
--------

Allow comments
    Toggle whether other users can comment on the given contnet item.  For
    some content types, this will be enabled by default.  Enabling this will
    display a comments form at the bottom of the content item.
Exclude from navigation
    Explicitly exclude the current content item or folder from appearing in
    navigation listings, including navigation portlets or the top-level
    navigation tabs
Presentation mode
    For Page content items only.  Displays a special presentation link that
    automatically generates a slideshow from page content.  This relies on a
    well-structured document with headings and lists to work well.
Table of contents
    For Page content items only. Displays a table of contents on the page,
    drawn from headings and subheadings included in the body text. This is a
    quick and easy way of helping users navigate your page, especially if the
    given page is lengthy. Ensure that your page content is divided up into
    logical sections, with appropriate headings and subheadings for this to be
    most effective.


.. _renaming-content:

Renaming content
================

Within |project-name|, content is identified using short names, which are
unique within any given folder or area and are used as part of the item's URL;
you'll see the identifier in your web browser's address bar.

This ID is automatically generated based upon the ``Title`` that was specified
when the content was first created.  This will automatically remove any
special characters that are disallowed in URLs and attempt to normalise the
short name.

In some cases, the default short name assigned will be either overly
complicated or simply not indicative of what the content consists of.  The
good news is that you can easily adjust the short name to be anything you'd
like.

.. _links-maintained:

.. note::
   Don't worry about existing links to your content!  |project-name| will
   automatically keep track of all of your old short names and URLs such that
   anyone still using old links will be redirected automatically to the new
   address.  Any links within your own content on |project-name| will
   automatically point to the new short.

To do this, decide whether you wish to rename just one item or several:

Renaming one content item or folder
-----------------------------------

.. note::
   If you're attempting to rename a folder and the folder has a default view,
   the site will ask you to rename the default view itself, rather than the
   surrounding folder. To access the folder explicitly, see
   :ref:`renaming-multiple` and access the folder using its parent. Read more
   about :ref:`Default views [default-view]`.

#. Browse to the given content item or folder you wish to rename.

#. Click :menuselection:`Actions --> Rename`.

#. Adjust the short name or title as required.

#. Click ``Rename all`` to complete the process.

#. Your content is now accessible using the new short name and URL.
   See the `note above <links-maintained_>`_ for details.


Renaming several items at once
------------------------------

#. Browse to the folder that holds the content items or folders you wish to
   rename.

#. Click ``Contents`` to view the main contents listing for the folder.

#. Select the checkboxes next to each item in the listing you wish to rename.

#. Click the ``Rename`` button at the very bottom of the listing.

#. Adjust the short names or titles as required. You do not need to change
   every field that is present, only what you want to modify.

#. Click ``Rename all`` to complete the process.

#. Your content is now accessible using the new short name and URL.
   See the `note above <links-maintained_>`_ for details.


Benefits
--------

Benefits of simple, descriptive short names will help in several ways:

* Shorter identifiers make for shorter URLs.  Google and other search engines
  will value shorter, descriptive addresses and rank your content higher.

* Remember that users may be typing in your web URL directly. Shorter URLs
  will help anyone doing this.  This is especially useful if you're creating
  publications or emailing links to people.

* Having a shorter URL with clear words will make identifying what your page
  is about easier.

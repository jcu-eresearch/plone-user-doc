Introducing |project-name| and Plone
************************************

|project-name| utilises open-source :abbr:`CMS (Content Management System)`
called `Plone <http://www.plone.org>`_ to allow users to easily share content,
files, and other digital objects within a web environment without needing to
learn web authoring technologies.  Being a :abbr:`CMS (Content Management
System)`, Plone can be used to constructure a flexible, content-driven
website, interactive web portal, or a secure collaborative workspace.

Access |project-name| at |project-url| to get started.


Site Layout: An Overview
========================

The |project-name| site will be laid out in a similar fashion to that shown
below, depending on what features and customisations have been made. Remember
that the image of the site will almost certainly look slightly different to
what is shown below as both content and overall theme, including *fonts*,
*colours*, *layout*, may have potentially been customised.

This example shows a user with full access.  How |project-name| appears to you
depends on whether you are logged in, and what permissions your user account
has in any particular area of the site. Permissions are dynamic and can change
across different folder or content, depending on the site.

.. image:: /images/site_layout.png
   :align: center
   :scale: 75%


1. **Top navigation tabs** are links across the top of a page are the top-level
   of navigation.  Primary folders or other types of content can be added or
   changed here with appropriate permissions. Typically, a site administrator
   will configure these top-level links.  For the general public or normal
   users, however, these serve as a quick way to access the main areas of
   information on the portal.

2. **Content management views** are the tools for editing and managing content
   that you have access to. If this set of tabs is not present, then it is
   likely that you only have view access to the current folder or content item.

3. **Content action menus** is a set of menus that perform various actions
   relating to the management of content:

   State
      This controls the workflow state (and thus permissions) for content.
   Add new
      Create and upload of new content, images, folders and more. Content is
      created by type, and this menu lists all types of content a user can
      create.
   Display
      Controls the appearance of a folder or a content item. For example,
      folders can be configured to show dynamic listings or tables, or
      otherwise have a content item show as its *home page*.
   Actions
      Provides the ability to cut, copy, and paste content items
      within a site, as well as the ability to delete and rename items.
      Other custom actions may be present underneath this menu.

4. **Search** is a search engine for content on the site.  Users can enter
   keywords from any part of content, including titles, descriptions, and full
   text to find results. Content inside of various files, including PDFs,
   Microsoft Office files and more, are searchable.

5. **Main page content** displays the primary body of information on a given
   page is displayed here, which will change dependent on the type of content
   being viewed.  If the current content item is a Page, then the body of the
   document will be displayed.  If the current item is an Image, then a
   thumbnail and picture metadata will be shown. If the current page is a
   Folder, then this may display a listing of content present or be configured
   to show just a single page.

#. **Portlets** are small windows of information may be configured on the left
   or right-hand side of any page.  Portlets typically display snippets of
   content and links to other information on a site. One such example is a
   ``News`` portlet, which will aggregrate information about news items that
   exist on the site. There are a number of different portlets available by
   default, including some that can pull in information from external sources
   like RSS feeds.

#. **Personal menu** is a drop-down menu revealing access to personal
   preferences, the user dashboard, and the ability to log out. Site
   administrators can use this menu to access the site control panel. Certain
   other options may be available depending on your level of access.


Much ado about content
======================

There are many types of content that can be created, viewed, downloaded or 
commented upon with a site, including:

.. content-start

Event
   An upcoming event, meeting, conference, or some other incident. Objects of
   this type typically appear under events listings on the site.
File
   Individual content uploaded from a local computer. Users may download
   or access the given file via links inside Pages or directly from Folder
   listings.
Folder
   Similar to those on a hard drive, folders contain content and are
   used to give a site structure.  Folders can be nested to any depth
   required and will typically be displayed in navigation listings for ease of
   access by users.
Image
   Storage type for pictures uploaded from a local computer.
   Images can be inserted into Page content, displayed in albums and lists,
   and otherwise stored for viewing.  Supported image types include JPEG,
   GIF, PNG and TIFF.
Link
   Automatic link to another web address, which may be another item
   in the portal or to an external resource.
Page
   The main content for a site is contained within Pages, which can feature
   text, images, hyperlinks, and other rich HTML.
News Item
   A piece of related to a notable occurrence, such as a press release or
   update. Objects of this type typically appear under news listings on the
   site.

There may be others based on the site configuration and your user's level of
access.

By default, content that is created will be displayed in navigation listings
for ease of access. This behaviour is customisable either on a site-wide basis
or for individual content items or folders.
.. content-end

For in-depth information about content management, see
:ref:`adding-and-editing-content`.



Navigation within the site
==========================

|project-name| is similar to other sites and web-based systems: they consist of
structure and content and feature a web-based editor to add and modify content.
For example, a site may have any number of folders, images, pages, files, and
other types of content. The structure can be nested in any format, and as deep
as required, much like structuring a computer's hard drive or a network share.

As new content is added, it will appear either in the top-level navigation
of the site, or if placed into sub-folders and nested, then in the ``Navigation``
portlet listing, which appears automatically as required.

Read more about :ref:`customising-layout-design`.

If unsure of the location of a particular file or folder, use the
**Search**  box at the top of an page. Just type in a name or keyword, and
a list of all related documents will be displayed.


Compared to other CMS platforms
===============================

If you're familiar with other open-source :abbr:`CMS (Content Management
System)` platforms, such as Joomla, Wordpress or Drupal, |project-name| is
similar and performs in a simliar fashion.  Plone, the platform that
|project-name| is built on, is notably more secure, and provides a number of
interactive, collaborative workspace tools for users to interact.

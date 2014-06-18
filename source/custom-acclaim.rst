Working with |project-name|
***************************

|project-name| is a collaborative venture between medical schools in Australia
and New Zealand that focuses on benchmarking graduate outcomes in the clinical
domain.  The |project-name| portal provides several key aspects of
functionality, which are detailed below.

Getting started
===============

Make sure you have perused the documentation on :ref:`logging-in` and have
authenticated to |project-name|.  The following documentation covers topics
related to |project-name|-specific functionality. For all other information
about content management and other general functionality, see
:ref:`adding-and-editing-content` and subsequent pages.

Creating and managing forms
===========================

For full details about how to manage online forms, see :ref:`online-forms`.
This documentation includes how to create forms, add and modify form fields,
and work with captured data.


Working with videos
===================

Videos can be uploaded to the site following the same methodology as creating
any other content.  It will be helpful for you to review the documentation on
:ref:`adding-and-editing-content` first before proceeding, as this will help
you understand the basics of content management.


Adding a new video
------------------

.. important::
   Because the |project-name| site is designed for examiner training, you
   should take care when adding information to the uploaded video.  Aspects
   like the title and summary **are displayed to users** and thus you should
   take care not to give away the expected results.  For example, use more
   generic names about training stations and video numbers rather than
   explaining what grade the video pertains to.

#. Browse to the location in the site you wish to add the video.

#. Click :menuselection:`Add new --> Video`.

#. Add suitable metadata to the video, including a title and a summary of the
   content of the video.  Pay attention to the important note above.

#. Choose the ``Video File`` to upload from your computer.  See
   :ref:`video-suggestions` for details on formats and settings.

#. Configure the width and height for the video display in pixels.  This is
   the size at which the video will be shown on the page initially, and users
   have the ability to make the video full-screen on their device.  Smaller
   settings (or using the defaults) is suggested for mobile users.

#. Ignore the ``YouTube URL`` and ``Subtitle file`` fields.

#. Add any rich text you would like to be displayed underneath the video into
   the ``Transcript`` area.  This could include images, links, or to
   other sites that might relate to the video.

   In particular, adding a link to a given form the user needs to fill out is
   especially useful, and you may wish to configure the link to open in a new
   window, for ease of use by a visitor.

#. Configure any other metadata required.  See
   :ref:`setting-advanced-metadata-properties` for more information.

#. Click the ``Save`` button to create your video content item.  This content
   item can now be linked to, shared, and otherwise used as any other piece of
   content on the site.

.. _video-suggestions:

Technical suggestions
---------------------

* Videos must be uploaded in ``.mp4`` format for maximum compatibility with
  a viewer's browser (standard ``H264`` video codec and ``AAC`` audio codec).
  Without this configuration, videos are likely to fail to play or may exhibit
  unusual behaviour.

* Viewers may be looking at your video on many different devices, so a high
  level of video compression (or a lower video bitrate) is recommended.
  Contact your video production or technical staff for more information.

* Maximum resolution of around ``720p`` should be sufficient for both a
  detailed experience on desktop browsers, but small enough for viewing on
  mobile devices as well.

* |project-name| uses MediaElement.js to integrate the playback of videos in
  the site.  This open-source project aims to enable HTML5 video support in a
  common fashion across all browsers and devices. For browsers and platforms
  that lack ``H264`` capabilities, either a Flash-based or Silverlight-based
  player will be used as a fallback.

* Blank video playback or videos failing to play at all are likely an
  indicator of incorrect video or audio codecs present within your uploaded
  video.  Check the codec information using a program like VLC Media Player or
  the command-line ``avprobe`` on Mac or Linux and confirm as per the
  :ref:`video-suggestions` above.


Editing a video
---------------

#. Browse to the location in the site you wish to modify.

#. Click the ``Edit`` link on the page.

#. Modify the relevant settings on the page.  For example, you could upload a
   new version of a video or change the video's title or description.

#. Click ``Save`` to make your changes.


Viewing a video
---------------

.. note::
   If you experience issues with displaying a video, check to make sure you're
   using the latest version of your browser.  For platforms that do not
   support MP4 natively (earlier versions of Internet Explorer and some Linux
   browsers), ensure your `Adobe Flash Player
   <http://get.adobe.com/flashplayer>`_ and `Microsoft Silverlight
   <http://www.microsoft.com/silverlight>`_ (if on a Windows platform) plugins
   are installed and up-to-date.

#. Browse to the location in the site where the video is located, or use the
   direct web address provided to you.

#. Click or tap the large play icon in the middle of the video.

#. The video will begin playing.

#. Use the controls provided to play, pause and skip to another part of the
   video.  Videos can be made full-screen using the button at the right.

#. For mobile devices such as smartphones and tablets, the video will likely
   display full-screen whilst playing.  Click the relevant button to minimise
   and close the video once done.


Troubleshooting
---------------

If a video fails to playback in your browser, contact the site administrator
to have them ensure the video is in the correct format.  If a file is of the
``MP4`` format, the video must be produced accordingly to the
:ref:`video-suggestions` above.


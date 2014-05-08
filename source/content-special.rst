Using other types of content
****************************


Adding and editing events
=========================

The **Event** content type allows you to create events for others to see.
These events can be automatically included on the calendar portlet, and in
other locations. In order to add an event:

#. Browse to the location in the site you wish to add this. Typically,
   there will be a dedicated *Events* folder that already exists.  If not,
   consider creating one as a way of grouping your content items.

#. Create the new event via :menuselection:`Add new --> Event`

   .. image:: images/add_new_menu1.png
      :alt: Add new menu
      :align: center

#. Complete the information as required to construct your event item. The
   following is a guide on what metadata corresponds to what aspect of the
   event:

   +-----------------+--------------------------------------------------------+
   | Metadata item   | Description                                            |
   +=================+========================================================+
   | Title           | The name of the event                                  |
   +-----------------+--------------------------------------------------------+
   | Description     | A short description with details about the event       |
   +-----------------+--------------------------------------------------------+
   | Event location  | Where the event is going to be held                    |
   +-----------------+--------------------------------------------------------+
   | Event starts    | Date/time in the format                                |
   +-----------------+--------------------------------------------------------+
   | Event ends      | Date/time in the format                                |
   +-----------------+--------------------------------------------------------+
   | Event body text | Rich text with full details about the event. Can       |
   |                 | include images, formatted text, links and more.        |
   +-----------------+--------------------------------------------------------+
   | Attendees       | List of people who are to be attending                 |
   +-----------------+--------------------------------------------------------+
   | Event URL       | A web address related to the event                     |
   +-----------------+--------------------------------------------------------+
   | Contact Details | Various details about whom to contact about the event. |
   +-----------------+--------------------------------------------------------+

#. Click ``Save`` to create your content item.

#. If the resulting content needs to be published, then follow the
   instructions for :ref:`publishing-content`.


Adding and editing news items
=============================

The **News Item** content type allows you to create news items (or content to
be highlighted) on |project-name|.  News can be automatically displayed in a
special portlet, which is automatically updated as updated news is created.
News items can have a special leading image associated with them, which is
automatically displayed in ``Summary`` listings and when viewing the news item
itself.

In order to add a news item:

#. Browse to the location in the site you wish to add this. Typically,
   there will be a dedicated *News* folder that already exists.  If not,
   consider creating one as a way of grouping your content items.

#. Create the new event via :menuselection:`Add new --> News Item`

   .. image:: images/add_new_menu1.png
      :alt: Add new menu
      :align: center

#. Complete the information as required to construct your content item. The
   following is a guide on what metadata corresponds to what aspect:

   +---------------+--------------------------------------------------------+
   | Metadata item | Description                                            |
   +===============+========================================================+
   | Title         | A short descriptive title of the news content          |
   +---------------+--------------------------------------------------------+
   | Description   | A short introduction to the news item                  |
   +---------------+--------------------------------------------------------+
   | Body text     | Rich text with full details of the content. Can        |
   |               | include images, formatted text, links and more.        |
   +---------------+--------------------------------------------------------+
   | Image         | An image to appear as part of the news item            |
   +---------------+--------------------------------------------------------+
   | Image Caption | The text that will appear under the image as a caption |
   +---------------+--------------------------------------------------------+

#. Click ``Save`` to create your content item.

#. If the resulting content needs to be published, then follow the
   instructions for :ref:`publishing-content`.


Adding links as content
=======================

**Link** content items can be created within |project-name| and essentially act
as bookmarks or pointers to other web pages and sites. They are useful as they
appear in navigation listings, as top-level tabs, and elsewhere, and when a
user clicks on them, they will be automatically taken to the target page.

.. note::
   If the user has access to edit a given Link, then they'll be taken to a view
   explaining the link. This helps content editors and managers if they need to
   change the target URL.

#. Browse to the location in the site you wish to add this.

#. Create the new event via :menuselection:`Add new --> Link`

   .. image:: images/add_new_menu1.png
      :alt: Add new link
      :align: center

#. Complete the information as required to construct your content item. The
   following is a guide on what metadata corresponds to what aspect:

   +-------------+--------------------------------------------------------+
   | Metadata    | Description                                            |
   +=============+========================================================+
   | Title       | A short descriptive title for the link                 |
   +-------------+--------------------------------------------------------+
   | Description | A longer outline of the link. Whilst this is not shown |
   |             | directly to the user, it will be shown as a tooltip if |
   |             | users hold their mouse over the link in navigation.    |
   +-------------+--------------------------------------------------------+
   | URL         | The absolute URL for the link                          |
   +-------------+--------------------------------------------------------+

#. Click ``Save`` to create your content item.

Adding a Collection
===================

.. note::
   Collections can only be created by site administrators. If you require a
   Collection to be configured, please contact your site administration
   accordingly.

Collections are effectively a saved search, allowing a set of pre-configured
criteria to be applied to site content in order to display a list of items.
Some examples of Collection applications are:

* **New content** - all content created on the site in the last 7 days
* **Content nearing expiry** - all content with an expiration date with the next 7 days
* **Your content** - all content created on the site by the current user

Essentially, any aspect of content metadata can be used to configure a
Collection. To add a Collection:

#. Browse to the location in the site you wish to add this.

#. Create the new event via :menuselection:`Add new --> Collection`

#. Enter a title for the collection, other metadata as required, and configure
   search terms to control the result listing.

   .. image:: images/collection_criteria.png
      :alt: Collection criteria
      :align: center

   In the example above, the Collection displays all content created in the
   last 7 days. Use the selection boxes to add different search criteria. A
   preview of the results will be displayed and updated as your configuration
   changes.

#. Once you are satisfied with the results, click ``Save`` to finish
   creating the Collection.

Search criteria
---------------

The search criteria for the collection can be based on any of the metadata
associated with content.  Some of the most common are listed below:

Title
   The standard title of a content item
Description
   The description associated with a content item
Tag
   The keywords used to describe an item
Creation Date 
   The time and date an item was created
Creator 
   The user ID of the person who created the content
Review State 
   The content item's workflow state, such as private, pending or published
Effective Date 
   The publishing time and date for a content item
Expiration Date 
   The time and date the content will no longer be available
Location 
   The path to where in the site the content resides on the site


.. only:: forms

    Creating online forms
    =====================

    You can easily create web-based forms to capture information from users.  Forms
    can be created such that the results are either emailed to a user or group of
    users on submission, or else saved in a local file on the site, available for
    download at any time.  Forms on |project-name| have a large number of field
    types available, and one notable benefit is that your forms can be used within
    your site's existing security, rather than relying on a third-party provider.

    Basic concepts
    --------------

    A web form has this general workflow:

    + Display the front-facing form to a user.  This form typically
      consists of a number of fields, which might include input boxes,
      drop-down or radio button lists, file uploads, and more.
    + The user visits the form and fills out the details.
    + The user clicks the submit button to send form information
      to the server.
    + The server processes the form submission, validating it (if configured)
      and returns any errors to the user.  This might happen if a field
      is configured as ``Required`` but the user did not enter a value.
    + This continues until the form submission is correctly submitted.
    + The server then processes the form submission according to the actions
      on the form.  For a typical form, this is either emailing the results
      to someone or storing in an online CSV file.
    + The server displays a thank-you page or similar to the user.

    There can be variations on the above, given a specific form, but typically,
    this is the general process.

    Creating a new form
    -------------------

    To add a new form:

    #. Browse to the location in the site you wish to add the form.

    #. Use :menuselection:`Add new --> Form Folder` to begin creating your
       form.

       .. image:: images/add_new_menu1.png
          :alt: Add new form folder
          :align: center

    #. Configure the form accordingly.

       The only option you're required to specify is the ``Title`` field, which
       will dictate the heading and name of the form being displayed to users,
       exactly the same way as other ``Title`` fields on other content do.

       For other options, see :ref:`form-options`

    #. Click ``Save`` to create the form.

    Once your form is created, you'll see a default form that looks a little
    like this:

    .. image:: images/new_form.png
       :alt: Newly created form
       :align: center
       :width: 250px

    .. _form-options:

    Form options
    ------------

    Here's a description of the options available for forms, which can be
    configured by editing the given form via the :menuselection:`Edit` link.

    =====================  =============================
    Option                 Description
    =====================  =============================
    Title                  Short, descriptive title of the form
    Description            A medium-length description of the form's purpose
                           or action.
    Submit Button Label    The text to display on the form's submit button
    Show Reset Button      Select to show a reset button on the form, allowing
                           the user to clear their entry and start over Reset
                           Button Label
    Reset Button Label     The text to display on the form's reset button,
                           if enabled.
    Action Adapter         Select which of the actions the form should take
                           after submit.  If first creating a form, you'll
                           just see 'Mailer' for emailing results.  Others can
                           be added later.
    Thanks Page            Configure which page to show after the form has been
                           submitted.  Typically, this will thank the user, or
                           give them further instructions.
    Force SSL connection   Force the form to be shown over a secure (SSL)
                           connection.  Your site must be configured
                           specifically for this functionality.  Consult your
                           site administrator if in doubt.
    Form Prologue          Rich text to display above the form. You may want to 
                           introduce your form, explain what it does, add
                           friendly images, and more.
    Form Epilogue          Rich text to display below the form. You may want to 
                           sign off and say thanks here.
    =====================  =============================

    Using the Quick Editor
    ----------------------

    Your form also comes with a simple Quick Editor, which allows you to drag
    and drop fields onto your page, as well as easily edit and update your
    other form features.  You should familiarise yourself with `Form fields`_
    and `Form features`_ so you know what functionality is available.

    .. image:: images/form_quickeditor.png
       :alt: Example form quick editor 
       :align: center
       :width: 400px

    Form fields
    -----------

    Once your form is created, you can add any number of fields to the form.
    Each of the fields has a different purpose.  To add any of these to the
    form, either use the Quick Editor (see `Using the Quick Editor`_), or
    otherwise click :menuselection:`Add new --> [field type]`, selecting the
    type of field you wish to add.  You can hover your mouse over a field to
    see its description rather than needing to rely on this list.

    .. image:: images/form_fields.png
       :alt: Example form fields
       :align: center
       :height: 300px

    =====================           =============================
    Field                           Description
    =====================           =============================
    Captcha Field                   Verification field the user must complete. This prevents misuse and spam.
    Checkbox Field                  True or false field where the user can choose to select or deselct the box.
    Date/Time Field                 Field that captures either a date, or date and time.
    Decimal Number Field            Text field that validates input to ensure decimal numbers are entered.
    Fieldset Begin                  Marker indicating the start of a fieldset (group of fields)
    Fieldset End                    Marker indicating the end of fieldset (group of fields)
    Fieldset Folder                 Folder-like entity that can contain fields.
    File Field                      Upload field for files from the user. Use with caution as users may upload
                                    undesirable files. Files uploaded are attached to mail sent on form
                                    submission.
    Label Field                     Basic label-only text field. Useful for displaying some short text.
    Lines Field                     Input field for multiple lines of text (such as a list of text values)
    Multi-Select Field              Selection list or checkbox list for multiple values.
    Password Field                  Input field for passwords (protects visible input with stars or dots).
    Rating-Scale Field              Multi-question field for rating a number of questions
    Rich Label Field                Basic rich-text content to display on the form (no input).
    RichText Field                  Rich-text content editor for capturing formatted content from the user.
    Selection Field                 Single-selection field using either a drop-down list or radio buttons.
    String Field                    Basic single-line text input field.
    Text Field                      Multi-line text input field.
    Whole Number Field              Text field that validates input to ensure integers are entered.
    =====================           =============================

    For each field, you will be presented with a number of different options
    for customising that field. Have a read of each different option to get an
    idea as to what they do.  The most common options across fields are:

    =====================  =============================
    Option                 Description
    =====================  =============================
    Field label            Short, descriptive title of the field for display on the form.
    Field help             A medium-length description of the field's purpose or similar help text.
    Required               Whether the field is required or not.  If this is enabled 
                           for a field and the user does not enter a value, the form will error
                           during user submission.
    Default                The default value to display on the form. This can be
                           used to help guide the user.
    =====================  =============================

    Other fields will have options like maximum length (for text fields),
    available options (for selection or multi-selection fields), and so forth.
    You can add new fields and change options with the knowledge you can easily
    change things as you need at any time.

    Once you've added your form field, you can see the result of the rendered
    field by clicking back to your form.

    Form features
    -------------

    In addition to fields, there are also a number of form helpers that you can
    use.  These are added into your form in the same way as fields, by using
    the **Add new** drop-down menu, and locating the relevant entry.

    =====================           =============================
    Special features
    =====================           =============================
    Image                           Standard image for inclusion in pages or thank you pages.
    Page                            Standard page content. May be useful for extra help pages for forms.
    Thanks Page                     A thank-you page that can be displayed after a form submission is
                                    successful.  One is added automatically to new forms. Configure
                                    which Thanks page to use via the Edit tab on your main form.
    Mailer Adapter                  Enables a form to email submission results to recipients.
                                    Enabled by default for forms, but you will need to configure
                                    your email address for sending.
    Save Data Adapter               Enables a form to save its data in a online-stored file.
                                    Users' submissions are added into this CSV or TSV file and it
                                    can be downloaded at any time by a suitable user.
    Custom Script Adapter           Run custom script upon a form submission. Requires Manager rights
                                    to create and use.
    =====================           =============================

    Common tasks
    ------------

    Form submissions should be emailed
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    Your form can be configured such that data being entered gets emailed to
    you, or a number of specific email addresses (or email aliases or lists).
    To do this:

    #. Browse to the form on your site.

    #. Your form may already have a ``Mailer Adapter`` configured. Click the
       ``Contents`` tab and look for an item called ``Mailer`` in the
       listing.  
       
       #. If this exists, you should click its link, and click ``Edit``
          to edit this instead.

       #. If not, use :menuselection:`Add new --> Mailer Adapter` to add this feature to
          your form.

    #. Configure the mailer adapter accordingly.  Look under each of the
       collapsed sections to reveal options.  For example, you can:

       * Configure the Recipient and their email address
       * Add CC and BCC recipients
       * Configure the email's subject
       * Add extra text to display in the body of the email
       * Configure which fields should be sent within the emails
              
    #. Use the ``Save`` button to either update or create your mail
       configuration.  Any form submissions will start sending email
       immediately.

    It is possible to add multiple ``Mailer Adapter``s onto your form if you
    have specific email requirements to different people.  For instance, you
    may want only a certain subset of people to be emailed with certain data
    or with a specific subject line.  Make sure you test your form before
    making it live!


    Form submissions should be securely saved online
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    Your form can be configured such that data being entered gets saved into a
    secure location on your site, and is able to be downloaded by users with
    appropriate permission later.

    .. important::
       Forms that capture files from users using a ``File Field`` can only
       be emailed as attachments.  They cannot be stored on your site or
       associated with a ``Save Data Adapter``.

    .. warning::
       Your saved data structure will get out of sync with existing data if
       you change your form's structure, add fields or remove fields, after
       receiving submissions.  If you plan to update your form, ensure you
       `Clear saved form submissions`_ first.

    To do this:

    #. Browse to the form on your site.

    #. Your form may already have a ``Save Data Adapter`` configured. Click the
       ``Contents`` tab and look for an item called ``Saved Data`` (or
       similar) in the listing.
       
       #. If this exists, you should click its link, and click ``Edit``
          to edit this instead.

       #. If not, use :menuselection:`Add new --> Save Data Adapter` to add
          this feature to your form.

    #. Configure the save data adapter accordingly.  Look under each of the
       collapsed sections to reveal options.  For example, you can:

       * Configure the fields to be saved
       * Configure extra technical data to be saved.  The ``REMOTE_ADDR`` and
         ``HTTP_X_FORWARDED_FOR`` record the IP address of the incoming
         submission, and the ``HTTP_USER_AGENT`` field captures the user's
         reported browser.
       * Select the download format for your file (either comma-separated or
         tab-separated).  Don't change this after receiving form submissions.
       * Include column names in the output as the first line of the file.

    #. Use the ``Save`` button to either update or create your configuration.
       Any form submissions will start capturing data immediately.

    Testing your form
    -----------------

    After adding some fields, and customising the form helpers, view your form
    using the standard ``View`` link to ensure it appears as you'd expect.

    The form is fully functional as you see it, so you can interact with the
    form and even submit it to check the results and ensure it works correctly.

    .. important::
       Remember that if you have a ``Save Data Adaptor`` within your form any
       testing you perform will be saved inside its local storage.  Thus, you
       may want to clear your tests before considering the form live.
       See `Clearing saved form submissions`_ for details.

       Similarly, if you have configured a ``Mailer Adaptor`` to send email
       responses, then these will be triggered as well.

    Downloading saved form submissions
    ----------------------------------

    .. note::
       This is only applicable if you created a ``Save Data Adapter`` for your
       form.

    Once visitors have been submitting your form, you will either find
    yourself wanting to get access to the saved data.

    #. Browse to the form on your site.

    #. Click ``Contents`` to locate the ``Save Data Adapter`` on the form.

    #. Click the link for the ``Save Data Adapter`` in the listing.

    #. Click the saved input link in the middle of the page.

    The downloaded file can now be opened in any desktop program for analysis,
    including Microsoft Excel, LibreOffice, or anything that supports CSV or
    TSV file formats.

    Clearing saved form submissions
    -------------------------------

    .. note::
       This is only applicable if you created a ``Save Data Adapter`` for your
       form.

    .. warning::
       Clearing data is permanent and irreversible. Always take a copy of your
       data before performing this action.

    #. Browse to the form on your site.

    #. Click ``Contents`` to locate the ``Save Data Adapter`` on the form.

    #. Click the link for the ``Save Data Adapter`` in the listing.

    #. Click the ``Clear Saved Input`` button on the page.






Getting started
***************

.. _logging-in:

Logging in
==========

In order to make any changes or perform actions on |project-name|, the first
and most significant step is to access the site and log in. To perform
any content management tasks, such as creating content or modifying existing
items, or to access secured content, you also must have been granted suitable
permissions.

.. ifconfig:: metadata['project']['auth'] == 'jcu-ldap'

   |project-name| utilises your existing JCU credentials in order for you to
   log in. Any changes to your password are managed centrally by the IT
   helpdesk and will automatically follow through to be used on
   |project-name|.

.. ifconfig:: metadata['project']['auth'] == 'aaf'

   Because |project-name| utilises :term:`Single Sign On (SSO)` you will
   utilise an existing set of credentials to log in.  Due to the nature of this
   process, in order to share content with colleagues, each individual must log
   in to |project-name| at least once before they can be given access.

   Most users will use their existing institutional username and password (or
   other credentials) to log in via the :term:`Australian Access Federation
   (AAF)`.

.. ifconfig:: metadata['project']['auth'] == 'local'

   Because |project-name| utilises local authentication, you will utilise a
   set of credentials that are local to this site.  The site administrator must
   create this account and provide permissions before you are able to log in.


.. ifconfig:: metadata['project']['auth'] == 'aaf'

    Institutional Authentication
    ----------------------------

    .. important::

        Before proceeding, ensure that your credentials have been provided by an
        **institution** or **research organisation**, rather than being local
        to |project-name|.  If you attempt to sign in to an institution's
        authentication system using local |project-name| credentials, this
        process will fail.


    #. The login link is located in the top-right hand corner of the page:

       .. image:: /images/login_link.png
          :alt: Portal Login Link
          :align: center
          :scale: 75%

    #. You will be presented with the option to utilise AAF authentication to
       log in.

       .. image:: /images/login_shib.png
          :alt: Portal Login Link
          :align: center
          :scale: 50%

    #. Select your institution or organisation from the dropdown box.

       .. note::

          If your institution or organisation doesn't appear in the list,
          then you should contact your IT support staff about whether you
          are part of the :term:`Australian Access Federation (AAF)`. If you
          are a collaborator associated with an organisation subscribed to the
          AAF, then you can obtain an AAF Virtual Home account by following
          the instructions in the `AAF Virtual Home User Guide
          <https://vho.aaf.edu.au/guides/user-guide.pdf>`_.

    #. Click the ``Login`` button.

    #. Enter your institutional or organisational credentials and login.

       .. note::

          This is a screen shot of the James Cook University login page - your
          institution's page will look different and may behave in a slightly
          different manner.

       .. image:: /images/idp_jcu.png
          :alt: JCU Identity Provider
          :align: center
          :scale: 50%

    #. You may be prompted to release certain details about yourself from your
       organisation, including name, email address, and other particulars.
       You must accept this to continue so that you can be identified within
       our system.

    #. Once logged in, notice that your name is displayed at the top-right
       hand corner and that you can click on this to display the user
       actions menu.

       .. image:: /images/user-tools-menu.png
          :alt: User actions menu
          :align: center
          :scale: 75%


.. ifconfig:: metadata['project']['auth'] == 'jcu-ldap'

    JCU Authentication
    ------------------

    Using JCU-based crentials to login follows the same process as
    :ref:`local-authentication:, with two notable differences:

    * Credentials are the same as other JCU systems, being your user ID and
      password, rather than a site-local account.
    * Password reset requests will not work as your credentials are supplied
      from the main authentication database. See :ref:`login-issues` for
      details.

    A |project-name| site likely utilises both JCU and local-based accounts.
    Contact your site administrator if you have questions.

.. _local-authentication:

Local Authentication
--------------------

For local authentication, use the instructions that follow.

If you are visiting your site for the first time, the site administrator needs
to have provided you with a username and temporary password.  Otherwise, ensure
that you know your pre-existing credentials.


#. The login link is located in the top right hand corner of the page.

   .. image:: /images/login_link.png
      :alt: Portal Login Link
      :align: center
      :scale: 75%

#. .. ifconfig:: metadata['project']['auth'] == 'aaf'

      Click on the ``Local Login`` link.

   .. ifconfig:: metadata['project']['auth'] != 'aaf'

      The same login fields are used for all types of authentication on this
      site.

#. Enter the user name and password that you have for the portal.

   .. image:: /images/login.png
      :alt: Portal Login
      :align: center
      :scale: 50%

#. Click on the login button.

#. If you are unable to login, you can retry your login.  If you have forgotten
   your password, follow the given link to start the reset process.


Logging out
-----------

When you're finished working with |project-name|, you should always ensure that
you log out.

#. Click your username in the top-right hand corner of the site to reveal
   the user actions menu.

#. Click the ``Log out`` link.

   .. ifconfig:: metadata['project']['auth'] == 'aaf'

       .. note::

          If you are logged in via your instutional credentials, you can log
          out of the portal, but your browser will remember you for use on
          other :term:`Australian Access Federation (AAF)` services.  To log
          out entirely, either quit the browser you use are using, or clear all
          cookies relating to ``aaf.edu.au`` and ``|project-server-host|``.


.. _login-issues:

If you cannot log in
--------------------

.. ifconfig:: metadata['project']['auth'] == 'jcu-ldap'

    JCU Authentication
    ~~~~~~~~~~~~~~~~~~

    Since authentication is provided by your existing JCU credentials, you
    should contact the `IT Helpdesk <https://jcueduau.service-now.com/>`_
    with your queries or password reset requests.


.. ifconfig:: metadata['project']['auth'] == 'aaf'

    Insitutional Authentication
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~

    Since authentication is provided by your institution directly, please refer
    to your local helpdesk for troubleshooting and password reset requests.
    For details on how to contact your helpdesk, please refer to your
    insitution's website.


Local Login
~~~~~~~~~~~

If you are unable to login to the portal, you may have forgotten your password.
If you believe this is the case, click onto the ``Local Login`` link, and
then click on ``Forgot your password?`` and follow the steps.

If you still can't log in, or have forgotten your username, then contact
the site administration for assistance.


Permissions and access
======================

Each user can be granted specific :ref:`role <roles>` in different areas of the site.
Roles can be granted either site-wide (called :ref:`global roles
<global-roles>`), which are the managed by site administrators, or granted
within a specific area of the site (called :ref:`local roles <local-roles>`),
which can be managed by users that already have permissions.

Access can be granted either to a specific user or a group of users.  Creation
and management of groups of users is managed by site administrators.

Issues or concerns about insufficient access should be directed towards your
site administrator or nominated representative.

For more information on granting and controlling access, see
:ref:`sharing-your-content`.

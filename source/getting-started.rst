Getting started
***************

.. _logging-in:

Logging in
==========

In order to get started with |project-name|, the first step is to access the
site and log in. To perform any content management tasks, such as creating
content or modifying existing items, or to access secured content, you also
must have been granted suitable permissions.

.. ifconfig:: 'jcu-ldap' in metadata['project']['auth']

   * |project-name| utilises your existing JCU credentials in order for you to
     log in. Read more in :ref:`jcu-authentication`.

     Any changes to your password are managed centrally by the IT
     helpdesk and will automatically follow through to be used on
     |project-name|.

.. ifconfig:: 'aaf' in metadata['project']['auth']

   * |project-name| utilises institutional :term:`Single Sign On (SSO)`,
     allowing you to utilise your existing set of university or research
     organisation credentials to log in.  Due to the nature of this process, in
     order to share content with colleagues, each individual must log in to
     |project-name| at least once before they can be given access.
     Read more in :ref:`institutional-authentication`.

.. ifconfig:: 'local' in metadata['project']['auth']

   * Because |project-name| utilises local authentication, you can utilise a
     set of credentials that are specific to this site.

   .. ifconfig:: 'self-registration' in metadata['project']['auth']

      * You have the ability to self-register for an account on |project-name|
        and do not require a site administrator to create an account for you.
        Follow the steps below in :ref:`registering`.

   .. ifconfig:: 'self-registration' not in metadata['project']['auth']

      * The site administrator must create your account and provide permissions
        before you are able to log in.  Contact the administrator of your site
        for more information.

.. ifconfig:: 'local' in metadata['project']['auth'] and 'aaf' in metadata['project']['auth']

   * |project-name| allows both insitutional users and local users to login to
     the same site.  Take care when selecting your login method: if you have a
     separate username and password for eSpaces only (called a *local account*),
     then use the ``Local Login``.


.. ifconfig:: 'aaf' in metadata['project']['auth']

    .. _institutional-authentication:

    Institutional Authentication
    ----------------------------

    .. important::

        Before proceeding, ensure that your credentials have been provided by
        an **institution** or **research organisation**, rather than being
        local or specific to |project-name|.  If you attempt to sign in to an
        institution's authentication system using local |project-name|
        credentials, this process will not work.

    #. The login link is located in the top-right hand corner of the page:

       .. image:: /images/login_link.png
          :alt: Portal Login Link
          :align: center
          :scale: 75%

    #. Choose your login method.  Insitutional authentication is already
       pre-selected for you.

       .. image:: /images/login_shib.png
          :alt: Portal Login Link
          :align: center
          :scale: 50%

    #. Select your institution or organisation from the dropdown menu.

       .. note::

          If your institution or organisation doesn't appear in the list,
          you should contact your IT support staff about whether you
          are part of the :term:`Australian Access Federation (AAF)`.

          If you are a collaborator associated with an organisation subscribed
          to the AAF, then you can obtain an AAF Virtual Home account by
          following the instructions in the `AAF Virtual Home User Guide
          <https://vho.aaf.edu.au/guides/user-guide.pdf>`_.

    #. Click the ``Login`` button.

    #. You will be taken your selected organisation's authentication page.
       Enter your credentials and login.

       .. note::

          This is an example screen shot of the James Cook University login
          page - your institution's page will look different and may behave in
          a slightly different manner.  Follow your own organisation's login
          steps to proceed.

       .. image:: /images/idp_jcu.png
          :alt: JCU Identity Provider
          :align: center
          :scale: 50%

    #. You may be prompted to release certain details about yourself from your
       organisation to |project-name|, including name, email address, and
       other particulars.  You must accept this to continue so that you can be
       identified within our system.

    #. Once logged in, notice that your name is displayed at the top-right
       hand corner.

       You can click on this to display the user actions menu,
       which you'll use to change your settings and log out.

       .. image:: /images/user-tools-menu.png
          :alt: User actions menu
          :align: center
          :scale: 75%


.. ifconfig:: 'jcu-ldap' in metadata['project']['auth']

    .. _jcu-authentication:

    JCU Authentication
    ------------------

    Using JCU-based crentials to login follows the same process as
    :ref:`local-authentication`, with two notable differences:

    * Credentials are the same as other JCU systems, being your user ID and
      password, rather than a site-local account.
    * Password reset requests will *not* work as your credentials are supplied
      from the main authentication database. See :ref:`login-issues` for
      details.

    |project-name| will likely utilise both JCU and local-based accounts.
    Contact your site administrator if you have questions about your account.


.. ifconfig:: 'local' in metadata['project']['auth']

    .. _local-authentication:

    Local Authentication
    --------------------

   .. ifconfig:: 'self-registration' in metadata['project']['auth']

      * You have the ability to self-register for an account on |project-name|
        and do not require a site administrator to create an account for you.
        Follow the steps below in :ref:`registering`.

   .. ifconfig:: 'self-registration' not in metadata['project']['auth']

      * The site administrator must create your account and provide permissions
        before you are able to log in.  Contact the administrator of your site
        for more information.

    For local authentication, use the instructions that follow.

    If you are visiting your site for the first time, the site administrator needs
    to have provided you with a username and temporary password.  Otherwise, ensure
    that you know your pre-existing credentials.


    #. The login link is located in the top right hand corner of the page.

    .. image:: /images/login_link.png
        :alt: Portal Login Link
        :align: center
        :scale: 75%

    .. ifconfig:: 'aaf' in metadata['project']['auth']

        Click on the ``Local Login`` link.

    .. ifconfig:: 'aaf' not in metadata['project']['auth']

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

   .. ifconfig:: 'aaf' in metadata['project']['auth']

       .. note::

          If you are logged in via your instutional credentials, you can log
          out of the portal, but your browser will remember you for use on
          other services from your local institution or your federation :term:`Australian Access Federation (AAF)` services.  To log
          out entirely, either quit the browser you use are using, or clear all
          cookies relating to ``aaf.edu.au`` and ``|project-server-host|``.


.. _login-issues:

If you cannot log in
--------------------

If you're experiencing issues logging in, first determine what sort of account
you are using and follow the relevant troubleshooting steps below.

.. ifconfig:: 'jcu-ldap' in metadata['project']['auth']

    JCU Authentication
    ~~~~~~~~~~~~~~~~~~

    Since authentication is provided with your existing JCU credentials, you
    must contact the `IT Helpdesk <https://jcueduau.service-now.com/>`_
    with queries or password reset requests.


.. ifconfig:: 'aaf' in metadata['project']['auth']

    Insitutional Authentication
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~

    Since authentication is provided by your institution directly, please refer
    to your local helpdesk for troubleshooting and password reset requests.
    For details on how to contact your helpdesk, please refer to your
    insitution's website.


.. ifconfig:: 'local' in metadata['project']['auth']

    Local Login
    ~~~~~~~~~~~

    If you are unable to login to the portal, you may have forgotten your password.
    If you believe this is the case, click onto the ``Local Login`` link, and
    then click on ``Forgot your password?`` and follow the steps.

    If you still can't log in, or have forgotten your username, then contact
    the site administration for assistance.


.. ifconfig:: 'self-registration' in metadata['project']['auth']

    .. _registering:

    Registering for a local account
    ===============================

    Details coming shortly.


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

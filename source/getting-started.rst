Getting started
***************

.. _logging-in:

Logging in
==========

In order to get started with |project-name|, the first step is to access the
site and log in. To perform any content management tasks, such as creating
pages, editing items, or accessing secured content, you also
must have been granted suitable permissions.

The types of logins available on |project-name| are:

.. ifconfig:: 'jcu-ldap' in metadata['project']['auth']

   * *JCU computer accounts*. See :ref:`jcu-login`.

.. ifconfig:: 'aaf' in metadata['project']['auth']

   * *Australian university/research institution accounts*.  See
     :ref:`aaf-login`.

.. ifconfig:: 'tuakiri' in metadata['project']['auth']

   * *New Zealand university/research institution accounts*.  See
     :ref:`tuakiri-login`.

.. ifconfig:: 'local' in metadata['project']['auth']

   * *Local accounts*. See :ref:`local-login`. These are
     accounts that are specific to |project-name|.

     .. ifconfig:: 'self-registration' in metadata['project']['auth']

        You may self-register for an account; see :ref:`registering`.


.. ifconfig:: len(metadata['project']['auth']) > 1

   .. important::

      Take care when selecting your login method. Get in touch with
      your site administrator if you're unsure what sort of account you have.

      If you're having issues logging in, see :ref:`login-issues`.


.. Types of login for this project
.. ifconfig:: 'aaf' in metadata['project']['auth']

   .. _aaf-login:

   Logging in with an Australian institutional account
   ---------------------------------------------------

   |project-name| utilises institutional :term:`Single Sign On (SSO)`, powered
   by the :term:`Australian Access Federation (AAF)`.  This allows login with
   an existing university or research organisation account.  In order to share
   content with colleagues, each user must log in to |project-name| at least
   once before they can be found.

   .. important::

      Before proceeding, ensure that your credentials have been provided by an
      *institution* or *research organisation*, rather than being local to
      |project-name|.  If you try to sign in to an institution using local
      |project-name| credentials, it won't work; see :ref:`local-login`
      instead.

   #. Click ``Login`` at top-righthand corner of the page:

      .. image:: /images/login_link.png
         :alt: Portal Login Link
         :align: center
         :scale: 75%

   #. Choose your login method.  Australian institutional login is already
      pre-selected for you.

      .. image:: /images/login_aaf.png
         :alt: Australian Institutional login
         :align: center
         :scale: 50%

   #. Select your organisation from the dropdown menu.

      .. note::

         If your institution or organisation doesn't appear in the list, you
         contact your IT support staff about whether you are part of the
         :term:`Australian Access Federation (AAF)` or can join.

   #. Click the ``Login`` button.

   #. You will be taken to the selected organisation's authentication page.
      Enter your credentials and login.

      .. note::

         This is an example of the James Cook University login page. Your
         institution's page will look different and may behave in a slightly
         different manner.  Follow your own organisation's login steps to
         proceed.

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

   .. _jcu-login:

   Logging in with a JCU account
   -----------------------------

   You can use your JCU credentials to log in to |project-name|.
   Logging in with these details follows the same process as in
   :ref:`local-authentication`: essentially, enter your JCU user ID and
   password into the |project-name| login form and click ``Login``.

   However, there are several notable differences:

   * Credentials are the same as other JCU systems, being your existing user
     ID and password. They are case-sensitive on |project-name|.

   * The password reset page on |project-name| is for local logins only,
     Password reset requests directly on |project-name| will *not* work as
     your credentials come from the main JCU identity system.

   * Any changes to your password are managed centrally and will flow through
     to |project-name|.  See the `Library & Computing Services
     <http://www-public.jcu.edu.au/libcomp/computing/>`_ page for details on
     how to change your JCU password.

   Contact your site administrator if you have questions about how the site is
   configured for login.


.. ifconfig:: 'local' in metadata['project']['auth']

   .. _local-login:

   Logging in with a Local Account
   -------------------------------

   Because |project-name| utilises local accounts, you can login with a
   username and password that are specific to this site.

   .. ifconfig:: 'self-registration' in metadata['project']['auth']

      .. note::

         You have the ability to self-register for an account on
         |project-name|. Follow the steps in :ref:`registering`; you don't
         need to wait for a site administrator to create an account for you.

   .. ifconfig:: 'self-registration' not in metadata['project']['auth']

      .. note::

         A site administrator must create accounts on |project-name| before
         you can login.  Contact this person for more information before
         proceeding.

   .. ifconfig:: len(metadata['project']['auth']) > 1

      .. note::

         This login method is particularly useful for users that aren't
         associated with other account types.


   #. Click the ``Login`` link in the top right hand corner of the page.

      .. image:: /images/login_link.png
         :alt: Portal Login Link
         :align: center
         :scale: 75%

   #. .. ifconfig:: 'aaf' in metadata['project']['auth']

         Click on the ``Local Login`` heading and enter your details in the
         login form provided.

      .. ifconfig:: 'aaf' not in metadata['project']['auth']

         Enter the user name and password that you have for the portal.

      .. image:: /images/login.png
         :alt: Portal Login
         :align: center
         :scale: 50%

   #. .. ifconfig:: 'aaf' in metadata['project']['auth']

         Click the ``Local Login`` button.

      .. ifconfig:: 'aaf' not in metadata['project']['auth']

         Click the ``Login`` button.

   #. Once logged in, notice that your name is displayed at the top-right
      hand corner.

      You can click on this to display the user actions menu,
      which you'll use to change your settings and log out.

      .. image:: /images/user-tools-menu.png
         :alt: User actions menu
         :align: center
         :scale: 75%


Logging out
-----------

When you're finished working with |project-name|, you should always ensure that
you log out.

#. Click your username in the top-right hand corner of the site to reveal
   the user actions menu.

#. Click ``Log out``.

.. ifconfig:: 'aaf' in metadata['project']['auth']

   .. important::

      If you are logged in via your instutional credentials, you can log
      out of the portal, but your browser will remember you for use on
      other services from your local institution or your federation
      :term:`Australian Access Federation (AAF)` services.  You'll see an
      example of this if you click ``Login`` again on |project-name|; the
      AAF login box shows you're already AAF-authenticated.

      To log out entirely, either restart the browser you use are using, or
      clear all cookies relating to ``aaf.edu.au`` and |project-server-host|.


.. _login-issues:

Solving login issues
====================

.. note::

   If you're experiencing issues logging in, follow the troubleshooting steps
   below; they will help to resolve most situations.

* Ensure your username and password are correct and retry logging in.
  Remember *both* are case-sensitive.

.. ifconfig:: 'aaf' in metadata['project']['auth']

   * Ensure that you are logging into the correct institution for your user
     account.  For example, if you have a James Cook University account, then
     this is what you must select.

   * An issue may be present with your institution's account.  Since
     authentication is provided by your institution directly, please refer to
     your local helpdesk for troubleshooting and password reset requests.
     Please refer to your institution's website for contact details.

.. ifconfig:: 'local' in metadata['project']['auth']

   * If you have forgotten your password to your local |project-name| account,
     click the ``Forgot your password?`` link on the login page and follow the
     steps.

.. ifconfig:: 'jcu' in metadata['project']['auth']

   * An issue may be present with your JCU account.  Contact the `IT Helpdesk
     <http://www.jcu.edu.au/helpdesk/>`_ with your support request and they
     will assist you further.

* Try clearing your browser's cache and cookies, restarting your browser, or,
  in extreme cases, restarting your computer.

If you're still unable to login, contact your site administrator for more
assistance.


.. _registering:

Registering for a local account
===============================

.. For sites without local authentication
.. ifconfig:: 'local' not in metadata['project']['auth']

   .. note::

      Local accounts are not enabled for |project-name|. Please follow the
      steps for :ref:`logging-in`.

.. For sites with local authentication
.. ifconfig:: 'local' in metadata['project']['auth']

      .. ifconfig:: 'aaf' in metadata['project']['auth']

         .. note::

            Remember that if you have an existing institutional account for a
            university or research organisation you do not need to register
            for an account. Just follow the steps for :ref:`logging-in`.

    .. ifconfig:: 'self-registration' not in metadata['project']['auth']

       Self-registration of accounts is not available for |project-name|.
       Contact your site administrator for more information regarding account
       management and associated policies.

   .. ifconfig:: 'self-registration' in metadata['project']['auth']

      You have the ability to self-register for an account on |project-name|,
      meaning that you do not require a site administrator to create an account
      for you.

      .. ifconfig:: 'aaf' not in metadata['project']['auth']

         #. Click the ``Register`` link at the top of any page.

         #. Complete the registration form with the required details,
            including the verification field, if present.  Take note of your
            username, you'll need this to log in.

         #. Click the ``Register`` button at the bottom of the form to
            complete your registration.

            .. image:: /images/login-registering.png
                :alt: Portal Registration
                :align: center
                :scale: 50%

            Your registration form may have slight differences.

         #. You will be required to validate your email address in order to
            use your account.  You will shortly be sent a validation email, in
            which you'll find a link you need to click to verify your account
            and set a password.

         #. Once you have completed these steps, your account will be ready
            for use.

      .. ifconfig:: 'aaf' in metadata['project']['auth']

         #. Click the ``Log in`` link at the top of any page.

         #. Click the ``Register`` section on the login page to reveal the
            account registration form.

            .. image:: /images/login-registering.png
                :alt: Portal Registration
                :align: center
                :scale: 50%

            Your registration form may have slight differences.

         #. Complete the registration form with the required details,
            including the verification field, if present.  Take note of your
            username, you'll need this to log in.

         #. Click the ``Register`` button at the bottom of the form to
            complete your registration.

         #. You will be required to validate your email address in order to
            use your account.  You be sent a validation email containing a
            link you'll need to click to verify your account and set a
            password.

         #. Once you have completed these steps, your account will be ready
            for use.

      If you're collaborating with colleagues, they can now find your
      account on |project-name| and may share content with you.


Permissions and access
======================

In a nutshell, a user can be granted access to perform specific actions in
different areas of the site.

Access is granted via *roles*, which can be granted either within a specific
area of the site (called :ref:`local roles <local-roles>`), which can be
managed by users that already have permissions, or across an entire site site
(called :ref:`global roles <global-roles>`), which are the managed by site
administrators.

Access can be granted either to a specific user or a group of users.  Creation
and management of groups of users is managed by site administrators.

Issues or concerns about insufficient access should be directed towards your
site administrator or nominated representative, such as a colleague or
collaborator.

For more information on granting and controlling access, see
:ref:`sharing-your-content`.

Managing portlets
=================

What are portlets?
------------------

Portlets are small panels of information that you can display to either help
your users or improve page display. If you've used your Plone site, you'll
already have used portlets - likely without even knowing.  Here's an example:

.. image:: /images/portlet_example.png
   :alt: Portlet example
   :align: center

.. image:: /images/portlet_manage.png
   :alt: Manage portlet
   :align: right

The area highlighted in red contains the portlets. Portlets may exist (by
default) on the right hand side of the page. On the example image, you can see
a Navigation portlet on the right.

You can customise your portlets to suit by adding static information, live
updated listings (such as events, news, or collections), RSS feeds from
external sites, flexible navigation, search and more.

Behaviour and inheritance
-------------------------

Portlets applied to a given folder (or the top-level of the site) will, by
default, be shown for all content items beneath that folder.  For example, if a
navigation portlet is configured on a folder called ``News``, then all news
items inside that folder will also see the same portlet.  It is possible to
override this behaviour on sub-folders or individual content items, however.


Permission to change portlets
-----------------------------

.. only:: user-portlet-management

    By default, portlet management is only available to users that are Site
    administrators.  However, for |project-name| this restriction has been
    relaxed to allow content editors the ability to control their portlets.

To determine if you can add or edit portlets, look for the ``Manage portlets``
link. If you see it, then you have sufficient permission. If not, then you'll
need to contact a site administrator to have them make the changes for you or
otherwise give you access.


Adding new portlets
-------------------

To add a new portlet:

#. Browse to the area of the site the portlet should be shown. For example, if
   you add a portlet at the top-level of your site, it will appear everywhere,
   except when overriden.

#. Click the ``Manage portlets`` link at the bottom of the page, or at the bottom
   of either left or right portlet column.

   .. image:: /images/portlet_manage1.png
      :alt: Manage portlet
      :align: right

#. On the ``Manage portlets`` page, click the ``Add portlet`` menu at the top
   of the column you'd like to add a portlet to.

#. Examine the different types of available portlets. Most are simple and 
   self-descriptive as to what that they provide. For example, if you want to
   add some static content like images or text, then choose ``Static Text
   Portlet``. Feel free to experiment here. You can easily remove new portlets
   later.

#. Click the name of the portlet you'd like to add.

#. On the next page, configure the portlet accordingly. Each portlet is
   different in their options.  Configuration fields will customise how the
   portlet and its information are displayed. You can come back at any time to
   adjust settings further.

#. Once you're ready, click the ``Save Settings`` button to create the portlet.

#. Click the ``Return`` link of the ``Manage portlets`` page to go back to see
   your results. You may need to clear your cache (or hold the :kbd:`Shift` key and
   click your browser's ``Refresh`` button) to see the change.


Editing existing portlets
-------------------------

.. image:: /images/portlet_edit.png
   :alt: Edit portlet
   :align: right

To edit an existing portlet:

#. Browse to the area of the site that the portlet is applied to. If you can't
   find specifically where this is, don't worry - just browse to somewhere you
   see the portlet as the site directs you accordingly.

#. Click the ``Manage portlets`` link at the bottom of either left or right
   portlet column.

#. On the ``Manage portlets`` page, click the name of portlet you'd like to
   modify. In the example given here, you could click ``Calendar`` or 
   ``RSS: ABC News`` to modify the options.

#. Change the options you'd like to modify. Each portlet's options are
   different, so we encourage you to experiment with different configurations.
   You can always come back.

#. Once you're ready, click the ``Save`` button to save modifications to the
   portlet.

#. Click the ``Return`` link of the ``Manage portlets`` page to go back to see
   your results. You may need to clear your cache (or hold the :kbd:`Shift` key and
   click your browser's ``Refresh`` button) to see the change.


Managing portlets
-----------------

You can also re-order, hide, override and remove portlets from your site or
from a specific area on the site. To manage your portlets:

.. image:: /images/portlet_edit.png
   :alt: Edit portlet
   :align: right

#. Browse to the area of the site that you'd like to manage portlets for.

#. Click the ``Manage portlets`` link at the bottom of the portlet column.

#. On the ``Manage portlets`` page, you'll see a list of existing portlets.
   There are several actions you can now perform:

   To re-order portlets:
       Use the up and down arrows in the listing. Up arrows move the given
       portlet up one position, and down arrows move the given portlet down one
       position.
   To hide a portlet:
       Click the ``Hide`` link next to the portlet's name. This is a safe
       alternative to removing a portlet if you think you might want to show it
       again at some point.
   To remove a portlet:
       Click the ``'X'`` icon next to the portlet's name. This will remove the
       portlet and is not reversible. If you think you might need the portlet
       later, we suggest you just ``Hide`` it.
   To override the portlets in an area:
       Click the relevant drop down menu under ``'Block/unblock portlets'`` and
       choose the option you'd like. By selecting ``Block`` under ``Parent
       portlets`` for instance, you will prevent parent folders' portlets from
       being displayed here. Remember that by default, portlets from parent
       folders are applied to child content.

#. Once you're done managing your portlets, click the ``Save settings`` button at the bottom of the column.


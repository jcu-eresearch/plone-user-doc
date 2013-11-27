Customising Layout and Design
*****************************

**Within your Plone site, you have the ability to control what information is displayed,
where and how**

Managing Portlets
=================

**Portlets are small panels of information that you can associate with different 
areas of your site.**

You can customise your portlets to suit by adding static information, live updated listings
(such as events, news, or collections), RSS feeds from external sites, flexible navigation, 
search and more.  By default, portlet management is only available to users that are Site 
Administrators, however this may be different for your Plone site.

**What are portlets**

Portlets are small panels of information that you can display to either help your users or 
improve page display. If you've used your Plone site, you'll already have used portlets - 
likely without even knowing.  Here's an example:

.. image:: /images/portlet_example.png
   :alt: Portlet example
   :align: center

.. image:: /images/portlet_manage.png
   :alt: Manage portlet
   :align: right

The area highlighted in red contains the portlets. Portlets may exist (by default) on the 
right hand side of the page. On the example image, you can see a Navigation portlet on the right.

As mentioned above, you will need to be a Site Administrator to be able to add or modify your portlets.
If you are an Editor, you will be able to perform these actions too. To determine if you can add or edit 
portlets, look for the 'Manage portlets' link as shown to the right. If you see it, then you have 
sufficient permission. If not, then you'll need to contact a Site Administrator to have them make the changes
for you or give you access.

Also keep in mind that a portlet is applied to a given folder (or top-level of the site), then by
default, those portlets will be shown on the area they're applied to and for all content below it,
such as sub-folders and pages (unless specifically overriden).


**Adding new portlets**

To add a new portlet:

1. Browse to the area of the site you'd like to see the portlet. So, if you add a portlet at the top-level of your site, it will appear everywhere. 
2. Click the *Manage portlets* link at the bottom of the portlet column.

.. image:: /images/portlet_manage1.png
   :alt: Manage portlet
   :align: right

3. On the 'Manage portlets' page, click the 'Add portlet' menu at the top of the column you'd like to add a portlet to.
4. Have a look through the different types of available portlet. Most are self-explanatory and describe a listing of content that they provide. If you want to just add some static content like an image or text, then choose *Static Text Portlet*. Feel free to experiment here. You can easily remove new portlets later.
5. Click the name of the portlet you'd like to add.
6. On the next page, configure the portlet accordingly. Each portlet is different in their options - all options will configure how the portlet and its information are displayed. You can come back at any time to adjust them.
7. Once you're ready, click the *Save Settings* button to create the portlet.
8. Click the *Return* link of the *Manage portlets* page to go back to see your results. You may need to clear your cache (or hold the Shift key and click your browser's Refresh button) to see the change.

.. image:: /images/portlet_edit.png
   :alt: Edit portlet
   :align: right

**Editing existing portlets**

To edit an existing portlet:

1. Browse to the area of the site that the portlet is applied to. If you can't find specifically where this is, don't worry - just browse to somewhere you see the portlet.
2. Click the *Manage portlets* link at the bottom of the portlet column.
3. On the *Manage portlets* page, click the name of portlet you'd like to modify. In the example to the right, you could click 'Calendar' or 'RSS: ABC News' to modify the options.
4. Change the options you'd like to modify. Each portlet's options are different, so we encourage you to experiment with different configurations. You can always come back.
5. Once you're ready, click the 'Save' button to save modifications to the portlet.
6. Click the *Return* link of the *Manage portlets* page to go back to see your results. You may need to clear your cache (or hold the Shift key and click your browser's Refresh button) to see the change.


**Managing portlets**

You can also re-order, hide, override and remove portlets from your site. To manage your portlets:

.. image:: /images/portlet_edit.png
   :alt: Edit portlet
   :align: right

1. Browse to the area of the site that you'd like to manage portlets for.
2. Click the *Manage portlets* link at the bottom of the portlet column.
3. On the *Manage portlets* page, you'll see a list of existing portlets.

   1. **To re-order portlets**, use the up and down arrows in the listing. Up arrows move the given portlet up one position, and down arrows move the given portlet down one position.
   2. **To hide a portlet**, click the *Hide* link next to the portlet's name. This is a safe alternative to removing a portlet if you think you might want to show it again at some point.
   3. **To remove a portlet**, click the *'X'* icon next to the portlet's name. This will remove the portlet and is not reversible. If you think you might need the portlet later, we suggest you just *Hide* it.
   4. **To override the portlets in an area**, click the relevant drop down menu under *'Block/unblock portlets'* and choose the option you'd like. By selecting *Block* under *Parent portlets* for instance, you will prevent parent folders' portlets from being displayed here. Remember that by default, portlets from parent folders are applied to child content.

4. Once you're done managing your portlets, click the *Save settings* button at the bottom of the column.

========================================
Create opportunities from a contact form
========================================

Adding a contact form to a website makes it easy to convert visitors into leads and opportunities.
After a visitor submits their information, an opportunity can be created automatically, and assigned
to a designated sales team.

Add a contact form to a website
===============================

By default, the *Contact Us* page on an Odoo website displays a preconfigured contact form.


Customize contact forms
=======================

Contact forms can be customized to capture information that suits the needs of a specific sales
team.

- :guilabel:`Action`: the default action for a contact form is :guilabel:`Send an Email`. Select
  :guilabel:`Create an Opportunity` from the drop-down list to capture the information in the *CRM*.
- :guilabel:`Sales Team`:
- :guilabel:`Salesperson`:
- :guilabel:`Marked Fields`:
- :guilabel:`Mark Text`:
- :guilabel:`Labels Width`:
- :guilabel:`On Success`:
- :guilabel:`URL`:
- :guilabel:`Visibility`:

.. image:: opportunities_form/form-customization.png
   :align: center
   :alt: The form configuration settings on an Odoo website.

.. important::
   If leads are activated in CRM settings, selecting :guilabel:`Create an Opportunity`
   generates a lead instead. To activate leads, navigate to :menuselection:`CRM app -->
   Configuration --> Settings` and tick the :guilabel:`Leads` checkbox, then click :guilabel:`Save`.

Customize contact form fields
-----------------------------

In Edit mode on the website, click on any field to start editing it. The following information can
be edited for each field on the Contact Form:

- :guilabel:`Type`: choose a custom field option or an existing field. Examples include phone, file
  upload, language, etc.
- :guilabel:`Input Type`: determine the type of entry customers should input. Available options are
  text,email, telephone, and URL.
- :guilabel:`Label`: type in the display name to show users what information is needed from
  them.
- :guilabel:`Position`: choose the way the label is aligned with the rest of the form. The
  label can be hidden, above the field, to the far left of the field, or right adjusted and closer
  to the field.
- :guilabel:`Placeholder`: type in an example to guide users how to input information where
  formatting is important, such as a phone number or email address.
- :guilabel:`Default Value`:
- :guilabel:`Required`:
- :guilabel:`Visibility`:
- :guilabel:`Animation`:

.. tip::
   Forms can be created from scratch to serve a wide variety of purposes. However, Odoo's default
   *Contact Us* page is designed to fit most users' needs. Start with the default form and modify
   from there.

View opportunities
==================

============
Event tracks
============

Odoo *Events* provides users with the ability to create, schedule, and manage talks, lectures,
demonstrations, presentations, etc., which are otherwise known as *Tracks*.

The Odoo *Events* application also has an option for users to allow event attendees to propose
talks for an event, which can then be approved (or disapproved) by internal users on the database.

Configuration
=============

First, there are some settings that need to be enabled, in order for users to get the most out of
their event tracks.

To do that, navigate to :menuselection:`Events app --> Configuration --> Settings`, and tick the
checkbox beside the :guilabel:`Schedule & Tracks` setting. Doing so allows users to manage and
publish an event schedule with various tracks.

Also, when that setting checkbox is ticked, two additional setting options appear beneath it:
:guilabel:`Live Broadcast` and :guilabel:`Event Gamification`.

.. image:: track_manage_talks/track-settings.png
   :align: center
   :alt: The Schedule and Tracks setting in the Odoo Events app, along with corresponding options.

The :guilabel:`Live Broadcast` option allows users to air tracks online through a *YouTube*
integration.

The :guilabel:`Event Gamification` options allows users to share a quiz with track attendees once
the track is over, in order to test how much they learned.

.. note::
   With the :guilabel:`Event Gamification` setting enabled, an :guilabel:`Add Quiz` button appears
   on track forms, allowing the user to quickly create a quiz specific to the topic related to that
   particular track.

Once all desired settings have been enabled, be sure to click the :guilabel:`Save` button in the
upper-left corner of the :guilabel:`Settings` page.

Event Tracks page
=================

To access, modify, and/or create tracks for an event, first navigate to a preconfigured event, or
create a new one from the *Events* application.

To do that, navigate to :menuselection:`Events app`, and either select a pre-existing event from the
:guilabel:`Events` dashboard, or create a new one by clicking :guilabel:`New`.

Once on the desired event form, click into the :guilabel:`Tracks` smart button at the top of the
form. If that smart button is not readily available, click the :guilabel:`More` :icon:`fa-sort-desc`
drop-down menu to reveal hidden smart buttons.

Then, click :guilabel:`Tracks` from the resulting drop-down menu.

Clicking that smart button reveals the :guilabel:`Event Tracks` page for that particular event,
which presents all the tracks (both scheduled and proposed) for the event, if there are any.

.. image:: track_manage_talks/event-tracks-page.png
   :align: center
   :alt: Typical event tracks page for an event in the Odoo Events application.

The tracks are presented in a default Kanban view, but there is also the option to view these tracks
in a :guilabel:`List`, :guilabel:`Gantt` chart, :guilabel:`Calendar`, :guilabel:`Graph`, or
:guilabel:`Activity` view. All of which are accessible in the upper-right corner of the
:guilabel:`Tracks` page.

In the default Kanban view, the tracks are categorized into different stages. The default stages
are: :guilabel:`Proposal`, :guilabel:`Confirmed`, :guilabel:`Announced`, :guilabel:`Published`,
:guilabel:`Refused`, and :guilabel:`Cancelled`. All of which can be edited, if needed.

Clicking into a track from the :guilabel:`Event Tracks` page reveals the track form for that
particular track.

Create event track
------------------

From the :guilabel:`Event Tracks` page, click :guilabel:`New` to reveal a blank event track form to
use to create an event track.

.. image:: track_manage_talks/event-track-form.png
   :align: center
   :alt: Typical event track form in the Odoo Events application.

Start by giving this track a :guilabel:`Title`.

Then, if desired, add an accompanying image to the track via the :icon:`fa-pencil`
:guilabel:`(pencil)` icon that appears when the cursor hovers over the :icon:`fa-camera`
:guilabel:`(camera)` icon in the upper-right corner of the form. When clicked, proceed to upload the
desired image for the track.

Next, apply a :guilabel:`Track Date` for the track, and designate a :guilabel:`Location` where the
talk is planning to be held.

Then, add a :guilabel:`Duration` to the track.

If the :guilabel:`Live Broadcast` setting has been enabled, users have the option to add a
corresponding link in the :guilabel:`YouTube Video Link` field.

If the :guilabel:`Always Wishlisted` checkbox is ticked, the talk is automatically set as a favorite
for each registered attendee.

Assign an internal user to be in charge of managing this event in the :guilabel:`Responsible` field.
By default, the user who initially created the track is assigned.

Then, ensure the track is applied to the correct event in the :guilabel:`Event` field. By default,
this field is populated with the event related to the *Event Tracks* page the track was originally
created from.

Next, choose to add existing tags, or create new ones, to further organize the track. These tags,
and their corresponding tag categories are utilized on the event specific website - mainly on the
*Talks* web page on the event website, via the drop-down filter menus.

Beneath that general information section, there are three tabs: :guilabel:`Speaker`,
:guilabel:`Description`, and :guilabel:`Interactivity`.

Speaker tab
~~~~~~~~~~~

The :guilabel:`Speaker` tab on an event track form is filled with various fields related to the
specific speaker who is planning to conduct/host the track.

.. image:: track_manage_talks/speaker-tab.png
   :align: center
   :alt: The Speaker tab on an event track form in the Odoo Events application.

Contact Details section
***********************

In the :guilabel:`Contact Details` section, proceed to use the :guilabel:`Contact` drop-down field
to select an existing contact from the database as the main point of contact for the talk.

If this contact is not yet in the database, type in the name of the contact, and click
:guilabel:`Create` to create and edit the contact form later, or click :guilabel:`Create and
edit...` to be taken to that new contact's contact form, where the rest of their pertinent
information can be entered.

The :guilabel:`Contact Email` and :guilabel:`Contact Phone` fields are greyed-out and populated with
the information found on that chosen contact's contact form. These fields are not modifiable.

Speaker Bio section
*******************

In the :guilabel:`Speaker Bio` section, proceed to enter information related to the specific speaker
scheduled to conduct/host the track.

Start by entering a :guilabel:`Name`, :guilabel:`Email`, and :guilabel:`Phone` number for the speaker.

Next, if desired, add an image to appear alongside the speaker biogrpahy on the event website, via
the :icon:`fa-pencil` :guilabel:`(pencil)` icon that appears when the cursor hovers over the
:icon:`fa-camera` :guilabel:`(camera)` icon. When clicked, proceed to upload the desired image for
the speaker.

Then, enter a :guilabel:`Job Position` for the designated speaker, followed by the
:guilabel:`Company Name` associated with the speaker.

In the :guilabel:`Biography` field, proceed to enter in a custom biography with any speaker-related
information.

Description tab
~~~~~~~~~~~~~~~

The :guilabel:`Decription` tab of an event track form is a blank text field, in which a description
of the track can be entered. The information entered here appears on the specific track page on the
event website.

Interactivity tab
~~~~~~~~~~~~~~~~~

The :guilabel:`Interactivity` tab on an event track form features a single option at first:
:guilabel:`Magic Button`.

.. image:: track_manage_talks/interactivity-tab.png
   :align: center
   :alt: The Interactivity tab on an event track form in the Odoo Events application.

When the checkbox beside :guilabel:`Magic Button` is ticked, Odoo displays a *call to action* button
to attendees while the track is taking place.

With that checkbox ticked, three more options appear, all of which are related to the
:guilabel:`Magic Button`:

- :guilabel:`Button Title`: enter a title to appear on the button for attendees
- :guilabel:`Button Target URL`: enter a URL for Odoo to take attendees who click the button
- :guilabel:`Show Button`: enter a number in the field, and the button will appear that many
  :guilabel:`minutes after Track start`

Publish event track
===================

Once all the desired configurations are complete on an event track form, proceed to move it into the
appropriate Kanban stage on the :guilabel:`Event Tracks` page for the event it is meant for.

Then, from the event track form, click the :guilabel:`Go to Website` smart button, and Odoo reveals
the event track page as it will appear on the event website.

In order for the track page to be viewable (and accessible) for event attendees, toggle the
:guilabel:`Unpublished` switch to :guilabel:`Published`, thus making it accessible for attendees.

.. image:: track_manage_talks/published-toggle.png
   :align: center
   :alt: The track-related event submenu options on an event website built with Odoo Events.

.. seealso::
   - :doc:`event_essentials`
   - :doc:`track_manage_talks`

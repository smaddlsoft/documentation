===================
Vendor costs report
===================

.. |RFQ| replace:: :abbr:`RfQ (Request for Quotation)`
.. |RFQs| replace:: :abbr:`RfQs (Requests for Quotation)`
.. |POs| replace:: :abbr:`POs (Purchase Orders)`
.. |caret| replace:: :icon:`fa-caret-down` :guilabel:`(down)` icon

With the *Purchase* application, users can track the fluctuation of vendor costs over time. This
allows users to identify the most expensive vendors, and track seasonal changes.

Create a vendor costs report
============================

To create a vendor costs report, first navigate to :menuselection:`Purchase app --> Reporting -->
Purchase` to open the :guilabel:`Purchase Analysis` dashboard. By default, the dashboard displays a
line chart overview of the untaxed total of POs (Purchase Orders) with a confirmation date for the
current month, or of RFQs (Requests for Quotation) with a status of draft, sent, or cancelled.

Add filters and groups
----------------------

On the top-right, click the :icon:`oi-view-pivot` :guilabel:`(pivot)` icon to switch to pivot view.

Click into the :guilabel:`Search...` bar and remove any default filters. Then, click the |caret| to
open the drop-down menu that contains the :guilabel:`Filters`, :guilabel:`Group By`, and
:guilabel:`Favorites` columns.

.. note::
   Unless otherwise specified, the report displays data from both |RFQs| and |POs|. This can be
   changed by selecting either :guilabel:`Requests for Quotation` or :guilabel:`Purchase Orders`
   under the :guilabel:`Filters` column.

Under the :guilabel:`Filters` column, select a date range to use for comparison. The report can be
filtered by either :guilabel:`Order Date` or :guilabel:`Confirmation Date`. Choose one from the
list, and click the |caret| to specify the date range, either by month, quarter, or year.

Next, under the :guilabel:`Group by` column, select :guilabel:`Vendor`. Then, select
:guilabel:`Product`.

.. note::
    Selecting :guilabel:`Product` is **not** required for this report, however, as it provides
    additional insight into the performance of individual vendors, it is recommended. Additional
    selections can be made under the :guilabel:`Group by` heading as well, including
    :guilabel:`Product Category`, :guilabel:`Status`, and :guilabel:`Purchase Representative`.

    To ensure the report is generated correctly, make sure that :guilabel:`Vendor` is the **first**
    selection made under the :guilabel:`Group By` column.

Next, make a selection under the :guilabel:`Comparison` heading. These options are only available
after the date range is selected under the :guilabel:`Filters` column, and vary based on that range.
:guilabel:`Previous Period` adds a comparison to the previous period, such as the last month or
quarter. :guilabel:`Previous Year` compares the same time period from the previous year.

.. note::
   While multiple time-based filters can be added at once, only one comparison can be selected at a
   time.

.. image:: vendor_costs_report/filters-groups.png
   :align: center
   :alt: The drop-down menu of filters, group by and comparison options for the vendor costs report.

Add measures
------------

After selecting the :guilabel:`Filters`, :guilabel:`Group by`, and :guilabel:`Comparison` settings,
click out of the drop-down menu.

By default, the report displays with the following measures: :guilabel:`Order`, :guilabel:`Total`,
:guilabel:`Untaxed Total`, and :guilabel:`Count`. Click :guilabel:`Measures` at the top-left to open
the drop-down list of available measures. Click :guilabel:`Average Cost` to add it to the report.
Select any additional measures to add to the report, or click on any of the already selected
measures to remove them, if desired.

.. tip::
   It is recommended to run the report with at least :guilabel:`Average Cost`, :guilabel:`Total`, or
   :guilabel:`Untaxed Total` selected from the :guilabel:`Measures` list. Additional measures, such
   as :guilabel:`Days to Receive`, can be added to provide additional insights.

View results
============

The vendor costs report displays in the *pivot* view by default. Click :guilabel:`Insert in
Spreadsheet` to add the pivot view into an editable spreadsheet format within the *Dashboards* app.
If the Odoo *Documents* app is installed, the report can be inserted into a blank or existing
spreadsheet, and exported.

.. image:: vendor_costs_report/sample-vendor-report.png
   :align: center
   :alt: A sample of a vendor costs report with the measures set as total and average costs.

.. note::
   The vendor costs report is also available in *graph* view. Click the :icon:`fa-area-chart`
   :guilabel:`(area chart)` icon to change to graph view. Click the corresponding icon at the top of
   the report to switch to a :icon:`fa-bar-chart` :guilabel:`(bar chart)`, :icon:`fa-line-chart`
   :guilabel:`(line chart)`, or :icon:`fa-pie-chart` :guilabel:`(pie chart)`.


Save and share a favorite search
--------------------------------

The *Favorites* feature found on Odoo reports allows users to save their most commonly used filters,
without having to reconstruct them every time they are needed.

To create and save a new *Favorites* configuration on a report, follow the steps below:

#. Set the necessary parameters using the :guilabel:`Filters`, :guilabel:`Group By` and
   :guilabel:`Measures` options.
#. Click the :icon:`fa-caret-down` :guilabel:`(down)` icon next to the :guilabel:`Search...` bar to
   open the drop-down menu.
#. Under the :guilabel:`Favorites` heading, click :guilabel:`Save current search`.
#. If desired, enter a new name for the report.
#. Tick the :guilabel:`Default Filter` checkbox to have these filter settings automatically
   displayed when the report is opened. Otherwise, leave it blank.
#. Tick the :guilabel:`Shared` checkbox to make this filter configuration available to all other
   database users. If this checkbox is not ticked, only the user who creates the filter can access
   it.
#. Click :guilabel:`Save` to preserve the configuration for future use.

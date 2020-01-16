## Tasks

***Within 24 Hours of Meeting***

 - [ ] Update the [shared calendar][calendar] series by extending it and and inviting any new attendees.
 - [ ] Visit the learning [shared document folder][folder].
 - [ ] Right-click on `Meeting - 2019 - MM - DD`.
 - [ ] Select {% if site.reference == 'onedrive' %}`copy to`{% else %}`Make a copy`{% endif %}.
 - [ ] Replace MM and DD in the document name with the two-digit month and day of the upcoming meeting.
 - [ ] Open the document and follow the steps in the ***Do these things to set up this document section***.
 - [ ] Update the calendar invite for the next meeting to add:
   * Write-enabled link to the agenda document.
   * Copy/pasted role assignments and agenda detail.


***Tips***
* Create a short todo list of instructions in the agenda template.  
This can be used to collect information into a single place for review during the meeting, 
or linking to metrics in a spreadsheet.
* Put the most important task to complete first in the agenda.

{% if site.reference != nil %}
***To create a new shared document***
{% capture type %}default_roles/scheduler-{{site.reference}}.md{% endcapture %}
{% include {{ type }} %}
{% endif %}

{% include links.md %}
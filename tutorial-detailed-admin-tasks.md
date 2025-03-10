---
layout: page
category: walkthrough
title: Administration tasks
is-detailed: true

---

<div id="toc">
Table of Contents
<ol>
    <li><a href="#logging_in">Logging In</a></li>
    <li><a href="#users">Adding Users</a></li>
    <li><a href="#admin-groups">Creating groups and adding users to them</a></li>
    <li><a href="#admin-new-inst">Adding new instruments</a></li>
    <li><a href="#admin-reports">Creating project and monthly reports</a></li>
</ol>
</div>

<a name="login"/>

{% include logging_in.md detailed=page.is-detailed %}


In order to perform the tasks in this section you must be a MISO admin.
Email IT, CC Morgan Taschuk and request to be added to the `MISO_ROLE_ADMIN`
Active Directory group.

<a name="users" href="#" id="toplink">top</a>

# 2. Adding Users

OICR uses Active Directory authentication for MISO. Users must be added by IT; once added,
they can then log in to MISO using their email credentials.

1. Please email ithelpdesk@oicr.on.ca and CC Morgan Taschuk to request that the user be added to MISO LIMS by
making them part of the following Active Directory groups:
    * If the person is to be added as an admin: `MISO_ROLE_ADMIN` and `MISO_ROLE_INTERNAL` groups.
    * If the person is not to be given admin access: `MISO_ROLE_INTERNAL` group.

{% include admin-new-inst.md %}

{% include admin-reports.md %}


< <a href="tutorial-detailed-introduction">Introduction</a> | <a href="index">Home</a> | <a href="tutorial-detailed-boxes">Working with Boxes</a> >

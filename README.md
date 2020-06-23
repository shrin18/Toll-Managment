# System SW Epic Creator

This tool is used to report issues and faults in a calibration system of a Scania Truck with all the necessary specifications regarding who makes the report and what is the status of the part which is damaged. Collecting the information of every vehicle part and the  fault data and retrieving them on uses is main aim of this project. Apart from storing vehicle records it keeps record of all the employees working and all the departments that are currently active or reactive.

This project is built in VB.net with framework 4.6.1 and SQL-Server as database. Because the project uses "Visual Studio" so it is windows operating system dependent. Although database is used, but the images of vehicle are not stored in it, for not letting the database go overloaded and affecting the performance of the project.

The structure of the project is as follows:

<ul>
<li>The employee section contains an option to "Add", "Edit", "View" and "Settings"</li>
<li>Create issue. There are two types of issues Epic and SOP issues. Every issue has certain fields which the reporter needs to fill in along with whom he wants to assign the issue to<?li>
<li>An agile epic is a body of work that can be broken down into specific tasks (called “stories,” or “user stories”) based on the needs/requests of customers or end users.Epics are a helpful way to organize your work and to create a hierarchy </li>
</ul>

The section for epic issue creates an issue on the epic form which can have epic links with stories. Whereas the issues in the SOP creates issues for the SOP. Each projects contains:

<ol>
<li>Project info</li>
<li>Priority of the issue</li>
<li>Name of the assignee</li>
<li>Version of the project</li>
</ol>

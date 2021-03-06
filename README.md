# DBM
Database Manager (DBM) is SmallBasic software developed by Abhishek Sathiabalan 
The software is licensed under the EULA found in the Assets Folder. 

v1.1.2.1

#Features :
<ol type = "1">
	<li> Bootstrapper lets you run your own SmallBasic code and use the Application as a framework </li>
	<li> GUI on top of the sqlite database engine </li>
	<li> You can export to the following : HTML , SQL , XML , and CSV </li>
	<li> You can import data into the database from a CSV file and SQL file </li>
	<li> Ability to log all transactions made using the application </li>
	<li> Ability to extend the application  </li>
	<li> GUI lessens the requirement to know SQL </li>
	<li> Dynamic Plugin Loader </li>
	<li> Simple Configuration </li>
	<li> Server-less </li>
	<li> Excellent for debugging purposes  </li>
	<li> License is fairly open </li>
	<li> Partial Localization for over 50 languages </li>
</ol>

Do not use this application if :
<ol type = "1">
	<li> You are technically illiterate </li>
	<li> You do not wish to learn SQL.  </li>
	<li> You do wish to have concurrent writes. Currently sqlite does not offer that ability but does serial writes </li>
</ol>

#Specifications 
<ol type = "1">
	<li> See the Sqlite Specifications . The application is built on top of Sqlite</li>
</ol>

#Bugs
<ol type = "1">
	<li> Editing view may not store data correctly if SQL Specific constraints are present</li>
</ol>

#Road Map :
<ul>
	<li> XML Based Menu and Actions </li>
	<li> Localization Initiative </li>
	<li> Cross Engine Support </li>
	<ul>
		<li>MySQL</li>
		<li>Odbc</li>
		<li>OleDb</li>
		<li>SqlServer</li>
	</ul>
	<li>Custom Connection Strings </li>
</ul>

#Notice:
Due to a git versioning issue all previous commits have been reset and are no longer comparable.
The first commit of the new version is v1.1.2.1. Previous versions such as v1.1.2.0 are on the release tab.
Other changes can be followed through pull requests.
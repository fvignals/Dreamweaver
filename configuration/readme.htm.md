<style type="text/css">

<!--

th

	{font-family:Verdana,Arial,Helvetica,sans-serif;

	font-size:10pt;

	font-weight:bold}

h2

	{font-family:Verdana,Arial,Helvetica,sans-serif;

	font-size:18pt}

td, p

	{font-family:Verdana,Arial,Helvetica,sans-serif;

	font-size:10pt}

code

	{font-size:11pt}

.grey

	{color:#666666}

.red

	{color:#FF0000}

.TO_FIX

	{background-color:#F90;

	padding:2px}

-->

</style>

</head>

<body bgcolor="#FFFFFF">

<h2>Adobe Dreamweaver CC 2017 configuration folders</h2>

<p>Many Dreamweaver features are extensions developed in JavaScript and HTML. The configuration folders contain these extensions. When you customize or extend Dreamweaver, you modify these files or add your code source files to one or more of these

  folders. By familiarizing yourself with these folders, you can discover the interface for extensions as well as working examples of each extension type.</p>

<p><em><strong class="red">Warning:</strong> The files in the configuration folders are critical to the functioning of Dreamweaver. <strong>Do not modify, delete, or add to these files unless you know how to customize and extend Dreamweaver.</strong> Before you attempt to customize Dreamweaver, read </em><a href="http://www.adobe.com/go/learn_dw_extending_en" target="_blank">Extending Dreamweaver</a><em> and </em><a href="http://www.adobe.com/go/learn_dw_api_en" target="_blank">The Dreamweaver API Reference</a><em>. </em></p>

<p>Some folder names are obvious. For example, Objects are grouped in the Objects folder; Behaviors are grouped in the Behaviors folder. One folder that does not correspond to a particular extension type is the Shared folder. The Shared folder is the central repository

  for utility functions, classes, and images that are commonly used by all extensions.</p>

<p>Each subsequent installation of Dreamweaver produces another version of the configuration directory per user. Dreamweaver appends each old configuration folder with a version number (for example &quot;Configuration-1&quot;, &quot;Configuration-2&quot;, etc.) where the higher the number,

 the newer the folder. The most recent version of the configuration folder is always called, simply, &quot;Configuration&quot;.</p>

<p>The following table maps the configuration files and folders with Dreamweaver features:</p>

<table width="100%" border="1" cellpadding="5" cellspacing="0">

<tbody>

<tr align="left">

<th bgcolor="#99FF00" valign="top">File/folder name</th>

<th bgcolor="#99FF00" colspan="2">Contents</th>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">ActiveXNames.txt</th>

<td colspan="2">A list of ActiveX class IDs; used to populate the ClassID pop-up menu in the ActiveX inspector.

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">brackets.json</th>

  <td colspan="2">Specifies Brackets preferences.</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">CustomBrowserViewableExtTypes.txt</th>

  <td colspan="2">Customized viewable extension types in browser</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Extensions.txt</th>

<td colspan="2">

<p>A list of file extensions recognized by Dreamweaver. </p>

<p>If you add an extension to this file, double-clicking a file with that extension in the Site panel opens it in Dreamweaver.</p>

<p>Extensions.txt also determines what file types are shown in the File &gt; Open dialog box. 
To show files of a particular type in that dialog box by default, add the appropriate extension to the first line of Extensions.txt. For more information, see
	<cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">FTPExtensionMap.txt</th>

<td colspan="2">

<p>A list of file extensions and the transfer modes associated with them.</p>

<p>This file determines how files are uploaded and downloaded by Dreamweaver: in ASCII mode or Binary mode. You can add items to this list or change the mode of existing items. On the Macintosh, this file is also used to set the file type and creator of files

 that are downloaded from a non-Macintosh server. </p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">IceIdList.txt</th>

<td colspan="2">

<p>Lists id or class values that will be promoted to ICE editable regions when the user creates a new 

HTML file with InContext Editable regions.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">KeyboardLayouts.xml</th>

  <td colspan="2">Keyboard layouts for different locales</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">state.json</th>

  <td colspan="2">Specifies whether the panels on the sidebar is enabled or not.</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">version.xml</th>

<td colspan="2">

<p>The version.xml file contains information about your Dreamweaver installation. Do not edit or delete this file.</p>

</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">ViewableExtTypes.txt</th>

  <td colspan="2">Lists the extension types that can be viewed in Dreamweaver on Windows.</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">ViewableExtTypesMac.txt</th>

  <td colspan="2">Lists the extension types that can be viewed in Dreamweaver on macOS.</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">webkitCssFunction.js</th>

  <td colspan="2">The functions in this file are used to make direct CSS Style edits to the Webkit DOM.</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top"><p>ActiveContent</p></th>

  <td colspan="2">Dreamweaver searches for the regular expressions listed within this folder in order to 

determine if a script block is actually a special active-content conversion script block.</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Behaviors</th>

<td colspan="2">Files used by the Behavior inspector.</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Actions</th>

<td colspan="2">

<p>Items that appear in the Actions (&#43;) pop-up menu in the Behavior inspector.</p>

<p>Each action is separated into two files (one .js file and one .htm file) for localization purposes. The HTML file contains the interface for the behavior: the text and form fields that appear in a dialog box when you select the action from the Actions pop-up

 menu. The JavaScript file contains the JavaScript code that inserts the behavior into your document. Do not make changes to this file unless you are proficient in JavaScript and familiar with the Behavior API as documented in

<cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">BracketsProject</th>

  <td align="left" colspan="2" valign="top">Default project root of Brackets.</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">BracketsUtils</th>

  <td align="left" colspan="2" valign="top">Contains Brackets .json preferences </td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">BrowserProfiles</th>

  <td align="left" colspan="2" valign="top">Contains the browser profiles for different profiles</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">browsers</th>

  <td align="left" colspan="2" valign="top">Contains the WebKit browser used for Live View. This folder also contains the default style sheet applied to pages when you enter Live View;<br />

    if you don't like the default font, padding, or other values you can change them here.</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">Issues</th>

  <td colspan="2">

  <p>Files that define and search the user's document for browser rendering issues. The files in this folder are executed when the user runs a Browser Compatibility Check.

  </p>

  <p>Each Issue is separated into two files (one .js file and one .htm file) for localization purposes. The HTML file contains the localizable strings that will be presented to the user in the Browser Compatibility Check panel, should the issue be detected. (Issues

    have no user interface in and of themselves, so the body of the Issue HTML file is empty.) The JavaScript file contains the JavaScript code that defines the browsers for which the issue is relevant, that returns the strings from the HTML file, and that detects

    the presence of the issue in the user's document. Do not make changes to this file unless you are proficient in JavaScript and familiar with the Issues API as documented in

  <cite>Extending Dreamweaver</cite>.</p>

  </td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">BuiltIn</th>

<td align="left" colspan="2" valign="top">

<p>Templates for creating a variety of documents, including different page layouts.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">CEP</th>

  <td align="left" colspan="2" valign="top">CEP HTML Engine</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">CEPExtensions</th>

  <td align="left" colspan="2" valign="top">CEP extensions</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Certs</th>

  <td align="left" colspan="2" valign="top">Contains CA root certificates.</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Classes</th>

<td align="left" colspan="2" valign="top">

<p>Files used to read JavaBeans as data sources.</p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">CodeColoring</th>

<td align="left" colspan="2" valign="top">

<p>XML files that contain the color assignments for the Code View of a document. The CodeColoring directory also has specific files that correspond to the supported scripting languages (Javascript, VBScript, C#, and Visual Basic) where colors are assigned to

 code blocks and keywords.</p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">CodeHints</th>

<td align="left" colspan="2" valign="top">XML files that contain the associations and content for providing code hints while editing in Code view. (Note that many of the tags and attributes that are available as Code Hints come from tag libraries; see the Tag

 Libraries folder below.) </td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Commands</th>

  <td align="left" colspan="2" valign="top">

  <p>Items that appear in the Commands menu (and other menus within Dreamweaver).</p>

  <p>Many of the commands in this folder are separated into two files (one .js file and one .htm file) for localization purposes. The HTML file contains the interface&#8212;the text and form fields that appear in a dialog box when you select the command from the menu&#8212;for

    the command, if there is one, and it may also contain localizable strings and references to external JavaScript files (including the .js file of the same name). The JavaScript file contains the JavaScript code that makes the command work; do not make changes

    to this file unless you are proficient in JavaScript.</p>

  <p>You may notice that some of the items in the Commands folder have the same names as some of the items in the Objects folder. This is because some objects launch commands. Commands are more flexible than objects, but only objects can appear in the Insert

    panel. By calling a command from an object file, Dreamweaver can get the best of both kinds of extensions.</p>

  </td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Connections</th>

  <td colspan="2">

  <p>The files in this directory determine what appears in the plus (&#43;) pop-up menu of the database panel. This directory also includes the scripts (stored in the Scripts subfolder) used to retrieve data from the server. For more information about data connections,

    see &quot;The Database API&quot; in <cite>Extending Dreamweaver</cite>. </p>

  </td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Content</th>

<td align="left" colspan="2" valign="top">

<p>The Content folder contains the files used by the Reference panel.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">CSS</th>

  <td colspan="2" align="left" valign="top">CSS transition-related files</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">DevicePreview</th>

  <td align="left" colspan="2" valign="top">Contains strings that are used in Device Preview</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Dialogs</th>

  <td align="left" colspan="2" valign="top">Files to configure certain Dreamweaver dialogs. These should not be changed.</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">DocumentTypes</th>

  <td align="left" colspan="2" valign="top">

  <p>Basic templates for each supported document type.</p>

  </td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">ExtensionData</th>

<td align="left" colspan="2" valign="top">

<p><b class="grey">Note:</b> The files in this directory are only included for backwards compatibility, and are not used in the current method for working with extensions.

</p>

<p>XML metadata: Group and Participant data for extensions, including server behaviors.</p>

</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">MM</th>

<td colspan="2">

<p>XML Group and Participant extension data files. </p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Feedback</th>

  <td align="left" colspan="2" valign="top">Files related to feedback for different Dreamweaver features.</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Floaters</th>

  <td align="left" colspan="2" valign="top">

  <p>Custom floating panels.</p>

  </td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Fonts</th>

  <td align="left" colspan="2" valign="top">The fontStrings.xml file, which defines the default fonts that appear in the Font menu in the Property inspector, the font and font-family menus in the CSS panel, and other places in the Dreamweaver user interface.</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Formatters</th>

  <td align="left" colspan="2" valign="top">Scripts for applying various display formats, such as different Date/Time display formats or setting text to all uppercase or all lowercase.</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">FreeFonts</th>

<td align="left" colspan="2" valign="top">Fonts available to use with Dreamweaver</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">FreeFontsUtility</th>

  <td colspan="2" align="left" valign="top">Fonts utility</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99"><p>GradientEditor</p></th>

  <td align="left" colspan="2" valign="top">Gradient-related file</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">InAppWalkthrough</th>

  <td align="left" colspan="2" valign="top">In-app help strings in Dreamweaver.</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Inspectors</th>

<td align="left" colspan="2" valign="top">

<p>Custom property inspectors.</p>

<p>Most of the property inspectors in Dreamweaver are built into the core code of the product, but some&#8212;such as the inspectors for the

<code>META</code>, <code>TITLE</code>, and <code>LINK</code> tags&#8212;are written in HTML and JavaScript. The property inspectors in this folder are separated into two files (one .js file and one .htm file) for localization purposes. The HTML file contains the

 interface for the inspector: the text and form fields that appear in the Property inspector floating panel. The JavaScript file contains the JavaScript code that makes the inspector work; do not make changes to this file unless you are proficient in JavaScript

 and familiar with the Property inspector API as documented in <cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">JavascriptTests</th>

  <td align="left" colspan="2" valign="top">Javascript test files</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">jQuerySwatch</th>

  <td align="left" colspan="2" valign="top">jQuery functions</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">JSExtensions</th>

  <td align="left" colspan="2" valign="top">

  <p>Custom shared libraries.</p>

  <p>The custom shared libraries in this folder make Dreamweaver's extensions more powerful and flexible by adding new JavaScript functions. Because some of the files in the Translators and Commands files depend on these shared libraries, they should not be removed.

    To add your own shared libraries to Dreamweaver, see the section on C-level extensibility in

  <cite>Extending Dreamweaver</cite>.</p>

  </td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Knowledgeengines</th>

<td colspan="2" align="left" valign="top">Language-specific parser engines that parse user-entered code for a specific language (for example, PHP) and generate the generic metadata to be used by Dreamweaver's code hinting mechanism.<br />

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">LinterRuleSets</th>

  <td align="left" colspan="2" valign="top">Includes rule sets Dreamweaver uses for linting</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">MediaQuery</th>

  <td align="left" colspan="2" valign="top">Includes the styling information for different media queries</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Menus</th>

<td align="left" colspan="2" valign="top">

<p>The file that defines the entire menu structure for Dreamweaver (menus.xml), and a backup copy of that file (menus.bak) to allow you to restore default menus.

</p>

<p>The menus.xml file specifies the names and behavior of all menus and menu items in Dreamweaver (with a few notable exceptions; see Behaviors above and ServerBehaviors below, for example, for information on how the (&#43;) menus in the Behaviors and Server Behaviors

 panels, respectively, are populated). It also specifies all of the keyboard shortcuts and mnemonics used by Dreamweaver. For information about menu commands and menus.xml, see &quot;Menus and Menu Commands&quot; in

<cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">Adaptive Sets</th>

  <td align="left" colspan="2" valign="top">Keyboard shortcuts that are adapted for different locales</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Custom Sets</th>

<td align="left" colspan="2" valign="top">

<p>Customizations of the menu.xml file that provide keyboard shortcuts similar to other products.</p>

</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">MM</th>

<td align="left" colspan="2" valign="top">

<p>Files (called menu commands) that control the behavior of many of the menu items in Dreamweaver.</p>

<p>This folder is reserved for the menu commands that ship with Dreamweaver. To add your own menu commands, save them in another subfolder of the Menus folder.

</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">NDD</th>

  <td align="left" colspan="2" valign="top">Content for the New Document dialog</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">NodeOutputExtensions</th>

  <td align="left" colspan="2" valign="top">Images and messages for the NodeOutput preview</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Objects</th>

<td align="left" colspan="2" valign="top">

<p>Items that appear in the Insert menu and Insert bar.</p>

<p>To appear in the Insert bar and Insert menu, all Object files must be stored in a subfolder of the Objects folder and be listed in the insertbar.xml and menus.xml files. For more information about modifying these files, see &quot;Insert Bar Objects&quot; in

<cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Overlays</th>

  <td align="left" colspan="2" valign="top">CSS grid-related files</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Patches</th>

  <td align="left" colspan="2" valign="top">Patch-related files</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Plugins (Windows)<br />

plug-ins (Macintosh) </th>

<td align="left" colspan="2" valign="top">

<p>Any plug-ins that can be used to play active content (such as Flash movies) in Dreamweaver, as well as a list of plug-ins that Dreamweaver does not support (UnsupportedPlugins.txt).

</p>

<p>Dreamweaver automatically scans the plug-ins folders of any browsers on your hard drive for a suitable plugin when you opt to play plugin content, so storing plug-ins in this folder is not strictly necessary.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99"><p>Queries</p></th>

  <td align="left" colspan="2" valign="top">Queries folder</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Reports</th>

<td align="left" colspan="2" valign="top">

<p>Files associated with the Site Reports feature.</p>

<p>The folders inside Reports contain the Site Reports that ship with Dreamweaver; you can create additional reports and save them in one of the existing folders or create a new subfolder. For more information about Reports, see The Reports API in

<cite>Extending Dreamweaver</cite>. </p>

</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">HTML Reports </th>

<td align="left" colspan="2" valign="top">

<p>Report files for analyzing your HTML (such as finding images with missing alt attributes, removing empty tags, or finding untitled documents).

</p>

</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Workflow </th>

<td align="left" colspan="2" valign="top">

<p>Report files for assisting with site maintenance tasks (such as finding all the files checked out by a specific user or finding recently modified documents).

</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Responsive Starter Assets</th>

  <td colspan="2">CSS and asset files for responsive starter templates</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">SassFrameworks</th>

  <td colspan="2">Files used by CSS preprocessors that use the Sass framework.</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Server Behaviors</th>

<td colspan="2">

<p>The files used by the Server Behaviors inspector. Each server model ( ASP/JavaScript, ASP/VBScript, ColdFusion, and PHP/MySQL) has a corresponding subfolder. The ServerBehaviors.xml file in each subfolder determines what appears in the plus (&#43;) menu of the

 Server Behaviors panel. </p>

<p>Server behaviors create the functionality that Web applications need, such as filtering records based on user criteria, paging through records, linking result lists to details pages, and inserting records into a result set. For more information about editing

 Server Behaviors files, see &quot;Server Behaviors&quot; in <cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">ServerDebugOutput</th>

<td align="left" colspan="2" valign="top">

<p>Supporting files for ColdFusion debugging.</p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Server Formats</th>

<td colspan="2">

<p>The files used to format dynamic data. Each server model (ASP/JavaScript, ASP/VBScript, ColdFusion, and PHP/MySQL) has a corresponding subfolder. The Formats.xml file in each subfolder determines what appears in the Formats menu; it can be (carefully) hand

 edited if you would like to add additional formats. </p>

<p>For more information about editing Server Formats files, see &quot;Data Formatting&quot; in

<cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Server Models</th>

<td colspan="2">

<p>The files that define available server models. Each server model (ASP/JavaScript, ASP/VBScript, ColdFusion, and PHP/MySQL) has an HTML file containing configuration information, and a corresponding subfolder to store specific implementations of certain functions

 for each server model.<br />

For more information about editing Server Model files, see &quot;Server Models&quot; in <cite>

Extending Dreamweaver</cite>. </p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Shared</th>

<td colspan="2">

<p>Files to be shared by multiple extensions. (Any extension can reference the files in these directories.)

</p>

<p>Many third-party extensions&#8212;and many Dreamweaver features&#8212;depend on the functions defined in Shared files, so the files in this folder should never be overwritten, and existing functions in the files should not be modified.

</p>

<p>To add your own shared files, create a separate folder inside the Shared directory and store your files there.

</p>

</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Common</th>

<td colspan="2">Shared scripts and classes for use in extensions throughout the Configuration folder.  </td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Controls</th>

<td colspan="2">Common user interface controls for use mainly in Server Behaviors.  </td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">CssGrids</th>

  <td colspan="2">CSS stylesheet manager</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Dinamico</th>

<td colspan="2">Support for site-specific code hints.  </td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">Emmet</th>

  <td colspan="2">Support for Emmet abbreviations.</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Fireworks</th>

<td colspan="2">Supporting files for Fireworks integration.  </td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Flash</th>

<td colspan="2">Supporting files for the SWFObject-based Flash embedding scheme introduced in Dreamweaver CS4.</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">HandleBars</th>

  <td colspan="2">Handle bars file</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">ICE</th>

<td colspan="2">Helper JavaScript classes for In-Context Editing Commands and Property Inspectors.

<br />

</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">jQuery</th>

  <td colspan="2">jQuery-related functions</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">jQueryWidgets</th>

  <td colspan="2">Support for jQuery widgets.</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">LiveEdit</th>

  <td colspan="2">Files for editing in LiveView</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">MM</th>

<td colspan="2">Shared scripts, images, and classes used by the extensions that ship with Dreamweaver. Third-party extensions may use these files as well, but often more up-to-date functionality can be found in the files in the Common folder.</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">NFW</th>

  <td colspan="2">NFW strings properties</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">OAWidget</th>

<td colspan="2">Support for widget insertion.  </td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">RDSAPI</th>

<td colspan="2">Files for creating connections on the server and turning on remote debugging for ColdFusion.</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Recordset</th>

<td colspan="2">Supporting files for CFC-based recordsets.</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">Spry</th>

<td colspan="2">

<p>All the files necessary to support Spry-related features in Dreamweaver. Generally, the files in the DesignTime folders control the appearance and functionality of widgets, effects, and data sets at authoring time, while the files in the non-DesignTime folders

 control the appearance and functionality of widgets, effects, and data sets in the browser.

</p>

<p>Files needed by the browser to support Spry functionality are copied to the user's site when the user saves a page containing a Spry widget, data set, or effect.

<br />

</p>

</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">UltraDev</th>

<td colspan="2">Shared scripts, images, and classes used by server-related extensions that ship with Dreamweaver. Third-party extensions may use these files as well, but often more up-to-date functionality can be found in the files in the Common folder.</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">XHTMLDTD</th>

<td colspan="2">The XHTML DTDs used by Preview In Browser for XSLT Pages.</td>

</tr>

<tr>

<th align="left" bgcolor="#CCFF99" valign="top">XMLPrefixes</th>

<td colspan="2">A list of common XML namespace prefixes and corresponding URIs. Used by the XML Schema Generator.</td>

</tr>

<tr>

  <th align="left" bgcolor="#CCFF99" valign="top">XSLTransform</th>

  <td colspan="2">Runtime server-side code to do a XSLT Transform process on a given application server technology (PHP, ASP, etc.). Used by the XSLT Server Behavior.</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Snippets</th>

  <td align="left" colspan="2" valign="top">Supporting files and default contents for the Snippets panel.  </td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">SourceControl</th>

<td align="left" colspan="2" valign="top">Supporting files for Source Control functionality.  </td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Startup</th>

<td align="left" colspan="2" valign="top">

<p>Scripts that run when Dreamweaver starts up. </p>

<p>For more information on creating startup scripts, see &quot;The Document Object Model&quot; in

<cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">SVGOptions</th>

  <td align="left" colspan="2" valign="top">SVG options</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">TagHighlight</th>

  <td align="left" colspan="2" valign="top">Lists the tags that are self-closing and those that are not.</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">TagLibIntrospection</th>

<td align="left" colspan="2" valign="top">Supporting files for the tag library tag importers (the tag importers are in the TagLibraries/TagImporters directory).</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99" height="48">TagLibraries</th>

<td align="left" colspan="2" valign="top"><p>Contains the tag database (TagLibraries.vtm) and tag definition files for the markup and scripting languages supported by Dreamweaver.

</p>

  <p>These folders also contain the files for the dialog interface that appears to the user within Dreamweaver for editing tags. For more information, see &quot;Tag Libraries and Dialogs&quot; in <cite>Extending Dreamweaver</cite>. </p></td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99" height="48">Templates</th>

<td colspan="2" align="left" valign="top">Supporting files for the Flash Video feature.

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99" height="48">Themes</th>

  <td align="left" colspan="2" valign="top">Dreamweaver interface themes</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99" height="48">Third Party Source Code

</th>

<td align="left" colspan="2" valign="top">Information about source code not created by Adobe that provides functionality to Dreamweaver. For example, this folder contains information about the JavaScript interpreter that Dreamweaver uses.</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">ThirdPartyTags</th>

<td align="left" colspan="2" valign="top">

<p>Files that define the syntax and tag names of third-party markup (such as ASP, PHP, and custom HTML).</p>

<p>Third-party tag definition files are XML files. Each XML file contains one or more tagspecs, and each tagspec may have an associated GIF file that defines the icon for the markup. For more information about third-party tags and tagspecs, see

<cite>Extending Dreamweaver</cite>.</p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Toolbars</th>

<td align="left" colspan="2" valign="top">

<p>Defines the toolbars available and the icons and commands on each toolbar.</p>

</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">ToolbarsOptions</th>

  <td align="left" colspan="2" valign="top">Dreamweaver toolbar options</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">Translators</th>

<td align="left" colspan="2" valign="top">Translator files. Data translators translate specialized markup such as server-side includes, conditional JavaScript statements, or other server markup such as PHP, CFML, or ASP into code that Dreamweaver can read and

 display.</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Updates</th>

  <td align="left" colspan="2" valign="top">Options for installing in-app updates</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">Validators</th>

  <td align="left" colspan="2" valign="top">Supporting scripts for adding text field entry validation to forms.

  </td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">VisualCSS</th>

  <td align="left" colspan="2" valign="top">CSS properties</td>

</tr>

<tr>

  <th align="left" valign="top" bgcolor="#CCFF99">VisualMediaQuery</th>

  <td align="left" colspan="2" valign="top">Visual media query string properties</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">WebServices</th>

<td align="left" colspan="2" valign="top">

<p>Supporting files for specific Web Service connections.</p>

</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">workspace</th>

<td align="left" colspan="2" valign="top">The default workspace layouts that ship with Dreamweaver (Windows). When you modify these workspaces or create new ones from within Dreamweaver, the XML files describing them are saved in your User Configuration/workspace

 folder.</td>

</tr>

<tr>

<th align="left" valign="top" bgcolor="#CCFF99">WorkspaceMac</th>

<td align="left" colspan="2" valign="top">The default workspace layouts that ship with Dreamweaver (Macintosh).
When you modify these workspaces or create new ones from within Dreamweaver, the XML files describing them are saved in your User Configuration/WorkspaceMac

 folder.</td>

</tr>

</tbody>

</table>

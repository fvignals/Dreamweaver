Dreamweaver
===========

##The Dreamweaver CS6 Configuration Folders

Many Dreamweaver features are extensions developed in JavaScript and HTML. The Configuration folders contain these extensions. If you customize or extend the Dreamweaver product, you modify these files or add your code source files to one or more of these folders. By familiarizing yourself with these folders, you can discover the interface for extensions as well as working examples of each extension type.

***Warning: The files in the Configuration folders make up much of the Dreamweaver product. Do not modify, delete, or add to these files unless you know how to customize and extend Dreamweaver. Before you attempt to customize Dreamweaver, read Extending Dreamweaver and The Dreamweaver API Reference.*** 

Some folder names are obvious. For example, Objects are kept in the Objects folder; Behaviors are kept in the Behaviors folder. One folder that does not correspond to a particular extension type is the Shared folder. The Shared folder is the central repository for utility functions, classes, and images that are commonly used by all extensions.

Each subsequent installation of Dreamweaver produces another version of the Configuration directory per user. Dreamweaver appends each old Configuration folder with a version number (for example "Configuration-1", "Configuration-2", etc.) where the higher the number, the newer the folder. The most recent version of the Configuration folder is always called, simply, "Configuration".

The following Configuration files and folders correspond to how Dreamweaver features are organized:

> - Extensions.txt	
>	A list of file extensions recognized by Dreamweaver.
>	If you add an extension to this file, double-clicking a file with that extension in the Site panel opens it in Dreamweaver.
>	Extensions.txt also determines what file types are shown in the File > Open dialog box. To show files of a particular type in that dialog box by default, add the appropriate extension to the first line of Extensions.txt. For more information, see Extending Dreamweaver.
> - next file

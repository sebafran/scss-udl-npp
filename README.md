# scss-udl-npp
SCSS User Defined Languages - UDL version 2.1 for [Notepad++][1]

Because I love some of the features of Notepad++ i wanted to use it for [SASS / SCSS](http://sass-lang.com). Natively there is no scss in it and I did not find a satisfactory plugin so I had to do it myself. There are two here:
1. `scss.xlm` - For default setting light mode. I tried to make css highlighting resemble this default CSS syntax highlighting provided by [Notepad++][1]
2. `scss-BlackBoardTheme` - as the name suggests for Black Board Theme

## How to use

The infos comes from [npp user manual](https://npp-user-manual.org/docs/user-defined-language-system/#import-a-udl)

Once you have the XML, you can then import it into your Notepad++, so that you can use that UDL yourself. There are two main ways to do this:

1. Copy the XML into the appropriate `userDefineLangs` subfolder. Exit all instances of Notepad++ and reload, then the new UDL will be available.
2. Use the Import… button, navigate to the source XML, and the UDL will be immediately available.

The differences between those two methods are when the UDL will be available to Notepad++, and which config file will hold that UDL, per UDL File Locations.

Individual UDL files are stored in one of two `userDefineLangs` subfolders. Each XML file in that folder is used to define one or more UDL.

1. `%AppData%\Notepad++\userDefineLangs`: this is the default location for most Notepad++ installations
2. `<notepad++_directory>\userDefineLangs`: this is the location for portable versions, or if you turned on “local configuration mode” (or disabled `%AppData%`) during the installation. `<notepad++_directory>` refers to whatever folder the `notepad++.exe` application executable is located.



[1]: http://notepad-plus-plus.org/

NBCustomDirectoryStructurePlugin
================================

This Netbeans plugins allows you to choose a zip file to be extracted into a parent folder of your choosing


To build the plugin for use within netbeans you will need to:
- checkout the source to your local machine
- Open the project in netbeans 8
- Right click the project and select create NBM (This will create an .nbm file in the build folder.)
- Go to Tools -> Plugins -> Click the Downloaded tab -> Add Plugins...
- Browse to the project build folder and select the newly created nbm file

Once the plugin has been installed you will likely have to restart your IDE. After the restart you will need to setup the plugin to point to a zip you have created that will be extracted when creating this new directory. To do this:
- Go to Tools -> Options -> Misc Tab -> Custom Directory Structure subtab -> and select the ZIP on your local computer

Then to use it just right click a folder in a project select New -> Other -> In the PHP categorie there should now be a Custom Directory Option, select that click next -> Enter the new folder name you want to use as the parent folder to extract your zip contents into -> click finish. 

And now you have your new directory structure.
 

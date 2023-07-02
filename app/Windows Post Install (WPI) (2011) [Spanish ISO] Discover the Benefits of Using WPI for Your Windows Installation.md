# How to use Windows Post Install (WPI) to customize your Windows installation
 
Windows Post Install (WPI) is a tool that allows you to automate the installation of software, drivers, updates and settings after installing Windows. It is especially useful for creating customized Windows images or for installing multiple programs on a new computer.
 
In this article, we will show you how to use WPI to create your own Windows installation disc or USB drive with your preferred software and settings. You will need a Windows Post Install (WPI) (2011) [Spanish ISO] file, which you can download from [here](https://netcityme.com/wp-content/uploads/2022/11/Windows_Post_Install_WPI_2011_Spanish_ISO.pdf). You will also need a Windows installation disc or USB drive, and a program to burn or mount ISO files, such as [PowerISO](https://www.poweriso.com/).
 
**Download File »»» [https://www.google.com/url?q=https%3A%2F%2Fblltly.com%2F2uysK2&sa=D&sntz=1&usg=AOvVaw0pNSMUDGq6YwbpvKeSyauH](https://www.google.com/url?q=https%3A%2F%2Fblltly.com%2F2uysK2&sa=D&sntz=1&usg=AOvVaw0pNSMUDGq6YwbpvKeSyauH)**


 
## Step 1: Prepare your WPI configuration
 
First, you need to extract the WPI ISO file to a folder on your computer. You can use PowerISO to do this by right-clicking on the ISO file and selecting "Extract files...". Choose a destination folder and click "OK".
 
Next, open the extracted folder and run the WPI.exe file. This will launch the WPI configuration interface, where you can select the software and settings that you want to install after Windows. You can browse through different categories of software, such as antivirus, browsers, office, multimedia, etc. You can also add your own software by clicking on the "Add" button and browsing for the executable file.
 
For each software that you select, you can configure various options, such as silent installation, reboot required, command line parameters, etc. You can also edit the description and icon of the software by clicking on the "Edit" button. You can also change the order of installation by dragging and dropping the software in the list.
 
When you are done with selecting and configuring the software, you can also customize the appearance and behavior of WPI by clicking on the "Options" button. Here you can change the theme, language, resolution, timer, password, etc. of WPI. You can also enable or disable various features, such as auto-start, auto-install, auto-reboot, etc.
 
Finally, you can save your WPI configuration by clicking on the "Save" button. This will create a Config.js file in the same folder as WPI.exe. You can also backup your configuration by clicking on the "Backup" button and choosing a location to save it.
 
## Step 2: Integrate WPI with your Windows installation disc or USB drive
 
Now that you have prepared your WPI configuration, you need to integrate it with your Windows installation disc or USB drive. This will allow WPI to run automatically after installing Windows.
 
If you are using a Windows installation disc, you need to copy all the files from the disc to a folder on your computer. You can use PowerISO to do this by inserting the disc into your drive and opening it with PowerISO. Then select all the files and folders and drag them to a destination folder on your computer.
 
Descargar Windows Post Install (WPI) (2011) [ISO Español],  Windows Post Install (WPI) (2011) [Spanish ISO] Download,  Cómo usar Windows Post Install (WPI) (2011) [ISO Español],  How to use Windows Post Install (WPI) (2011) [Spanish ISO],  Windows Post Install (WPI) (2011) [ISO Español] Tutorial,  Windows Post Install (WPI) (2011) [Spanish ISO] Tutorial,  Windows Post Install (WPI) (2011) [ISO Español] Opiniones,  Windows Post Install (WPI) (2011) [Spanish ISO] Reviews,  Windows Post Install (WPI) (2011) [ISO Español] Requisitos,  Windows Post Install (WPI) (2011) [Spanish ISO] Requirements,  Windows Post Install (WPI) (2011) [ISO Español] Características,  Windows Post Install (WPI) (2011) [Spanish ISO] Features,  Windows Post Install (WPI) (2011) [ISO Español] Problemas,  Windows Post Install (WPI) (2011) [Spanish ISO] Problems,  Windows Post Install (WPI) (2011) [ISO Español] Soluciones,  Windows Post Install (WPI) (2011) [Spanish ISO] Solutions,  Windows Post Install (WPI) (2011) [ISO Español] Alternativas,  Windows Post Install (WPI) (2011) [Spanish ISO] Alternatives,  Windows Post Install (WPI) (2011) [ISO Español] Comparativa,  Windows Post Install (WPI) (2011) [Spanish ISO] Comparison,  Windows Post Install (WPI) (2011) [ISO Español] Beneficios,  Windows Post Install (WPI) (2011) [Spanish ISO] Benefits,  Windows Post Install (WPI) (2011) [ISO Español] Ventajas,  Windows Post Install (WPI) (2011) [Spanish ISO] Advantages,  Windows Post Install (WPI) (2011) [ISO Español] Desventajas,  Windows Post Install (WPI) (2011) [Spanish ISO] Disadvantages,  Windows Post Install (WPI) (2011) [ISO Español] Preguntas Frecuentes,  Windows Post Install (WPI) (2011) [Spanish ISO] Frequently Asked Questions,  Windows Post Install (WPI) (2011) [ISO Español] Guía de Instalación,  Windows Post Install,  Windows Post Install,  Windows Post Install,  Windows Post Install,  Windows Post Install,  Windows Post Install,  Windows Post Install,  Windows Post Install,  Windows Post Install,  Windows Post Install,  Mejor programa que Windows Post Install
 
If you are using a Windows installation USB drive, you can skip this step as you already have all the files on your USB drive.
 
Next, open the folder where you copied or have your Windows installation files and navigate to the "sources" folder. Here you need to create a new folder called "$OEM$" (without quotes). Inside this folder, create another folder called "$1" (without quotes). Inside this folder, create another folder called "Install" (without quotes).
 
Now copy all the files and folders from your WPI folder (the one where you extracted the WPI ISO file) to the "Install" folder that you just created. Make sure that you copy everything, including WPI.exe and Config.js.
 
Finally, you need to create a file called "SetupComplete.cmd" (without quotes) in the same folder as WPI.exe and Config.js. This file will tell Windows to run WPI after completing the installation. To create this file, open Notepad and type the following commands:

    @echo 8cf37b1e13

    

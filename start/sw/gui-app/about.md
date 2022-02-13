---
label: need-help

title: Desktop GUI Application
subsection: gui-app
section: start-sw
description: 
---

# Desktop GUI Application
# Lazarus GUI First project : A Window is 10 Secondes !

# Lazarus installation on Fedora 35
su -c ' dnf -y install lazarus; dnf -y update; dnf -y upgrade; '

![001_2022-02-13-11-31-46_INSTALLATION_](https://user-images.githubusercontent.com/96615531/153753562-e8b3fee7-5676-4ad1-82cb-9d8f0f0fa91a.png)

NB : I’m on Fedora 35 Workstation ( Gnome 41 ) and I use the Pantheon Desktop as DE then the generated Windows will look different than on Gnome, it doesn’t matter for Lazarus.
( dnf -y groupinstall ‘pantheon desktop’; #this add 151MiB to have a nice desktop )

![002-2022-02-13-11-49-08_PANTHEON_DESKTOP_](https://user-images.githubusercontent.com/96615531/153753556-07223c02-b242-47b8-836d-80bdcd859476.png)

Create Folders to Receive the Project : /home/tux/DEV_/LAZARUS_PROJECTS_/GUI_First_Try_

![003_2022-02-13-11-43-54_FOLDERS_](https://user-images.githubusercontent.com/96615531/153753589-e27c9f1f-16e1-4bff-92bc-625478d9553d.png)

Start Lazarus

![003B_2022-02-13-13-50-34_START_LZ_](https://user-images.githubusercontent.com/96615531/153754017-1e992954-bbb6-49b2-a4a2-b19440ce47ca.png)

New Project Creation : Project / New Project

![004_2022-02-13-12-39-37_NEW_OROJECT_](https://user-images.githubusercontent.com/96615531/153753624-62e5ceed-90c1-4b33-953f-7bd6629cde18.png)

Select Application ( as we want GUI ) + OK

![005_2022-02-13-12-01-08_APPLICATION_](https://user-images.githubusercontent.com/96615531/153753645-518d26f8-d43f-4d76-901f-efb3a579bffd.png)

Lazarus creates automatically your fisrt Graphic User Interface Form1 ! GAME OVER !

Press F9 to run

![006_2022-02-13-12-51-31__FORM1_RUN_](https://user-images.githubusercontent.com/96615531/153753688-d5d1427e-1d63-4d6d-956a-1d4b5e3a8c6d.png)

Ctrl F2 to stop

![007_2022-02-13-12-54-39_FORM1_STOP_](https://user-images.githubusercontent.com/96615531/153753768-cd684e4d-d111-4759-9641-41d1b7c7c255.png)

Project save as : /home/tux/DEV_/LAZARUS_PROJECTS_/GUI_First_Try_

![008_2022-02-13-13-29-19_SAVE_AS_](https://user-images.githubusercontent.com/96615531/153754057-a85cc068-1c12-4548-a3db-d0b466e644c4.png)

![009_2022-02-13-13-27-12_TREE_](https://user-images.githubusercontent.com/96615531/153754075-d1350528-0f35-436b-94d7-869e8a1fd030.png)

Close Lazarus

Run your program from DOUBLE CLIC File or CLI : 

/home/tux/DEV_/LAZARUS_PROJECTS_/GUI_First_Try_/GUI_First_Try_project1

Both Works well !

![010_2022-02-13 13-23-30_FORM1_RUN_CLI_](https://user-images.githubusercontent.com/96615531/153754132-cdc4be0f-7504-49db-9827-9275a12a4b30.png)


NEXT STEP : Customizing The Form and making it doing something...




---
label: need-help

title: Desktop GUI Application
subsection: gui-app
section: start-sw
description: 
---

# Desktop GUI Application
# MonoDevelop GUI First project : A Window in 90 Secondes !


MonoDevelop installation on Fedora 35

su -c ' dnf -y install monodevelop; dnf -y update; dnf -y upgrade; '

![ME001_2022-02-13-18-22-38](https://user-images.githubusercontent.com/96615531/153767298-ac35b529-c73c-4aa4-a91f-3a394502974a.png)

NB : I’m on Fedora 35 Workstation ( Gnome 41 ) and I use the Pantheon Desktop as DE then the generated Windows will look different than on Gnome, it doesn’t matter for Lazarus.
( dnf -y groupinstall ‘pantheon desktop’; #this add 151MiB to have a nice desktop )

![ME002_2022-02-13-18-25-19](https://user-images.githubusercontent.com/96615531/153767341-47da5076-96ce-4269-b07d-5e5315507a0c.png)

Create Folders to Receive the Project : /home/tux/DEV_/MONODEVELOP_PROJECTS_/

Start MonoDevelop

![ME003_2022-02-13-18-31-34](https://user-images.githubusercontent.com/96615531/153767384-ab6b199e-d97b-48c9-946b-3e783b49a3d0.png)

New Project Creation : File / New / Solution ( Ctrl+Shift+N )

![ME004_2022-02-13-18-35-45](https://user-images.githubusercontent.com/96615531/153767443-fcb9f8bc-1922-4a01-943d-09e819705442.png)

Select other / .NET / Gtk# 2.0 Project (C#) as we want GUI + Next

![ME005_2022-02-13-18-32-59](https://user-images.githubusercontent.com/96615531/153767514-b6b89c54-8a0e-48d7-8bec-c06d4e6c1da1.png)

Project Name : GUI_First_Try_Project_
Solution Name : GUI_First_Try_Solution_
Location : /home/tux/DEV_/MONODEVELOP_PROJECTS_
+ Create

![ME006_2022-02-13-18-45-25](https://user-images.githubusercontent.com/96615531/153767650-435041e5-ab6b-4fe7-84a4-2a202df3d4fb.png)

MonoDevelop Creates automatically a pseudo WinForm with all standard tools

![ME007_2022-02-13-18-50-07](https://user-images.githubusercontent.com/96615531/153767800-afae9e78-7786-4583-b56f-497bf1b865f6.png)

![ME008_2022-02-13-18-51-11](https://user-images.githubusercontent.com/96615531/153767848-0a856aef-04f0-417c-937b-f3d32ecca6f0.png)

For test purpose : 
Drag and Drop on the center of the Form : ToolBox / Conteneurs / Fixed

![ME009_2022-02-13-18-57-34](https://user-images.githubusercontent.com/96615531/153768103-ecdaf9af-13e2-43e0-a21f-e4b1c72fd242.png)

Drag and Drop on the center of the Form : ToolBox / Widgets / Calendar

![ME010_2022-02-13-19-00-01](https://user-images.githubusercontent.com/96615531/153768209-97e34222-9fa2-48d3-b038-9523d9708fdd.png)

We can modify Calendar's properties

![ME011_2022-02-13-19-04-32](https://user-images.githubusercontent.com/96615531/153768356-e15e7f23-7ce9-46a0-9d81-8334cc815c28.png)

To Run the Window

Build / Build All ( F8 )

![ME012_2022-02-13-19-05-59](https://user-images.githubusercontent.com/96615531/153768422-ea43f102-369d-4235-8f5c-1b5e3c9fa60b.png)

Run / Start Debugging ( F5 )

![ME13_2022-02-13-19-09-19](https://user-images.githubusercontent.com/96615531/153768567-f775a7e8-9d49-4c8f-8baa-ff2cb5e96747.png)

![ME014_2022-02-13-19-12-00](https://user-images.githubusercontent.com/96615531/153768650-97d21fa1-3534-462c-ba71-9c5c30517e6e.png)

Run / Stop ( Shift + F5 )

![ME015_2022-02-13-19-14-00](https://user-images.githubusercontent.com/96615531/153768757-edfdc10f-6362-428c-a7d3-fb503fe1d8dd.png)

File / Close Solution

![ME016_2022-02-13-19-16-04](https://user-images.githubusercontent.com/96615531/153768827-88417385-fafc-41ce-8199-09f2b0f9647b.png)

NEXT STEP : Customizing The Form and making it doing something... 





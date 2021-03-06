## This is still work in progress

# Irnas hardware workflow

This repo represents Institute Irnas hardware design workflow and design guide.

If you want to contribute to open source projects at [Institute Irnas][irnas_web] this is the starting point
to get familiar with design flow and project structure.

Several things are important when creating new hardware project.
- Specification
- Schematics
- PCB
- Overall documentation
- Keeping track of project versions

Keeping this in mind Institute Irnas created this workflow guide, which relies on GitHub, for internal use, but also for people who would like to contribute to many projects Institut Irnas is working on.

One of the main things in Open source community is documentation, which is in many cases missing from the project. Here you will find the extensive guide on how to use all features of GitHub platform to keep project clean and organized. Combining all these guides together we created the "Irnas_GitHub_hardware_workflow" which we at Irnas use to create new projects.

There are several documents in this repository, and the first one to read is ["Irnas_GitHub_hardware_workflow"][hardware_workflow]. This document explains how the project evolves from an idea in someone's head to the working PCB on their desk. Next is ["Irnas_GitHub_hardware_guide"][hardware_guide]. It describes the folder structure of the repository, how to use git tool for tracking hardware versions, and how to use GitHub features for issue tracking in hardware. Last two are ["Irnas_hardware_sch_guide"][sch_guide] and ["Irnas_hardware_pcb_guide"][pcb_guide]. Thay will show the best practice how to create schematic and PCB files along with some design tips. Folder "Project" is a template for project structure.

In Project folder, you will find the schematics template we at Irnas use to provide detailed information about circuit schematics. Also some PCB tips, for getting your PCB prepared for manufacturing and assembly. BOM templates and many other useful documents.

The templates will be provided for the Altium and KiCad EDA software tools, but this guide can be used with any other popular EDA tool like Eagle, OrCAD, etc.

* [Irnas_GitHub_hardware_workflow.md][hardware_workflow]
* [Irnas_GitHub_hardware_guide.md][hardware_guide]
* [Irnas_hardware_sch_guide.md][sch_guide]
* [Irnas_hardware_pcb_guide.md][pcb_guide]
* Project


---

#### License

All our projects are as usefully open-source as possible.

Hardware including documentation is licensed under [CERN OHL v.1.2. license](http://www.ohwr.org/licenses/cern-ohl/v1.2)

Firmware and software originating from the project are licensed under [GNU GENERAL PUBLIC LICENSE v3](http://www.gnu.org/licenses/gpl-3.0.en.html).

Open data generated by our projects is licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

All our websites and additional documentation are licensed under [Creative Commons Attribution-ShareAlike 4 .0 Unported License] (https://creativecommons.org/licenses/by-sa/4.0/legalcode).

What this means is that you can use hardware, firmware, software and documentation without paying a royalty and knowing that you'll be able to use your version forever. You are also free to make changes but if you share these changes then you have to do so on the same conditions that you enjoy.

Koruza, GoodEnoughCNC, and IRNAS are all names and marks of Institut IRNAS Race. 
You may use these names and terms only to attribute the appropriate entity as required by the Open Licences referred to above. You may not use them in any other way and in particular, you may not use them to imply endorsement or authorization of any hardware that you design, make or sell.

  [irnas_web]:  <https://www.irnas.eu>
  [hardware_guide]: <Irnas_GitHub_hardware_guide.md>
  [hardware_workflow]: <Irnas_GitHub_hardware_workflow.md>
  [sch_guide]: <Irnas_hardware_sch_guide.md>
  [pcb_guide]: <Irnas_hardware_pcb_guide.md>
  [project]: <>

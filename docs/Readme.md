<a href="https://www.vipm.io/package/pantherlab_lib_dependency_inspector/"> <img src="https://www.vipm.io/package/pantherlab_lib_dependency_inspector/badge.svg?metric=installs"></a> <a href="https://www.vipm.io/package/pantherlab_lib_dependency_inspector/"><img src="https://www.vipm.io/package/pantherlab_lib_dependency_inspector/badge.svg?metric=stars"></a>

This tool employs a private linker method to analyze the relationships between LabVIEW files. This method requires a LabVIEW file (VI, LVlib, LVclass, or CTL) as input and generates an array containing all the links associated with that file. A key advantage of this method is that it does not necessitate opening the LabVIEW file itself.

## Getting Started

Open LabVIEW and go to Tools-->PantherLAB-->Simple Dependency Inspector

<iframe width="1024" height="768" src="https://github.com/user-attachments/assets/11ca6f74-3081-4b22-a3ec-fe2b505240c1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Instructions

![2024-10-14_14-34-18](https://github.com/user-attachments/assets/3bbc5774-548d-4d1a-b2ef-28f4c57c0bc5)


1. Choose the folder containing your LabVIEW code.
2. Select the specific files or folders you want to analyze for dependencies. Use the Shift key to select multiple items.
3. If you selected folders, specify the LabVIEW file types to include in the analysis.
4.Specify the Working Path, where the .dot file and dependency image will be saved.
5. Select the Image type for the dependencies. SVG is the preferred option, but LabVIEW cannot handle these images directly. If you choose SVG, the image will open in your default browser.
6.Select the File Types you want to include in your plot.
7. Decide whether to include all LabVIEW dependencies in the plot. Note that this may result in a large and complex diagram that can be difficult to interpret.
8.Click the "Find Dependencies from Selection" button to begin the analysis.

<iframe width="1024" height="768" src="https://github.com/user-attachments/assets/6bd5cf6e-1886-4d72-bc05-e60b0d485e06" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Install Graphviz

[Graphviz web site](https://www.graphviz.org)

![install](https://github.com/user-attachments/assets/3635e128-68ae-4264-a108-cf0440d1fe48)

This tool utilizes Graphviz to generate the plots, Dependency Inspector does a check internally to see if this tool is installed in your OS, if not this 'Install Graphviz' button will be shown, click it and accept the install dialog (windows), if you want to do it manually go to graphviz web site and check for instructions.

For windows Dependency Instpector will execute this command line, you'll need to accept and that is all.
```console
winget install graphviz
```

For Linux you'll need sudo level and execute this in a new terminal
```console
sudo apt install graphviz
```


## Symbols

Dependency Inspector creates 2d pictures with different symbols depending on the file type:

![simbols](https://github.com/user-attachments/assets/1836cc24-1e98-4899-9d53-ce3a34e07786)

1. Library files (*.lvlib)
2. Virtual Instrument (*.vi)
3. Typedefs (*.ctl)
4. Class (*.lvclass)

## Report Issues and Request Features:
Encountered an issue or have a feature suggestion? Let us know on GitHub: 
https://github.com/PantherLAB/DependencyInspector/issues

**Struggling with LabVIEW and/or DQMH projects?** We can help! Our team (CLA, LabVIEW Champion, DQMH Trusted Advisor) ofers LabVIEW development, LabVIEW training, and contracting services.

**Ready to take the next step?** Contact us today at [enrique.noe@pantherlab.com.mx] or [info@pantherlab.com.mx] to discuss your specific needs.

## Links
- [PantherLAB website](https://pantherlab.com.mx/)
- [DQMH Website](https://dqmh.org/)
- [LabVIEW Wiki](https://labviewwiki.org/wiki/Home)
- [GCentral](https://www.gcentral.org/)

### Social Networks:
- [Linkedin](https://www.linkedin.com/company/pantherlabmx/)
- [Twitter](https://x.com/PantherLAB_)
- [Facebook](https://www.facebook.com/profile.php?id=61556228677680)
 

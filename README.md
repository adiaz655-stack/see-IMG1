# Installation/updating/removal problems occur the most frequently across applications such as: Python 3.11, KWin, and Davinci Resolve, and more in the category sample, while App image demonstrates the greatest variety of problem states such as: Loading/startup, performance, and crashing, and more in the entity sample

  

Situation: Two samples were drawn from a Manjaro discussion forum. The category sample was drawn on September 21, 2026, at 8:08pm, and the entity sample was drawn on September 22, 2026 at 2:01am. The top ten subject lines for both the category and entity sample were taken for further analysis.

  

Complication: But does drawing the top ten subject lines from a Manjaro discussion forum for both the category and entity sample show what problem state(s) occur the most frequently across applications in the category sample? And, does it indicate what application demonstrates the greatest variety of problem states in the entity sample?

  

Resolution: Installation/updating/removal problems occur the most frequently across applications in the category sample such as Python 3.11 and KWin, while App image demonstrates the greatest variety of problem states in the entity sample such as installation/updating/removal, and loading/startup problems.

  

Section 1 analyzes entities taken from the category sample

Section 2 analyzes entities taken from the entity sample

  

and

  

Section 3 visualizes the relationships between entities and their problem states in from the

entity sample

  

*Reply counts register discussion activity and may serve as provisional indicators of user interest or support demand. They do not independently establish the frequency, severity, or technical significance of reported problems. The priorities identified in this analysis are therefore candidates for further investigation, not recommendations for resource allocation. Engineering expertise and operational evidence are required to assess their significance and determine appropriate responses.*

-----

## Section 1: Installation/updating/removal problems occur the most frequently across applications such as: Python 3.11, KWin, Davinci Resolve and more in the category sample

  

Situation: A sample of subject line queries related to application problems were collected, and dissected, so they could be better analyzed. - -See TAB1- - for the complete catalogue.

  

Complication: But does knowing that users are experiencing different problems across different applications answer which problem state(s) occur the most frequently across applications? and whether or not these problem states are application specific?

  

Resolution: Installation/updating/removal problem states are the most frequent across applications in the sample. Although the problem state is not application specific, because 6 applications that serve different functions are associated with installation/updating/removal problems. While all other problem states identified are only associated with 2 or 3 applications.

 
|                                     topic                                    | replies | views |  tags  |  Named Entity 1 | Named Entity 2 |              Problem              |
|:----------------------------------------------------------------------------:|:-------:|:-----:|:------:|:---------------:|:--------------:|:---------------------------------:|
| Appimage load error (Shotcut)                                                | 38      | 638   |        | App image       |                | Loading / startup                 |
| Is it possible to install and run Python 3.11 script in virtual environment? | 17      | 3137  | plasma | Python 3.11     |                | Installation / updating / removal |
| Firefox addon:Open in VLC media player?                                      | 16      | 621   |        | Firefox         | VLC            | Incorrect output/behaviour        |
| Freecad appimage fails to start after update                                 | 13      | 227   |        | Freecad         | App image      | Loading / startup                 |
| Cannot build OpenShot                                                        | 12      | 484   |        | Openshot        |                | Loading / startup                 |
| How do I install "debug package" of kwin?                                    | 12      | 224   | plasma | KWin            |                | Installation / updating / removal |
| Zombied programs refuse to close with SIGKILL/SIGCHLD                        | 11      | 194   |        | SIGKILL         | SIGCHILD       | Freezing/ unresponsiveness        |
| How do I install Davinci Resolve on Manjaro Linux?                           | 11      | 1037  |        | Davinci resolve | Manjaro        | Installation / updating / removal |
| Burn bootable Windows 10 ISO image to USB stick with dd?                     | 11      | 2681  |        | Windows 10      |                | Installation / updating / removal |
| Installing and using XLibre on Manjaro                                       | 9       | 408   |        | XLibre          | Manjaro        | Installation / updating / removal |
>**TAB 1: Third-Party Software category sample results ranked by number of replies, with named entities and problem states derived from subject lines.**

 .
└── Third-Party Software Category Search Results/
├── Loading/startup/
│ ├── App image
│ ├── Freecad
│ └── Openshot
├── Installation/updating/removal/
│ ├── Python 3.11
│ ├── KWin
│ ├── Davinci Resolve
│ ├── Manjaro
│ ├── Windows 10
│ └── XLibre
├── Incorrect output/behaviour/
│ ├── Firefox
│ └── VLC
└── Freezing/unresponsiveness/
├── SIGKILL
└── SIGCHILD

  

>**DIA1: Relationships between named entities and problem states, derived from the third-party software category sample, organized according to the smaller of the two sets.**

 ----

## Section 2: App image is associated with the most amount of problem states such as: loading/startup, installation/updating/removal, performance and more in the entity sample

  

Situation: A sample of subject line queries all related to App image were collected, and dissected so that they can be better analyzed. - -See TAB2- - for the full catalog.

  
Complication: But does knowing the problem states that arise in relation to App image answer if there are a variety (if any) of problem states associated with App image in comparison to other applications in the entity sample?

Resolution: App image is associated with four different problem states. Including loading/startup, installation/updating/removal, crashing, and performance. Which is a lot more compared to other applications included in the sample, only being associated with one problem state.

|                                   topic                                  | replies | views |          tags         | Named Entity 1 |      Named Entity 2     | Named Entity 3 |              Problem              |
|:------------------------------------------------------------------------:|:-------:|:-----:|:---------------------:|:--------------:|:-----------------------:|:--------------:|:---------------------------------:|
| Appimage - error while loading shared libraries: libwebkit2gtk-4.0.so.37 | 16      | 9093  | appimage              | App image      | libwebkit2gtk-4.0.so.37 |                | Loading / startup                 |
| Many AppImages have stopped working after today's update :/              | 15      | 5591  | appimage              | App image      |                         |                | Performance                       |
| AppImages kann ich nicht mehr öffnen                                     | 14      | 334   | appimage              | App image      |                         |                | Loading / startup                 |
| New DeLinuxCo Cinnamon ISO with pre-installed AppImages                  | 9       | 666   | appimage              | DeLinuxCo      | Cinnamon ISO            | App image      | Installation / updating / removal |
| How do I start appimages from the terminal (shortcut in /usr/bin)?       | 9       | 4124  | xfce; appimage        | App image      | /usr/bin                |                | Loading / startup                 |
| Appimage rawtherapee lässt sich nicht mehr starten                       | 8       | 1572  | appimage              | rawtherapee    | App image               |                | Loading / startup                 |
| AppImage not working - App opens for around 2-3 seconds the closes       | 4       | 4276  | appimage              | App image      |                         |                | Crashing                          |
| Openshot 3.0 fails to start                                              | 1       | 911   | appimage              | Openshot 3.0   |                         |                | Loading / startup                 |
| VSCodium AppImage won't launch; symbol lookup error; libgio              | 1       | 2610  | qt; appimage          | VSCodium       | App image               | libgio         | Loading / startup                 |
| UnityHub can't install a unity version                                   | 1       | 2724  | xfce; appimage; unity | UnityHub       |                         |                | Installation / updating / removal |

>**TAB 2 Third-Party Software category sample results ranked by number of replies, with named entities and problem states derived from subject lines.**
  
 ----
## Section 3: App image is visually represented to have the most amount of problem states in the entity sample

  

Situation: A sample of subject line queries all related to App image were collected, and organized into a logic tree to represent the findings of - -TAB 2 - -. - -See TAB 2 and DIA 2- - for the full catalog

  

Complication: But does TAB 2 visually demonstrate all four problem states associated with App image compared to other applications?

  

Resolution: App image falls under all four problem states. Including loading/startup, installation/updating/removal, performance, and crashing. - -DIA 2- - visually showcases that App image falls under all four problem states. While all other applications only fall under one problem state.
 
.
└── Third-Party Software Entity Search Results/
├── Loading/startup/
│ ├── App image
│ ├── libwebkit2gtk-4.0.s0.37
│ ├── /usr/bin
│ ├── Rawtherapee
│ ├── Openshot 3.0
│ ├── VS Codium
│ └── Libgio
├── Installation/ updating/ removal/
│ ├── DeLinuxCo
│ ├── Cinnamon ISO
│ ├── App image
│ └── UnityHub
├── Performance: App image
└── Crashing: App image

  

>**DIA 2 Relationships between named entities and problem states, derived from the third-party software category sample, organized according to the smaller of the two sets.**

  

The "Third- Party Software Category Search Results" node organizes the entities according to their associated problem states, that identifies which applications experience performance and crashing problems, while recognizing that App image falls under all 4 problem states.. In the 3rd child node, performance problems are only associated with App image. Representing that the application failed during performance. In the 4th child node, crashing problems are only associated with App image. Representing that the application crashed. CODA These associations verify the findings of TAB1. In that App image is associated with the most amount of problem states. Showcasing that App image falls under all 4 problem states. While all other applications are only associated with one problem state.





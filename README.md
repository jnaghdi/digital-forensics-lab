# Digital Forensics Lab & Shared Cyber Forensic Intelligence Repository

| Hands-on labs                                                                            | Forensic Intelligence Repository                                                              |
| ---------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------- |
| <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/BJA_Logo.png" width="130"> | <img src="https://www.nist.gov/sites/default/files/images/2017/06/16/dsh-st.jpg" width="130"> |

### Features of Repository

===================

- Hands-on Digital Forensics Labs: designed for Students and Faculty
- Linux-based lab: All labs are purely based on [Kali Linux](https://www.kali.org/downloads/)
- Lab screenshots: Each lab has PPTs with instruction screenshots
- Comprehensive: Cover many topics in digital forensics
- Free: All tools are open source
- Updated: The project is funded by DOJ and will keep updating
- Two formalized forensic intelligence in JSON files based-on case studies

---

## Table of Contents (updating)

- Basic Computer Skills for Digital Forensics
  - [Number Systems](/Basic_Computer_Skills_for_Forensics/0_Number_Systems.pptx)
  - [PC Introduction](/Basic_Computer_Skills_for_Forensics/1_PC_Introduction.pptx)
  - [Windows Command Line Tutorial](/Basic_Computer_Skills_for_Forensics/2_Win_command_line_tutorial.pptx)
  - [Linux Command Line Tutorial](/Basic_Computer_Skills_for_Forensics/3_Linux_command_line_tutorial.pptx)
  - [Advanced Linux Command Line Tutorial](/Basic_Computer_Skills_for_Forensics/4_Advanced_linux_command_line.pptx)
- Computer and Digital Forensics (updated on Oct. 2021)
  - [Introduction to Digital Forensics](/Basic_Computer_Skills_for_Forensics/5_Introduction_to_digital_forensics.pptx)
  - [Sleuth Kit Tutorial](/Basic_Computer_Skills_for_Forensics/6_Sleuth_Kit_Tutorial.pptx)
  - [USB Image Acquisition](/Basic_Computer_Skills_for_Forensics/7_USB_Image_Acquisition.pptx)
  - [Evidence Search Techniques](/Basic_Computer_Skills_for_Forensics/8_Evidence_search_techniques.pptx)
  - [Data Carving](/Basic_Computer_Skills_for_Forensics/9_Data_Carving.pptx)
  - [Steganography](/Basic_Computer_Skills_for_Forensics/10_Steganography.pptx)
  - [Forensic Report Template](/Basic_Computer_Skills_for_Forensics/Forensic_Report_Template.pdf)
- Computer Forensics Case Study
  - [Investigating P2P Data Leakage](#Investigating-P2P-Data-Leakage) (added on June 2021)
  - [Investigating NIST Data Leakage](#Investigating-NIST-Data-Leakage)
  - [Investigating Illegal Possession of Images](#Investigating-Illegal-Possession-of-Images "Networking forensics")
  - [Investigating Email Harassment](#Investigating-Email-Harassment)
  - [Investigating Illegal File Transferring (Memory Forensics)](#Investigating-illegal-File-Transferring "Memory Forensics")
  - [Investigating Hacking Case](#Investigating-Hacking-Case)
- Mobile Forensics Case Study
  - [Investigating Android 10](#Investigating-Android-10) (added on Oct/24/2021)
  - iOS 13 (to be released...)
- Forensic Intelligence Repository
  - [Email forensics](/STIX_for_digital_forensics/Email_Harassment)
  - [Illegal Possession of Images](/STIX_for_digital_forensics/Illegal_Possession_Images)
- Tool Installation
  - [Tools Used](#Tools-Used)
  - [Installation PPTs](https://raw.githubusercontent.com/frankwxu/digital-forensics-lab/main/Help/Kali_Installation_2020.pptx)
  - Installation Scripts (see commands as follows)

```
# The following commands will install all tools needed for Data Leakage Case. We will upgrade the script to add more tools for other labs soon.

wget  https://raw.githubusercontent.com/frankwxu/digital-forensics-lab/main/Help/tool-install-zsh.sh
chmod +x tool-install-zsh.sh
./tool-install-zsh.sh
```

---

### Investigating P2P Data Leakage

==============

The [P2P data leakage case study](https://github.com/frankwxu/digital-forensics-lab/tree/main/NIST_Data_Leakage_Case) is to help students to apply various forensic techniques to investigate intellectual property theft involving P2P. The study include

- A large and complex case involving a uTorrent client. The case is similar to NIST data leakage lab. However, it provides a clearer and more detailed timeline.
- Solid evidence with explanations. Each evidence that is associated with each activity is explained along with the timeline. We suggest using this before study NIST data leakage case study.
- 10 hands-on labs/topics in digital forensics

**Topics Covered**

| Labs   | Topics Covered                      | Size of PPTs |
| ------ | ----------------------------------- | ------------ |
| Lab 0  | Lab Environment Setting Up          | 4M           |
| Lab 1  | Disk Image and Partitions           | 5M           |
| Lab 2  | Windows Registry and File Directory | 15M          |
| Lab 3  | MFT Timeline                        | 6M           |
| Lab 4  | USN Journal Timeline                | 3M           |
| Lab 5  | uTorrent Log File                   | 9M           |
| Lab 6  | File Signature                      | 8M           |
| Lab 7  | Emails                              | 9M           |
| Lab 8  | Web History                         | 11M          |
| Lab 9  | Website Analysis                    | 2M           |
| Lab 10 | Timeline (Summary)                  | 13K          |

---

### Investigating NIST Data Leakage

==============

The [case study](https://github.com/frankwxu/digital-forensics-lab/tree/main/NIST_Data_Leakage_Case) is to investigate an image involving intellectual property theft. The study include

- A large and complex case study created by NIST. You can access the [Senario, DD/Encase images](https://www.cfreds.nist.gov/data_leakage_case/data-leakage-case.html). You can also find the [solutions](https://www.cfreds.nist.gov/data_leakage_case/leakage-answers.pdf) on their website.
- 13 hands-on labs/topics in digital forensics

**Topics Covered**

| Labs   | Topics Covered                      | Size of PPTs |
| ------ | ----------------------------------- | ------------ |
| Lab 0  | Environment Setting Up              | 2M           |
| Lab 1  | Windows Registry                    | 3M           |
| Lab 2  | Windows Event and XML               | 3M           |
| Lab 3  | Web History and SQL                 | 3M           |
| Lab 4  | Email Investigation                 | 3M           |
| Lab 5  | File Change History and USN Journal | 2M           |
| Lab 6  | Network Evidence and shellbag       | 2M           |
| Lab 7  | Network Drive and Windows shellbag  | 5M           |
| Lab 8  | Master File Table ($MFT) Analysis   | 4M           |
| Lab 9  | Windows Search History              | 4M           |
| Lab 10 | Windows Volume Shadow Copy Analysis | 6M           |
| Lab 11 | Data Carving                        | 3M           |
| Lab 12 | Crack Windows Passwords             | 2M           |

---

### Investigating Illegal Possession of Images

=====================

The [case study](https://github.com/frankwxu/digital-forensics-lab/tree/main/Illegal_Possession_Images) is to investigate the illegal possession of Rhino images. This image was contributed by Dr. Golden G. Richard III, and was originally used in the DFRWS 2005 RODEO CHALLENGE. NIST hosts the [USB DD image](https://www.cfreds.nist.gov/dfrws/Rhino_Hunt.html). A copy of the image is also available in the repository.

**Topics Covered**

| Labs  | Topics Covered                                                       | Size of PPTs |
| ----- | -------------------------------------------------------------------- | ------------ |
| Lab 0 | HTTP Analysis using Wireshark (text)                                 | 3M           |
| Lab 1 | HTTP Analysis using Wireshark (image)                                | 6M           |
| Lab 2 | Rhion Possession Investigation 1: File recovering                    | 9M           |
| Lab 3 | Rhion Possession Investigation 2: Steganography                      | 4M           |
| Lab 4 | Rhion Possession Investigation 3: Extract Evidence from FTP Traffic  | 3M           |
| Lab 5 | Rhion Possession Investigation 4: Extract Evidence from HTTP Traffic | 5M           |

### Investigating Email Harassment

=========

The [case study](https://github.com/frankwxu/digital-forensics-lab/tree/main/Email_Harassment) is to investigate the harassment email sent by a student to a faculty member. The case is hosted by digitalcorpora.org. You can access the [senario description](https://digitalcorpora.org/corpora/scenarios/nitroba-university-harassment-scenario) and [network traffic](http://downloads.digitalcorpora.org/corpora/scenarios/2008-nitroba/nitroba.pcap) from their website. The repository only provides lab instructions.

**Topics Covered**

| Labs  | Topics Covered                                 | Size of PPTs |
| ----- | ---------------------------------------------- | ------------ |
| Lab 0 | Investigating Harassment Email using Wireshark | 3M           |
| Lab 1 | t-shark Forensic Introduction                  | 2M           |
| Lab 2 | Investigating Harassment Email using t-shark   | 2M           |

### Investigating Illegal File Transferring

=========

The [case study](https://github.com/frankwxu/digital-forensics-lab/tree/main/Illegal_File_Transferring_Memory_Forensics) is to investigate computer memory for reconstructing a timeline of illegal data transferring. The case includes a scenario of transfer sensitive files from a server to a USB.

**Topics Covered**

| Labs   | Topics Covered                        | Size of PPTs |
| ------ | ------------------------------------- | ------------ |
| Lab 0  | Memory Forensics                      | 11M          |
| part 1 | Understand the Suspect and Accounts   |              |
| part 2 | Understand the Suspect’s PC           |              |
| part 3 | Network Forensics                     |              |
| part 4 | Investigate Command History           |              |
| part 5 | Investigate Suspect’s USB             |              |
| part 6 | Investigate Internet Explorer History |              |
| part 7 | Investigate File Explorer History     |              |
| part 8 | Timeline Analysis                     |              |

### Investigating Hacking Case

=========

The [case study](https://github.com/frankwxu/digital-forensics-lab/tree/main/NIST_Hacking_Case), including a disk image provided by [NIST](https://www.cfreds.nist.gov/Hacking_Case.html) is to investigate a hacker who intercepts internet traffic within range of Wireless Access Points. Note that the PPT is encrypted with a password as one of the major assignments. Email fxu at ubalt dot edu to ask the password if you are a faculty member.

**Topics Covered**

| Labs  | Topics Covered   | Size of PPTs |
| ----- | ---------------- | ------------ |
| Lab 0 | Memory Forensics | 8M           |

### Investigating Android 10

=========

| Labs      | Topics Covered                          | Size of PPTs |
| --------- | --------------------------------------- | ------------ |
| Lab 0     | Intro Pixel 3                           | 3M           |
| Lab 1     | Pixel 3 Image                           | 2M           |
| Lab 2     | Pixel 3 Device                          | 4M           |
| Lab 3     | Pixel 3 System Setting                  | 5M           |
| Lab 4     | Overview: App Life Cycle                | 11M          |
| Lab 5.1.1 | AOSP App Investigations: Messaging      | 4M           |
| Lab 5.1.2 | AOSP App Investigations: Contacts       | 3M           |
| Lab 5.1.3 | AOSP App Investigations: Calendar       | 1M           |
| Lab 5.2.1 | GMS App Investigations: Messaging       | 6M           |
| Lab 5.2.2 | GMS App Investigations: Dialer          | 2M           |
| Lab 5.2.3 | GMS App Investigations: Maps            | 8M           |
| Lab 5.2.4 | GMS App Investigations: Photos          | 6M           |
| Lab 5.3.1 | Third-Party App Investigations: Kik     | 4M           |
| Lab 5.3.2 | Third-Party App Investigations: textnow | 1M           |
| Lab 5.3.3 | Third-Party App Investigations: whatapp | 3M           |
| Lab 6     | Pixel 3 Rooting                         | 5M           |

### Tools Used

========

| Name                    | version    | vendor                                                          |
| ----------------------- | ---------- | --------------------------------------------------------------- |
| Wine                    | 6.0        | https://source.winehq.org/git/wine.git/                         |
| Vinetto                 | 0.98       | https://github.com/AtesComp/Vinetto                             |
| imgclip                 | 05.12.2017 | https://github.com/Arthelon/imgclip                             |
| Tree                    | 06.01.2020 | https://github.com/kddeisz/tree                                 |
| RegRipper               | 3.0        | https://github.com/keydet89/RegRipper3.0                        |
| Windows-Prefetch-Parser | 05.01.2016 | https://github.com/PoorBillionaire/Windows-Prefetch-Parser.git  |
| python-evtx             | 05.21.2020 | https://github.com/williballenthin/python-evtx                  |
| xmlstarlet              | 1.6.1      | https://github.com/fishjam/xmlstarlet                           |
| hivex                   | 09.15.2020 | https://github.com/libguestfs/hivex                             |
| libesedb                | 01.01.2021 | https://github.com/libyal/libesedb                              |
| pasco-project           | 02.09.2017 | https://annsli.github.io/pasco-project/                         |
| libpff                  | 01.17.2021 | https://github.com/libyal/libpff                                |
| USN-Record-Carver       | 05.21.2017 | https://github.com/PoorBillionaire/USN-Record-Carver            |
| USN-Journal-Parser      | 1212.2018  | https://github.com/PoorBillionaire/USN-Journal-Parser           |
| JLECmd                  | 1.4.0.0    | https://f001.backblazeb2.com/file/EricZimmermanTools/JLECmd.zip |
| libnl-utils             | 3.2.27     | https://packages.ubuntu.com/xenial/libs/libnl-utils             |
| time_decode             | 12.13.2020 | https://github.com/digitalsleuth/time_decode                    |
| analyzeMFT              | 2.0.4      | https://github.com/dkovar/analyzeMFT                            |
| libvshadow              | 12.20.2020 | https://github.com/libyal/libvshadow                            |
| recentfilecache-parser  | 02.13.2018 | https://github.com/prolsen/recentfilecache-parser               |

## Contribution

=============

- Frank Xu
- Malcolm Hayward
- Richard (Max) Wheeless

<script async src="//static.getclicky.com/101329461.js"></script>

<img width="1" height="1" src="//in.getclicky.com/101329461ns.gif" />

<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/ksb44j1gmfoc4ht18prk" alt="trackgit-views" />
</a>

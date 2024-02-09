IBM Class called Learning COBOL Programming with VSCode

# Learning COBOL Programming with VSCode

## Welcome to your introduction to COBOL!
This introductory COBOL course helps a novice learn the Structure of COBOL programs, Data types & Variable Handling, Intrinsic Functions, Branching logic and more. The goal of the course is to enable the participant to be able to write basic COBOL programs. This is a fantastic compliment to the IBM z/OS Practitioner path for the IBM Mainframe.
On successful completion of this course, learners are eligible to earn their 'Learning COBOL Programming with VSCode'  badge.

Catch the  COBOL Fridays webinar series replays - these webinars were curated for first-time programmers, life-long learners, and anyone interested in learning COBOL.

Get ready to dive into some actual COBOL!
Course duration- Approx 16 hours

Lab 1. Setting up VSCode and Extensions

# ![Shape1](RackMultipart20240209-1-hrjkq8_html_3d0f2ea06bbb1535.gif)

# Lab 1. Setting up VSCode and Extensions

##

## Overview

This lab covers all aspects of the download and installation of Visual Studio (VS) Code and the necessary prerequisites. This lab will cover the necessary steps and information to download and install the prerequisites needed for the subsequent labs within this course. This software is needed for one or more of the applications we will be utilizing in our labs throughout the course.

## Objectives

- Install node.js
- Install Java SDK
- Install and run Visual Studio Code
- Install Zowe Explorer plugin
- Install IBM Z Open Editor plugin
- Complete registration

**Lab instructions**

### Install node.js:

1. Check for node.js installation and verify that the version number is v8 or higher.

Open your workstation's version of the command prompt (called Terminal on Mac OS X). Once the command prompt is open, use the command in Example 1 to check if your workstation currently has a version of node.js installed.

1. _Node.js version_

C:\Users\User\> node -v

V12.16.1

If you do not see a version number after you submit the command, you do not have node.js installed, or if it shows a version less than v8, you should continue following these instructions. If you do see a version number and it is v8 or higher, you can move on to section Install Java SDK.

1. If node.js version is less than v8, or node isn't installed at all.

Updating node.js to the appropriate version number is a relatively simple process because the installer takes care of most of the "heavy lifting". All you will need to do is visit the Node.js download site, provided below, and follow the download and installation instructions for your specific workstation platform. Do this same process if you do not already have node.js installed.

[https://nodejs.org/en/download/](https://nodejs.org/en/download/)

This process will install the latest versions of Node.js and the node package manager (npm) and overwrite any older version files in your system. This removes the step of needing to manually uninstall the previous versions beforehand.

1. Once completed, verify the installation and proper version number, as shown previously in Example 1.

| **Note** : The version numbers in our examples are provided purely for reference and may not reflect the latest versions of the software. |
| --- |

###

### Install Java SDK:

1. Check for Java installation and verify that the version number is v8 or higher.

Open your workstation's version of the command prompt, if not already open. Once the command prompt is open, use the command in Example 2 to check if your workstation currently has a version of Java installed. Java SDK 8 is the preferred version for these labs, however, any versions higher than that will suffice.

1. _Java version_

C:\Users\User\> java -version

java version "1.8.0\_241"

Java(TM) SE Runtime Environment (build 1.8.0\_241-b07)

Java HotSpot(TM) 64-Bit Server VM (build 25.241-b07, mixed mode)

If you do not see a version number after you submit the command, you do not have Java installed or if it shows a version less than v8, you should continue following these instructions. The display format of the version number for Java is slightly different than what is displayed for node.js. With Java, the second value in the displayed version number, i.e. the "8" in Example 2, is the version number. So, our example is showing Java SDK version 8. If you do see a version number and it is v8 or higher, you can move on to section Install VSCode.

1. If your version of Java displayed is less than v8, you need to uninstall the current version on your workstation and reinstall the correct version. Follow the link below to uninstall instructions that represent your workstation operating system (OS).

###### _Linux_: [https://www.java.com/en/download/help/linux\_uninstall.xml](https://www.java.com/en/download/help/linux_uninstall.xml%20)

_Mac:_[https://www.java.com/en/download/help/mac\_uninstall\_java.xml](https://www.java.com/en/download/help/mac_uninstall_java.xml%20)

_Windows:_ [https://www.java.com/en/download/help/uninstall\_java.xml](https://www.java.com/en/download/help/uninstall_java.xml%20)

1. Once Java is uninstalled from your workstation, you can click the Java JDK 8 download link below and follow the installation instructions for your specific OS.

https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

1. Verify the installation and proper version number as shown in Example 2.

| **Note** : You will be prompted to register a new Oracle account in order to download the installation file, please do so. If you have an existing account, you may use that to log in and continue. |
| --- |

##

## Install VSCode

If you do not already have VSCode installed on your workstation, please do so now by following the download and installation instructions at the link below:

[https://code.visualstudio.com/download](https://code.visualstudio.com/download)

[![](RackMultipart20240209-1-hrjkq8_html_a984f15eff87ad15.png)](https://github.com/openmainframeproject/cobol-programming-course/blob/master/Images/image025.png)

1. _VSCode download site_

| **Note** : Be sure to select the correct installation file for your workstations respective OS, shown in Figure 1. |
| --- |

##

## Install VSCode extensions

This section introduces two VSCode extensions, Zowe Explorer and IBM Z Open Editor, listed in Figure 2, and instructions on how to install them.

[![](RackMultipart20240209-1-hrjkq8_html_8aa579c44e84840c.png)](https://github.com/openmainframeproject/cobol-programming-course/blob/master/Images/image026.png)

1. _VSCode required extensions_

###

### Zowe Explorer:

Zowe is a new, and the first open source framework for z/OS and provides solutions for development and operations teams to securely manage, control, script and develop on the mainframe like any other cloud platform. Out of the box, the Zowe Explorer provides a lot of functionality allowing z/OS developers access to jobs, datasets and (USS) files on a z/OS server. Backed by the Zowe CLI and z/OSMF, developers now have powerful features that makes it easy to work with z/OS within the familiar VSCode environment. This extension can be used to edit COBOL and PL/I files opened on z/OS MVS™ and USS using the Zowe extension's Data Sets and USS views. It can even run JCL and lets you browse job spool files. For more information on Zowe Explorer and its interaction with z/OS please visit:

https://ibm.github.io/zopeneditor-about/Docs/interact\_zos\_zowe\_explorer.html

### Install Zowe Explorer:

Open VSCode and in the left side tool menu select **Extensions**. From there, in the "Search Extensions in Marketplace" search field, type Zowe Explorer. Search results will begin populating, select **"Zowe Explorer"** and click **install** , depicted in Figure 3.

[![](RackMultipart20240209-1-hrjkq8_html_8a8d870a87a933bd.jpg)](https://github.com/openmainframeproject/cobol-programming-course/blob/master/Images/image030.jpg)

1. _Install Zowe Explorer in VSCode_

The Zowe community has a number of on-line videos that walk through the steps required to install, configure and operate the Zowe Explorer, see: [http://www.youtube.com/watch?v=G\_WCsFZIWt4&t=0m38s](http://www.youtube.com/watch?v=G_WCsFZIWt4&t=0m38s)

### IBM Z Open Editor:

IBM Z Open Editor brings COBOL and PL/I language support to Microsoft VSCode. It is one of the several next generation capabilities for an open development experience for z/OS®. It also works in association with the Zowe Explorer plugin. For more information on IBM Z Open Editor, please visit:

[https://ibm.github.io/zopeneditor-about/Docs/introduction.html#key-capabilities](https://ibm.github.io/zopeneditor-about/Docs/introduction.html#key-capabilities)

### Install IBM Z Open Editor:

Open VSCode and in the left side tool menu select **Extensions**. From there, in the "Search Extensions in Marketplace" search field, type IBM Z Open Editor. Search results will begin populating, select **" IBM Z Open Editor "** and click **install** , depicted in Figure 4.

[![](RackMultipart20240209-1-hrjkq8_html_778fbb48b71cbc37.jpg)](https://github.com/openmainframeproject/cobol-programming-course/blob/master/Images/image032.jpg)

1. _Install IBM Z Open Editor in VSCode_

| **Note** : There may be some limitations with IBM Z Open Editor if running a 32-bit Java version on Windows. |
| --- |

#

### Register for an account:

Follow the link provided below to register for an account with the mainframe. This account registration will provide you with a username, password and z/OSMF URL to establish your connection to the mainframe and must be done before moving on to lab 2.

#### **Registration Link:**

[https://www-01.ibm.com/events/wwe/ast/mtm/cobolvscode.nsf/enrollall?openform](https://www-01.ibm.com/events/wwe/ast/mtm/cobolvscode.nsf/enrollall?openform)

# ![Shape2](RackMultipart20240209-1-hrjkq8_html_3d0f2ea06bbb1535.gif)

# Lab 2. Connecting to the Mainframe

##

## Overview

In this lab exercise you will connect to an IBM Z mainframe system, view a simple COBOL hello world program in VSCode, submit JCL to compile the COBOL program, and view the output.

## Objectives

- Setup connection profile in Zowe Explorer
- Connect to z/OS through connection profile
- Filter data sets
- Submit "hello world" job
- View jobs output

## Lab instructions

1. The lab assumes installation of VSCode with Z Open Editor and Zowe Explorer extensions as shown in Figure 1.
 ![Shape4](RackMultipart20240209-1-hrjkq8_html_eabda32f1af4c09a.gif) ![Shape3](RackMultipart20240209-1-hrjkq8_html_a663d82735559f4a.gif)

_Click Extensions icon_

_List should include:_

_1. IBM Z Open Editor_

_2. Zowe Explorer_

![](RackMultipart20240209-1-hrjkq8_html_7fd1886488cf9f65.png)

1. _VSCode extensions_

1. Click the Zowe Explorer icon as shown in Figure 2.
 ![Shape5](RackMultipart20240209-1-hrjkq8_html_d6eb493ae813597b.gif)

![](RackMultipart20240209-1-hrjkq8_html_8085d24c7d6ab272.png)

 ![Shape6](RackMultipart20240209-1-hrjkq8_html_1ddfec3792af4d46.gif)

_Zowe Explorer_

1. _Zowe Explorer icon_

1. In order to connect to the lab system, get your team configuration zip file and extract it. You can obtain the team configuration zip file from the .zip file you downloaded along with this document.

![](RackMultipart20240209-1-hrjkq8_html_7c16185e34ac91a3.png)

1. _Team Configuration Zip Folder_

1. Open the extracted folder. You will find the two configuration files as shown in Figure 4.
 ![Shape7](RackMultipart20240209-1-hrjkq8_html_4b2a9286b31eed4e.gif)

![](RackMultipart20240209-1-hrjkq8_html_8739f19095318a6c.png)

 ![Shape8](RackMultipart20240209-1-hrjkq8_html_767556ade2e28ac4.gif)
1. _Inside the Team Configuration folder_

1. Now back on your VS Code window, select the Explorer tab, and press the "Open folder" button in the left bar.
 ![Shape11](RackMultipart20240209-1-hrjkq8_html_cc04cdc0c1d68628.gif) ![Shape10](RackMultipart20240209-1-hrjkq8_html_e4e378e721ca102a.gif) ![Shape9](RackMultipart20240209-1-hrjkq8_html_1336987b8910d6b7.gif)

![](RackMultipart20240209-1-hrjkq8_html_f5b5baac8bc1a0f1.png)

1. _Click the Open Folder button_

1. A pop-up window would show up, select the folder containing the team configuration files..
 ![Shape12](RackMultipart20240209-1-hrjkq8_html_ae0831ee604a4580.gif)

![](RackMultipart20240209-1-hrjkq8_html_e1ae19c26549d090.png)

1. _Select the Team Configuration folder_

 ![Shape13](RackMultipart20240209-1-hrjkq8_html_ac27a28c2a9541eb.gif)

If you are prompted to trust the authors of the files in the folder as shown in Figure 7, select **Yes, I trust the authors**. ![](RackMultipart20240209-1-hrjkq8_html_956ab238fee8f78f.png)

 ![Shape14](RackMultipart20240209-1-hrjkq8_html_8096a58a9cec4aae.gif)
1. _Trust the Authors of Files in The Folder_

1. Your connection should be added automatically to the Data Sets list as shown in Figure 8.
 ![Shape15](RackMultipart20240209-1-hrjkq8_html_ae0831ee604a4580.gif)

![](RackMultipart20240209-1-hrjkq8_html_2a71ebb705242a9.png)

 ![Shape16](RackMultipart20240209-1-hrjkq8_html_318ec589dbf1da54.gif)
1. _LearnCOBOL Connection_

If the connection does not appear, hover to the far right of the Data Sets line and press the + icon. Afterward, select the **LearnCOBOL** connection as shown in Figure 9.

 ![Shape17](RackMultipart20240209-1-hrjkq8_html_456713e402a86337.gif)

![](RackMultipart20240209-1-hrjkq8_html_c439f6a32a4ff6b2.png)

 ![Shape18](RackMultipart20240209-1-hrjkq8_html_a494c0b835f2edbd.gif)
1. _Adding the Connection manually_

1. Press the LearnCOBOL connection..
 ![Shape19](RackMultipart20240209-1-hrjkq8_html_ae0831ee604a4580.gif)

![](RackMultipart20240209-1-hrjkq8_html_4aa5306f28f3b555.png)

 ![Shape20](RackMultipart20240209-1-hrjkq8_html_1ead47bb027b8836.gif)
1. _Password prompt_

1. The connection prompts for a username as shown in Figure 11. **Please enter the username assigned to you! Do not use the sample username of Z99998.**
 ![Shape21](RackMultipart20240209-1-hrjkq8_html_b829131d2c1e82c1.gif)

![](RackMultipart20240209-1-hrjkq8_html_e9d71f7ff9c214c4.png)

 ![Shape22](RackMultipart20240209-1-hrjkq8_html_e54b04e249db979b.gif)
1. _Enter assigned user name_

1. Enter your assigned password as shown in Figure 12.
 ![Shape23](RackMultipart20240209-1-hrjkq8_html_366ce79551f95c4f.gif)

![](RackMultipart20240209-1-hrjkq8_html_8ae4af9c5b4af21f.png)

 ![Shape24](RackMultipart20240209-1-hrjkq8_html_c4be4f135dd805fe.gif)
1. _Accept connections with self-signed certifications_

1. Expansion of the connection (LearnCOBOL.zosmf) reads "Use the search button to display datasets". Click the search button as shown in Figure 13.
 ![Shape25](RackMultipart20240209-1-hrjkq8_html_a04f3b181ea406af.gif)

![](RackMultipart20240209-1-hrjkq8_html_2a4c52faef8e624e.png)

1. _Search button_

1. A prompt to "Search Data Sets" will appear as shown in Figure 14. **Please enter the username assigned to you! Do not use the sample username of Z99998.**
 ![Shape26](RackMultipart20240209-1-hrjkq8_html_6ff815819ba12a6a.gif)

![](RackMultipart20240209-1-hrjkq8_html_7126134e0caa8158.png)

1. _Select a filter_

1. A list of data set names beginning with your username will appear as shown in Figure 15. You may have a different list as compared to what is shown in Figure 15.
 ![Shape27](RackMultipart20240209-1-hrjkq8_html_61f8d22f36b68da2.gif)

![](RackMultipart20240209-1-hrjkq8_html_d0500bddb94983f2.png)

 ![Shape28](RackMultipart20240209-1-hrjkq8_html_75d21828a374f25d.gif)
1. _Filtered data set names_

1. Expand **\<USERNAME\>.CBL** to view COBOL source members, then select member **HELLO** to see a simple COBOL 'Hello World!' program as shown in Figure 16.
 ![Shape29](RackMultipart20240209-1-hrjkq8_html_2b0bc09d7b9d7784.gif)

![](RackMultipart20240209-1-hrjkq8_html_f21c9e677a8a8f7e.png)

1. _USERNAME.CBL_

1. Expand **\<USERNAME\>.JCL** to view JCL and select member HELLO which is the JCL to compile and execute simple 'Hello World!' COBOL source code as shown in Figure 17.
 ![Shape30](RackMultipart20240209-1-hrjkq8_html_e07983ff28dc041d.gif)

![](RackMultipart20240209-1-hrjkq8_html_22cf28e0decffdae.png)

1. _USERNAME.JCL_

1. Right click on JCL member **HELLO** , a section box appears. Select **Submit Job** for system to process HELLO JCL as shown in Figure 18. The submitted JCL job compiles the COBOL HELLO source code, then executes the COBOL HELLO program.
 ![Shape31](RackMultipart20240209-1-hrjkq8_html_984214af7effdba.gif)

![](RackMultipart20240209-1-hrjkq8_html_ec4a89c8dcedd14c.png)

1. _Submit Job_

1. Observe the 'Jobs' section in Zowe Explorer as shown in Figure 19.

![](RackMultipart20240209-1-hrjkq8_html_8e4e642c1a7e6f6.png)

1. _JOBS section_

1. Again, click on the + to the far right on the Jobs selection. Result is another prompt to 'Create new'. Select your connection (LearnCOBOL.zosmf) from the list as shown in Figure 20.
 ![Shape32](RackMultipart20240209-1-hrjkq8_html_adefdf0be4fc97e.gif)

![](RackMultipart20240209-1-hrjkq8_html_c244a5319aa38630.png)

 ![Shape33](RackMultipart20240209-1-hrjkq8_html_edd2f3e4c3541ad3.gif)

+

1. _Select LearnCOBOL connection_

1. As a result, the JCL jobs owned by your username appear. HELLOCBL is the JCL job name previously submitted. Expand HELLOCBL output to view sections of the output as shown in Figure 21.
 ![Shape34](RackMultipart20240209-1-hrjkq8_html_57542b8862160a60.gif)

![](RackMultipart20240209-1-hrjkq8_html_14a364cc94fad2cf.png)

1. _HELLOCBL output_

1. Select **COBRUN:SYSPRINT(101)** to view the COBOL compiler output. Scroll forward in the COBOL compile to locate the COBOL source code compiled into an executable module as shown in Figure 22. Observe the Indicator Area in column 7, A Area beginning in column 8, and B Area beginning in column 12. Also, observe the period (.) scope terminators in the COBOL source.

![](RackMultipart20240209-1-hrjkq8_html_8546cc5843c3eac1.png)

1. _COBOL compiler output_

1. View the COBOL program execution by selecting **COBRUN:SYSOUT(104)** from the LearnCOBOL in the Jobs section of Zowe Explorer as shown in Figure 23.
 ![Shape35](RackMultipart20240209-1-hrjkq8_html_b19328b996abb21d.gif)

![](RackMultipart20240209-1-hrjkq8_html_bc3671c19d3f2779.png)

1. _COBOL program execution_

1. The following URL is another excellent document describing the above VSCode and Zowe Explorer details with examples:

[https://marketplace.visualstudio.com/items?itemName=Zowe.vscode-extension-for-zowe](https://marketplace.visualstudio.com/items?itemName=Zowe.vscode-extension-for-zowe)

Lab 3. Successful vs. Unsuccessful Job Execution

# ![Shape1](RackMultipart20240209-1-zjq4rf_html_3d0f2ea06bbb1535.gif)

# Lab 3. Successful vs. Unsuccessful Job Execution

| **Note** : It may take a few seconds to load in all segments of this lab. If files are not loading, hit the refresh button on the list that appears when hovering over the section bar. |
| --- |

##

## Overview

In this lab exercise you will run a simple payroll application that will result in a successful compile and execution. You will then run a second payroll application that will produce an error. You are tasked with identifying the issue, fixing it, and resubmitting the program for a successful compile and execution.

## Objectives

- Submit and view output from successful run of PAYROL00 program
- Submit and view output from unsuccessful run of PAYROL0X program
- Identify the root of the error
- Fix the error
- Resubmit and view output from PAYROL0X job for a successful run

## Lab instructions

1. View the _PAYROL00_ COBOL source code member in the _'id'.CBL_ data set.

1. Submit the JCL member, _PAYROL00_, from the _id.JCL_, where id is your provided username. This is where _id.JCL(PAYROL00)_ compiles and successfully executes the _PAYROL00_ program.

![Shape4](RackMultipart20240209-1-zjq4rf_html_bc05d77c5bbff1e1.gif) ![Shape2](RackMultipart20240209-1-zjq4rf_html_f834f5056127e9b6.gif) ![Shape3](RackMultipart20240209-1-zjq4rf_html_4d71ae37a4979c6a.gif) ![Shape5](RackMultipart20240209-1-zjq4rf_html_156ead3bb2956cd7.gif) ![](RackMultipart20240209-1-zjq4rf_html_73bb183f217fbee2.png)

1. _Submit PAYROL00 job_

| **Note** : If you receive this error message after submitting the job: ![](RackMultipart20240209-1-zjq4rf_html_77f747cec2f09657.png) That is because you submitted the job from the .CBL data set and not the .JCL data set. |
| --- |

1. View both compile and execution of _PAYROL00_ job output, referenced in Figure 2.
 ![Shape9](RackMultipart20240209-1-zjq4rf_html_47c2dbf5e4d49870.gif) ![Shape8](RackMultipart20240209-1-zjq4rf_html_a7cfdaaf2b5103b2.gif) ![Shape7](RackMultipart20240209-1-zjq4rf_html_459f7647be1a2777.gif) ![Shape6](RackMultipart20240209-1-zjq4rf_html_47c2dbf5e4d49870.gif)

Execution

Compile

![](RackMultipart20240209-1-zjq4rf_html_58af9f419e7b2cc0.png)

1. _PAYROL00 output_

1. Next, view _PAYROL0X_ COBOL source code member in _id.CBL_ data set.

1. View and submit the JCL member, _PAYROL0X,_ from the _id.JCL_ dropdown. This is where _id.JCL(PAYROL0X)_ compiles and executes the _PAYROL0X_ program.

1. View the compile of _PAYROLL0X_ job output, notice there is no execution output.

Do you notice a difference between this compile and the previous job compile shown in Figure 3?

![](RackMultipart20240209-1-zjq4rf_html_4676e6dd8a1edf5a.png)

1. _Compare job compiles_

The difference is the return/condition code associated with each job output, located both next to the job output name within the JOBS section as shown above, or at the end of the compile output as, 0Return code ##. A return code of 12 means there was an error, but how do we know what that error was? Continue to find out!

1. Observe the text associated with _IGYPA3146-S_ on line 137 within the job output (compile), illustrated in Figure 4.
 ![Shape11](RackMultipart20240209-1-zjq4rf_html_a1f9df2708f90186.gif) ![Shape12](RackMultipart20240209-1-zjq4rf_html_291656f14dfb008c.gif) ![Shape10](RackMultipart20240209-1-zjq4rf_html_d6fbf7ea67c79c1b.gif)

![](RackMultipart20240209-1-zjq4rf_html_3a5c94b9a533a1f5.png)

1. _IGYPA3146-S message_

Notice that this line tells you to focus on the _GROSS-PAY_ picture clause in order to identify the problem. Use this information, modify the _PAYROL0X_ COBOL source code to fix the error. Be sure you are editing the correct code.

1. After modifying, re-submit the _PAYROL0X_ JCL to verify the problem has been identified and corrected, resulting in a successful compile and execution with a return code of zero, shown in Figure 5.
 ![Shape15](RackMultipart20240209-1-zjq4rf_html_f0fbe9606beb8292.gif) ![Shape16](RackMultipart20240209-1-zjq4rf_html_e882d3737bcfa871.gif) ![Shape13](RackMultipart20240209-1-zjq4rf_html_a4a65825e7ad87f1.gif) ![Shape14](RackMultipart20240209-1-zjq4rf_html_f0fbe9606beb8292.gif)

Second Submit

First Submit

![](RackMultipart20240209-1-zjq4rf_html_d48997d36354144d.png)

1. _Compare return codes_

# ![Shape17](RackMultipart20240209-1-zjq4rf_html_3d0f2ea06bbb1535.gif)

# Lab 4. Reading Records

| **Note** : All action items followed by a \* sign, include exercise hints, which are located at the end of this exercise. |
| --- |

## Overview

This lab demonstrates the 'end-of-file' COBOL coding technique for reading all data records from a sequential file.

## Objectives

- Familiarize with COBOL source code vs. JCL
- Identify error in program using the IGY message
- Correct the source code
- _Analyze ABENDU4038 output_
- Correct the JCL

## Lab instructions

1. If not already, open VSCode and select Zowe Explorer from the left sidebar.

| **Note** : If you are opening a new instance of VSCode (i.e. you closed out of it after the previous usage), you may need to 'Select a filter' again. You can do so by selecting the search icon ( ![](RackMultipart20240209-1-zjq4rf_html_39abcc131ac011a.png) ) next to your named connection in the DATA SETS section and then reselecting the filter previously used. It should be in the listed filters after you have selected the search symbol. |
| --- |

1. View these COBOL source code members listed in the _id.CBL_ data set:

- _CBL0001_
- _CBL0002_

1. View these three JCL members in the _id.JCL_ data set:

- _CBL0001J_
- _CBL0002J_
- _CBL0003J_

![](RackMultipart20240209-1-zjq4rf_html_d4e3ddf7554cfeb8.png)

1. _Id.JCL(CBL0001J).jcl_

1. Submit job, _JCL(CBL0001J)_, within the DATA SET section.

1. View that job output using the JOBS section.

- _COBRUN:SYSPRINT(101) -_ COBOL program compiler output
- _RUN:PRTLINE(103)_ - COBOL program execution output, shown in Figure 2.

![](RackMultipart20240209-1-zjq4rf_html_97eda54367338b63.png)

1. _RUN:PRTLINE(103) for JCL(CBL0001J)_

1. Submit job, _JCL(CBL0002J)_, within the DATA SET section.

1. View that job output using the JOBS section.

- _COBRUN:SYSPRINT(101)_ - COBOL program compiler output

Locate COBOL compiler severe message IGYPS2121-S within the output file referred to in step 7, shown in Figure 3.

![](RackMultipart20240209-1-zjq4rf_html_e730b212409a8c67.png)

1. _IGYPS2121-S message_

1. Edit _CBL(CBL0002)_:

- Determine appropriate spelling of PRINT-REX, correct it within the source code and save the updated source code.

1. Re-submit job, _JCL(CBL0002J),_ using the DATA SET section and view the output in the JOBS section.

- _COBRUN:SYSPRINT(101)_ COBOL program compiler output
- _RUN:PRTLINE(103)_ is the COBOL program execution output (if correction is successful)

1. Submit job, _JCL(CBL0003J),_ using the DATA SET section.

1. View _CBL0003J ABENDU4038_ output, using the JOBS section:

- View the _IGZ00355_ abend message in _RUN:SYSOUT(104)_ from the COBOL program execution output.
- _IGZ00355_ reads, program is unable to open or close ACCTREC file name, shown in Figure 4 guiding you to the root of the error.
 ![Shape18](RackMultipart20240209-1-zjq4rf_html_abf6a1095650c8f0.gif)

![](RackMultipart20240209-1-zjq4rf_html_32b7be8025377b2f.png)

1. _RUN:SYSOUT(104) message_

1. Fix this error by editing _JCL(CBL0003J):_

- Determine the DDNAME needed, but missing or misspelled. \*
- Correct it within the code and save

1. Re-submit job, _JCL(CBL0003J),_ using the DATA SET section.

1. View _CBL0003J_ output using the JOBS section, your output should look like Figure 5.

- _RUN:PRTLINE_ - COBOL program execution output (if correction is successful)

![](RackMultipart20240209-1-zjq4rf_html_374b78bf5b243a9d.png)

1. _RUN:PRTLINE(103) for JCL(CBL0003J)_

#####

#####

#####

##### _Lab hints_

13. The error is located on line 11, adjust '_ACCTREX'_ accordingly.

 ![Shape19](RackMultipart20240209-1-zjq4rf_html_459345d5fbe74467.gif)

![](RackMultipart20240209-1-zjq4rf_html_ebc93988e90f2557.png)

1. _Error in id.JCL(CBL0003J).jcl_

# ![Shape20](RackMultipart20240209-1-zjq4rf_html_3d0f2ea06bbb1535.gif)

# Lab 5. Generating Reports

## Overview

This lab utilizes two COBOL programs, CBL0004 and CBL0005, located within your id.CBL data set, as well as two JCL jobs, CBL0004J and CBL0005J, located within your id.JCL data set. The JCL jobs are used to compile and execute the COBOL programs, as discussed in previous labs. You will practice generating reports with COBOL, in addition to, reformatting displayed output for a report.

## Objectives

- Submit job and view successfully generated report
- Compare the differences between two reports
- Edit the source code for the second report to reflect the proper format for currency
- Successfully resubmit the job with the changes reflected in the output

## Lab instructions

_Using VSCode and Zowe Explorer:_

1. Submit job: CBL0004J

1. Observe the report written with headers like Figure 1 below.

![](RackMultipart20240209-1-zjq4rf_html_59a9c477eae788ec.png)

1. _Report with headers_

1. Submit job: CBL0005J

1. Observe the report data lines are written without dollar currency symbol, illustrated in Figure 2.

![](RackMultipart20240209-1-zjq4rf_html_490700532aeaf993.png)

1. _No currency symbol in output_

1. Modify id.CBL(CBL0005) to include the dollar currency symbol in the report.

_\*Hint: Compare with CBL0004 line 25_

1. Re-submit job: CBL0005J

1. Observe the report data lines should now include the dollar currency symbol, shown in Figure 3.

![](RackMultipart20240209-1-zjq4rf_html_fc4b3036560a6e8a.png)

1. _Currency symbol added to output_


Lab 6. Editing Reports

# ![Shape1](RackMultipart20240209-1-3ufq7y_html_3d0f2ea06bbb1535.gif)

# Lab 6. Editing Reports

| **Note** : All action items followed by a \* sign, include exercise hints, which are located at the end of this exercise. |
| --- |

## Overview

This lab requires two COBOL programs, CBL0006 and CBL0007 and two respective JCL Jobs, CBL0006J and CBL0007J, to compile and execute the COBOL programs. All of which are provided to you in your VSCode - Zowe Explorer.

## Objectives

- Observe new additions to the report
- Submit job and verify the additions are present in the generated report
- Identify and correct syntax error
- Verify the correction is successful

## Lab instructions

_Using VSCode and Zowe Explorer:_

1. Take a moment and look over the source code of the two COBOL programs provided: CBL0006 and CBL0007.

1. Compare CBL0006 with CBL0005 from the previous lab. Do you notice the differences?

1. Observe the new CLIENTS-PER-STATE line within the WORKING-STORAGE \> PROCEDURE DIVISION.
2. Observe the new paragraph IS-STATE-VIRGINIA within that same division.
3. This paragraph checks whether the client is from Virginia. If that condition is met (true) then the program should add 1 to the clients from Virginia total.
4. Program writes "Virginia Clients = ", in last line of report.

1. Submit CBL0006J

1. View the job output from the JOBS section and verify the steps mentioned above were executed.
 ![Shape2](RackMultipart20240209-1-3ufq7y_html_5ba12183d6d566dc.gif)

![](RackMultipart20240209-1-3ufq7y_html_fff11b3cd9e3b3a2.png)

1. _Id.JCL(CBL0006J) output_

1. Submit CBL0007J

1. Find the compile error, IGYPS2113-E, in the job output.

1. Go ahead and modify id.CBL(CBL0007) to correct the syntax error outlined by the IGYPS2113-E message.\*

1. Re-submit CBL0007J

1. Validate that the syntax error was corrected by getting an error free output file.

![](RackMultipart20240209-1-3ufq7y_html_73374c5a99a0a456.png)

1. _Successful compile_

_Lab Hints_

7.

![](RackMultipart20240209-1-3ufq7y_html_c286726906e88a01.png)

# ![Shape3](RackMultipart20240209-1-3ufq7y_html_3d0f2ea06bbb1535.gif)

# Lab 7. Implementing Trailers

| **Note** : All action items followed by a \* sign, include exercise hints, which are located at the end of this exercise. |
| --- |

## Overview

This lab requires two COBOL programs, CBL0008 and CBL0009 and two respective JCL Jobs, CBL0008J and CBL0009J, to compile and execute the COBOL programs. All of which are provided to you in your VSCode - Zowe Explorer.

## Objectives

- Practice the use of trailers
- Identify data name definition error using the IGY message
- Correct the source code
- Verify the correction is successful

## Lab instructions

_Using VSCode and Zowe Explorer:_

1. Take a moment and look over the source code of the two COBOL programs provided: CBL0008 and CBL0009.

1. Submit CBL0008J

1. Observe report written with trailers consisting of limit and balance totals at the bottom of the output.
 ![Shape4](RackMultipart20240209-1-3ufq7y_html_e7dfcf33a85769d7.gif)

![](RackMultipart20240209-1-3ufq7y_html_a4abd272b9a6f7c0.png)

1. _Limit and balance totals_

1. Submit CBL0009J

1. Was the job successful? If not, find the compile error message to understand why.

1. Modify id.CBL(CBL0009), correcting the compile error.\*

![](RackMultipart20240209-1-3ufq7y_html_2b73d16beac27860.png)

1. _IGYPS2121-S error message_

1. Re-submit CBL0009J

1. Validate that the syntax error was corrected by getting an error free output file like in Figure 3. The correction should report written with trailers consisting of limit and balance totals, like Figure 1.
 ![Shape5](RackMultipart20240209-1-3ufq7y_html_f7603eaa8fdcb805.gif)

![](RackMultipart20240209-1-3ufq7y_html_915269029b10b838.png)

1. _Successful compile_

_Lab Hints_

6.

![](RackMultipart20240209-1-3ufq7y_html_809ed9779d50d1d4.png)

![Shape6](RackMultipart20240209-1-3ufq7y_html_3d0f2ea06bbb1535.gif)

# Lab 8. Working with COMP-3

| **Note** : All action items followed by a \* sign, include exercise hints, which are located at the end of this exercise. |
| --- |

## Overview

Many of the previous COBOL lab programs you have worked with thus far are reading records containing two packed decimal fields, the client account limit and the client account balance. In this lab, the total of all client account limits and balances used a COMPUTE statement, where the COMP-3 fields contained the packed decimal internal data.

## Objectives

- Practice the use of COMPUTE
- Understand the need for COMP-3 fields
- Identify the compile error and understand the underlying cause
- Use that information to correct and verify the program runs successfully

## Lab instructions

### Preface

-
### What happens when an internal packed decimal field is not described using COMP-3?

Without using COMP-3 to describe the field, the COBOL program treats the data as DISPLAY data (EBCDIC format). This lab demonstrates what happens during program execution without using COMP-3.

_Using VSCode and Zowe Explorer:_

1. Submit the job, _id.JCL(CBL0010J)_

1. Observe that the compile of the COBOL source was successful, however, also observe that the execution of the job failed. How can you tell?

There's no CC code next to CBL0010J(JOB#), instead there is an ABENDU4038 message. U4038 is a common user code error typically involving a mismatch between the external data and the COBOL representation of the data.

1. Read the execution SYSOUT message carefully. The SYSOUT message mistakenly believes the records are 174 characters in length while the program believes the records are 170 characters in length.

Packed decimal (COMP-3) expands into two numbers where only one number would typically exist. If the program reads a packed decimal field without describing the field as COMP-3, then program execution becomes confused about the size of the record because the PIC clause, S9(7)V99, is expecting to store seven numbers plus a sign digit when only three word positions are read. Therefore, execution reports a four-record length position discrepancy.

1. Edit id.CBL(CBL0010) to identify and correct the source code problem.\*

1. Submit id.JCL(CBL0010J) and verify correction is successful with a CC 0000 code.

_Lab Hints_

4. The ACCT-LIMIT PIC clause in the ACCT-FIELDS paragraph should be the same as the PIC clause for ACCT-BALANCE.

# ![Shape7](RackMultipart20240209-1-3ufq7y_html_3d0f2ea06bbb1535.gif)

# Lab 9. Intrinsic Functions

| **Note** : All action items followed by a \* sign, include exercise hints, which are located at the end of this exercise. |
| --- |

## Overview

This lab contains data that includes a last name, where last name is all upper-case. It demonstrates the use of intrinsic functions together with reference modification to lower-case the last name characters, except the first character of the last name. This lab requires two COBOL programs, CBL0011 and CBL0012 and two respective JCL Jobs, CBL0011J and CBL0012J, to compile and execute the COBOL programs. All of which are provided to you in your VSCode - Zowe Explorer.

## Objectives

- Practice the manipulation of data expression in output
- View and understand the usage of intrinsic functions paired with reference modifications
- Correct the syntax for the date/time intrinsic function
- Verify the change is valid

## Lab instructions

_Using VSCode and Zowe Explorer:_

1. Submit job, CBL0011J.

1. Observe the report output, last name, with first character upper-case and the remaining characters lower-case.

Figure 1, below, illustrates the difference in output from lab 8 compared to this lab. Notice that in the previous lab, the last names were listed in all capitalized characters, whereas, as previously stated, this lab output has only the first character of the last name capitalized.

![](RackMultipart20240209-1-3ufq7y_html_a0a2141ae71fa6e0.png)

1. _Lab 9 vs. lab 8 output_

1. Observe the PROCEDURE DIVISION intrinsic function, lower-case, within the WRITE-RECORD paragraph. This intrinsic function is paired with a reference modification resulting in output of last name with upper-case first character and the remainder in lower-case.

1. Submit CBL0012J

1. Observe the compile error.

Previous lab programs made use of a date/time intrinsic function. The date/time intrinsic function in this lab has a syntax error that needs to be identified and corrected.

1. Modify id.CBL(CBL0012) correcting compile error.\*

1. Re-submit CBL0012J

1. Corrected CBL0012 source code should compile and execute the program successfully. A successful compile will result in the same output as CBL0011J.

_Lab Hints_

6. Refer to CBL0011 line 120 for the proper formatting of the function-name causing the compile error.




# progressbar

How to use ProgressBar component


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Page](#page)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     progressbar=C:/Convertigo/Studio 8.2.1/workspace/progressbar/.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     progressbar=C:/Convertigo/Studio 8.2.1/workspace/progressbar//archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __progressbar__ project


## Mobile Application

Describes the mobile application global properties

### Pages

#### Page

<h1>ProgressBar usage</h1>
<ul>
<li>First progress bar is of type 'determinate' and positioned in the Toolbar</li>
<li>Second progress bar has a buffer and value incrementing. Color is set to 'success' (green)</li>
<li>Third progress bar is of type 'indeterminate'. Color is set to 'warnning' (orange)</li>
<li>Fourth progress bar is fired with the 'Start' button. It call a 'main' sequence that takes time to execute. It also calls at regular interval another sequence that will give us the main sequence status. Color is set dynamically to different color, depending on the sequence's response.</li>
</ul>
<img src="doc/progressbar.gif">




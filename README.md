Rubyweaver
==========

Ruby syntax highlighting for Dreamweaver. I created this back in 2005/2006 
so I could write Ruby/Rails code in Dreamweaver and get some syntax highlighting.

How to install on CS6
==========

* Download the zip folder from Git
* Extract the ZIP folder on your desktop
* Right click on Dreamweaver and "Run as administrator"
* Select Help>Manage Extensions
* In the Extensions panel select File>Package ZXP Extension
* Select the rubyweaver.mxi in the rubyweaver-master folder
* Save rubyweaver.zxp in the same folder
* Click the Install Button in the Extensions panel
* Select rubyweaver.zxp
* Accept the License
* Verify you want to install an unsigned extension
* Restart Dreamweaver and you're all set!

I've also used this on CS4 with no problems, but I don't entirely remember the installation process. I believe you can skip creating the zxp and just install it from the mxi file.

Features
========

Gives full Ruby and Rails functionality to Dreamweaver, including the following:

* Inserts a "Rails" object with tools to automatically insert VTL code into your document (appears in "Insert" toolbar in MX 2004 and up). 
* Adds .rb, .rhtml, .erb, .rxml, .rjs, .yml, and .sql extensions in Dreamweaver and associates those files with Dreamweaver for editing. 
* Adds Rails RHTML, Rails ERB, Ruby, YML, and SQL as a new document types in Dreamweaver. Also adds default pages which will open as the new document when these types are selected.
* Supports color coding, tag hints, etc.

Version History
===============

Latest version 2.3.3: released January 14, 2008

  <table border="1" cellspacing="0" cellpadding="3">
    <tr>
      <td class="nowrap">Version 2.3.3 </td>
      <td>Split view and design view issues resolved for rhtml (legacy) files.</td>
    </tr>
    <tr>
      <td class="nowrap">Version 2.3.0 </td>
      <td>Now compatible with Ruby on Rails 2.0 erb files</td>
    </tr>
    <tr>
      <td class="nowrap">Version 2.2.0 </td>
      <td>Now compatible with all versions of Dreamweaver!</td>
    </tr>
    <tr>
      <td class="nowrap">Version 2.1.2 </td>
      <td>Branch from Legacy version with added RJS support.</td>
    </tr>
    <tr>
      <td class="nowrap">Version 2.0.2 </td>
      <td>Legacy version created for Dreamweaver versions MX and MX2004. Certain file types were causing errors and not loading properly.</td>
    </tr>
    <tr>
      <td class="nowrap">Version 2.0.1 </td>
      <td>Added more buttons to "Insert" bar, including: unless, image_tag, link_to, url_for, javascript_include_tag, and stylesheet_link_tag</td>
    </tr>
    <tr>
      <td class="nowrap">Version 2.0.0 </td>
      <td>My first contribution with .rxml support added and Rails object to Insert toolbar </td>
    </tr>
    <tr>
      <td class="nowrap">Version 1.5.0</td>
      <td>Latest version developed by Rob Cameron with .rb, .rhtml, .yml, and .sql support. Also came with color coding and tag hints. </td>
    </tr>
  </table>


Known Issues
============

* To get the proper HTML coloring to show up in Rails files you need to go to Edit > Preferences > Code Hints. Click on the Tag Library Editor link, then click on the HTML Folder at the top of the tree. Below turn on the checkbox for Rails RHTML, Rails ERB, and Ruby.
* Do not add file extensions to the Edit > Preferences... > File Types / Editors > Open in code view list. This will cause the Split and Design views to stop working for these file types.

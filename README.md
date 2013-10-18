Rubyweaver
==========

Ruby syntax highlighting for Dreamweaver. I created this back in 2005/2006 
so I could write Ruby/Rails code in Dreamweaver and get some syntax highlighting.

It's been so long since I've used Dreamweaver that I have no idea how to actually
install it anymore, but people are still using it so I'm providing the code here.
If someone knows how to install it please issue me a pull request with updates
to this README explaining how. Thanks!

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

<pre>

    __/\\\\\\\\\\\\\\\______________________________/\\\\\\____        
     _\///////\\\/////______________________________\////\\\____       
      _______\/\\\______________________________________\/\\\____      
       _______\/\\\___________/\\\\\________/\\\\\_______\/\\\____     
        _______\/\\\_________/\\\///\\\____/\\\///\\\_____\/\\\____    
         _______\/\\\________/\\\__\//\\\__/\\\__\//\\\____\/\\\____   
          _______\/\\\_______\//\\\__/\\\__\//\\\__/\\\_____\/\\\____  
           _______\/\\\________\///\\\\\/____\///\\\\\/____/\\\\\\\\\_ 
            _______\///___________\/////________\/////_____\/////////__
                                                                                   

</pre>


Description
===========

Tool is a static html portfolio site generator (think jekyll, hyde, pelican, etc). It simplifies the process of making a portfolio to simply organizing the work in folders and generating the site.

Some configuration is required. See config/example.php for variables. Add more config files to manage more sites.

Note some functionality might not work because of external library dependencies. Please file issues in the forum so we can address these as they come up.

See the following site to get an example of the possiblities 
<http://portfolio.rchrd.net/>. More media will be added in the future.

Enjoy!


Getting Started
===============

If you visit tool.php through your webserver there is a gui to help get you started.

You can also run tool.php from the command line.

Run the following command to generate the example site. This should generate html in example/output and resize and copy images over into the output directory. 

    php tool.php -c example

Later you can try using the sync command to sync this to your server. Make sure to add your server details to a config.

    php tool.php -c mysite -s



Sites using this tool
=====================

- <http://portfolio.rchrd.net/>


Release Notes
============= 

02/15/13 -- Added a web gui to tool.php removed the make file to simplify config
01/22/13 -- Pushed to Github®


Author
======

Richard Caceres

- <http://github.com/rcaceres/>
- <http://rchrd.net>


Ascii art generated at <http://patorjk.com/software/taag/>



TODO
====

- [done] Reduce the amount of configuration necessary.
- [done] Update makefile so it is relative and doesn't need absolute paths
- Actually add an audio player
- Replace waveform generation with something more compatible
- [done] Add parsing of weblock files
- Add parsing of mov files
- [done] Add parsing of rtf files
- [done] Add parsing of pdf files
- Add parsing of md (markdown) files
- Sniff out youtube and vimeo videos and replace with embeds
- [done] Create a user interface for tool in place of the make command
- [done]Create a setup file where a user can input their config or have multiple config defintions and so they can control multiple sites!

License
=======

MIT
---

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


= activerecord-oracle_enhanced-adapter

* http://rubyforge.org/projects/oracle-enhanced/

== DESCRIPTION:

Oracle "enhanced" ActiveRecord adapter contains useful additional methods for working with new and legacy Oracle databases
from Rails which are extracted from current real projects' monkey patches of original Oracle adapter.

See http://github.com/rsim/oracle-enhanced/wikis for more information.

For questions and feature discussion please use http://groups.google.com/group/oracle-enhanced

Blog posts about oracle-enahnced can be found at http://blog.rayapps.com/category/oracle-enhanced

Bugs and enhancement requests can be reported at http://rsim.lighthouseapp.com/projects/11468-oracle-enhanced

== REQUIREMENTS:

* Works (has been tested) with ActiveRecord version 2.0, 2.1 and 2.2 (these are the same as Rails versions)
* Requires ruby-oci8 library to connect to Oracle
* Requires ruby-plsql gem to support custom create, update and delete methods (but can be used without ruby-plsql if this functionality is not needed)

== INSTALL:

* sudo gem install activerecord-oracle_enhanced-adapter

== LICENSE:

(The MIT License)

Copyright (c) 2009 Graham Jenkins, Michael Schoen, Raimonds Simanovskis

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
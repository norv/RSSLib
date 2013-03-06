## RSSLib

RSSLib is a library used for reading and writing RSS feeds for your websites. It is **not** a standalone application.

Support for PHP 4+ is planned, but at first I'll be using SimpleXML, which is only available for PHP 5+ and is only turned on by default in 5.3+. RSSLib also purposely throws exceptions in the event that something goes wrong. If you wish to terminate your application gracefully in the event of a feed error, you should enclose RSSLib code in try{} catch(){} blocks.

### Development Branch

If you wish to modify RSSLib to suit your application, it is recommended that you pull the development branch instead, as it contains the Unit Tests and PHPDoc pages. However if you're just using RSSLib "as is", the master branch should be more than sufficient.

### Contributions

If you wish to contribute to the project, I'm more than happy to recieve pull requests. As it is, this is more for my own learning than anything else, so I'd be glad to hear from you if you have an improvment in mind. Or if you don't want to send a pull request, you may also open a bug report or feature request in the tracker.

The project in licensed under the GNU GPL v3, so you may fork the project and change it however you like.

### License

Copyright (C) 2013 Scotty Christianson (The Craw)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

This license, and the copyright above must remain in the file, and in
any derivative works.

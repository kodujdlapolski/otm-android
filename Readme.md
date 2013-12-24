# OpenTreeMap for Android

## Getting Started

OpenTreeMap for Android has 2 major dependencies:

  - An OpenTreeMap web application installation
  - A "skin,"  which is a child application that uses the OTM library.

The source for the OpenTreeMap web application is available on github

<a href="https://github.com/azavea/OpenTreeMap">https://github.com/azavea/OpenTreeMap</a>

A default skin is included in this repository under ExampleApp.


A note on google-play-services_lib
----------------------------------

The google-play-services library is downloaded from the SDK manager

To use:

+ Download google-play-services using the SDK manager
+ include it in your workspace
+ Make sure that the reference to google-play-services_lib in project.properties is  correct.  (In Eclipse : Properties/Android/Reference)

Tested with revision 9

USDA Grant
---------------
Portions of OpenTreeMap are based upon work supported by the National Institute of Food and Agriculture, U.S. Department of Agriculture, under Agreement No. 2010-33610-20937, 2011-33610-30511, 2011-33610-30862 and 2012-33610-19997 of the Small Business Innovation Research Grants Program. Any opinions, findings, and conclusions, or recommendations expressed on the OpenTreeMap website are those of Azavea and do not necessarily reflect the view of the U.S. Department of Agriculture.


License
---------------

OpenTreeMap is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

OpenTreeMap is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with OpenTreeMap.  If not, see <http://www.gnu.org/licenses/>.

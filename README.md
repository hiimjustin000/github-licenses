# github-licenses
Get all the licenses that are included in GitHub.

# Licenses
All licenses are functions that are listed below. Some take the name, and optionally, the year. For example:
```js
const Licenses = require("github-licenses");
Licenses.MIT("Deez Nuts"); // copyright 2021
Licenses.MIT("Deez Nuts", 2012); // copyright 2012
```

The list of licenses that are included are:

License | Function | Takes name/year
--------|----------|----------------
Academic Free License v3.0 | AFL | No
Apache license 2.0 | APACHE | No
Artistic license 2.0 | ART | No
Boost Software License 1.0 | BSL | No
BSD 2-clause "Simplified" license | BSD2C | Yes
BSD 3-clause "New" or "Revised" license | BSD3C | Yes
BSD 3-clause Clear license | BSD3CC | Yes
Creative Commons Zero v1.0 Universal | CC0 | No
Creative Commons Attribution 4.0 | CCBY | No
Creative Commons Attribution Share Alike 4.0 | CCBYSA | No
Do What The F You Want To Public License | WTFPL | No
Educational Community License v2.0 | ECL | No
Eclipse Public License 1.0 | EPL1 | No
Eclipse Public License 2.0 | EPL2 | No
European Union Public License 1.1 | EUPL | No
GNU Affero General Public License v3.0 | AGPL | No
GNU General Public License v2.0 | GPL2 | No
GNU General Public License v3.0 | GPL3 | No
GNU Lesser General Public License v2.1 | LGPL21 | No
GNU Lesser General Public License v3.0 | LGPL3 | No
ISC | ISC | Yes
LaTeX Project Public License v1.3c | LPPL | No
Microsoft Public License | MSPL | No
MIT | MIT | Yes
Mozilla Public License 2.0 | MPL | No
Open Software License 3.0 | OSL | No
PostgreSQL License | POSTSQL | Yes
SIL Open Font License 1.1 | OFL | Yes
University of Illinois/NCSA Open Source License | NCSA | Yes
The Unlicense | UNL | No
zLib License | ZLIB | Yes

# CLI
The CLI allows you to choose a license and write to a file. (Default: (cwd)/LICENSE)

Format: licenses (license) (option(s))

Options:

Name | Description
-----|------------
--output/-n? | The output of the license
--name/-n | The name of the licensor
--year/-y? | The year the license was created

# License
This project is licensed under the [MIT License](./LICENSE).
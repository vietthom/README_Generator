<div></div>
  <h3>readme generator</h3>
  
  ## Table of contents
  *[Description](#description)
  *[Installation Instructions](#installation-instructions)
  *[Usage](#usage)
  *[License](#license)
  *[Contributors](#contributors)
  *[Testing](#testing)
  *[Questions](#questions)

  ## Description
  This application allows the user to create a readme file in the command line by following the prompts provided. 

  ## Installation instructions
  *Clone this directory *cd into the directory *Install all necessary node packages *start the application in the command line with node index.js

  ## Usage
  From the command line, run the command: node index.js, follow the prompts and provide the appropriate answers to create your readme file. 

  ##License
  ()=>{
    if(response.project_license == 'MIT License'){
      return `[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)`;
        } else if(response.license === "GNU AGPLv3") {
            return `[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)`;
        } else if(response.license === "GNU GPLv3") {
            return `[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)`;
        } else if(response.license === "GNU LGPLv3") {
            return `[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)`;
        } else if(response.license === "Mozilla Public License 2.0") {
            return `[![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)`;
        } else if(response.license === "Apache License 2.0") {
            return `[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)`;
        } else if(response.license === "Boost Software License 1.0") {
            return `[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)`
        } else if(response.license === "The Unlicense") {
            return `[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)`
    }
  }

## Contributors
None Applicable

## Testing 
None Applicable 

## Questions 
Github: httpsL//github.com/thomle0418
Email: thomle0418@gmail.com

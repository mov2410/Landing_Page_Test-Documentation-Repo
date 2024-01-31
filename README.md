This repository contains a complete set of templates for creating standard documentation for landing page testing.

The templates are based on the IEEE-730-2014 IEEE Standard for Software Quality Assurance Processes.

The FURPS+ model is used to classify software requirements as Functionality, Usability, Reliability, Performance, Supportability, and others such as Design, Implementation, Interface, Physical, and other qualities.

The Kano model is used to prioritize different types of customer requirements and features based on their impact on customer satisfaction.

The structure of the repository can look like this:

/Landing-Page-Test-Documentation-Repo

\|--- /master-test-plan

\| A directory for the pretesting documentation where you can describe the overall test   
\| activity, including test strategy, requirments to be verificated, test plan, roles and   
\| responsibilities, test schedule, etc.

\|----\| test-plan-template.md

\|----\| test-strategy-template.md

\|----\| requirements-specification-template.md

\|

\|----/ test-cases

\| In this directory, you can place files that contain descriptions of test cases for the landing page.

\|----\| test-case-template.md

\|----\| / test-case-set-1

\|---------\| test-case-1_1.md

\|---------\| test-case-1_2.md

\|---------\| ...

\|----\| / test-case-set-2

\|---------\| test-case-2-1.md

\|---------\| test-case-2-2.md

\|---------\| ...

\|----\| ...

\|

\|---- /test-checklists

\| This directory is where you can place checklists, such as exploratory checklist, sanity   
\| checklist, or regression checklist.

\|----\| checklist-template.md

\|----\| / exploratory-testing

\|----\| / sanity-testing

\|----\| / regression-testing

\|----\| ...

\|

\|---- / test-scripts

\| This is where automated test scripts are located, for example, using tools such as Selenium   
\| or Cypress.

\|----\| test-script-1.js

\|----\| test-script-2.js

\|----\| ...

\|

\|---- /test-data

\| A directory for test data files (e.g. JSON or CSV files) that can be used in your tests.

\|----\| test-data-file-1.json

\|----\| test-data-file-2.json

\|----\| ...

\|

\|----/screenshots

\| In this directory, you can place screenshots that are created during landing page testing.   
\| Separating them by category (for example, /desktop and /mobile) can be useful.

\|----\| /desktop-screenshots

\|---------\| screenshot-1.png

\|---------\| screenshot-2.png

\|---------\| ...

\|----\| /mobile-screenshots

\|---------\| screenshot-1.png

\|---------\| screenshot-2.png

\|---------\| ...

\|

\|---- /test-results

\| Here you can store test results, such as report files or XML files. Separating them by   
\| category, e.g., / defect, / test-execution, etc.) can be useful

\|----\| defect-report-template.md

\|----\| test-execution-report.md

\|----\| traceability-matrix-report-template.md

\|----\| performance-test-report-template.md

\|----\| security-test-report-template.md

\|----\| user-acceptance-test-report-template.md

\|----\| test-summary-report-template.md

\|----\| / defect-reports

\|---------\| test-report-1.md

\|---------\| test-report-2.md

\|---------\| ...

\|----\| / test-execution-reports

\|---------\| test-report-1.md

\|---------\| test-report-2.md

\|---------\| ...

\|----\| / …

\|----\| / xml-files

\|---------\| test-result-1.xml

\|---------\| test-result-2.xml

\|---------\| ...

\|

\|----/rtm

\| The directory for the Requirements Target Matrix (RTM), where you can track which test   
\| cases meet specific requirements.

\|----\| requirements-test-matrix-template.md

\|----\| rtm-1.md

\|----\| rtm-2.md

\|----\| …

\|

\|----\| README.md   
\| General information about the repository, a description of the structure   
\| and instructions for use.

\|----\| LICENSE   
\| The license file that defines the terms of use of your test repository.

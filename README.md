# data-republican-caucuses

## About this story

[Meet ‘the five families’ that wield power in McCarthy’s House majority](https://www.washingtonpost.com/politics/interactive/2023/house-republican-five-families/)

The Problem Solvers Caucus, Republican Governance Group, Main Street Caucus, Study Committee and Freedom Caucus negotiate as House Speaker Kevin McCarthy has a four-seat majority.

## About the data

This dataset contains the membership of each voting Republican to the five major ideological caucuses for Republicans in the U.S. House of Representatives about two months after the start of the 118th Congress, according to The Post's research and reporting.

While membership in these groups is not always publicly available, The Post identified affiliations based on public lists where available and reported where not available.

Most Republicans belong to at least one group, but many claim membership to more than one due to personal interests and political leanings. About a dozen Republicans choose not to be a part of any of the five groups, according to The Post's reporting.

Data as of March 24, 2023.

## Methodology

Membership data for the [Problems Solvers Caucus](https://problemsolverscaucus.house.gov/), [Republican Governance Group](https://republicangovernance.com/), [Main Street Caucus](https://bacon.house.gov/mainstreetcaucus/) and [Republican Study Committee](https://rsc-hern.house.gov/) comes from group websites and Post reporting. The House Freedom Caucus does not provide a list of members, so membership was determined by press releases and Post reporting, including photos of Freedom Caucus events. The Post also communicated with some individual member offices to check affiliations.

Nonvoting House members are not included in this dataset.

## Folders of note in this repo

• data/republican-caucuses.csv - Download the data used in this story.

## Data dictionary

Variables that can be found in the data:

- `bioguide`: Member's unique identification number within the Biographical Directory of the United States Congress.
- `first_name`: First name of the GOP House member.
- `last_name`: Last name of the GOP House member.
- `state`: State for the district the member represents.
- `district`: Congressional district number for the district the member represents.
- `problem_solvers`: Republican House members that are part of the Problem Solvers Caucus. TRUE indicates that the member is part of the group. Note: There are also Democrats in this caucus who are not included here.
- `governance_group`: Republican House members that are part of the Republican Governance Group, formerly the "Tuesday Group". TRUE indicates that the member is part of the group.
- `main_street`:  Republican House members that are part of the Main Street Caucus. TRUE indicates that the member is part of the group.
- `study_committee`: Republican House members that are part of the Republican Study Committee. TRUE indicates that the member is part of the group.
- `freedom_caucus`: Republican House members identified as part of the House Freedom Caucus. TRUE indicates that the member is part of the group.

## Changelog

## Credits

Research and reporting by Adrián Blanco Ramos, Marianna Sotomayor and Hannah Dormido. Editing by Kevin Uhrmacher and Annah Aschbrenner. Copy editing by Gaby Morera Di Núbila.

## Licensing

This data is published under an [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license](https://creativecommons.org/licenses/by-nc-sa/4.0/).

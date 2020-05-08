# COVID Tracking in Prisons

```
                     ________
M               M   /_  __/ /  ___
M M           M M    / / / _ \/ -_)
M M M       M M M   /_/_/_//_/\__/         __        ____
M M M M   M M M M     /  |/  /__ ________ / /  ___ _/ / /
M M M M M M M M M    / /|_/ / _ `/ __(_-</ _ \/ _ `/ / /
M M M M M M M M M   /_/__/_/\_,_/_/ /___/_//_/\_,_/_/_/
M M M M M M M M M     / _ \_______    (_)__ ____/ /_
M M M M M M M M M    / ___/ __/ _ \  / / -_) __/ __/
M M M M M M M M M   /_/  /_/  \___/_/ /\__/\__/\__/
                                 |___/

```

## Data sources and caveats
The Marshall Project, the nonprofit investigative newsroom dedicated to the U.S. criminal justice system, [is compiling data on the prevalence of coronavirus infection in prisons across the country](https://www.themarshallproject.org/2020/05/01/a-state-by-state-look-at-coronavirus-in-prisons). The Associated Press is sharing the data as the most comprehensive current national source of COVID-19 outbreaks in state and federal prisons.

Lawyers, criminal justice reform advocates and families of the incarcerated have worried about what was happening in prisons across the nation as coronavirus began to take hold in the communities outside. Through data collected by The Marshall Project we can see that thousands of prisoners have caught the illness as prisons became the center of some of the country’s largest outbreaks. Thousands more workers, correctional officers and medical staff have been sickened. And hundreds of people—most of them incarcerated—have died.

This data is an effort to track how those people have been affected and where the crisis has hit the hardest.

## Methodology
The data tracks the number of COVID-19 tests administered to people incarcerated in all state and federal prisons, as well as the staff in those facilities. It has been collected on a weekly basis by Marshall Project reporters who contacted each prison agency directly and verified published figures with officials.

Each week, the reporters ask every prison agency for the total number of coronavirus tests administered to its staff members and prisoners, the cumulative number who tested positive among staff and prisoners, and the numbers of deaths for each group.

The time series data is aggregated to the system level; there is one record for each prison agency on each date of collection. Not all departments could provide data for the exact date requested, and the data indicates the date for the figures.

To estimate the rate of infection among prisoners, we also collected population data for each prison system. In cases where current data was unavailable, we used the most recent available population numbers from the agencies in 10 states: Alabama, Alaska, Arkansas, Indiana, Illinois, Louisiana, Maryland, Montana, Nevada, Ohio.

To estimate the rate of infection among prison employees, we collected staffing numbers for each system. Where current data was not publicly available, we acquired other numbers through our reporting, including calling agencies or from state budget documents. In six states, we were unable to find recent staffing figures: Alaska, Hawaii, Kentucky, Maryland, Montana, Utah.

As with all COVID-19 data, our understanding of the spread and impact of the virus is limited by the availability of testing. Epidemiology and public health experts say that aside from a few states that have recently begun aggressively testing in prisons, it is likely that there are more cases of COVID-19 circulating undetected in facilities. Sixteen prison systems, including the Federal Bureau of Prisons, would not release information about how many prisoners they are testing.

The Marshall Project plans to update this dataset on a weekly basis.

## Record layout
There are three tables in this data, each in its own comma-separated values (csv) file.

`covid_prison_cases.csv` contains our weekly time series data on tests, infections and deaths in prisons. The first dates in the table are on March 26

It includes these columns:
* `name` - The name of the state or "Federal" for the Federal Bureau of Prisons
* `abbreviation` - The two-letter postal code abbreviation for the state or "US" for the Bureau of Prisons
* `staff_tests` - The cumulative number of tests administered to prison employess, including correctional officers and other staff.
* `prisoner_tests` - The cumulative number of tests administered to incarcerated people.
* `total_staff_cases` - The cumulative number of positive coronavirus cases among prison employees.
* `total_prisoner_cases` - The cumulative number of positive coronavirus cases among the incarcerated population.
* `total_staff_deaths` - The number of deaths of prison employees to date.
* `total_prisoner_deaths` - The number of deaths of prisoners to date.
* `as_of_date` - The date these data reflect.
* `notes` - Caveats or explanation about any aspect of this row of data.

Any questions that a prison agency could not or would not answer are left blank.

The second table in the dataset, `prison_populations.csv`, contains a one-time, recent snapshot of the population of people incarcerated in each of these prison systems, collected as close to April 15 as possible.

It includes these columns:
* `name` - The name of the state or "Federal" for the Federal Bureau of Prisons
* `abbreviation` - The two-letter postal code abbreviation for the state or "US" for the Bureau of Prisons
* `april_pop` - The total population of people held in the agency's prisons and secure facilities.
* `as_of_date` - The date the data reflect. In some instances, an April figure was not available, and we used the most recent number the agency could provide.

The third table in the dataset, `staff_populations.csv`, contains a one-time, recent snapshot of the headcount of workers for each prison agency, collected as close to April 15 as possible.

It includes these columns:
* `name` - The name of the state or "Federal" for the Federal Bureau of Prisons
* `abbreviation` - The two-letter postal code abbreviation for the state or "US" for the Bureau of Prisons
* `april_pop` - The total population of people working for the agency.
* `as_of_date` - The date the data reflect. In some instances, an April figure was not available, and we used the most recent number we could acquire.
* `notes` - Any caveats or notes about the data.

## Attribution
In stories attribute this data to: “According to an analysis of state prison cases by The Marshall Project, a nonprofit investigative newsroom dedicated to the U.S. criminal justice system”

## Contributors
Many reporters and editors at The Marshall Project contributed to this data, including: Katie Park, Tom Meagher, Weihua Li, Gabe Isman, Cary Aspinwall, Keri Blakinger, Andrew R. Calderón, Maurice Chammah, Eli Hager, Jamiles Lartey, Nicole Lewis, Joseph Neff, Alysia Santo, Beth Schwartzapfel, Christie Thompson, Abbie VanSickle.

## Bugs
If you have questions about the data, please email us at [info+covidtracker@themarshallproject.org](mailto:info+covidtracker@themarshallproject.org) or file a [Github issue](https://github.com/themarshallproject/COVID_prison_data/issues).
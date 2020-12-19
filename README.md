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
The Marshall Project, the nonprofit investigative newsroom dedicated to the U.S. criminal justice system, has partnered with The Associated Press to compile data on the prevalence of COVID-19 infection in [prisons across the country](https://www.themarshallproject.org/2020/05/01/a-state-by-state-look-at-coronavirus-in-prisons). The Associated Press is sharing this data as the most comprehensive current national source of COVID-19 outbreaks in state and federal prisons.

Lawyers, criminal justice reform advocates and families of the incarcerated have worried about what was happening in prisons across the nation as coronavirus began to take hold in the communities outside. Data collected by The Marshall Project and AP shows that hundreds of thousands of prisoners, workers, correctional officers and staff have caught the illness as prisons became the center of some of the country’s largest outbreaks. And thousands of people — most of them incarcerated — have died.

In December, as COVID-19 cases spiked across the U.S., the news organizations also shared cumulative rates of infection among prison populations, to better gauge the total effects of the pandemic on prison populations. The analysis found that by mid-December, one in five state and federal prisoners in the United States had tested positive for the coronavirus -- a rate more than four times higher than the general population.  

This data, which is updated weekly, is an effort to track how those people have been affected and where the crisis has hit the hardest.

## Methodology
The data tracks the number of COVID-19 tests administered to people incarcerated in all state and federal prisons, as well as the staff in those facilities. It is collected on a weekly basis by Marshall Project and AP reporters who contact each prison agency directly and verify published figures with officials.

Each week, the reporters ask every prison agency for the total number of coronavirus tests administered to its staff members and prisoners, the cumulative number who tested positive among staff and prisoners, and the numbers of deaths for each group.

The time series data is aggregated to the system level; there is one record for each prison agency on each date of collection. Not all departments could provide data for the exact date requested, and the data indicates the date for the figures.

To estimate the rate of infection among prisoners, we collected population data for each prison system before the pandemic, roughly in mid-March, in April, June, July, August, September and October. Beginning the week of July 28, we updated all prisoner population numbers, reflecting the number of incarcerated adults in state or federal prisons. Prior to that, population figures may have included additional populations, such as prisoners housed in other facilities, which were not captured in our COVID-19 data. In states with unified prison and jail systems, we include both detainees awaiting trial and sentenced prisoners.

To estimate the rate of infection among prison employees, we collected staffing numbers for each system. Where current data was not publicly available, we acquired other numbers through our reporting, including calling agencies or from state budget documents. In six states, we were unable to find recent staffing figures: Alaska, Hawaii, Kentucky, Maryland, Montana, Utah.

To calculate the cumulative COVID-19 impact on prisoner and prison worker populations, we aggregated prisoner and staff COVID case and death data up through Dec. 15. Because population snapshots do not account for movement in and out of prisons since March, and because many systems have significantly slowed the number of new people being sent to prison, it’s difficult to estimate the total number of people who have been held in a state system since March. To be conservative, we calculated our rates of infection using the largest prisoner population snapshots we had during this time period.

As with all COVID-19 data, our understanding of the spread and impact of the virus is limited by the availability of testing. Epidemiology and public health experts say that aside from a few states that have recently begun aggressively testing in prisons, it is likely that there are more cases of COVID-19 circulating undetected in facilities. Sixteen prison systems, including the Federal Bureau of Prisons, would not release information about how many prisoners they are testing.

Corrections departments in Indiana, Kansas, Montana, North Dakota and Wisconsin report coronavirus testing and case data for juvenile facilities; West Virginia reports figures for juvenile facilities and jails. For consistency of comparison with other state prison systems, we removed those facilities from our data that had been included prior to July 28. For these states we have also removed staff data. Similarly, Pennsylvania’s coronavirus data includes testing and cases for those who have been released on parole. We removed these tests and cases for prisoners from the data prior to July 28. The staff cases remain.

## Record layout
There are four tables in this data, each in its own comma-separated values (csv) file.

`covid_prison_cases.csv` contains our weekly time series data on tests, infections and deaths in prisons. The first dates in the table are on March 26

It includes these columns:
* `name` - The name of the state or "Federal" for the Federal Bureau of Prisons
* `abbreviation` - The two-letter postal code abbreviation for the state or "US" for the Bureau of Prisons
* `staff_tests` - The cumulative number prison employees, including correctional officers and other staff, tested.
* `staff_tests_with_multiples` - The cumulative number of tests administered to prison employees, including correctional officers and other staff where unique patients was not available.
* `prisoner_tests` - The cumulative number of incarcerated people tested.
* `prisoner_tests_with_multiples` - The cumulative number of tests administered to incarcerated people where unique patients was not available.
* `total_staff_cases` - The cumulative number of positive coronavirus cases among prison employees.
* `total_prisoner_cases` - The cumulative number of positive coronavirus cases among the incarcerated population.
* `total_staff_deaths` - The number of deaths of prison employees to date.
* `total_prisoner_deaths` - The number of deaths of prisoners to date.
* `as_of_date` - The date these data reflect.
* `notes` - Caveats or explanation about any aspect of this row of data.

Any questions that a prison agency could not or would not answer are left blank.

The second table in the dataset, `prison_populations.csv`, contains snapshots of the population of people incarcerated in each of these prison system for whom data on COVID testing and cases are available. This varies by state and may not always be the entire number of people incarcerated in each system. In some states, it may include other populations, such as those on parole or held in state-run jails. This data is primarily for use in calculating rates of testing and infection, and we would not recommend using these numbers to compare the change in how many people are being held in each prison system. If you need data to look at that fluctutation, we'd suggest you look at [this other dataset we compiled for this purpose](https://github.com/themarshallproject/COVID_prison_population_data).

It includes these columns:
* `name` - The name of the state or "Federal" for the Federal Bureau of Prisons
* `abbreviation` - The two-letter postal code abbreviation for the state or "US" for the Bureau of Prisons
* `march_pop` - The total population of people held in the agency's prisons and secure facilities.
* `as_of_date_march` - The date the data reflect.
* `april_pop` - The total population of people held in the agency's prisons and secure facilities.
* `as_of_date_april` - The date the data reflect.
* `june_pop` - The total population of people held in the agency's prisons and secure facilities.
* `as_of_date_june` - The date the data reflect.
* `july_pop` - The total population of people in prison in July.
* `as_of_date_july` - The data the count reflects.

The third table in the dataset, `staff_populations.csv`, contains a one-time, recent snapshot of the headcount of workers for each prison agency, collected as close to April 15 as possible.

It includes these columns:
* `name` - The name of the state or "Federal" for the Federal Bureau of Prisons
* `abbreviation` - The two-letter postal code abbreviation for the state or "US" for the Bureau of Prisons
* `april_pop` - The total population of people working for the agency.
* `as_of_date` - The date the data reflect. In some instances, an April figure was not available, and we used the most recent number we could acquire.
* `notes` - Any caveats or notes about the data.

The fourth table in the dataset, `covid_prison_rates.csv`, contains the rates of cases and deaths for prisoners. There is one for every state and federal prison system and an additional row with the `National` totals. 

It includes these columns:

* `name` - The name of the state or "Federal" for the Federal Bureau of Prisons or "National" for a national total.
* `latest_week` - The most recent week's case data on which these cumulative numbers are based.
* `cumulative_prisoner_cases` - The total number of positive cases among prisoners to date.
* `prisoner_cases_pct` - The percentage of the largest known prison population since March that have tested positive, to date.
* `prisoner_case_rate` - The rate of prisoners who've tested positive.
* `cumulative_prisoner_deaths`
* `prisoner_deaths_pct` - Deaths as a percentage of the largest known prison population since March that have tested positive, to date.
* `prisoner_death_rate`- The rate of prisoners who've died.

## Attribution
In stories attribute this data to: “According to an analysis of state prison coronavirus cases by The Marshall Project, a nonprofit investigative newsroom dedicated to the U.S. criminal justice system, and The Associated Press.”

## Contributors
Many reporters and editors at The Marshall Project and The Associated Press contributed to this data, including: Katie Park, Tom Meagher, Weihua Li, Gabe Isman, Cary Aspinwall, Keri Blakinger, Jake Bleiberg, Andrew R. Calderón, Maurice Chammah, Andrew DeMillo, Eli Hager, Jamiles Lartey, Claudia Lauer, Nicole Lewis, Humera Lodhi, Colleen Long, Joseph Neff, Michelle Pitcher, Alysia Santo, Beth Schwartzapfel, Damini Sharma, Colleen Slevin, Christie Thompson, Abbie VanSickle, Adria Watson, Andrew Welsh-Huggins.

## Bugs
If you have questions about the data, please email us at [info+covidtracker@themarshallproject.org](mailto:info+covidtracker@themarshallproject.org) or file a [Github issue](https://github.com/themarshallproject/COVID_prison_data/issues).
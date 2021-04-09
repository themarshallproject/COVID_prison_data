# Changelog
All notable changes to this project will be documented in this file. This captures all of the posts made on the discussion board of [our data.world mirror of the data](https://data.world/associatedpress/marshall-project-covid-cases-in-prisons/discuss/marshall-project-covid-cases-in-prisons/racahcnh).

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).


## 2021-04-09
Howdy folks. We have new data, including two weeks of snapshots for March 30 and April 6. In addition to the new data, there are two major changes for you to be aware. First, we've added the vaccine numbers we've been collecting since December. The prison agencies have been very erratic in their release of these figures. We plan to flesh them out as we can over time, and hope this is all useful for you in the meantime. There are four new columns. `staff_partial_dose` and `prisoners_partial_dose` indicate the cumulative number of each group that have gotten one shot of a two-dose vaccine. `staff_full_dose` and `prisoners_full_dose` track how many of each have gotten two shots of a two-dose vaccine or one-shot of the Johnson & Johnson vaccine. Be aware that some agencies will only release the number who've gotten at least one shot.

We've also noticed another disturbing update in the data published by the Federal Bureau of Prisons. They have removed five deaths from their figures. They attributed the change to three private prisons that they no longer are housing any people in. Because their death totals would have dropped, we have left that field blank this week. So we have even less of an understanding of the total or current toll of the pandemic in federal prisons. We continue to ask the BOP to provide updated data and are filing records requests, but for now, treat that agency with all due caution.

That's all for this week. If you have questions as you review this, please get in touch: info+covid@themarshallproject.org.

## 2021-04-06
Hey everyone. Wanted to pop in to let you all know that we do have data for last week and it is forthcoming. A few of our states were extremely tardy, and we've had our hands full wrapping up [this story that published today](https://www.themarshallproject.org/2021/04/06/as-states-expand-vaccine-eligibility-many-people-in-prison-still-wait-for-shots) with our friends at the AP about the slow progress in vaccinating prisoners.

So rest assured, we will release numbers by the end of this week, and they will include data for last week as well as this week, and we'll also begin releasing the vaccination numbers we've been collecting since December for all of the prison systems. Until then, thanks for your patience. Stay tuned.

## 2021-03-26
Hi everyone. We have new data for you this week, along with one major update regarding our total figures.
Starting the week of March 9, we noticed the total number of cases in the federal prisons began dropping. The Bureau of Prisons's response was that they are removing prisoners who are released from their counts of active and recovered cases. As a results, we are unable to accurately determine the total number of infections in federal prisons. You can get more background in [this Twitter thread we posted today](https://twitter.com/MarshallProj/status/1375500147384270852). We asked the Bureau to help fill in the missing numbers and they declined to do so. We will continue to try to get those figures so we can resume counting those cases in the biggest prison system. Fingers crossed.

We also corrected the dates of the last data for Maryland, which was put into the wrong week. We added a new set of data for Maryland for last week, as well as for Alabama and Massachusetts.

That's all for now. Enjoy your spring weekend.

## 2021-03-19
Hello folks. We're back with our regular Friday data release. In addition to the data for this week, there are a few historic changes you should take note of:
- Arizona reclassified four deaths that had been preliminarily idenitifed as COVID as unrelated. They didn't provide updated past figures, so we have removed some previous weeks' data where the numbers were higher than the current total.
- Nevada officials revised their prisoner and staff case numbers, starting with the week of Feb. 23, 2021, saying that there had been errors in previous weeks, including some negative cases counted as positives. Because they have not provided revised figures for past weeks, we have withdrawn data for several weeks in January and February prior to the revision.
- We recently received a trove of historic data on testing and cases in Wyoming's prisons, which allowed us to update many weeks in the past year for that state. It enabled us to fill in many of our blanks, particularly in the fall and winter. 
Have a great weekend, everybody.

## 2021-03-13
Hey everybody! Sorry for the late update this week. We had a lot of late arriving data and a few other projects that held us up this week. New cases continued to drop. This week they're at their lowest level since April. This is a good sign things may be turning around, we hope.

We have a few things to note. First, we're adding a CHANGELOG of all of these weekly update notes from the [data.world project](https://data.world/associatedpress/marshall-project-covid-cases-in-prisons) to the mirror in [our Github repository](https://github.com/themarshallproject/COVID_prison_data). Long overdue. We've added December counts for the prisoner COVID testing populations in `prison_populations.csv`. There are also fixes to errata in two states. In Florida, the number of recovered prisoners initially reported for last week was off by 40 and has been updated. Also, the number of tests of prisoners last week included an additional digit. It was 118,784, not 1,187,184. This has been fixed too. Finally, there has been some issues with Nevada data lately. The state health department acknowledged in late February that there were a number of errors in how they were reporting case numbers in prisons, including, apparently, counting negative test results as positives in some instances. We're trying to get revised figures from the state and hope to have those updated next week. Until then, be wary of any case numbers from Nevada in January or February.

That's all for now. Have a good weekend, all.


## 2021-03-05
Hi friends, we're back with another round of data for this week. We saw a small uptick in new cases among prisoners from last week, but we remain about where we were in June. There are three small data fixes you should note. In last week's staff cases numbers in New Mexico and California, numbers were transposed and have been corrected now. Also last week, Missouri erroneously reported about 300 more staff cases than they intended to. They have since revised their numbers down and we have updated last week's case numbers accordingly. That's it for now. Have a good weekend and stay safe, everyone.

## 2021-02-26
Hello, partners. I'm here with our latest update. Again this week the number of new cases in prisons dropped. We haven't seen case numbers this low since June, which is a very good sign. There are two significant changes in the data worth noting. First, at the end of August, Maryland changed how they defined their number of tests for prisoners. Previously it had been how many prisoners were tested, and then the same column shifted to how many tests were administered to prisoners. So we have moved our prisoner tests for Maryland to the "`_with_multiples`" column starting with the Aug. 31 data collection. And in Missouri, we noticed that for many weeks in late 2020, the cumulative number of COVID-19 cases did not include people who died from the disease. We revised our figures from mid-July 2020, when the Missouri Department of Corrections began omitting deaths from its total case counts, through February 2021. That should cover it for this week. Thanks, all!

## 2021-02-19
Hi folks. We've updated our data for the week. One thing to note is we've adjusted the prisoner population for Arizona in many months when a small subset of the population was counted twice, leading to slight overcounts.
You all may be interested in [a series of seminars happening now on finding and working with COVID-19 data](https://www.youtube.com/watch?v=CR-MO6eEUJw), sponsored by the COVID-19 Data Dispatch and the National Association of Science Writers. I'll be speaking at a session on the 24th on engaging with data providers. The workshops are free. I hope you can join us. Have a good weekend!

## 2021-02-12
Hi everyone. We have a new week of data. This week, new COVID-19 cases among prisoners were the lowest number since October. Looking back at the peaks in December, it's all the more remarkable, and scary, to see how the virus was spreading unchecked in prisons.

With this week's data, there are a few small fixes to note, if you're following these systems. Montana's staff cases inadvertently included a juvenile facility the last 2 weeks and has been updated. For the federal Bureau of Prisons, last week's numbers of prisoner cases originally omitted active cases in privately run facilities. The number has been fixed.

Stay safe and have a good weekend, everybody.

## 2021-02-05
Hi folks, we just uploaded this week's data haul. As always, there are some new things for you to note as you start to dig in.

Last week, Florida reduced their number of prisoner deaths from 205 to 203, but couldn't tell us when those deaths were or when they appeared in the data, simply that they had gotten autopsies were no longer considered COVID-related. So we put NA for the 1/26 row for Florida's deaths. This week, it's back up to 205, so those are presumably new reports of prisoner deaths.

Indiana has changed how it's reporting recovered prisoners. Prior to Feb. 1, 2021, Indiana counted some people more than once in their recovered numbers, if someone who had been considered recovered once tested positive a second time (though the positives were unique) and then recovered again. This caused in some weeks in January the number of recovered cases to be higher than the total number of people who tested positive. After Feb. 1, they say they are only reporting unique people recovered, so be careful when comparing this figure to more recent weeks. We've made a note in Indiana's data in all previous weeks, so be aware of this issue if you're tracking recoveries there.

Pennsylvania has taken down its case dashboard for about a month because of issues they've had with data quality. In the meantime, they are only reporting cases in a small subset of facilities and offices. That is much less than we've had access to in the past, so we are marking those as NA (or empty here) until their data returns.

Also, the eagle-eyed among you may notice some mention of vaccines in our notes. We are attempting to collect information on vaccine rollouts. We're not quite there yet in terms of data coverage or quality, so we aren't releasing that yet, but we hope to in the coming weeks.

If you see anything weird or have any questions, let me know. Otherwise, have a great weekend and stay safe.

## 2021-01-29
Hi everyone, we have more new data for you this week and a few things to make sure you're aware of.
We have gotten new monthly prison population figures from Nebraska. This has been a white whale we've been chasing for a long time, so it's great to have those finally. We also are releasing rates of cases and deaths for staff in many—but not all—states. North Dakota revised their testing numbers, so we've updated their figures for just about every week back to the beginning of the pandemic. We also found that the number of prisoners tested and the number of tests conducted were in the wrong columns for some weeks in New York, which switched its metric in December, and for Utah. We've updated them and made a note in the "notes" column. We also found that Mississippi revised its number of cases and tests, so we have removed the figures originally supplied for 1/5/21 and 1/13/21. We're trying to get revised figures for those dates, but can't say if or when they'll come. That about covers it on our end. Good luck working with this. Have a good weekend, all.

## 2021-01-22
Hello fellow data enthusiasts. We updated a lot of our data today, and I'm here to run you through the changes. First, we added new population snapshots for prisoners for the months of September, October and November. Keep in mind that these populations are for the groups of prisoners represented in the state's COVID testing. This is generally not every prisoner under the supervision or jurisdiction of the prison agency, so tread carefully as you describe this group. As part of that update, we also revised the prison population figures for Arkansas and Pennsylvania slightly, based on conversations we had with data folks in each of those states.

Wyoming today announced its first prisoner death, leaving Vermont as the only prison system to not have a prisoner die of coronavirus. We backfilled past weeks' data in Wyoming because the man died on Dec. 22.

This week, Massachusetts revised several past weeks of testing data that it seems were 1,000 tests higher than they should have been. We fixed that here. We've also aligned historic testing data for some past weeks for systems where the number of prisoners tested was in the column for total tests conducted, or vice versa. These fixes affected Idaho, Arizona, California, Oklahoma, Louisiana and the federal Bureau of Prisons.

Finally, for now, in late December, Tennessee gave us a number of staff tests that included contract employees, which it had not done before, or since. We've adjusted that figure to make it comparable to other weeks of data, and we're inquiring to see if we can get the more complete count for every week.

Whew, I think that covers it. Oh, and this week saw the highest number of staff deaths reported since the pandemic began.

Have at the data, and when you have questions, let us know so we can help. Have a good weekend, everybody.

## 2021-01-15
Hey all, we just updated our data for the week. The number of reported new cases dropped a bit, but we saw the highest number of new deaths reported. It is an interesting indicator, but I would counsel you to approach it with caution. 

Unfortunately, most prison systems reveal no details about people who die. Nothing about their time of death, location, age, sex or race. So we don’t know exactly when most of these people died. Some could have died weeks, or even months, ago and were just reported this week. So if you're using this data, be careful not to report this as a deaths that happened this week. These are deaths that were reported this week. The distinction is important. Holler if you have questions.
## 2021-01-08
Hi everybody. Happy new year! We're back, and although we weren't publishing updates, we have been collecting data over the last few weeks. So this is a big update, with new data snapshots from 12/22, 12/29 and 1/5. Though they didn't quite reach the highs set in mid-December, the new case numbers the last few weeks have still been quite a bit higher than anything we saw until December. As you review the data, let us know if you have any questions. More coming next week.

## 2020-12-23
Heading into the holiday weekend, wanted to let you know that we'll be a little quiet as we have a skeleton crew on duty. We will be collecting data the next few weeks as much as possible but we won't publish a new update until Jan. 7, when we'll have three weeks of new data to share. Hope you all have a safe and happy holidays.

## 2020-12-18
Hi all, a slight revision heading into the weekend. We've changed `covid_prison_rates.csv` after finding that a previous version included infection rates for prison employees that undercounted staff populations in at least one state. We've removed the employee rates for now to review them again and plan to update soon. The staff and prisoner case numbers and the prisoner rates are not affected by this revision. Have a great weekend.

## 2020-12-18
Hey everybody. Big update this week. First, today The Marshall Project published this story with the Associated Press finding that 1 in 5 prisoners and prison staff nationwide have gotten coronavirus. In some states, that number is much higher. We've added a new csv to this data distribution called covid_prison_rates.csv that includes the cumulative infection and death rates for every state and federal prison system, along with a national total.

On top of that, we saw cases rocket again this week, with more than 25,000 new cases among prisoners, a 10 percent increase.

And a few other small updates include new figures from Mississippi last week and updated Nebraska staff case numbers filling in some gaps back to July. Finally, you should be aware that Nevada suddenly started reporting deaths this week, with eight among prisoners and two staff members. We're curious as to when those deaths actually occurred, and are trying to verify that they indeed happened in the last week. If we get better information about when those deaths happened, we'll update accordingly.

Take a look at the new rates csv and documentation, and let us know what questions you have.

## 2020-12-11
Hello, folks. Here's this week's updated data. We counted a 10 percent jump in new cases among prisoners this week and our highest number of new cases among staff. This also includes small updates to previous week's data for Maine, North Dakota and Rhode Island.

We'd love to know what you all are doing with this data. Please let us know how you're using it and share your work with us.

Have a good weekend!

## 2020-12-05
Good morning, everyone. Overnight, California, Nebraska and Ohio updated their numbers for this week, so we've added them in here for all of you to use as well. Have a good weekend.

## 2020-12-04
Hi everybody. Because of the Thanksgiving holiday, we did not release data last week, but not to worry, we did collect it. We saw another record number of new cases among prisoners the week ending Nov. 24. We also had a high number of cases this week. This seemed to work out for us in terms of collecting the data, so we may take a similar approach over the holidays later in the month. We'll keep you posted on that.

A couple of things to note in this release is that Arkansas had a bit of a snafu in how they reported staffing numbers. They changed their counting system in September, but...didn't tell anyone. So it took us a bit to unravel why staff cases were being reported as static for several weeks. The upshot is that we've removed staff cases in Arkansas from early September until November when we were able to get new updated figures from them. So a big jump in new cases last week after several months of not reporting. We've also had issues with Oklahoma revising its number of deaths a couple times over the past month. We're asking them for revised figures, but for now there are two weeks without death totals in that state. We expect that updated numbers may still come in later today or over the weekend from a handful of states—Nebraska, California, Ohio. If they do, we'll put the latest numbers here right away. Thanks for checking out the data and let us know what questions you have.

## 2020-11-20
I spoke too soon. More data came in, so we updated again. We added Massachusetts, Nebraska and Mississippi. We also got updated data for California staff and prisoners. As you'd expect, the weekly number of new cases rose yet again to a new all-time high.

## 2020-11-20
Hi everybody. We've updated our weekly data and are again seeing our highest number of new cases among both prisoners and staff for the second week in a row. There are a couple of things you should notice in here. First, Texas reclassified three deaths as no longer related to coronavirus. Those people have been removed from the counts now, and this affected Texas's numbers back to late July. We added Nebraska's numbers for last week, along with updated prisoner testing numbers for Connecticut last week. And we also adjusted Montana's staff cases to remove a small handful at a juvenile facility that we generally exclude from our counts. That should about cover it. Have a good weekend and stay safe out there, everyone.

## 2020-11-13
Hi friends, we're back with another round of prison coronavirus data. This week, we saw the largest one-week increase in new cases on record, a massive 8% jump. You'll find it all in the covid_prison_cases.csv. There are a few other updates you should be aware of. North Dakota continues to tinker with its testing numbers, revising by small measures. 

This week, North Dakota's Department of Corrections and Rehabilitation revised its testing figures slightly, back to the beginning of the pandemic. We updated our figures here accordingly.

Rhode Island also resurfaced last week (though not this week) after being conspicuously absent from the data. Before November, Rhode Island included "presumed positive" cases in their case totals, which they have since begun reporting separately. We believe most of our historic data in this csv excluded presumed cases. For our online tracker, we estimated missing historic data based on the percentages of cases that were confirmed positive on Nov. 3.

Hawaii inadvertently counted one staff case twice last week. We revised our figures based on their update. And we updated the [query ranking states by their case rates here on data.world](https://data.world/associatedpress/marshall-project-covid-cases-in-prisons/workspace/query?queryid=1c148e14-1055-4388-b41a-2f9207abaa3d) to use more recent population figures, from August. We hope to have September's prisoner populations available soon. I think that covers it. If this week is any indicator of what's to come, things are going to be getting even worse in our prisons. More next week.

## 2020-11-06
Hi everybody. We had a few states trickle in late, so we thought we'd just do one big update this week. As you'll see, we have another big batch of new prisoner cases. And for the second week in a row, we saw the highest number of new positive cases reported among prison staff members.

There are few small caveats you should be aware of in this update:

- We caught that the number of prisoner deaths we recorded in Delaware last week was wrong. There were 11 deaths in Delaware, not 17. It has been updated in our data.
- We finally got some new numbers from Rhode Island for the first time in months. Because they have still had 0 deaths among prisoners or staff, we backfilled the intervening weeks death numbers for the state.
- West Virginia began to break down its staffing cases number by the type of facility. In the past, we could only get a total number that included jails and juvenile facilities (which we exclude everywhere else in the country). So you'll see a drop in West Virginia's staff numbers this week as we only take the figures for prisoners and work-release. In our online tracker, we have gone back to the past weeks of data and estimated the staff breakdown based on the overall size of the staff for each sector. You'll want to be aware of that and consider a similar approach as needed.

That should about cover it. Hit us up with any questions you have. Have a good weekend, everyone.

## 2020-10-30
Howdy, friends. We've updated our data for this week, which saw the most new cases among staff members since the beginning of the pandemic. We also saw the second-highest number of new cases among prisoners this week. In addition to the data for Oct. 27, we've also added a few updates to last week's figures. We added Nebraska, which came in very late. North Dakota revised their testing figures for last week. And we spotted a mistake where two numbers were transposed in Michigan's testing totals, and corrected that. It's too early to say if this rise is the start of a new trend, but we'll be keeping a close eye on it in the coming weeks. As always, if you have any questions, let us know. We'd be happy to help.

## 2020-10-22
We've updated our weekly data this evening. One thing to note is that Texas reclassified one death as unrelated to COVID, so we've removed that person from the prisoner death counts there back to mid-August. We've noted it in the notes field for Texas each week. I'm sure more data will come in tomorrow, and we'll share when we have it.

## 2020-10-16
As expected, we got some updated numbers today from Massachusetts, as well as Connecticut, Tennessee and New Jersey, and have pushed them up here. Have a great weekend, everybody.

## 2020-10-15
Hi, everybody. We updated our data for the week. Likely Massachusetts and maybe others will roll into tomorrow, so we'll post those updates when we have them.

## 2020-10-08
Howdy, friends. We posted our data release for this week. A few state systems have not come in yet, so I'll expect a small update tomorrow with a few of them. Stay tuned.

## 2020-10-02
Hey everyone. We brought some new updates today. We received this week's data from Massachusetts, Illinois, Montana and Delaware today. As a result, we caught a mistake in last week's Massachusetts staff cases, which incorrectly counted an additional 100 staff cases. Last week's figures has been corrected.

We also published new prisoner population numbers for August. In the process, we updated the reporting dates for some states in July, which inadvertently were showing as 2019 rather than 2020. That should cover it all. If you have any questions or need a hand with the data, please don't hesitate to reach out to us at info+covid@themarshallproject.org. Have a good weekend and stay safe.

## 2020-10-01
Hi everybody. We've posted our initial round of data for this week. There are seven states outstanding at this time. I'm expecting some, if not all, of them to show up with data tomorrow, in which case we'll update this again with the latest complete figures. One thing to note is that North Dakota revised their testing totals going back to Aug. 18 after they noticed some double counting in their figures. We updated all of our historic data accordingly.

## 2020-09-18
Hi friends,
We got some late arriving data today from Massachusetts, New Jersey, Delaware, Montana, Alaska and Wyoming. We also got an updated July prison population from Alabama that we added to `prison_populations.csv`. Have a great weekend, all!

## 2020-09-17
Hi everybody,
We've updated our COVID-19 prison data for the week. You should note that Kansas and Arizona revised some of their staff cases and testing numbers in recent weeks, so take a look at the "Notes" column where changes are flagged. Also this week, Georgia redesigned its data portal, which led us to discovered that we had inadvertently double-counting some prisoner cases and recoveries in privately run and county facilities. We have corrected those variables for many weeks in the data where needed, back to early April. So if you are particularly interested in Georgia, it's worth a close look. That's it for now. We expect there may be more updates from a few last slowpoke states tomorrow, in which case we'll push them to data.world in the afternoon.

## 2020-09-11
Hiya,
We got some late arriving testing data from Montana and Massachusetts we've added for this week. We've also updated `prison_populations.csv` with a July headcount of prisoners. There's a word of explanation we should make clear here about this csv: it contains snapshots of the population of people incarcerated in each of these prison systems for whom data on COVID testing and cases are available. This varies by state and may not always be the entire number of people incarcerated in each system. In some states, it may include other populations, such as those on parole or held in state-run jails. This data is primarily for use in calculating rates of testing and infection, and we would not recommend using these numbers to compare the change in how many people are being held in each prison system. For that purpose, we'd suggest looking at the `updated_prison_populations.csv`, which was compiled for just that purpose.

As always, if you have any questions or need a hand with the data, please don't hesitate to reach out to us at info+covid@themarshallproject.org. Have a good weekend, everybody.

## 2020-09-04
Hi folks,
As expected, a few more states drifted in today. We just added Massachusetts, Connecticut and Montana, along with an update to Florida's testing figures. Have a great holiday weekend, all.

## 2020-09-03
Hi friends,
We're back with another update this week. There are fewer major changes than we've seen in recent weeks. A few small things to be aware of, include:

- Alabama revised its case numbers for 8/25 after posting a wildly wrong number of prisoner cases
- Florida's prisoner tests dropped by 500 in a week. They've been doing some revisions to their data, but we're asking for a better explanation. That field is empty as result this week.
- Similarly, Louisiana's number of staff tests dropped by 40. We're asking them explain why and have left it open for now. 
- There are six states that haven't provided data yet this week. We expect some of them will come in tomorrow, and we'll update the csv when we have them. Thanks!

## 2020-08-27
Hey friends,
We've updated our weekly COVID data. As always, there are a few updates and revisions we wanted to flag.

- In Florida, the Aug. 18 data initially included a value for prisoner tests. Since then, the numbers have been revised according to prison officials, reflecting a lower number as of Aug. 25. We have updated the August 18 figure to be missing until the correct figures can be obtained
- Also in Florida, the Aug. 11 and Aug. 18 staff testing numbers were initially noted as staff members tested, but have since been changed to number of tests for staff - which may include the same staff member being tested more than once
- In New York, the Aug 18. figure for number of staff members recovered initially included a figure reported by the DOC that was later stated to be incorrect. The DOC did not provide a corrected figure, so it has since then been removed
- Starting this week, we've changed our Massachusetts data source to the Massachusetts Supreme Judicial Court. The previous dataset from the Department of Corrections excluded prisoner releases and staff recoveries. All data beginning with April 22 onward has been updated to use SJC figures.

That's all for this week! Thanks again for following this data. If you have any questions, please feel free to reach out, either here, or at info+covidtracker@themarshallproject.org. We're happy to help however we can.

## 2020-08-20
Hi everyone,
We have updated our weekly covid data. In the process, a few systems made updates and revisions you should know. We also adjusted our population figures in one state.

- Wyoming got back to us with last week's numbers, which have been updated in the week of August 11 data. Note, they said the testing numbers are "approximate"
- In New Mexico, our Aug. 11 data initially noted prisoner tests as individual prisoners tested. We have since updated these to be the number of tests for prisoners - which may include the same inmate tested more than once
- For the Federal Bureau of Prisons, our Aug. 11 data originally had an incorrect number for the total staff positive cases. It has been updated.
- In Kansas, our Aug. 11 staff figures initially included one juvenile facility, which has been removed. The staff testing numbers were initially reported by state prison officials with an error, and have been corrected.
- In Florida, the number of staff deaths as of Aug. 11 initially recorded two deaths. That number has since been updated to reflect the death of a third employee on August 10 which was reported by prison officials on August 19
- As of August 11, Nevada reported 94 cases of COVID among staff members. Since then, the numbers have been revised according to prison officials, reflecting a lower number as of August 18. We have updated the August 11 figure to be missing until the correct figures can be obtained
- In mid-August, Pennsylvania began reporting cases for prisoners and staff in community correction facilities. We have included these cases starting with numbers as of Aug. 18, and have updated inmate population figures to add individuals held in community corrections facilities.

That's all for this week! Thanks as always for using the data. If you have any questions about the data, please feel free to reach out, either here, or at info+covidtracker@themarshallproject.org. We're happy to help however we can.

## 2020-08-14
Hey data pals,
We finally received some very minor updates from a few states today we decided to incorporate into the data.

- Ohio gave us the last explanations of its revised death numbers for Belmont, Chillicothe, Marion and Pickaway prisons, so those figures are now updated.
- Connecticut revised its number of prisoners tested and recovered for this week after they said they made a mistake in reporting them to us.
- Montana confirmed they have had no deaths of prisoners or staff.
- Michigan provided the number of staff recovered there.

Wanted to make sure you all saw and understood the changes. Have a great weekend!

## 2020-08-13
Hi friends,
We updated our weekly covid data. Along the way, a few systems made updates and revisions you should be aware of, if you're following this closely. We also adjusted our population figures in two states.

- We updated Arizona's population figures to include prisoners who were temporarily out of the facilities on the day of the snapshot.
- In the week of Aug. 4, the Federal Bureau of Prisons began to report four deaths of people who had been released to home confinement, under the supervision of halfway houses. Their testing and case totals, however, do not include people on home confinement, and testing figures do not include private prisons.
- Indiana's data for the week of Aug. 4 initially included three juvenile facilities, which have now been removed from the totals that week.
- Kansas' Department of Corrections reports that its testing numbers count only the first two tests for each person. So they may be an undercount of the total number of tests administered.
- For the week of Aug. 4, Michigan updated its number of prisoners tested after it miscalculated the number for that day. We've revised our figures accordingly.
- We updated Minnesota's prisoner population counts to include juveniles housed in one facility that also has adults in it.
- Ohio revised its death numbers after reviewing death certificates. This week we were able to remove one death at Belmont Correctional that was not related to COVID-19 from the data, beginning on June 16. There is still one more death in the historic counts we are waiting for the Department of Rehabilitation and Correction to provide information on.

That's all, folks. Thanks for using the data. If you've had a chance to explore it or use it in your research or reporting, we'd love to hear from you. Please reach out, either here or at info+covidtracker@themarshallproject.org.

## 2020-08-06
Hiya everybody,
With every new week, there are new wrinkles to the historical data that you should watch out for. Here are this week's:

- It turns out that Texas has been mislabeling its prisoner testing data and in fact has been offering the total number of tests conducted, and not the number of prisoners tested. We've moved all of Texas' testing figures to the `_with_multiples` columns accordingly.
- Similarly, we noticed that our data for Oregon's tests was inconsistent and needed to be standardized in the `_with_multiples` columns after confirming with prison officials that they are in fact reporting the total number of tests administered and one person could be represented more than once in those figures.
- Ohio revised its death numbers after reviewing death certificates. We were able to back out two of the deaths very easily from our historic counts, and are asking Ohio for more information on how and when to uncount the other two deaths that mistakenly attributed to COVID-19.
- Kansas' Department of Corrections reports coronavirus testing data for one juvenile facility. For consistency of comparison with other state prison systems, we removed this from the historical data prior to Aug. 4
- Montana's number of prisoner cases for July 28 was incorrectly logged and has been fixed.
- Tennessee made a mistake in the number of prisoner tests it reported for July 28 and updated it after we brought it to their attention.
- Iowa's total number of cases for July 14, 21 and 28 did not include prisoner deaths. They have been added to those sums.
- Pennsylvania's number of prisoner cases for July 28 mistakenly included those on parole and has been updated to remove them from the count.

As always, please feel free to reach out, either here, or at info+covidtracker@themarshallproject.org, with any questions that arise as you dig into the data. We're happy to help.

## 2020-07-30
Howdy partners,
We have lots of news to share with you about this week's coronavirus updates. We see that yet again the number of new cases among prisoners hit an all-time high.

This week we also collected a new snapshot of the prison populations in June and updated our prison_populations.csv with snapshots from March, April and June. Part of that work was making sure that the population numbers we have match the same populations for which the prisons are reporting coronavirus testing and cases. We also wanted to ensure that we're comparing similar populations across states—adult, sentenced prisoners. For six states with unified prison and jail systems—Alaska, Connecticut, Delaware, Hawaii, Rhode Island, Vermont—we count testing and case numbers from both detainees awaiting trial and sentenced prisoners. Similarly, in Maryland, several pre-trial facilities in Baltimore City are included in the figures.

Along the way, we spotted some inconsistencies that led us to adjust some of our historical data to remove a handful of juvenile facilities or jails. Here's what we've done this week:

- Maine's number of staff deaths for the week of July 21 was wrong. It should have been 0 and has been corrected.
- Indiana’s Department of Correction reports coronavirus testing data for three juvenile facilities. For consistency of comparison with other state prison systems, we removed them from the data prior to July 28.
- Montana’s Department of Corrections reports coronavirus testing data for one juvenile facility. For consistency of comparison with other state prison systems, we removed this from the data prior to July 28.
- North Dakota’s Department of Corrections and Rehabilitation reports coronavirus testing data for one juvenile facility. For consistency of comparison with other state prison systems, we removed this from the data prior to July 28.
- Pennsylvania’s Department of Corrections reports coronavirus testing data for those who have been released on parole. For consistency of comparison with other state prison systems, we removed these tests and cases for prisoners from the data prior to July 28.
- South Carolina’s Department of Corrections has begun to report cases—but not testing counts—for prisoners held in “other locations,” such as county jails and hospitals, as of July 21.
- Wisconsin’s Department of Corrections includes three juvenile facilities in its coronavirus testing and case data.
- West Virginia’s Division of Corrections and Rehabilitation reports coronavirus testing data for those held in jails and in juvenile detention facilities. For consistency of comparison with other state prison systems, we removed tests and case counts for these prisoners and detainees from the data prior to July 28. We made an exception for the staff testing figures, the juvenile facilities and jails cannot be disaggregated from the totals.

This is a lot to keep track of. If you have any questions about the data, please feel free to reach out, either here, or at info+covidtracker@themarshallproject.org. We're happy to help however we can.

## 2020-07-23
Hello, friends. We've updated our `covid_prison_cases.csv` data and have a few changes to note. Some of our prison agencies have been undertaking audits of their systems to ensure they're only reporting unique cases. Others said they made mistakes in weeks past and needed to correct their data. Here are a few states to be aware of where historic data has been updated:

- Connecticut - For the week of July 7, the prisoner cases were revised after Connecticut identified some duplicates in the numbers.
- Delaware - For the first two weeks of July, our number of prisoner cases did not include deaths and has been adjusted.
Kansas - The number of staff cases for the week of July 14 was previously incorrect.
- Louisiana - The state said it provided the wrong number of staff tested for the week of July 14 and the number has been corrected.
- Massachusetts - This week, Massachusetts identified a case of a prisoner who tested positive and was counted twice in early April, so past weeks were adjusted to remove the duplicate.
- Michigan - Michigan said it has been auditing its testing numbers to ensure they are counting unique prisoners and not total number of tests, and adjusted their figures for prisoner tests downward again this week. They said they have finished their audit and don't anticipate future adjustments.
- Tennessee - The number we had originally been given for Tennessee's staff tests for all of July and much of June were total tests rather than unique people tested. We've now updated the number with new figures from the Department of Corrections.

As Erin Kissane of the COVID Tracking project tweeted recently, "everything is an approximation of an approximation." I'm working on focusing on my breathing.

## 2020-07-23
Hi, everyone. We received word from Rhode Island's prison population provided by the state's Department of Corrections that the numbers they provided for updated_prison_populations.csv were incorrect. Rhode Island, which has a unified jail and prison system, included pre-trial detainees in the total that should not have been counted, rather than just the sentenced population we asked for. The data has been updated to include the correct numbers.

## 2020-07-17
Hey, folks. We've received new figures from Vermont on its sentenced prison population and so were able to add that state into updated_prison_populations.csv. As with other states with unified systems, we have excluded numbers of pretrial detainees (those who would be in local jails in other states) from this count.

## 2020-07-16
Hi, everyone. With today's collection of covid_prison_cases.csv data, several states have made changes to their historic data to take note of:

Michigan undertook an audit of cases and found duplicates that needed to be removed from its unique numbers. As a result, the number of cases dropped by 219 from the previous week. As an additional result of the audit, the prisoner test numbers fell by 717.
In Maryland, the number of prisoners tested dropped by 184 this week. Officials there did not respond to questions, but we are inquiring why the numbers fell so steeply.
In Connecticut, the state conducted a recent internal audit that identified duplicate tests in their counts. As a result, the number of prisoners tested dropped by 100, the number of cases dropped by 3 and the number recovered dropped by 9.

## 2020-07-16
Hi all! The data has been updated to include a sheet of prison population figures from March and June, to help newsrooms localize this story, which published today, July 16: https://apnews.com/9899b08a66a60f3106b563eb07c92c40

## 2020-07-10
Hi everyone. We've updated this week's data, which came with several adjustments to previous weeks' information that arose in the course of our reporting. These are all flagged in the "notes" field, but we want to be certain to bring them to your attention as well here.

New Mexico has updated its staff and prisoner case numbers over the past several weeks after they incorrectly reported them to us. The new figures for 6/9, 6/17, 6/23, and 6/30 are reflected here.

In West Virginia, an earlier version of this spreadsheet included testing figures for detainees in jails and juvenile facilities. For consistency with other states, we've limited the numbers for 6/30 to prisons and work release centers.

At the end of June, Vermont said it had inadvertently counted some small number of prisoners with positive cases more than once for the weeks of 6/2, 6/9, 6/16, 6/23 and 6/30. We've since revised those weeks' prisoner case counts accordingly.

In early July, Rhode Island began releasing information on "presumed positive" cases, which we are not including in these numbers and prompted us to revise our counts. For earlier weeks, we are reexamining the figures to try to remove the "presumed" cases from the counts and are dropping those figures for 6/18, 6/10, 6/1, 5/28, 5/20, 5/12, and 5/6 for now until we can get more accurate counts.

## 2020-06-04
Hey everybody, we have a few notes about today's prison coronavirus update. First, as you may have noticed, we've moved our data collection day up. We're now going to prisons on Tuesdays, in order to make it easier to get the most answers vetted and available for users during the week. We've also made a few small changes to past weeks of data, which are flagged in the "notes" field.

Revised past weeks of Texas staff testing numbers, which were overcounts.
Changed 5/27 Arkansas recovered counts, which it turned out included deaths.
Iowa adjusted its recovered counts for 5/27 after a prisoner later tested positive again.
We learned that Louisiana adjusted its staff case counts on 5/27, because its earlier figures had in some cases included multiple tests for an individual.

## 2020-05-22
Hi, everyone. We've updated our weekly coronavirus prison data today, May 22. There are two changes to the structure of the data that you should take note of. We have split our staff_tests and prisoner_tests each into two columns. We decided to do this after finding two states, Arkansas and Vermont, were unable to provide the unique number of prisoners and staff tested for coronavirus, but only the total number of tests administered. This seemed counter to how most states handle this figure, so we moved the data for those weeks where they had this policy into the separate staff_tests_with_multiples and prisoner_tests_with_multiples columns—meaning a single staff or prisoner could be counted multiple times in these numbers—so that it's still accessible to you. The new layout includes these column definitions:

* `staff_tests` - The cumulative number prison employees, including correctional officers and other staff, tested.
* `staff_tests_with_multiples` - The cumulative number of tests administered to prison employees, including correctional officers and other staff where unique patients was not available.
* `prisoner_tests` - The cumulative number of incarcerated people tested.
* `prisoner_tests_with_multiples` - The cumulative number of tests administered to incarcerated people where unique patients was not available.

## 2020-05-15
Hi, we’ve updated the weekly coronavirus prison data today, May 15, and wanted to note a few changes you should be aware of:

The population of prisoners in Montana in April in earlier releases was incorrect.
In past weeks, Vermont published the number of tests conducted of prisoners. For the first time, we now have the number of individual prisoners tested, so that number has dropped from previous releases.
Past weeks of data for the federal Bureau of Prisons now include recovered patients, which been excluded. Starting on May 13, we now also include in our totals cases at privately run federal facilities, which the agency began to publish after The Marshall Project reported on their absence.
On May 14, Texas began releasing information about surveillance tests of asymptomatic patients that had not been previously noted. At the same time, Texas has undertaken a new swatch of testing in many of its facilities. The two changes combine for a large jump in tests this week.
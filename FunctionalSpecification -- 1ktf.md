Functional Specification — 1000truefans (1ktf)

This is the outline for the development of the 100truefans website/webservice.
=============
Overview
1000truefans.com is a social media fanbase participation tool/service that allows fans to dedicate a portion of their social media feeds to an artist they want to support. Fans give limited permissions to the artist to auto-retweet, like, +1, or otherwise re-share artist content. Fans will eventually be able to limit the channels, number, or types of posts that will be auto-shared. The purpose is to allow fans who truly support and trust an artist to save time in showing their support for the artist. 

This spec is not intended to be complete or final. It is designed to describe the absolute minimum viable product that functions in support of artist and fan goals. Features for future versions are indicated in the roadmap below as ROADMAP but are NOT required for publishing/shipping.

The spec does NOT reference technical issues except to the extent that they are design issues and recommendations or ideas. All technical issues are reserved to a later date and practice.
=============
Scenarios.

1. Artist service providers (manager, agent, lawyer, PR) want to support artist but do not want to spend the time necessary to follow the artist throughout the day across social media channels. This way, they can share updates automatically with minimal effort.

2. Fan of artist works at a job where social media access is limited or not available. Rather than wait several hours to share content, fan can auto-share during the day to help the artist gain traction across channels.

3. Ardent supporter of charity (e.g., parent of child at private school for children with autism or parent of child with leukemia) can save time and show support by making initial decisions to auto-share relevant updates.


=============
Functions/features

Fan-side
Select channels
Select types of messages
Limit volume of messages.
seek authorization


Artist-side
authorize artist [needed? do searches (from midterm project spec) to identify candidates]
offer channels
propose packages (pre-set configuration options [adds ease of development])
authorize users to participate
identify key hashtags to trigger 1KTF (This <https://twitter.com/1Ktf> is taken :-(



Fan workflow:
select artist
ask to share
agree to share


1. Message to tweet
a. could be pre-set initially as testing.
b. next version selectable among preset options
c. next version: user-created

2. Time to tweet
a. could be fixed time (noon)
b. could be set of fixed options
c. could be user-selectable
d. could be random
e. could be random within windows (i.e., during work hours, after work)

3. Frequency/repetition
a. could be single time (only once, literally)
b. single time per day
c. multiple times per day (doesn’t this affect #2, time?)

a. single time, same or next day.
b. set number of days in row
c. selection from fixed alternative schedules (every day, every other, every third)
d. random schedule
e. user-selectable schedule
f. supermemo-like schedule (use basic default, e.g. fibonacci seq)

4. delivery mechanism
a. twitter — based on supposition that there is an API that is easily used by my skill-level of programmer.
b. email?
c. sms? Google SMS?
d. other choices? like what?

5. tracking behavior
a. display list of times/dates/messages
b. export list of times/dates/messages
c. select formats for export (CSV, excel)
d. what about input from other behavior (the dependent variable?) This should be beyond the scope of the tool and be part of some other system of personal data collection.
=============


Next: loose wireframe on paper.

Phase 1 gem (easier)
https://github.com/tweetstream/tweetstream

Phase 2 gem
https://github.com/sferik/twitter

Phase 3 FB or G+; Phase 4 the other one
# Track Fires

Data on New York City subway track fires received from the MTA in response to a July 2014 FOIL request. Covers the time period January 1, 2001 through October 30, 2014.

## Contents

`track-fires.csv` is a CSV of 9,593 individual track fires.

## Columns

* `Date`
* `Proximity to Station` - `I` for inside the station, `N` for north of the station, or `S` for south of the station.
* `Station`
* `Item Burnt`
* `Comments`
* `Fire Severity` - a numerical value from 1 (lowest) to 4 (highest)

## Notes

The value of the `Item Burnt` column is probably not consistent enough for any bulk analysis.  For example, the comments may describe a case where some trash catches fire, which then results in an insulator catching fire.  The item burnt may be listed as `DEBRIS`, `REFUSE`, `INSULATOR`, `PORCELAIN INSULATOR`, or something else.

Two rows erroneously list the item burnt as `DUMMY - Do Not USE`.

An MTA representative wasn't able to confirm that a severity value higher than 4 is impossible, but the MTA monthly reports appear to corroborate that 4 is the highest possible value, not just the highest value listed in this data.

The Forest Hills-71 Av station and its surrounding area has fairly consistently been the site of the most track fires, mostly minor debris fires.  We asked the MTA if they have investigated this or had an explanation, and received the following from a spokesperson:

*"The location you are referring to involves the Manhattan bound express and local tracks.  Many of our customers bring newspapers, coffee cups etc and wait for their morning train.  Trash cans on a busy station such as this with service every 90 seconds can overflow rather easily.  Some customers lay trash on top, others leave trash on the seats on the platform where it eventually finds its way to the tracks.  Additionally, there is an ongoing signal contract in this area with a lot of chipped out track with catch points and traps for debris.  The diamond crossover at the south end of the station has had many third rail components replaced.  Track cleaning has moved their station cleaning into the interlocking and we are now paying special attention to debris in the crossover and around end approaches, where cleaning is performed."*
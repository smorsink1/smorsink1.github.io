---
layout: post
title:  "Track Performance and Mile-and-a-Half Speed"
date:   2020-07-16 23:58:49 -0400
---

### Ryan Blaney's speed on 1.5-mile tracks and past performance at Texas Motor Speedway will make him a force to be reckoned with on Sunday.

(Thanks to https://www.racing-reference.info and https://www.nascar.com for the raw data)

When evaluating a driver's strength at a racetrack, fans and analysts often look for wins. If a driver pulls off a win, it probably means that their team had a good setup and that they drive the track well. Both their affinity for track and that of their team will likely carry into the future, leading to more good finishes at the track.

Fans and analysts aren't far off. It's tough to win a NASCAR Cup Series race, and winners perform well at future races. And performing well on a track isn't a fluke: most drivers reliably over-perform at at least one track.*

But focusing on wins alone isn't a great practice. By only looking at wins, you're throwing away a lot of potentially useful data, like where a driver finished. Also, not all drivers are in a position where winning races is a realistic option (in fact most are probably not). To get a better idea of track-specific driver performance, I decided to look at past finishing positions relative to how you would have expected the driver to perform.

Finishing position is not without its flaws (a forthcoming post will analyze the randomness in finishing position), but this approach gives us a more comprehensive view of driver performance at a track than we'd get by just focusing on wins. To reduce some randomness, I only focused on finishing positions in races where the driver completed the race, excluding races where largely random events outside of the driver's control prevented them from finishing.

To form an expectation of how a driver performs, I used their finishing positions from other races in the same season. If a driver usually finishes 25th, but finishes 6th at a specific track (and maintains this over-performance over a number of races), then we can conclude that the driver is good on that specific track. However, if a driver usually finishes in 3rd, but finishes 6th at a specific track (consistently over a number of races), then we're led to the opposite conclusion: this driver is probably not good at this track. This highlights the importance of adjusting for expectation: we can learn more about two drivers' track-specific performance even if they have the same finishes by looking at their typical finishes.

Looking ahead to Sunday's race at Texas Motor Speedway, here’s a look at the best and worst performers at Texas. We’re only looking at active drivers who have finished at least 5 races at Texas. You’ll see the driver’s average over-performance (how many spots better they finish at Texas compared to their average season finish in races not at Texas), as well as the upper and lower confidence interval on that average. This gives you an idea of how confident the data is in the average over-performance number - a wide confidence interval means there’s still a lot of uncertainty about the driver’s over-performance.

| Driver | Mean Over-Performance | Upper CI | Lower CI |
| --- | --- | --- | --- |
| Erik Jones | 7.0 | 12 | 1.9 |
| Ryan Blaney | 6.0 | 11.9 | 0.1 |
| Martin Truex Jr | 5.9 | 7.9 | 3.9 |
| Matt Kenseth | 5.0 | 7.5 | 2.4 |
| Jimmie Johnson | 4.9 | 8.1 | 1.7 |
| ... | ... | ... | ... |
| Matt DiBenedetto | -0.4 | 3.8 | -4.7 |
| Ryan Newman | -0.4 | 2.4 | -3.2 |
| Alex Bowman | -0.5 | 5.1 | -6.1 |
| Brad Keselowski | -0.7 | 4.5 | -5.9 |

Erik Jones and Ryan Blaney have considerably outperformed expectations in their limited races at Texas (Jones has finished 6 races at Texas, Blaney has finished 7). Notably, there is  uncertainty about their true average over-performance: it could well be that Ryan Blaney's true average over-performance at Texas is just 0.1 spots (by the same token, it could also be that Blaney's true average over-performance at Texas is 11.9 spots). Veterans like Martin Truex Jr, Matt Kenseth, and Jimmie Johnson have also performed well relative to expectations in the past at Texas. There is more certainty in the veterans' true average over-performances.

Another relevant data point when projecting a driver's performance at a given track is how fast their car has been on similar tracks. Unfortunately, with limited historical lap time data, I can't rigorously analyze whether having a fast car at a certain type of track predicts having a fast car at similar tracks. However, it stands to reason that teams that have excelled at setting up cars for other 1.5-mile tracks (Las Vegas, Charlotte, Atlanta, Homestead, and Kentucky so far this season) will continue to do so in Fort Worth on Sunday.

Here's a look at the fastest teams at mile-and-a-half tracks so far this season. They're ranked by the average Nascargraphs speed ranking of their cars at the 1.5-mile tracks. Also included is their performance on 1.5-milers relative to non-1.5-milers (a +5, for example, indicates that the team's average Nascargraphs speed ranking is 5 spots higher at 1.5-mile tracks than at other tracks).

| Owner | 1.5 Mile Speed Rank | Relative Performance |
| --- | --- | --- |
| Roger Penske | 6.1 | +4.9 |
| Rick Hendrick | 9.6 | +3.4 |
| Richard Childress | 12.9 | +7.1 |
| Joe Gibbs | 13.2 | -0.5 |
| Wood Brothers | 13.8 | -1.0 |

Penske cars, in addition to being fast overall, are particularly fast at 1.5-mile tracks this season. Hendrick cars have been fast too, also outperforming their other track performances at 1.5-mile tracks. Richard Childress cars have really stepped up the speed at 1.5-milers. On the other hand, Joe Gibbs and the Wood Brothers cars have been a tad slower at 1.5-milers than at other tracks, though their overall speed is still competitive.

Here's another breakdown of average speed rank at 1.5-milers vs non-1.5-milers, but this time for specific cars.

| Car Number (Driver) | 1.5 Mile Speed Rank | Relative Performance |
| --- | --- | --- |
| 9 (Chase Elliott) | 3.8 | +4.9 |
| 12 (Ryan Blaney) | 4.5 | +6.4 |
| 22 (Joey Logano) | 5.8 | +5.7 |
| 4 (Kevin Harvick) | 6.0 | +2.7 |
| 19 (Martin Truex Jr) | 7.5 | +5.8 |

So, not only is Ryan Blaney one of the best over-performers at Texas Motor Speedway, he also has the second-fastest car on 1.5-mile tracks in the series (Chase Elliott, the only driver with a faster 1.5-miler car than Blaney, has over-perfomed slightly at Texas in the past, averaging an over-performance of 2.6 positions). Furthermore, the over-performing speed of other Penske cars at 1.5-mile tracks suggests that Blaney's speed on tracks similar to Texas is no fluke.

There's obviously a lot that goes into each week's race, and a lot of uncertainty in the outcome. But between his past performance relative to expectation at Texas, and the 12 car's speed on 1.5-milers this season, Ryan Blaney could be poised for a big day on Sunday. Martin Truex Jr also has the combination of strong previous performances at Texas and a fast car on 1.5-milers. Hendrick cars have been strong on 1.5-milers: Chase Elliott and Jimmie Johnson (+4.9 positions average over-performance at Texas in the past) could get up in the mix as well. Oh, and there's also a guy named Kevin Harvick.

Notes:

\* In a sample of 80 drivers with significant race experience, 75 of them had mean performances relative to expectation that were significantly above than zero at at least one track. We extrapolate to say that roughly 93% of drivers over-perform (relative to how you'd expect them to perform based on their season results) at at least one track.

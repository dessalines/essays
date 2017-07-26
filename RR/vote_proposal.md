I have two proposals having to do with the way national holds votes. 

1. Switch away from the representative(grouped) voting that we do now, to individual, low-level voting (direct democracy).
   - Instead of waiting for branch delegates to report that they've received enough, we can simply wait for a quorum of all members(maybe once 1/2 or 2/3rds of all members have voted, then it can pass)
2. Switch to range or approval voting.
   - We could either create (or use the one we already have) a private facebook group for approval voting.
   - Or use [this site called simplevote, I built for us to use(a sample poll)](https://simplevote.ml/#/poll/QL5)

# 1) Doing away with representative voting

## Why representative(grouped) voting is bad

**A candidate with fewer votes can win** in a grouped voting election. Here's an example. 

Election on which is the best color, yellow or blue?

- 15 voters are grouped into 3 groups, A, B, and C, and 3 seats can be won. 

Ballots: 

| Voting group | Yellow | Blue |
| ------------ | ------ | ---- |
| A            | 2      | 3    |
| B            | 5      | 0    |
| C            | 2      | 3    |

Election:

| Candidate | Votes | %    | Seats won | Seats won % | % Error | Single-winner seats won | Single-winner seats won % | % Error |
| --------- | ----- | ---- | --------- | ----------- | ------- | ----------------------- | ------------------------- | ------- |
| Yellow    | 9     | 60%  | 1         | 33%         | 26%     | 0                       | 0%                        | 60%     |
| Blue      | 6     | 40%  | 2         | 66%         | 26%     | 1                       | 100%                      | 60%     |
| Sum       |       |      |           |             | 53%     |                         |                           | 120%    |

Blue wins, even though it got 3 less votes than yellow.

This is called the misrepresentation error, ~53% error in this election if we gave out 3 "seats", or 120% if its a single-winner. 

`misrepresentation error = sum(abs(percent_of_seats_won - percent_of_actual_votes))`

[Here's](https://docs.google.com/spreadsheets/d/1u8EAJWnNGhmOj1CaJyAL_XVXY6vqPGkb7E3Go3ZEoSA/edit#gid=0) an example of the misrepresentation errors for the 2017 UK election.

## Why was it used in the first place?

Representative voting **was** because it made it easier to tally votes with a small number of representatives, traveling across long distances to tally up a vote. So one state's rep could show up at a national convention, instead of every voter in the whole state. This isn't necessary nowadays, where we can place and tally up votes online. 



# 2) Switching to range voting

## What is it?

I've built a site that uses it called [simplevote, it might just be easiest to see it in action for a poll I set up for us](https://simplevote.ml/#/poll/QL5). We could easily use this for national, and I can tweak it for our needs. 

- [Range voting](http://rangevoting.org/UniqBest.html) is olympic score voting, so each voter chooses between `0-10` on candidates, with 10 being yes / liking, 5 being neutral, and 0 being no / dislike. 
- **You don't have to vote for every option**, not voting won't hurt your current votes.
- Range voting beats out [approval (a subset of it)](http://rangevoting.org/AppExec.html), [IRV](http://rangevoting.org/rangeVirv.html), and [First past the post](http://rangevoting.org/Plurality.html) for [minimizing voter regret.](http://rangevoting.org/UniqBest.html).  

![](https://miracleon32ndstreet.files.wordpress.com/2010/12/image12.png)

To calculate the winner(s), you take the average(s) for each candidate and rank them from highest average to lowest. I've coded different voting systems (STV, IRV), and they're much more difficult to calculate and explain, and less expressive in general. It also beats those even when voters are being dishonest, but for some reason they've found that voters are less likely to be dishonest when using range voting (probably because you have more choices). 

You can learn more about range voting at [rangevoting.org](http://rangevoting.org/).

# Additional issues

- How do we decide when a quorum(minimum # of voters) is reached? Maybe 1/2 of all members, 2/3rds, or 3/4ths, before it gets certified. 
- How long do the elections last? (1-2 weeks seems like a good default)
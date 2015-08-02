# EmotionalVoting

An app for voting on what you like the most.

## Motivation

I have seen many apps that enable voting or store data for polls, but I have not found one that does exactly what I want.  If you know of an app that fits the description of this app, please let me know :smile: .

## Example: Choose a project name

What starting a project, it can be good to actually name it to give the participants a sense of what the purpose of the project is.  All participants should have the right to propose suggestions for the project name, but when there are too many suggestions, it becomes very hard to find the best one.

A plain discussion can work, but strong personalities will influence the choices of others even if their suggestions are not the best.  The solution to this is a secret vote, so each participant can vote on the suggestion she likes the best without fear of offending the others.

### One suggestion per participant, one vote per participant.

Most often, participants will like their own suggestions best, so if each participant only gets to submit one suggestion, and only gets one vote, the result is likely to be that each suggestion gets only one vote (from the one who submited it).  One way to try to work around this is to deny votes on suggestions you have submitted yourself, but then the result may be wrong if you actually change your mind and don't like (all of) your suggestions after you submitted them.

### One suggestion per participant, multiple votes per participant.

One way to avoid the one vote per suggestion is to give multiple votes per participant.  People could still put all their votes on their own suggestion, but that can be avoided by only allowing one vote per person on each suggestion.  This should lead to the most liked suggesitons getting the most votes, but it limits the creativity of the participants.  Typically some participants will have no suggestion or maybe one while other participants will have many excellent suggestions.  This creativity should be welcomed, not suppressed.

### Multiple suggestions per participant, multiple votes per participant.

So, enabling creativity by allowing any number of suggestions and giving multiple votes sounds good, right?  But to make things practical, you have to limit the nuber of votes, and when the creativity is high, you get many suggestions, and the votes get thinned out so it is likely that they are spread out and suggestions will have few votes and the result becomes pretty random because you can win by having one more vote than the second best choice.  Also there will be less consensus since there will be MANY more votes for OTHER choices than the winning one, just not on the same contender.

### What about disliked suggestions?

In addition to finding a suggestion that is popular, voting should try to pick up if a suggestion is UNPOPULAR.  I would like the voting system to reflect that "I like THIS suggestion best, but I like ANY suggestion better than THAT!".  I would also like the system to make the voting group have as strong consensus as possible.

### Like the presidentional voting in France?

Please correct me if I am wrong here.  I want to learn :smile: .

When voting for a president in France, there are lots of candidates, and voting starts by everyone voting for their favorite.  After the first round, unless there is a 50%+ majority for any candidate, the candidate(s) with the least votes are removed from the contest, and there is a new round of voting where everyone gets to vote for their favorite of the remaining candidates.  If there is as 50%+ majority, a winner is announced, else the candidate(s) with the least votes is again removed from the contest, and there is a new round of voting.

This repeats until a candidate get over 50% of the votes, often the last vote has only two candidates.  That means that EVERYONE gets to vote for or against the actual candidate that wins (or abstain from voting).  This gives a nice warm feeling that YOUR vote counts.

### Any number of suggestions per participant, priority voting

Here is my suggestion:

Let every participant be allowed to add as many suggestions they want until the voting starts.  Then each participant gets presented the list of suggestions in random order (or alphabetically?).  The voter then must order the suggestions by how much they like each suggestion.

| Voter A | Voter B | Voter C | Voter D |
|---------|---------|---------|---------|
| name 1  | name 2  | name 3  | name 4  |
| name 3  | name 4  | name 2  | name 2  |
| name 2  | name 1  | name 4  | name 3  |
| name 4  | name 3  | name 1  | name 1  |


When voting is completed, we try to find a winner by looking at the suggestions at the top of everyone's list.  If a suggestion is at the top of over 50% of the voter's lists, we have a winner!

If no suggestion is at the top of over 50% of the voters, we start removing the topmost suggestion of some of the voters list.  We remove the least voted for suggestion that is at the top of the voter's list.  This will move the second most favorite choice up to first place.


### Optional

#### Limiting the number of suggestions

The final number of suggestions could be limited before voting to make scanning them not too difficult.  In that case the participant with the most suggestions will have one or more of their suggestions removed from the contest.  This requires each participant to prioritize their suggestions before voting starts.

#### Limit who can add suggestions

In some use cases, the people who should be allowed to submit suggestions will not be the same people allowed to vote.

#### Mark suggestion as "not acceptable"

In addition to order each suggestion by how much you like it, voters can mark a suggestion as "Not acceptable".  This makes it possible that the winner does not actually get 100% of the votes in the end, and the actually percentage is a reflection of how many of the voters felt this suggestion was at all acceptable.  A low number indicates poor consensus.

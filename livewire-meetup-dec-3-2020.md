# Livewire Meetup Dec 3, 2020

### Attendees
| Discord | Twitter | Github |
|--|--|--|
| @roni | @roniestein | @roni-estein |


### Fact-Checkers
| Discord | Twitter | Github |
|--|--|--|

## Topics

#### Updates to Livewire,
 @liam's contribution to the alpine entangle side

#### JSON fields manipulating them searching on them 
- using DTO’s both 
	- Spatie
	- Jess archer

#### Tall Forms
- Updates to tall forms
- Tina has put out some "good" YouTube videos
	- These focus on using tall forms from someone with amazing skill and expertise
	- If people are using tall forms, please consider sponsoring Tina; if her work saves you hours and you are using it to make money, it's a fair exchange, and it enables cool people to make tools that enable you to get stuff done.

- I have put up some "bad" YouTube videos.
	- These focus on using tall forms from scratch with no rehearsal. Just reading the docs and discussing the setup.
	- It does have a great way to set up your livewire environment for testing.
	- Also, all my videos are "totally cold turkey with no prep and not even a good mic."
		- I'll accept sponsorship towards screen casting equipment if you think you'd like to see more casts.

#### Livewire Newsletter
Liam runs a livewire newsletter; it's awesome and useful. If you want to contribute something, please contact him.

#### Hacks for optimizing search results in JSON and larger text fields
- We spoke at length on JSON and text fields on several projects. Tina @stockholm on the discord server brought up a great idea about making a search text field on your table and a related search keys table for your non "easily searchable" fields. You could manually update your search keys every time you update your data or make an observer that automatically does it for you on model update. 

#### Breeze Vs. Jetstream
- Discussion on what the differences were
- We didn't dive code.
- Jetstream
	- Teams
	- Forced device logout via session and ideas on where it could be used
	- Teams are weak sauce.
	- Can only belong to one team (I haven't verified this)
		- User->currentTeam I think people said, but if that were true, it would imply that the user could actually belong to many teams at a time but only access data for one team at a time, which for me is actually fine, and not weak sauce as it were. Will dig deeper between project; however, other people are free to discuss and improve this.
- Breeze
	- No teams.
	- No default livewire setup; not an issue takes 2 seconds, but I'll cover that in a video.
	- Everything is published right there into your app, and it's like laravel/ui with TailwindCSS.
	
## Contributing

Please PR to this repository if you were at the meeting, and you remember topics that I don't or points that I didn't bring up. (NOTE: Also also left for half an hour)

Please contribute points that you or someone brought up. If you source dive and research and show something is true or false, please PR that too.

Please add your Discord/Twitter/Github usernames to the PR under attendees or fact-checkers, and beside the item.

Lastly, I'm not "TWITTER" personality, But please consider following [me](https://twitter.com/roniestein)  to help get this information out to the laravel / livewire community. I rarely tweet. I only tweet code tweets and the odd comment on something funny. Scouts honour.
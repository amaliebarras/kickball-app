#User Studies
##Set 1 - Kickball 

###Personas 
####Lindsey D - 22, Female 
UT Sophomore socialogy major, from Iowa and new to Austin. Coaching so she can make friends. She wears shorts and t-shirts always and lives on campus. She's often got her headphones in jammin' to 90s Brooks & Dunn songs. 

####Matt C - 31, Male
Accountant in Miami, florida. Introvert who just loves sports and no one else wanted to coach. He has a lab mix named Bax but no kids. He eats Chili's probably too much, and is currently re-watching Louie Season 3. 

####Eileen M - 51, female. 
Eileen has two grown kids. She mostly shops at Kohl's and wears a lot of the color turquoise. She has an iPhone and is pretty tech savvy for an older lady (or she likes to think so). She's an early bird. 

### User Stories
As a team captain, I need to receive notifications so I can give my team updated information. 

As a team captain, I need to be able to forward notifications to my team quickly so I can relay information at a moment's notice. 

### Scenarios

Matt had a late night last night and is feeling pretty crappy today, which sucks because he has a playoff game later. He's trying to decide whether to have a mimosa brunch with his bro, or just take it easy so he can bring his A game tonight. It depends on who he's playing - the Lake Austin Otters (we got this) or Pleasant Valley Parrots (oh shit.) 

Lindsey had a super crazy day at work today and didn't notice that there was a 80% change of thunderstorms. It's 5 and there is a practice at 6. The team really needs to shape up before the big game Saturday, and she only wants to cancel if the league makes her, but the league hasn't sent any notifications so she wants to let her team know as soon as she knows. 


### Use Cases

1. Check weather app again
2. Close weather app
3. Go to league announcements page
4. refresh
5. refresh
6. oh, there's a subscribe button
7. subscribe to updates
8. wait
9. receive update
10. read prompt to dismiss or share with team
11. hit "share"
12. prompted to add text "looks like we have to cancel tonight, stay tuned for practice reschedule"
13. hit send
14. confirmation displayed


### User Flow 

// = Displayed to user

~ = Action taken by user

	//Receive notification
	~Dismiss 
		//End Flow
	~Share
		~Add text
			//Confirm? 
				~Yes
					//Confirmation Screen
				~Cancel
					//Back to Receive Notification Screen
		~Just Send
			//Confirm? 
				~Yes
					//Confirmation Screen
				~Cancel
					//Back to Receive Notification Screen
					

## Funny-Boys

y'all ever met a funny boy? a funny boy is someone with a _personality!_

####  Bro Jogan
 - Ex Motorcycle Wrestler  
 - Fascinated with the medicinal effects of loose leaf tea  




You make a buncha Funny Guys
it can be hard at first, so you can probably grind their bits up
throw your fnny gys into the grinder
You'll get back some amalgamation of those parts, and the rest will be s c a t t e r e d   t o   t h e   w i n d s
 -
All Your Funny Guys have stuff they wanna do. They can change their minds later but they should probably know what they want. For each of the guys, as they go on their goals they'll get into 'sitches. A sitch is some roadblock on the Funny Guy's goal. When it comes up, you'll have to figure out what they'd do next. Most Funny Guys get tunnel vision, so it's hard to suppress their motivation into a docile state. When a problem comes up and you don't know what to do, take some time away from your Guy and help another along their path. Funny Guys tend to get stronger as they do hard stuff and collect stories, so wherever you guide them, they will repay you for your help in power, experience, and friends..
-
Most Importantly, remember the wind. Whoever leaves you never really goes away. In fact, even in this place between time, there is no giving which is necessarily also receiving. Do not grow weary of her call.


1. make main page
2. make sitch generator
3. make guy generator
4. make useracc generator

sitch:
	id int not null primary key,
	title text, 
	desc text, 
	lastSitchId int,
	nextSitchId int default NULL,
	instructions text,
	state varchar default "s"
	players varchar,
	sitchmaster int 

user:
	id int not null primary key,
	uid varchar not null,
	mail varchar not null,
	pass varchar not null
	#each user has a table named uid."-guys" containing a list of all the guys they take care of

guy:
	id int not null primary key,
	name text, 
	desc text, 
	currentUser int default 0, #references user(id),



yourGuys()
{

}

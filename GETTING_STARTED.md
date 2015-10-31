#GaSiProMo

Welcome to Galactic Side Project Month! We'll be working on our own side projects through the month, using GaSiProMo as a way to stay motivated and share what we're doing.

This doc explains how to get started and how to keep in touch with other people through the month. If you have any questions, [email me](mailto:raj@codelympics.io)!

* [Set up](#setup)

* [Share progress with a weekly log](#log)

* [Chat rooms for GaSiProMo](#touch)

* [DevPost](#devpost)

##Set up<a id = "setup"></a>

###Create your GaSiProMo repo
1. Fork the [GaSiProMo repo](https://github.com/codelympics/GaSiProMo) on GitHub. This is where your project will live for the duration of GaSiProMo, and how we'll share updates.

2. Write something in the README.md saying what you're making. Once your readme isn't blank, it should appear in the GaSiProMo [project gallery](https://codelympics.io/projects/3/gallery) (it may take up to an hour). 

3. If you'd like to work in a group on a project, check out this Reddit [thread](https://www.reddit.com/r/codelympics/comments/3ox4o8/gasipromo_post_for_people_looking_to_make_or_join/).

### Mirror an existing project (optional)

If you want to keep working on an existing project, that's really easy. After you fork the GaSiProMo repo, set it up as a [mirror](https://help.github.com/articles/duplicating-a-repository/) to your existing project. 

Here's how I did it for my project For or Not. 

	$ cd fogornot
	# This is the directory where my project currently is. This should already be linked to an existing GitHub repo.

	$ git remote add --mirror=push gasipromo https://github.com/webmasterraj/GaSiProMo.git
	# Replace 'webmasterraj' with your GitHub id
	
I'll keep working in my usual project directory. But now when I push updates, I just add a second command to also push to the GaSiProMo mirror:

	$ git push && git push gasipromo


##Share progress with a weekly log<a id = "log"></a>

To share progress on your project, you can keep a weekly log on your README, so people can see the latest status on the project gallery.

**You should try to share an update on your project by Thursday each week**. I'll be sending out an email at the end of the week for people to check out GaSiProMo projects.

I set up my README for For or Not as an [example](https://github.com/webmasterraj/FogOrNot/blob/master/README.md). 

* I put the latest updates at the top, so that people don't have to scroll down to find them. 
* I also like writing longer entries. But I didn't want to clutter the readme, so I'm keeping the log entries on the readme short and linking to longer versions in a separate `project_logs` folder.
* I'd also suggest having a way for people to give you feedback. I created a Reddit thread on [/r/codelympics](http://www.reddit.com/r/codelympics) for public feedback, but you could also use your email or another private mode.

(If you mirrored an existing project, you will need to share the updates on your original README. If you don't want to do that, then feel free to keep working on your project separately, i.e. not mirrored, and use the GaSiProMo readme as a separate project log to share updates). 

##Chat rooms for GaSiProMo<a id = "touch"></a>

###[Gitter chat room for GaSiProMo](https://gitter.im/codelympics/GaSiProMo)
I set up this room for us to chat. It's like a public Slack room, where we can share things and ask for feedback/help.

###[Codelympics subreddit board](http://www.reddit.com/r/codelympics)
You can post stuff here too.


##DevPost

[DevPost](http://devpost.com/) has set up a #gasipromo tag for people who want to share their projects there too. Here's how to do it:

1. Set up an account on [Devpost.com](http://devpost.com/)
2. From your portfolio of the home page click “Start a Project” 
3. When you create the project add the tag “gasipromo” under the “Built With” Section
4. Done! Your project will be listed here: http://devpost.com/software/built-with/gasipromo

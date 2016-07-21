### What Is This App?

 * This app was created in response to [this blog challenge](https://betterologist.net/2016/07/you-are-a-failure-full-stack-2016-if/) to become a true 2016 full stack developer.
 * It is mostly a template created app, with Polymer's own google-signin component added.
 * It is made in response to the need for a HelloWorld app with **Authentication**
 
### HelloWorld Google-signin

To run this app as a HelloWorld, you'll need to do some setup first. What follows may be the easiest way:

 * Install [Polymer CLI using these instructions](https://www.polymer-project.org/1.0/start/toolbox/set-up#install-the-polymer-cli)
 * run **polymer serve** to see it running on your box
 
You can now inspect the code, and get to a spot where you implement your own quick HelloWorld.
 
### Is there an online demo running?

Yes. [ttfhw2.datafundamentals.com](https://ttfhw2.datafundamentals.com)

### How This App Was Created

This base app was created by [Polymer CLI using these instructions](https://www.polymer-project.org/1.0/start/toolbox/set-up#install-the-polymer-cli). See more details on this portion [here](aaa_UI_2016_state_of_the_art/blob/master/NOTES.md).

I then got a [google-signin cert from this site](https://developers.google.com/identity/sign-in/web/devconsole-project).

Then, [this documentation on the Polymer google-signin element](https://elements.polymer-project.org/elements/google-signin) led me on my way. The code to consume google sign-in was added manually.
I also found [this](https://developers.google.com/identity/sign-in/web/people) to be quite helpful.

### How to Isolate the Authentication Code?

This code is virtually isolated within my-view1.html. If you really want a clear view of the auth code, do a diff on my-view1.html and my-view2.html.

There is also one line within bower.json which you will need.

### Why were these technologies chosen?

The argument for Polymer is made in [aaa_UI_2016_state_of_the_art NOTES.md](https://github.com/TTFHW/aaa_UI_2016_state_of_the_art/blob/master/NOTES.md) 
which is identical to this project, except for the added authentication piece.

**Google-signin** is one of many available, including too many to mention here. 
It was chosen primarily because tight integration with Polymer is already provided.
The fact that almost everyone already has a google login is an extra benefit.

### Why wouldn't I roll my own Authentication?

15 years ago rolling your own was a perfectly good idea. 
Modern security needs have moved radically beyond what can be accomplished in a
few hours by a non-specialized developer. 

All I care about is getting a unique, consistent, well managed id-token, for each user. How that is accomplished is better
left to experts with their rather extravagent budgets, covering every corner case and need.






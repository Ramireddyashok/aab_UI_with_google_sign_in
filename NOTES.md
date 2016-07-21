### What Is This App?

 * This app was created in response to [this blog challenge](https://betterologist.net/2016/07/you-are-a-failure-full-stack-2016-if/)
 * It is basically a template created app, with Polymer's own google-signin component added.
 * It is made in response to the need for a HelloWorld app with Authentication

### How This App Was Created

This base app was created by [Polymer CLI using these instructions](https://www.polymer-project.org/1.0/start/toolbox/set-up#install-the-polymer-cli).

I then got a [google-signin cert from this site](https://developers.google.com/identity/sign-in/web/devconsole-project).

The code to consume google sign-in was then added manually.

### Why were these technologies chosen?

There may be more about this in the [aaa notes](https://github.com/TTFHW/aaa_UI_2016_state_of_the_art) 
which is identical to this project, except for the added authentication piece.

Google-signin is one of many available, including too many to mention here. 
It was chosen primarily because tight integration with polymer is already provided.

### Why wouldn't I roll my own Authentication?

15 years ago rolling your own was a perfectly decent idea. 
Modern security needs have moved radically beyond what can be accomplished in a
few hours by a non-specialized developer. 

All I care about is getting a unique, consistent, well managed id-token, for each user. How that is accomplished is better
left to experts with their rather extravagent budgets covering every corner case and need.






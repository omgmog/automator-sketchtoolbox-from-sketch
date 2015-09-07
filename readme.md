## Automator Action to Launch Sketch Toolbox from Sketch 3

![](https://blog.omgmog.net/images/sketch-to-sketch-toolbox.png)

This is an Automator action that I use to launch Sketch Toolbox from within Sketch 3.

You can use this in the following way:

1. Download the `Sketch Toolbox.workflow` and save it to `~/Library/Services`
2. Create an application-specific keyboard shortcut to trigger the service

You can create the keyboard shortcut easily enough:

- Open ‘Keyboard’ in ‘System Preferences’
- Select the ‘Shortcuts’ tab
- Add a new ‘App Shortcut’
- Set ‘Application’ to ‘Sketch’
- Enter the name you used for your service in ‘Menu Title’ (e.g. ‘Sketch Toolbox’)
- Set the keyboard shortcut you would like, I used `cmd` + `shift` + `,`

Once you've done that, when you press the configured keyboard shortcut while inside Sketch, Sketch Toolbox will launch.

![](https://blog.omgmog.net/images/Screen%20Shot%202015-07-30%20at%2015.31.58.png)

Read more about how to use this on my blog post "[Launching Sketch Toolbox from inside Sketch](https://blog.omgmog.net/post/launching-sketch-toolbox-from-inside-sketch/)"
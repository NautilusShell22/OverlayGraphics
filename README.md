# OverlayGraphics
Repo for Sports Graphics

Author's notes :
   I am an avid sports watcher so I was intrigued from a young age on how the scorecards work in different.
   Although professional studios use OBS and CasparCG to add overlays to live broadcasts, I tried my hand at a pretty simple HTML-python based overlay package.
   Using HTML-CSS for the overlay and Python for calling the REST APIs and some minor computation.

   Categotrizing this idea into 3 broad commits (with incremental updates included):
   Commit 1 -> Football - Little computation backend (for timekeeping) and very little data overhead.
   Commit 2 -> Cricket - Manual updation , Data heavy and a lot of data points for derivation.
   Commit 3 -> Motorsport - The most complex as the live leaderboard probably keeps track of the time sheet through some AWS server and updates(sorts) the live order as per that data.
   

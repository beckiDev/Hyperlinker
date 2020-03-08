RUN APPLICATION
Use Json server --a simple Node.js server that allows you to create fully working REST APIs

Install on your environment in terms to be able to run full Rest API
1. get an app "git@github.com:beckiDev/Hyperlinker.git"
2. install all dependencies 'npm run get_all_depp'
3. at global directory run 'npm install -g json-server'
4. run 'npm run dev'

But it is easily could be changed.
As for React.js, I used a new hooks implementation
and decided to not use redux because there are not that many actions.

WHY:
* App not using any 3rd party state management libs like Redux or MobX
  (not many states to manage, using react hooks for state management)
* App has not to match CSS styling yet one of the best mocking REST API apps

TODO:
- Front-End:
  * Add nice CSS Styling
  * Add function checking if expired and render the proper message
  * Add check to DB for id to prevent collision
  * Add better error handling

- Initial Security
  * Add ModSecurity to server
  * Save cookies on the user's browser
  * Prevent more than 10 requests from the same origin in the period of 60 seconds

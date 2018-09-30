#my-readable

my-readable is a content and comment web app which enables the user to post content to predefined categories, comment on their posts and other users' posts, and vote on posts and comments. 

Users will also be able to edit and delete posts and comments.The app uses React JS to render the UI and React-Redux to manage the state of the app.

The app has two parts to it - 

#1.Server

	Information about the API server and how to use it can be found in its [README file](api-server/README.md).

#2.Client

	Information about readable and how to use it can be found in its [README file](readable/README.md).
	
#Project Directory Structure
  
  
  my-readable/
	readable/
	  public/
		index.html
	  src/
		actions/
		  index.js
		components/
		  AddEditPost.js
		  App.css
		  App.js
		  App.test.js
		  ListPosts.js
		  ViewPost.js
		reducers/
		  index.js
		utils/
		  index.css
		  index.js
		  registerServiceWorker.js
	  README.md
	  package.json
	api-server/
	  categories.js
	  comments.js
	  config.js
	  posts.js
	  server.js
	  package.json
	  README.md
	README.md
# real-event

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Our Mock Database
To create our mock database, we’ll be using My JSON Server, which is a simple solution that requires no installation. We just need a Github repo with a db.json file in it. If you’ve been coding along, you may have already noticed that I’ve added a db.json file to the course’s repo:
In order to access our mock server, we’ll go to the url:

my-json-server.typicode.com/{GithubUserName}/{RepoName}

(Obviously, if you’re creating your own db.json file within your own Github account’s repo, you’ll want to fill in the blanks for your UserName and RepoName here.)

Adding ‘/events’ to the end of the URL allows us to target the events data specifically, so my-json-server.typicode.com/{GithubUserName}/{RepoName}/events is the URL we’ll soon use to make our call.

site is live on

https://eventlist.onrender.com

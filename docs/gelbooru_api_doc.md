## Gelbooru API Documentation (from socket.dev/npm/package/gelbooru-api)

Unofficial NodeJS wrapper for gelbooru.com

Gelbooru has millions of free description hentai and rule34, anime videos, images, wallpapers, and more!

This library will allow you to:

- Search posts with certain tags
- Get post by id
- Parse tags
- Search users

### Installation

`npm i gelbooru-api`

### Methods

First you should initialize the Gelbooru class, you can do it like this:

```javascript
const Gelbooru = require('gelbooru-api');
const GelbooruClient = new Gelbooru(tags);
```

**Search posts with certain tags:**

```javascript
GelbooruClient.search({
    tags: ['cat_ears', '1girl'],
    limit: 10,
    page: 1
}).then(posts => {
    console.log(posts);
}).catch(err => {
    console.error(err);
});
```

**Get post by id:**

```javascript
GelbooruClient.getPost(12345).then(post => {
    console.log(post);
}).catch(err => {
    console.error(err);
});
```

**Parse tags:**

```javascript
GelbooruClient.parseTags('cat_ears 1girl').then(tags => {
    console.log(tags);
}).catch(err => {
    console.error(err);
});
```

**Search users:**

```javascript
GelbooruClient.searchUsers({
    name: 'some_user',
    limit: 10,
    page: 1
}).then(users => {
    console.log(users);
}).catch(err => {
    console.error(err);
});
```


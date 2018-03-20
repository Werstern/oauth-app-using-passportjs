# oauth-app-using-passportjs
authorization app using PassportJs with google+ strategy

To make this app works, please create the keys.js file in config folder with some parameters(example below).
Replace phrases with <> in '' to string key from google+ api and url from mongoDB, description in <>.

module.exports = {
    google: {
        clientID: '<This is clientID in google+ api>',
        clientSecret: '<This is clientSecret in google+ api>'
    },
    mongodb: {
        dbURI: <Link to mongo db database. I use mlab.com>
    },
    session: {
        cookieKey: '<Everything you want>'
    }
};

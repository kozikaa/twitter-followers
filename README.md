# twitter-followers

#Install

#npm install --save get-twitter-followers

#Usage

import getTwitterFollowers from 'get-twitter-followers';

getTwitterFollowers(tokens, 'jsunderhood').then(followers => {
console.log(followers); // "User Objects" array https://dev.twitter.com/overview/api/users
});

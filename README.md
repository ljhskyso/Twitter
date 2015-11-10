# Project 3 - Twitter

Twitter is a basic twitter app to read and compose tweets the [Twitter API](https://apps.twitter.com/).

Time spent: 15 hours spent in total

## User Stories

The following **required** functionality is completed:

- [Y] User can sign in using OAuth login flow.
- [Y] User can view last 20 tweets from their home timeline.
- [Y] The current signed in user will be persisted across restarts.
- [Y] In the home timeline, user can view tweet with the user profile picture, username, tweet text, and timestamp.  In other words, design the custom cell with the proper Auto Layout settings.  You will also need to augment the model classes.
- [Y] User can pull to refresh.
- [Y] User can compose a new tweet by tapping on a compose button.
- [Y] User can tap on a tweet to view it, with controls to retweet, favorite, and reply.

The following **optional** features are implemented:

- [ ] When composing, you should have a countdown in the upper right for the tweet limit.
- [ ] After creating a new tweet, a user should be able to view it in the timeline immediately without refetching the timeline from the network.
- [ ] Retweeting and favoriting should increment the retweet and favorite count.
- [ ] User should be able to unretweet and unfavorite and should decrement the retweet and favorite count.
- [Y] Replies should be prefixed with the username and the reply_id should be set when posting the tweet,
- [ ] User can load more tweets once they reach the bottom of the feed using infinite loading similar to the actual Twitter client.

The following **additional** features are implemented:

- [Y] Animations
- [Y] Refine Login page
- [Y] Customize navigation bar
- [Y] Confirmation altercontrollers when retweeting
- [Y] TextView place holder text

## Video Walkthrough

Here's a walkthrough of implemented user stories:

@dropbox - gif @ https://www.dropbox.com/s/1uv73m4zbjexjav/HW3.gif?dl=0

@dropbox - quicktimes video @ https://www.dropbox.com/s/n7vv6oegzwri5dt/HW3.mov?dl=0

@imgur - gif @ http://imgur.com/L8nNjbn

[twitter app](http://i.imgur.com/L8nNjbn.gifv)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Had a hard time to parse time stamp to NSDate.

## License

    Copyright [2015] [Jiheng Lu]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

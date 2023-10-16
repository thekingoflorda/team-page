---
title: "Intro"
weight: 1
---
# Welcome

Welcome to Lemmy (on whichever server you’re reading this)

# About Lemmy

Lemmy is a federated platform for news aggregation / discussion. It’s being developed by the Lemmy devs: [https://github.com/LemmyNet](https://github.com/LemmyNet)

## About Federation

What does this federation mean?

It means Lemmy is using a protocol (Activitypub) which makes it possible for all Lemmy servers to interact.

- You can search and view communities on remote servers from here
- You can create posts in remote communities
- You can respond to remote posts
- You will be notified (if you wish) of comments on your remote posts
- You can follow Lemmy users/communities on other platforms that also use Activitypub (like Mastodon, Calckey etc) (There’s currently a known issue with that, see [here](https://lemmy.world/post/15786)

Please note that a server only starts indexing a server/community once it has been interacted with by a user of this server.

A great image describing this, made by [@ulu_mulu@lemmy.world](https://lemmy.world/u/ulu_mulu) : [https://imgur.com/a/uyoYySY](https://imgur.com/a/uyoYySY)

![](https://lemmy.world/pictrs/image/0006c2db-13c6-406e-97e7-6e274fddf355.png)

# About Lemmy.world

Lemmy.world is one of the many servers hosting the Lemmy software. It was started on June 1st, 2023 by [@ruud@lemmy.world](https://lemmy.world/u/ruud) , who is also running [https://mastodon.world](https://mastodon.world), [https://calckey.world](https://calckey.world) and others.

A list of Lemmy servers and their statistics can be found at [FediDB](https://fedidb.org/software/lemmy)

# Quick start guide

## Account

You can use your account you created to log in to the server on which you created it. Not on other servers. Content is federated to other servers, users/accounts are **not**.

## Searching

In the top menu, you’ll see the search icon. There, you can search for posts, communities etc.

![](https://lemmy.world/pictrs/image/1cd03dea-443b-4a92-ba87-5b45561200fd.png)

You can just enter a search-word and it will find the Post-titles, post-content, communities etc containing that word **that the server knows of**. So any content any user of this server ever interacted with.

You can also search for a community by it’s link, e.g. `!Netherlands@lemmy.nl`. Even if the server hasn’t ever seen that community, it will look it up remotely. Sometimes it takes some time for it to fetch the info (and displays ‘No results’ meanwhile…) so just be patient and search a second time after a few seconds.

## Creating communities

First, make sure the community doesn’t already exist. Use search (see above). Also try [https://browse.feddit.de/](https://browse.feddit.de/) to see if there are remote communities on other Lemmy instances that aren’t known to Lemmy.world yet.

If you’re sure it doesn’t exist yet, go to the homepage and click ‘Create a Community’.

![](https://lemmy.world/pictrs/image/d49e3218-fcee-4dc6-8879-7b5a4986da4d.png)

It will open up the following page:

![](https://lemmy.world/pictrs/image/b03c9fb1-69ba-43b5-985f-97c3820e146a.png)

Here you can fill out:

- Name: should be all lowercase letters. This will be the /c/
- Display name: As to be expected, this will be the displayed name.
- You can upload an icon and banner image. Looks pretty.
- The sidebar should contain things like description, rules, links etc. You can use Markdown (yey!)
- If the community will contain mainly NSFW content, check the NSFW mark. NSFW is allowed as long as it doesn’t break [the rules](https://mastodon.world/about)
- If you only want moderators to be able to post, check that checkbox.
- Select any language you want people to be able to post in. Apparently you shouldn’t de-select ‘Undetermined’. I was told some apps use ‘Undetermined’ as default language so don’t work if you don’t have it selected

## Reading

I think the reading is obvious. Just click the post and you can read it. SOmetimes when there are many comments, they will partly be collapsed.

## Posting

When viewing a community, you can create a new post in it. First of all make sure to check the community’s rules, probably stated in the sidebar.

![](https://lemmy.world/pictrs/image/bf81a5f5-997d-42e0-8544-5051cf9657d7.png)

In the Create Post page these are the fields:

- URL: Here you can paste a link which will be shown at the top of the post. Also the thumbnail of the post will link there. **Alternatively** you can upload an image using the image icon to the right of the field. That image will also be displayed as thumbnail for the post.
- Title: The title of the post.
- Body: Here you can type your post. You can use Markdown if you want.
- Community: select the community where you want this post created, defaults to the community you were in when you clicked ‘create post’
- NSFW: Select this if you post any NSFW material, this blurs the thumbnail and displays ‘NSFW’ behind the post title.
- Language: Specify in which language your post is.

Also see the [Lemmy documentation](https://join-lemmy.org/docs/en/users/02-media.html) on formatting etc.

## Commenting

## Moderating / Reporting

## Client apps

There are some apps available or in testing. See [this post](https://lemmy.world/post/465785) for a list!

# Issues

When you find any issue, please report so here: [https://lemmy.world/post/15786](https://lemmy.world/post/15786) if you think it’s server related (or not sure).

Report any issues or improvement requests for the Lemmy software itself here: [https://github.com/LemmyNet](https://github.com/LemmyNet)

## Known issues

Known issues can be found in the beforementioned post, one of the most annoying ones is the fact that post/reply in a somewhat larger community can take up to 10 seconds. It seems like that’s related to the number of subscribers of the community.

I’ll be looking into that one, and hope the devs are too.

+++
title = "\"What is The Matrix?\""
path = "/blog/2014/11/05/what-is-the-matrix"

[taxonomies]
author = ["Oddvar Lovaas"]
category = ["Thoughts"]
+++

<em>As part of our semi-regular series of having Matrix core team members write about how they see the overall project, here's Oddvar Lovaas' view.  Oddvar helps out with project management and promoting Matrix.</em>

According to the homepage, Matrix is "a new open standard for interoperable Instant Messaging and VoIP, providing pragmatic HTTP APIs and open source reference implementations for creating and running your own real-time communication infrastructure. "

That's all good - but you might be asking yourself "sure, but what can it do?" And more importantly, "what can it do for me?"

The original inspiration for Matrix was to fix the problem of fragmented IP communications, by creating a standard for creating and running your own real-time communication infrastructure. This means that if you want your app or program or website to be able to communicate user to user for example, you can use Matrix. Matrix is the protocol through which your communication packets are sent and received, and we provide HTTP APIs to make it easy to make use of this protocol in your code.

The nice thing here is that the user can to talk to any other user anywhere in the Matrix ecosystem, much like email or the web. For example, let's imagine I have an app whose goal is to keep the user updated on anything happening in the football world. Whenever any news drops in, the app is notified and thousands of users check the app for the news. This app could have a communication element where the users can talk in rooms (maybe a #general room and rooms for each football club) - or even between themselves or in groups of friends. Today, a lot of people would use an IM-client to do this, but with Matrix it wouldn't matter if you use a dedicated IM-app or talk inside the football app - since you are using the same Matrix account, you will get the same conversations in both clients!

In fact, imagine that later on you are chatting with some (non-football) friends on your Matrix-supporting chat-application. You can then easily check the previous conversation to see if anyone's appreciated the great joke you made earlier - without having to go back into the football app.

But Matrix's real potential and ultimate mission is to be a generic messaging and data synchronisation system for the web - allowing people, services and devices to easily communicate with each other with full history. It's easier to visualise the chat-application because we are used to chat-messages going back and to, but there's nothing stopping you from putting other data instead of chat-messages. For example, you could use the Matrix protocol to exchange moves - encrypted and secured, of course - in your Chess-game. In fact, your Chess-game could use Matrix both for chatting and exchanging payloads of data.

Imagine if you open up your favourite chat-application, and your contacts there include other users of the same app and also other Matrix-users (so the app has exposed itself to Matrix). Your friend, however, much prefers a different app, but he can still talk to you over the Matrix protocol. And if he ever moves to the other app (or any other Matrix-supporting app) - he would still have all the backlog and history of the conversation!

Obviously the problem here is that we can't instantly make the various chat-applications support Matrix. We believe if we can encourage and grow a truly open communication ecosystem, users will get used to the availability and benefits of interoperable services and they will demand it everywhere.

---
layout: post
title:  "Our Own DAC for Building Projects"
author: "Chadrick Mahaffey"
date:   2016-03-02 00:00:00 -0500
categories: crowd founding
---

Projects such as [Colony](http://colony.io/) and [Boardroom](http://boardroom.to/) in the [Ethereum](https://ethereum.org/) space, as well as others are building DAC governance management frameworks, so why start another one? I would say let’s do our best to work together in any way we can, share what we learn from the different focuses, but also understand the differences. The main (I think) being who the target end user is in these systems. I've been looking for the docs so I can study up more on the two projects, but haven't found much. If someone knows more please post in the comments.

### Nontechnical Folks and Energy Strapped Developers

Some (perhaps most) projects that are focused on building a framework that would aid in the building and managing of a DAC or DAO focus on the workers first. It’s not surprising seeing that most communities talking about DACs or DAOs come from an open source background. Those that are creating the product by the sweat of their brows are primarily who will own and run the project, usually in some kind of meritocratic way. I'm not saying this model is wrong. In fact I think this model makes a lot of sense under certain circumstances. In fact when I first contemplated a DAC management framework, the thing in my head ([BuildItHub](https://forum.safenetwork.io/t/builder-devs-designers-marketers-hub/303)) was developer and value creation focused.

#### Creativity First Model

The reality is *there are a lot more people with great big ideas than there is willing manpower to build those ideas*, especially when the real life obligations of putting bread on the table takes up so much of our time and the potential that the endeavor will be successful is questionable and the amount of effort to make it successful is substantial. Real incentives for work done makes sense. But let’s not start with the know-how folks.

I suggest that rather than start with the developers, *we back the entry point of joining a DAC up a step*. What I mean by that is we start with the work creative thinkers do. These people don't have to be technical folks, though if they are that's cool. We define our dream product with our tribe. We collaborate long and hard. Once we see it as clearly as we can in our collective vision, we strip it down to the most basic version. This version is far from ready for prime time. It's a foundation to learn from and build on. In the development community this is called a MVP (Minimum Viable Product). Once we know what our MVP is, we get it quoted by developers who show interest in the project. Then we as a community gather the required funds to build it. We keep control of the purse strings to verify the project is going as we think it should. As long as it is, we release the funds step by step. Once it's done, we have a real working app as a foundation to work with that is owned by us. We also have an invested community ready to take it to the next level. Just because we don't start with the developers doesn't prevent them from gaining some stake along the way. In fact I would suggest that the community offer them some, because remember the product is not complete by any means yet. It's an MVP.

At this point we can take it to new levels, new feature by new feature. We fund each new feature along the way using the same kind of processes we did with the initial MVP. Someday the project starts to gain non-invested users. They pay for the product and everyone with stake in the project receives dividends as the project gains a larger and larger user-base.

#### Advantages to The MVP First Approach

* MVPs are much cheaper than a full product.
* We might think we know what we want, but until we use it we really don't know, so we won't waste resources on less valuable things.
* It's much faster to build. This means we build momentum in weeks and months rather than months and years.
* We figure out things we missed early.
* We decide if it's really going to work before investing too much.
* Once done the MVP can be used and the next features will be obvious to us.

## How could we do this today?

So say we use something like the model above; how do we turn that model into a Distributed Autonomous Co-op? **Tokens** and **Smart Contracts** are the key technology pieces that could allow it. So let's get on the same page about what they are. 

### Tokens

Tokens are tradable, non-counterfeitable certificates you hold in a digital wallet. [Counterparty](http://counterparty.io/) and [Omni](http://www.omnilayer.org/) (Mastercoin) are two providers of custom tokens that live on the blockchain. MaidSafeCoins are Mastercoin assets. [Tokenly](https://tokenly.com/) is a framework for making Counterparty tokens easy to work with. Ethereum allows tokens on their blockchain as well. There are options available to us today. We don't have to wait to get started with tokens. 

### Smart Contracts

Smart contracts are applications that run exactly as programmed without any possibility of downtime, censorship, fraud or third party interference. Smart contracts are running today. I'm not an expert by any means, but the experts exist and it wouldn't take a developer long to get up to speed.

### Raw Data

Applications will need a decentralized, secure and private place for raw data. There are a few projects working on this. My favorite being [Maidsafe](http://maidsafe.net/) (yes, I have maidsafecoins) as I believe the scaling issues of having things on a blockchain will not be an issue there. As of this writing I don't think we have this. We will need to use a centralized solution until a decentralized one is available.

### Putting it All Together

When you put all the technologies together it allows for the owners of specific tokens to interact with specific contracts to modify specific data within the DAC. So let's use the above model and see what kinds of tokens and contracts we might need to make it happen.

## A Blueprint

This is just an example model. I'm not claiming it's perfect by any means, but it's something tangible. If someone has another idea or thinks this one could be improved upon, that's awesome. Let's find something worthwhile and see where we end up. Creativity of the crowd after all.

### An Idea Site

It always starts with an idea. We need a way for the tribe to ideate over a project, as well as [build more interest](http://www.freemyvunk.com/#!vnk-the-token/z2czn). Perhaps they can do this in anything (no need for walled gardens). Their own site, forum, wiki or whatever they decide. I don't think it would be a bad idea to allow the project to be created and talked about within the system either. Options and convenience for nontechnical folks until their own platforms are created. A list page with a simple CRU~~D~~ (create, retrieve, update and ~~delete~~) page per idea. A commenting system. No cutting edge tech is necessary here.

### Defining an MVP

The community would limit the big idea down to an MVP. 

### Getting Quotes and Picking One

At this point developers or teams of developers quote the MVP features and hosting. They would include things such as tech stack they plan to use, dollar amount, any ongoing hosting fees needed and their stake percent for the features they would complete. We would get a real feel for who knew what from these quotes.

The community would vote on what quote, or parts of different quotes to choose. I have an idea for using tokens for voting after the MVP is created, which is explained below, but not before (looking for some ideas here).

### Funding The Quote(s)

Once we have the quotes, FEATUREXYZ tokens are created. Perhaps one Token per dollar needed or whatever the community decides. The development funds stay in a wallet. Funds will be released through voting by those who have FEATUREXYZ tokens. Development cannot start until the feature(s) are funded.

### Development

The developer(s) will work on the project and give updates. Code will be available through a public repository for viewing. As long as things go according to plan the funds are released to developers on a regular basis through votes.

### MVP/Feature Complete

Once done a portion of each FEATUREXYZ token is given to the developers according to their agreed upon percent. At this point we have an MVP and tokens in the system distributed to everyone who has invested in the system. These are specific tokens and if the project creates income it is payed out to holders of the ***completed feature*** tokens.

### Next Features & New Tokens

Here is where things can get interesting. Because new tokens are added to the system only for funding new features, we need a good way to control how and when the proposed new features will create new tokens. I propose it's done by transferring tokens from completed features (dividend producing) to new proposed features (non-dividend producing). People who are already invested in the project must believe that these new features are important enough to risk their dividends. Once a certain amount of old tokens are assigned to the proposed feature the NEWFEATURE123 tokens are created and available for purchase. Perhaps those who transferred dividend producing tokens might get first dibs on the new tokens.

After the new feature is complete, the old FEATUREXYZ tokens that were used as votes are converted to the new NEWFEATURE123 and are now dividend producing again.

### Combating Pay To Control with Feature Ranking

We also want to make it hard for someone to come in and buy up all the new tokens and be able to take over control of the project. We might build in a feature ranking system where each address with a minimum amount of tokens, force ranks each completed feature in the system. The rankings are averaged from the entire community. Those features with the highest average rank, post a larger percentage of the dividends and perhaps tokens that are transferred from those high ranking features have more weight. 

## Summary

There are tons to think and talk about, but I think we are at a place now that we could start to work on this or something like it. I'd like to hear your ideas and more importantly I want to be involved in a community of people who want to do something similar. Please comment, if you want to post your own blog post around this idea I can make you a member of the blog team.
---
description: A Free Roleplay Framework for GTA:V using the alt:V client.
---

# 👋 Introduction

{% embed url="https://www.youtube.com/watch?v=k4d51-BjkZ0" %}
A pre-cursor to understand what the Athena Framework has to offer.
{% endembed %}

## Get Started

The Athena Framework is not for users who just want a quick roleplay server to spin up. You will have to write code, you will have to use a command line interface, and you will have to build things for your roleplay server. Athena only helps you write these things faster. That's it.

### Support on Patreon

Originally this framework **was not free** it's because of the people who supported the original product in a subscription based format that it is free today. Please consider supporting on Patreon.

[https://patreon.com/stuyk/](https://patreon.com/stuyk/)

### Why Use Athena?

The author of Athena has worked on a handful of game modes and been around the block a few times. The author is a full-time blockchain engineer and is a full-stack developer. Which means they are used to deploying services that run well and resist crashing.

It also takes less than 60 seconds to setup a full server with all prerequisites installed. Athena is particularly easy to use as it doesn't require any major database configuration (unless you want it to) and is uses one of the most commonly used runtime's today. Which is NodeJS.

It is entirely written in TypeScript from front-to-back and you only need to know one language to work on the entire server infrastructure.

That being said, Athena is built by industry developers and built for industry developers. If you choose to use Athena you also learn industry skills just by simply playing around with it.

### Fast Deployment

It is recommended to do a full install but quick instructions are provided below.

{% content-ref url="installation/installing-on-windows.md" %}
[installing-on-windows.md](installation/installing-on-windows.md)
{% endcontent-ref %}

{% content-ref url="installation/installing-on-linux.md" %}
[installing-on-linux.md](installation/installing-on-linux.md)
{% endcontent-ref %}

If you wish to use Athena but not make any changes to the core (unlikely you won't make changes) here are some simple instructions for the every day developer who just wants to test this with the alt:V Client quickly.

#### Windows

* [Install MongoDB Server](https://www.mongodb.com/try/download/community)
* [Install Git](https://git-scm.com/downloads)
* [NodeJS 17+](https://nodejs.org/en/download/)
* [alt:V Client](https://altv.mp/)

#### Run Commands in Terminal, PowerShell, or a CLI

{% tabs %}
{% tab title="Step 1" %}
```
git clone https://github.com/Stuyk/altv-athena
```
{% endtab %}

{% tab title="Step 2" %}
```
cd altv-athena
```
{% endtab %}

{% tab title="Step 3" %}
```
npm install
```
{% endtab %}

{% tab title="Step 4" %}
```
npm run update
```
{% endtab %}

{% tab title="Step 5" %}
```
npm run windows
```
{% endtab %}

{% tab title="Step 6" %}
* Launch the alt:V Client
* Join with`0.0.0.0:7788` in Direct Connect
  * If the above does not work, try `127.0.0.1:7788`
* That's it.
{% endtab %}
{% endtabs %}

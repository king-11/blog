---
title: "OnCampus Microsoft Interview"
date: 2021-08-10T13:22:41+05:30
tags: [microsoft, life, tech]
cover:
    image: "interview.webp"
    relative: true
canonicalUrl: https://king-11.hashnode.dev/interviewing-experience-microsoft
---

Microsoft is like a dream company for many people me included :P.

Why won't it be its the company which develops typescript making web app development so much easier, VSCode favourite IDE of all developers 😌, Azure Cloud Services, Windows the first Operating System that most people use.

![Microsoft Windows](https://media.giphy.com/media/thA1QtTj8ZYHK/giphy.gif)

The Process Included two parts the Coding Round and then Interviews, based on which students were selected. While Coding Round was eliminating Interviews were not, so everyone was able to give 2+ interviews.

## Coding Round

Microsoft provided us with two questions on Codility. The first one was an easy greedy + sorting question where you have to check by using available cranes can an object be moved from `B` to `E`. Sort the `(crane position - length , crane position + length)` then keep on moving B till it reaches a crane that has B and E in the same range. Made sure to swap B if it's greater than E. That was that.

![coding round](https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif)

Another one was also an easy greedy problem. We were given that a player made `T` dice moves off which he only remembers `N` moves exactly and mean of all the dice moves. So we just have to find the remaining possible value of move which can be done very easily by dividing the remaining sum ( found using mean*T - the sum of N) among all values equally and if some still remain divide it one to each.

>The thing about Codility is they won't run any test cases in front of you they are all hidden which I only realized after submitting 1st question.

## Interviews

2 Rounds were conducted for me there was no clear separation as to whether they were HR or Technical. I was asked HR-related and technical questions in both rounds.

### Round 1

#### Introduction

The interviewer asked me about myself. I had been finding the right answer for this for quite some time now. I started with personal info, then what I do? which is [open source](https://github.com/king-11) contributions, [technical blogging](http://blog.manlakshya.tech/) and attending conferences. He seemed impressed as he told me that wasn't the usual answer he gets.

I also told him about how I started my technical journey as a child curious to get acquainted with Windows XP and MS Office. Also, my current stack is Visual Studio Code and Typescript, both developed by MS again 😄.

![windows XP](https://media.giphy.com/media/4mXjpVNJAFlvi/giphy.gif)

#### Knight and Destination

The was that question given a `n*m` chessboard, and you have a Knight piece that needs to go from `S` to `D`, find the minimum number of moves required to reach destination `D`. I started with a crude simple BFS solution, and before coding, I explained my approach to him. After a go-ahead, I coded the initial solution, which was un-optimized. He asked me to do a quick dry run to show that it works.

![chessboard knight moves](https://media.giphy.com/media/32dfpYx8kBX1bXSEu8/giphy.gif)

Next, he asked me how would I do memoization so that the complexity is not exponential. So I implemented memorization using a `n*m` array which stores the minimum move from that location `(x,y)`. Next, he asked me how can I do pruning for the solution so that we don't go to longer paths if we already have a minimum implemented that was just an if-else check on the current minimum to stop when needed.

Finally, he asked me, since it was uninformed BFS, what better could be done. I told him that Dijkstra's Algorithm would do the job nicely, but since it's a matrix, we can use [A* Heuristic Search Algorithm](https://www.redblobgames.com/pathfinding/a-star/introduction.html) to do even better. I showed him why this would happen by defining the heuristic function as manhattan distance. I wasn't asked to code them, just what and how better?

#### Why Microsoft?

Finally, he seemed satisfied and asked me why Microsoft I also had it covered. My answer was that I wanted to empower new developers to build even better software using services like Azure, Typescript and VSCode which will give me a sense of pride that the software I built is being used by developers to create even better services for users.

#### Anything Else?

He then asked me if I wanted to ask anything. I asked him what he does, and day to day workings of his at Microsoft. He gladly told me about the project he was working on which included created higher-level APIs for Database manipulation in Azure.

![Database](https://media.giphy.com/media/kPrlykW2TpVU4HWx2O/giphy.gif)

### Round 2

#### Level Order Traversal Binary Tree

This started without my introduction. This time he gave me a problem after introducing himself. The problem was printing level order traversal of a binary time. This time I was asked to code first then explain, so I quickly went ahead and gave a solution using queue and yeah, it seemed good to him.

Although he stopped me midway when I used `auto` in C++ because that surely makes it difficult for humans at the end, humans should understand code, not just machines. Finally, I did a Dry Run of the implementation and was done with the question.

#### Explain Any Project

Next, he asked me what was the most difficult part of any project I had mentioned in my resume. I asked him do open-source contributions count? and he was impressed and went on to tell me that at Microsoft, they value Open Source so yes they count. So I told him, in brief, all the issues I had when I started with [DXHeroes](https://github.com/DXHeroes/dx-scanner/pulls?q=is%3Apr+author%3A%40me+) and [PGRouting](https://github.com/pgRouting/pgrouting) also talked a bit about my [GSOC project](https://summerofcode.withgoogle.com/projects/#5343790958641152), which I didn't particularly tell as GSOC project but just any open source contribution.

![google summer of code project](https://media.giphy.com/media/xTiTnoUnHxVaaVNWhO/giphy.gif)

#### Talk about GSOC Project and Async I/O

As open source is huge, he wanted to know just something specific he asked me about my GSOC Project at Chapel, which I cited as a productive parallel programming language. I told him that this was my first time working with C System Call, joked about getting my hands dirty with pointers, allocation, etc. ( he laughed too xD ).

I finally told him about issues with I/O multiplexing, which I was resolving using Asynchronous I/O. Async IO hit him as something that college don't have experience with, and he himself worked on it, so he told me, like, yeah, that is a totally different game.

#### Anything else?

Finally, my chance to ask, I asked him what interns do whether their code makes into actual user apps or not.

## End

Some people had round 3 as HR, or Technical mine wasn't, so after the interview, I was sad, but Training Placement Cell Representative told me that it wasn't the case that I was eliminated, so was happy again.

![work for me](https://media.giphy.com/media/kg129XRsLTbezr509v/giphy.gif)

And Yeah [Selected](https://www.linkedin.com/feed/update/urn:li:activity:6830505027312918529/) 😊

Thanks for reading :) and please share your thoughts. I always like to meet more enthusiastic people, so do reach out to me on [Twitter](https://twitter.com/1108King) or [Linkedin](https://www.linkedin.com/in/lakshyasingh11/) to share your feedback or for any queries. I'd be more than happy to help and connect.

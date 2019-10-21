---
title: Building My First End-To-End Product
date: 2019-10-21 18:21:53
tags:
---

In this post, I will take you through the journey on how our team built an entire functional product within a week in Masai School. It is not just specific to students in Masai School, but it will inspire anyone who is looking to get their foot in the door to this programming world.

## Introduction

Our project started on 14th Oct 2019. It's our Week-11 in Masai School and our team of two (Me and Madhu) was assigned to build a platform which brings teachers & students together to conduct tests online and keep track of how the student is performing in the tests.

## Our Journey

Before jumping to start coding, our team has to come with a plan for the entire week on how should we structure the workflow for this project. We spent our first two days entirely on planning from creating the Data Flow Diagram, Wireframes and Mock-ups for the project. We used draw.io for creating our DFD's and Figma for creating the mockups. In these two days we got a clear understanding of how our plan will lead us to build this product without any hiccups within a week.

Once we had our DFD's and mockups ready, we started with setting up our development environment. It's not a big setup but either way our setup should not drag us back and create unnecessary issues for us. We're using ReactJs which is a JavaScript framework by Facebook, Redux for state management in our app and Google's Firebase to handle our backend for our product. We've also set up Airbnb style guide with ESLint so that our code looks and works consistently. This is a very important factor in a collaborative project because it's not just about you and your code. Your entire team works together to build something which should lead to the completed product. It will be a nightmare if you're writing code without any specific rules or guidelines to follow.

We spent our entire day in implementing our base UI for our product without any functionalities. This helps us in getting clarity on how our backend to be structured. Even a single change in our UI may lead to changing our entire backend schema which is not viable, especially in a time-constrained product. After our UI is ready, we started implementing Redux to make a functional product locally without an actual backend, just to make sure everything is working as expected.

## Half-Way Through, What's Next?

It's Day-5 and that's when we started to look into Firebase. Firebase is a BaaS (Backend-as-a-Service) by Google which helps us to implement easy and simple MVPs (Minimal Viable Product). It's a different discussion all together on when one should prefer a Baas or dedicated backend for any product.

This is where we faced our first hurdle. Firebase is completely new for our team, also integrating something like firebase with redux is a different story altogether. We had to learn the basics of firebase before we can implement that in our product. So, we built a simple authentication app and a simple todo-list. We spent our entire day on getting a hang of how firebase works.

On Day-6, we started implementing firebase into our project and then we started facing issues one after another. As Redux is completely synchronous, we are facing issues in getting our required data from firebase asynchronously. Our entire app started breaking apart. We had only one day left in our schedule and we're running out of time very fast. Everyone will face this situation one time or another, but we should stay strong and consistent. I've dedicated almost 24hrs straight to fix everything and get this going.

Another complication in our product is students will land on the test page directly and we should be able to show the necessary content for them. It's not as easy as you think to get your unique test links to work on the fly. That's not how React works. It took another 4-5 hrs of undivided attention to fix this.

Hurray!! We did it. we completed a functional product within a week. It's a great experience to build something entirely from scratch in a collaborative manner. You'll love it when you do it. Thanks to Madhu for her commitment and efforts towards the product.

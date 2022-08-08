# Goal Getters

## 1. Problem Statement  

Some of the most successful people in the world set goals and usually their success depends on how well they can achieve those goals. **Goal Getters** is an application that will help people keep track of their goals and give them timely reminders to encourage them to keep working towards achieving those goals. Most of us want to be successful in life in whatever way we define that for our life, and **Goal Getters** will help each person achieve success through these core features:
</br>

1. The ability to set goals and track progress
2. Reminders to help achieve goals
3. Encouragement and motivation
4. A community of goal-setters to interact with and learn from
5. Tips and resources to help accomplish goals
</br>

Only you can determine what you want to strive for, but once you figure out your goals and can identify the steps along the goal achievement path, then that's where **Goal Getters** comes in. We want to help you accomplish your goals and achieve success and become a Goal Getter!

## 2. Top Questions To Resolve in Review

## 3. Use Cases

U1. As a user, I want to create a new account, so I can create new goals and track their progress.

U2. As a user, I want to login to my account, so I can see my goals and their progress.

U3. As a user, I want to logout of my account, so when I am finished checking my goal progress that no one else can see my data.

U4. As a user, I want to delete my account, so if I decided that I don't want to set goals I can remove my account and data.

U5. As a user, I want to edit my account, so if some information/data changes that I can make that change to my account.

U6. As a user, I want to create a new goal, so that I can start tracking my progress of accomplishing this goal.

U7. As a user, I want to edit a goal, so if I make a mistake or something changes I can make those edits to my goal.

U8. As a user, I want to create markers/steps for each goal, so that I can break down a goal further down into smaller achievable steps.

U9. As a user, I want to update a goal marker, so that as I achieve steps of my goal I can check those off and see the progress.

U10. As a user, I want to delete a goal, so that if I no longer want to have a certain goal I can remove it from my goals to achieve.

U11. As a user, I want to toggle reminders on or off for a goal, so that I can have control over if I get reminded about a goal.

U12. As a user, I want to share my goals with friends/family, so that I can hold myself accountable.

## 4. Project Scope

<div class="move2">
    <h3>4.1 In Scope</h3>
    <div class="move2">
    - Creating, retrieving, updating, and deleting an account. </br>
    - Creating, retrieving, updating, and deleting goals. </br>
    - Sending email/text message reminders to a user. </br>
    - Share a goal and it's progress with an external user </br>
    </div>
    <h3>4.2 Out of Scope</h3>
    <div class="move2">
    - Using Alexa, Google Home, Siri to create or track goal progress
    - A dedicated mobile application (iOS/Android) </br>
    - Community features that allow users to interact with each other</br>
    - Support features that give users tips on how to achieve their goals</br>
    - A way for you users to bet on themselves to accomplish goals</br>
    </div>
</div>

## 5. Proposed Architecture Overview

This initial iteration will provide the minimum viable product (MVP) including creating, retrieving, updating, and deleting an account, as well as creating, retrieving, updating, and deleting a goal. Furthurmore, a user will also be able to get timely encouraging reminders to help motivate them to achieve their goals.

We will use API Gateway and Lambda to create the endpoints need to accomplish all the tasks to have a functioning application as layed out above. These endpoints include:

- CreateUser
- GetUser
- UpdateUser
- DeleteUser
- CreateGoal
- GetGoal
- UpdateGoal
- DeleteGoal
- CreateReminder
- SendReminder
- UpdateReminder
- DeleteReminder

<style>
    .move2 {
        margin-left: 2em;
    }
</style>

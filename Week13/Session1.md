# Week 13: Session 1

Quite a few of us had not completed our code academy exercises on Redux from last Friday so we have been given just under half todays class time to finish them in. Most of this is due to the SDV602 assignment that keep the majority of us busy this last long weekend. For my part I have 6 of the 17 exercises left to do. These I am quickly whipping through. I am continuing to store my results for future reference when I implement redux into my website.

Following this we continued with our tutors planned lesson; learning Flux using material provided in our GitBook. 

Flux was designed by Facebook and is a pattern that implements the concept of a unidirectional dataflow as opposed to other flows such as the MVC model which has multiple flows going between the model and view.
Because it is unidirectional, if a new set of data is needing to be inserted the the flow starts all over again. This pattern prevents dataflows from affecting each other. This pattern is what is called Flux and consists of 

<ol>
    Action
    Dispatcher
    Store
    View
</ol>

The action creator is responsible for creating the actions which will be performed upon the state of the application.

The dispatcher is responsible for sending the action to be performed to the store. There can potentially be multiple stores within an application and the dispatcher works similar to a switchboard operator in that it will pass the action to the correct store.

The store holds all state of an application.

The view is what takes the current state and renders it for the user to see on screen.
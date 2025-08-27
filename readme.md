1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

   Ans: getElementById selects one element by its unique ID. getElementsByClassName selects a live collection of all elements that have a class name. querySelector selects the first element that matches a specific CSS selector. querySelectorAll selects a static list of all elements that match a specific CSS selector.

2. How do you **create and insert a new element into the DOM**?

   Ans: I create a element via using .createElement() function and insert it using .appendChild() .

3. What is **Event Bubbling** and how does it work?

   Ans: Event bubbling is the process where an event fired on a nested element spreads up to its parent elements.

4. What is **Event Delegation** in JavaScript? Why is it useful?

   Ans: Attaching a single event listener to a parent element is known as event delegation, and it is a useful method. This listener controls the events of all its child elements. It uses event bubbling to capture events from the child elements. This method works well for improving performance and controlling events on dynamically introduced content.

5. What are the differences between the **preventDefault() and stopPropagation()** methods?

    Ans:The preventDefault() function stops the browser's default response to an event. For example, it could prevent a form from submitting or a link from functioning. In contrast, StopPropagation() stops the event bubbling process. In this way, the event is kept from rising.

Live Link: https://joyassroy.github.io/assignment-5-Emergency-Hotline/

# quizEventListener

This code first checks to see if Pointer Events are supported by testing for window.PointerEventSupport. If Pointer Events aren’t supported, we add listeners for touch and mouse events instead. If Pointer Events are supported, we use variables for event names, which use the prefixed or unprefixed versions depending on the existence of window.PointerEvent.

Notice that event listeners are added to a specific element, swipeFrontElement, for a specific type of event.

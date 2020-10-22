I thought the test double blog article was really good, with the caveat that I don't understand exactly what problems or realizations he came across in production.

UI-Agnostic components are how we've been taught to write React from the start, an strictly use our definition of MVC as having our routing entirely separated from our React components (controllers in Express), and lifting any logic other than binding events into helper/services files... which are also not React components.

The code examples representing where he started look truly horrific, coming from that perspective.

Container/controller + view components (V and V/C of MVC) and UI-Agnostic Data Models seem like the most natural thing in the world, because we've always been doing that. The attitude Tommy is describing in others of the MVC-pattern being an outdated backend philosophy that doesn't work well for GUIs sounds like madness to me.

React uses a heuristic for its diffing process. Don't change HTML/element types, and you won't trigger a full teardown and rebuild, etc etc etc. The really interesting part of this article, was in how important and fundamental keys are to its diffing heuristic.

React doesn't have to tear everything down and re-render when changing:

<ul>
  <li key="2015">Duke</li>
  <li key="2016">Villanova</li>
</ul>

to

<ul>
  <li key="2014">Connecticut</li>
  <li key="2015">Duke</li>
  <li key="2016">Villanova</li>
</ul>

because the keys tell it, "Hey, this is staying the same, idiot!"
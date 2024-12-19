# CSS :hover Pseudo-class and Transition Interference

This repository demonstrates an uncommon CSS bug related to unexpected behavior with the `:hover` pseudo-class when used with transitions and nested elements.  The issue manifests as a jarring visual effect or a delay in the color change of a nested element when its parent element has a transition applied.

The bug is reproduced in `bug.css`. The solution is provided in `bugSolution.css`.

This is a subtle issue that might not be immediately apparent but can impact user experience.  The solution highlights different approaches to mitigate this problem.
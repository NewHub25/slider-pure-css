LIKE PAGE FROM https://developer.mozilla.org/en-US/docs/Web/CSS/timeline-scope

# timeline-scope:

The timeline-scope CSS property modifies the scope of a named animation timeline.

By default, a named timeline (i.e. declared using scroll-timeline-name or view-timeline-name) can only be set as the controlling timeline of a direct descendant element (i.e. by setting animation-timeline on it with the timeline name as its value). This is the timeline's default "scope".

timeline-scope is given the name of a timeline defined on a descendant element; this causes the scope of the timeline to be increased to the element that timeline-scope is set on and any of its descendants. In other words, that element and any of its descendant elements can now be controlled using that timeline.
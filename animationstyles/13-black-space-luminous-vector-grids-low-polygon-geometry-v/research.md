# Research — Early polygonal computer animation

## Style fingerprint

- **Visual/material vocabulary:** vector grid; faceted low-poly mesh; hierarchical joints; Gouraud shading; wireframe tunnel; primitive particle trail; mathematically smooth spline camera.
- **Motion logic:** Use rigid joint rotations and visible facets first, then introduce smooth interpolation as the bird accelerates; keep the grid vanishing point and camera roll exact.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [ACM SIGGRAPH — Computer Animation Chronology](https://history.siggraph.org/wp-content/uploads/2021/05/SVR-Issue-80-1992-Historical-Computer-Animation.pdf)
- [ACM SIGGRAPH — Early History of French CG](https://digitalartarchive.siggraph.org/wp-content/uploads/2018/03/Welker_paper.pdf)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.

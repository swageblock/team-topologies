# Part Two

## Static Team Topologies
1. Have you experienced situations where team structure seems to have detracted from our ability to successfully execute?
2. Have we made any team structure changes that informed only by an immediate need and wasn't made based on team interactions, handoffs, architecture, and cognitive load?
    - Have you seen these changes be successful long term or was intervention necessary?
3. Do we have full stack developers that would eliminate the need for a cross functional team makeup? 
    - When have we seen supporting evidence of this?
    - When have we seen contradictory evidence of this?
    - What devops team makeups have we experimented with?  Where were the results?  
    - What cultural barriers exist to us making cross-functional teams?
    - What space barriers exist to us making cross-functional teams?
    - What leadership/control barriers exist to us making cross-functional teams?
4. Do we desire our development teams to have situational awareness of the software running in production?  Do teams have the necessary expertise to succeed in this endeavor?
5. Do we have the necessary sensing built into the process and org structure to detect the need for change?
6. Does your team's makeup/design impact the success of other teams positively or negatively?  How could it improve?
7. Do your team's varied practices encourage or erode cross-team trust/confidence?
8. What are the tradeoffs among team organization strategies and which do we use today: Feature Teams, Product Teams, Cloud Teams, SRE Teams?
9. Is our cloud approach embracing the opportunities for self service that cloud offers when appropriate?  When is this appropriate?
10. Where do we find ourselves in the matrix presented on page 73?
11. Are we able to detect when teams capabilities are necessitating interactions with other teams?
12. Do we have the visibility necessary when teams interact to take action when the interactions indicate problems?
13. Does our organizational structure have a velocity (speed and direction)?

## Four Fundamental Team Topologies
1. What are teams that fall into the categories provided?
    - Stream-Aligned Teams
    - Enabling Teams
    - Complicated SubSystem Teams
    - Platform Teams
2. What characteristics apply to the teams that you categorized in each of these?
3. Do we have clear organizational Roles?
    ### Stream-Aligned Teams
    page 81 "Team aligned to a single, valuable stream of work;... single product or service, set of features, single user journey, or a single user persona." 
    - Are our SAT's aligned to a valueable stream of work?
    - Are most of our teams SAT's?
    - How much coordination is required when working with Service Teams for the SAT?
    - Do we have the capabilities required for a SAT defined to ensure effective team membership and size?
4. How does the proposed Stream-Aligned team compare/contrast with Product and Feature teams from the previous chapter?
5. Are there any expected behaviors that we do/don't do today on our teams that would be beneficial or not?
    ### Enabling Teams
    page 86 "... specialists in a given technical domain ... they help bridge [the] capability gap."
    - Which are our enabling teams?
    - Do they do well at not becoming ivory tower centers of knowledge?
    - Do we have any enabling teams that SAT's have built a permanent reliance on?
    - How do our enabling teams discover the needs of SAT's?
    - Would enabling teams need to have very deep understanding of business direction/strategy in order to guide research and recommendations?

6. Should we consider adoption of any of the metrics (or derivatives) from page 89?

    ### Complicated Subsystem Teams
    page 91 "responsible for building and maintaining a part of the system that depends heavily on specialist knowledge, to thae extent that most team members must be specialists"
    - Which are our CST's?
    - What specific capabilities do these teams take on from SAT's?
    - Are there examples where we have tried to create teams like this but ended up evolving into SAT's with a reusable subcomponent?
7. Are there areas where we should be leveraging CST's?

    ### Platform Teams
    page 92 "purpose [...] is to enable stream-aligned teams to deliver work with substantial autonomy"
    - Which are our platform teams?
    - Which qualities are we pursuing with our platform teams?
        - reliable, usable, and fit for purpose
    - Do we follow the tenant that platform "teams should always regard themselves as pure service providers for the domain teams?"
8. What is in our platform?  Does this match our need?
9. Does our platform team include SAT feedback as a process?
10. Do we have enough people on our platform teams?
11. Does our platform team include the capabilities to deliver the platform?
12. Is the platform team really a SAT for the business' SAT's?
13. Do we tend toward creating silos for testing, dba, network, UX, architecture, etc?
14. How are these silos akin to and different from CST's?
15. Do we tend to build a platform that is too large?
16. Do we tend to envision too many things as platforms?
17. Is our platform being built for the developers?
18. Does our platform have a Dev Ex that meets with the needs for autonomy that the business needs?
19. Do we have a plan for documentation/training?
20. Are we treating our platform like a product with a customer base?
21. What component teams would we want to move into the platform?
22. What would migrating tool teams to enabling teams look like in our organization?
23. Do we have support teams that need to be aligned to SAT's?
24. Are architects focused enough on API design, effectiveness, and shaping interactions between teams?

## Choose Team-First Boundaries
1. How would you characterize our architecture?  High Coupling?  Monolithic?
2. What are bounded contexts?  How could they be used in our system architecture and application design?
3. Do we have a distributed monolith?
4. What modes of monolithic design have you seen in our systems?  (page 112)
5. What is our current method to define software boundaries?
6. Could splitting subsystems by compliance requirement be a good approach for us?
7. How should we consider team and software boundaries with remote teams?
8. Should we be considering a remote-first approach?
9. Are there any risk fracture planes that we should be considering?
10. Are there other fracture planes that might make sense for us?
11. 

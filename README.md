# 260-manifesto
ANTI AGILE
# 268 Manifesto

## Principles for Effective Software Development

### Introduction:

Are you tired of the endless Agile meetings that seem to go nowhere? Does the constant push for "quick releases" make you feel like you're duct-taping a spaceship? Are you fed up with resolving code conflicts between two tasks you wrote yourself, like a double personality patient? Welcome to the 268 Manifesto, the anti-Agile manifesto. Here, we cut through the fluff and get back to basics—clear requirements, real testing, and quality over chaos. We're done with the "Agile" hamster wheel. Let's bring some sanity back to software development, shall we?

### Manifesto:
- **Write Automated Tests That Not Only Detect Bugs but Also Report Them Automatically**: This cuts down on manual bug reporting and gets those pesky issues identified and resolved faster than you can say "debugging hell."
- **Quality over Processes**: Look, we'd rather ship something that works beautifully than something that ticks all the bureaucratic boxes.
- **Don't Create Easter Eggs**: If there's no requirement, don't get cute. Save the surprises for your Easter basket.
- **Don't Promise the Stars to Customers**: Set realistic expectations. Overpromising leads to underdelivering, and nobody wants that.
- **Customers Are Not Testers**: Your users should be enjoying your product, not finding bugs. That's your job.
- **Automate What Can Be Automated**: Work smarter, not harder. Automate to streamline and reduce manual labor.
- **Avoid Vanity Rules**: Rules for the sake of rules? No thanks. If it doesn't improve quality, it's out.
- **Value Architecture over Quick Customer Release**: Solid, scalable architecture beats a rushed release every time. Patience, folks.
- **Make the Requirement a Task**: Each requirement should be treated as its own task, ensuring clarity and focus.

### Key Practices:

1. **Write Requirements, Not Tickets**:
   - Clear, detailed requirements are the name of the game. They capture user needs and business value, including those all-important safety-critical or security-critical requirements.
   - Write them with testing in mind. If you can't test it, why bother writing it?
   - Log the location in the code with comments with the implemented requirement unique ID and log the test to the requirement. This ensures traceability and accountability for each change made.
   - Generate a document that shows the implementation of the requirement locations in code and the status of the testing.
   - You don't need a meeting for each requirement. Assign it to a person; if they don't understand, they can ask questions. If the requirement is misleading or ambiguous, rewrite it better.
   - Avoid the ambiguity and lack of context that traditional tickets often bring. Make it crystal clear.

2. **A Bug Needs a Requirement**:
   - Every bug ties back to a requirement it flunked. This way, you know what went wrong and why.
   - If there’s no requirement for a new bug, create one.
   - If a bug was not detected in the development process, create a test to catch it in the future.

3. **Be Specific on Requirements**:
   - Spell out what needs to be achieved, including acceptance criteria and expected outcomes.
   - Specificity avoids misunderstandings. Everyone knows what they're shooting for.

4. **Focus on Automated Testing When Possible**:
   - Use automated testing tools and make sure every developer can run these tests.
   - Test based on the requirements to make sure the software behaves as expected.
   - Focus on behavior over unit tests that just cover the code. Simply running a function in a unit test doesn't prove it meets user needs. Ensure the application behaves correctly in real-world scenarios.
   - Automated tests should cover all requirements comprehensively and must be runnable by individual developers in automated environments.

5. **Don't Test Your Own Code**:
   - To maintain objectivity and effectiveness, developers shouldn't write the behavior tests for their own code.
   - Include a test engineer in the team who can write automated test code focusing on behavioral aspects of the software.
   - Develop tests for the requirement in parallel, and only close the requirement when the test is created and passed.
   - Independent testing helps spot issues the original developer might miss. This should be the only way to mark a requirement as done.

6. **Optimize Meetings**:
   - If you don't think you need to be in the meeting, excuse yourself.
   - If the team is co-located and sitting together, skip the formal meetings and talk directly.
   - Remind people at the start of the meeting or between topics that they can be excused if they have nothing to add.

7. **Quality Focus in Code Reviews**:
   - During code reviews, focus on quality. Ditch the vanity metrics and keep your eye on the requirements.
   - Implement practices like automated testing and continuous integration to keep standards high.

8. **Value Architecture over Quick Customer Release**:
   - Make architectural decisions that support both current and future needs, even if it means delaying the release. Technical debt is real, and you aren't the U.S. government—so don't just kick the can down the road.
   - Developers come and go, so the architecture needs to be not just robust, but also easy for new developers to pick up.
   - And let's be clear: the project manager can organize timelines and resources all they want, but they don't get to dictate the architecture. That's the realm of the developers and architects who understand the intricate details and long-term implications.

9. **Specialization within the Team**:
   - Create specialist roles within the team. Assign requirements to the right specialists to get the best outcomes. Let's leave the pre-industrial tribal behavior where everyone does everything in the past—specialization exists for a reason.
   - If you want redundancy because developers come and go, use code reviewers and testers to keep other team members up to date with changes.
   - Bugs should be fixed by the person responsible for the requirement, using their expertise to solve issues efficiently.

10. **Avoid Breaking Up Requirements into Over-Simplified Tasks**:
    - Don't break down requirements into overly simple tasks. It just adds overhead during full testing.
    - Small tasks lead to more pull requests and more time spent resolving conflicts. You'll feel like a double personality patient trying to merge code from two tasks you wrote yourself.
    - Make the requirement the task.
    - When possible, fix and implement multiple bugs/requirements together to streamline the testing process and reduce overhead.

### Conclusion:
The 268 Manifesto is all about enhancing the effectiveness of software development. By focusing on clear requirements, independent testing, automation, and avoiding vanity rules, we're all about delivering high-quality software that meets user needs and adapts to changing circumstances. Automated tests that detect and report bugs cut down on manual bug reporting and speed up issue resolution. Emphasizing robust architecture over quick releases ensures long-term scalability and maintainability. Direct communication should replace unnecessary meetings when the team is co-located. Automated tests must be runnable by individual developers to ensure flexibility. Specialization within the team ensures the best outcomes, with the person responsible for the requirement fixing the bugs. Avoiding the breakup of requirements into overly simple tasks, making the requirement the task, and ensuring parallel test development reduces overhead and streamlines the process.

# PR Code of Conduct

## As the Commit Author
- **DO** Verify that your project already passes extensive linting. Here is an some awesome list of <a href="https://github.com/dustinspecker/awesome-eslint">reputable eslint configs</a>. Linters should ensure, deprecated code is removed, unused dependencies removed, as well as many more DON'T automatically that we don't need to list them here.
- **DO** Keep security in mind, can't afford it to be an afterthought shipping product. <a href"https://dev.to/nirajkvinit/application-security-best-practices-defensive-programming-3o87"Security Best Practices</a>
- **DO** Passes all tests locally, ideally this is part of a git hook, and avoids slowing down pipeline builds unecessarily
- **DO** Keep your code concise! The less code there is to read, the less mental energy it takes to understand it. But remember to focus on conciseness of thought, not size. <a href="https://medium.com/geekculture/stop-playing-code-golf-at-work-ef77a310f450">Code golfing</a> is not encouraged.
- **DO** Write self-documenting code. Self-documenting code is code written in such a way that it already transmits a lot of information about what it is, what it does, and how it's implemented. This can be accomplished by making sure functions are properly named, correct verbiage is used, function signatures and types are defined and enforced, etc.
- **DO** Ensure you are using software development patterns such as modular CSS, using composable function patterns, managing data in contexts, and so on.
- **DO** Preemptively comment on your own PR if you realize a certain portion needs extra attention or is expected to spark discussion.
- **DO** Tag your PRS with WIP if the PR is intentionally incomplete. But, the act of creating a PR means you are inviting reviews so you should clearly mark the incomplete portions of your code as TBD if you do not want them to be commented on.
- **DO** Expect to receive multiple rounds of comments. It's likely you will need to re-check your PR after another round of commits because certain changes may draw more attention to other parts of the code
- **DON'T** Combine large refactors along with feature changes in the same PR. These two things should be done as two steps and evaluated individually. If the nature of the ticket requires both in the same PR, try to keep refactors and changes separated by commit.
- **DON'T** Forget to respond to comments before merging your PR. Sometimes a comment does not require code changes, but simply asks you to acknowledge that you read it, affirm a yes/no question, or clarify a client requirement.
- **DON'T** Be afraid to ask for clarification, push back on comments, or suggest rescoping work into future PRS. As the developer of the code you may be aware of some special case that the reviewer does not see immediately.
- **DON'T** Be anxious about PRs being perfect. PR can be useful as a public forum to generate discussion and ideas around a better solution.

## As a Code Reviewer
- **DO** Read the ticket in detail. Sometimes a question or concern that you have is already answered directly in the ticket.
- **DO** Explain your reasoning when suggesting changes. Talking it out can help both reader and author understand the motivation for such a change. Similarly don't just point out a mistake or bug in the code, but also suggest a potential fix in the comments
- **DO** Recognize pair programming opportunities. Sometimes it's better to pick up the phone and reach out to the author directly and work on a piece of code together rather than lengthy back-and-forth on the PR.
- **DO** Ask clarifying questions. Sometimes these lead to improved commenting around tricky parts of the code. Other times, they don't require any action, but will be a useful piece to reference if we need to revisit this PR in the future
- **DO** Make clear when suggestions or concerns are non-blocking. Sometimes you can mention something that might be a code smell or teaching moment, but does not require additional commits. In these cases, communicate your intent not-to-block clearly.
- **DO** Keep it civil. Code reviews are meant to improve the overall quality of the code, not a competition to find the most mistakes or try to embarrass the author.
- **DO** Take consideration of the urgency of the ticket before asking for lengthy refactors or expanding scope of the ticket. If a PR needs to be tactically merged, approve the PR and create new cleanup tickets under the TECHDEBT label
- **DO** use the Like button if you see an existing comment which already says what you wanted to say. This helps keep the PR more readable and avoids cluttering up the PR thread with small comments that just say things like "I agree"
- **DON'T** Commit over the author's code and rewrite it without talking to them first. There are many, many reasons why this is unproductive both from a technical and social perspective.
- **DON'T** Confuse opinion and fact. Opinions are great and encouraged, but should be argued for via persuasion, not as a blanket statement. See also <a href="https://medium.com/swlh/strong-opinions-loosely-held-might-be-the-worst-idea-in-tech-c3e65cb512f1">Strong Opinions Loosely Held Might be the Worst Idea in Tech</a>
- **DON'T** Be too dogmatic about certain practices. Goals are focused on delivering the best product experience for our clients, writing code is only a means to an end, but not the end itself. As such, when making pronouncements about what code MUST or MUST NOT do, this should be backed up with reasoned tradeoffs that lead to that decision from a **product** perspective.

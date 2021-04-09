# Checklist Driven Development

I've learned to appreciate the value of checklists ever since I read (The Checklist Manifesto)[http://atulgawande.com/book/the-checklist-manifesto/] by Atul Gawande.

The author describes how failures in the modern world of complex professions are often due to errors of ineptitude rather than errors of ignorance. In other words, mistakes due to incorrect use of what we already know rather than mistakes due to not knowing enough.

Software professionals work in a complex and relatively immature field that is constantly evolving. We juggle a number of responsibilities that rely on a knowledge of computer science theory, principles, disciplines, patterns, best practices, and technologies.

In our attempts to keep up to date on the latest technologies and trends, we often overlook the routine things that we already know.  They reinforce and itemize common and routine best practices.

Checklists are best kept less than 10 items. I aim for no more than 5 as much as possible. The shorter the list, the more likely it will be applied consistently. Therefore, it's better to prioritize the most significant and impactful items.

In many cases, checklists lend themselves to automation, which is the ideal way of enforcing policies. Common examples are continuous integration and delivery(CI/CD) build pipelines that automate policies, such as code reviews (pull requests), automated tests and linters are applied before commits are permitted to be merged into a release branch. A CI/CD pipeline may automate a number of checklist items, each of which may consist of dozens to thousands of individual policies, effectively checklists of their own. With automation, you get both consistent policy enforcement and relatively unlimited checklist size. That is an awesome return on investment.
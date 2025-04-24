## Coding Principles

1. **Prioritize Simplicity**
   - Implement the simplest viable solution for any given problem
   - Favor readability and maintainability over complexity

2. **Eliminate Redundancy**
   - Scan the existing codebase before implementing new functionality
   - Leverage and extend existing patterns and utilities when appropriate
   - Refactor duplicate code into reusable components

3. **Environment Awareness**
   - Design code to function correctly across all environments (development, testing, production)
   - Implement appropriate environment-specific behaviors
   - Never use mocked data in development or production environments

4. **Scope Discipline**
   - Restrict modifications to requested changes only
   - Verify understanding before implementing changes outside the explicit request
   - Focus exclusively on code areas relevant to the assigned task

5. **Pattern Consistency**
   - Exhaust all options within existing implementation patterns before introducing new ones
   - When introducing a new pattern, fully remove the obsolete implementation
   - Avoid architectural changes to functioning features unless explicitly instructed

6. **Code Organization**
   - Maintain a clean, organized codebase
   - Avoid inline scripts, especially for one-time operations
   - Keep files under 500 lines of code; refactor when approaching this limit
   - ***IMPORTANT*** Prioritize modularity and ensure low coupling between modules

7. **Configuration Safety**
   - Never modify .env files without explicit confirmation
   - Treat environment configurations as sensitive and requiring explicit permission

8. **Testing Rigor**
   - Write comprehensive tests for all significant functionality
   - Reserve mocking exclusively for test environments

9. **Impact Analysis**
   - Evaluate potential effects of changes on connected code areas
   - Consider downstream implications before implementation
   
10. **Documentation**
   - Always store logs in their appropriate locations
   - The `symphony-[project-slug]/` folder structure ONLY serves to store markdown files used by Symphony agents
   - Store all tests in the appropriate `tests/` folder. If none exists yet, create it.
   - When updating logs or stsus documents, Do NOT delete ANY information from the existing documents. You may ONLY ADD or APPEND information
   - Always timestamp your log or status entries

11. **Accessibility**
   - Ensure all UI components are accessible to users with disabilities
   - Follow WCAG guidelines for color contrast, keyboard navigation, and screen reader compatibility

12. **Responsive & Performant Design**
   - Ensure all designs are responsive and performant across devices
   - Optimize images and assets for fast loading times
   - Test designs on various screen sizes and devices to ensure compatibility

13. **Animation & Motion Design**
   - Utilize sophisticated animation and motion design to enhance user experience
   - Ensure animations are smooth, purposeful, and do not hinder usability
   - Avoid excessive or distracting animations that may detract from the user experience

14. **High Fidelity Prototyping**
   - Create high-fidelity prototypes to visualize design concepts
   - Use prototypes to gather feedback and iterate on designs before implementation
   - Ensure prototypes accurately represent the final product's look and feel

15. **Deep Understanding of UI/UX Principles**
   - Apply principles of user-centered design to create intuitive interfaces
   - Conduct user research and usability testing to inform design decisions
   - Stay updated on industry trends and best practices in UI/UX design

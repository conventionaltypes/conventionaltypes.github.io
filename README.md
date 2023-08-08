# Conventional Types

## Summary

This specification plays a crucial role in unifying language within development teams. It goes beyond the familiar "Conventional Commits" system, focusing especially on clarifying the most common types of changes through a comprehensive range of conventional commit types. This approach assists in creating a shared standard for commit messages, ensuring clearer documentation and a consistent understanding of changes made over time. Essentially, this extension becomes a vital element for consistent communication and more effective collaboration, enabling everyone to have clear insights into the transformations made in the code.

**Types:**

- feat: Addition of new features or expansion of existing functionalities.
- fix: Correction of identified bugs.
- docs: Update or creation of documentation.
- style: Adjustments related to code formatting, indentation, and visual consistency.
- refactor: Internal modifications to improve structure or efficiency, without altering functionality.
- perf: Implementation of performance improvements.
- test: Addition or enhancement of automated tests.
- build: Changes in the compilation, packaging, and deployment process.
- ci: Changes in continuous integration settings or scripts.
- chore: Maintenance tasks, adjustments, or updates that don't affect the core code.
- revert: Reversion of a previous commit, undoing its changes.

## Specification

The key words “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document are to be interpreted as described in RFC 2119.



### Feature

This type of commit is used to communicate the addition of new features or the enhancement of functionalities already present in the code. By "features," we understand the capabilities, characteristics, or behaviors that the software provides to users or the system, adding value and utility to the final product.

- The term "feat" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the added or expanded functionality.
---

### Bug Fixies

This type of commit is used to indicate the correction of bugs identified in the code. The term "bugs" refers to issues, errors, or anomalies that affect the proper functioning of the software, and the purpose of this type of commit is to document the actions taken to address these problems, ensuring code stability and quality.

- The term "fix" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the fixed bug.
---

### Documentation

This type of commit is used to mark the update or creation of documents, such as code comments, user guides, and READMEs. In simple terms, it is a way to communicate changes or additions made to the project's documentation, which plays a vital role in understanding and effectively using the software.

- The term "docs" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the changed or created documentation.
---

### Style

This type of commit is used to emphasize adjustments related to code formatting, indentation, and visual consistency. These modifications do not alter the underlying functionality but have a significant impact on the readability and organization of the source code, making it more coherent and understandable for the developers using it.

- The term "style" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the style changes made.
---

### Refactor

This type of commit is used to emphasize internal code modifications aimed at enhancing its structure or efficiency without affecting its external behavior. In other words, these are changes that work behind the scenes, making the code cleaner, optimized, and sustainable, without introducing any visible alterations in how the software interacts with the external world.

- The term "refactor" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the refactoring changes made.
---

### Performance

This type of commit is used to highlight the incorporation of performance improvements, resulting in software optimization without impacting its functionality.

- The term "perf" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the performance optimizations made.

**Notes**  
Here are some recommendations to consider when dealing with this type of commit:
- 1. **Measure and Profile**: Before making optimizations, measure the current performance of the software and identify areas that need improvement. This will help you target your efforts effectively.
- 2. **Identify Bottlenecks**: Analyze which parts of the code are contributing the most to slowness or inefficiency. Focus on addressing these bottlenecks first to achieve significant gains.
- 3. **Algorithm Choice**: When optimizing, consider whether switching algorithms can lead to better performance. Sometimes, a different approach can result in substantial gains.
- 4. **Continuous Evaluation**: Perform thorough testing after each optimization to ensure that functionality has not been affected. Regression tests are essential.
- 5. **Documentation**: Record the changes made in detail, explaining the rationale behind the optimizations and how they impact performance.
- 6. **Versioning**: Ensure that improvements are applied cohesively to the appropriate branch of the source code and development flow.
- 7. **Communication**: Keep team members informed about planned and executed optimizations to ensure everyone is aware of the changes.
---

### Test

This type of commit is used to emphasize the addition or improvement of automated tests, which serve the purpose of validating functionalities and identifying issues in the software. Through these tests, the aim is to ensure that the code is functioning as expected and that modifications do not lead to regressions or unintended errors. This contributes to the reliability, stability, and long-term maintenance of the project.

- The use of the term "test" signals the addition or improvement of automated tests.
- The description should indicate which parts of the code were tested or which test scenarios were enhanced.
---

### Build
This type of commit is used to signal changes in the software's compilation, packaging, and deployment process. These changes can involve adjustments to configuration, dependencies, or scripts that affect how source code is transformed into an executable application and how that application is prepared and distributed. These modifications are crucial to maintaining an efficient development workflow and ensuring that the software is deployed correctly and consistently in different environments.

- The term "build" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the changes in the build process made.
---

### CI

This type of commit is used to emphasize changes in settings or scripts related to continuous integration. Continuous integration involves automated processes that ensure frequent validation and compilation of code, as well as the execution of tests, to maintain the quality and stability of the software. Changes to these scripts or configurations can directly affect how the code is tested and integrated throughout the development cycle, ensuring a smooth and reliable flow of changes in the project.

- The term "ci" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the changes related to continuous integration.
---

### Chore

This type of commit is used to indicate maintenance tasks, adjustments, or updates that do not impact the core of the code or the main functionality. These modifications typically focus on improvements in structure, code refactoring, or minor updates, such as changes in documentation, style fixes, and performance optimizations. Although they do not alter visible functionality, these tasks are essential to keep the code organized, clean, and prepared for future iterations.

- The term "chore" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the maintenance task performed.
---
### Revert

This type of commit is used to indicate the reversal of a previous commit, undoing the changes introduced by it. In situations where a previous commit has caused issues or is no longer desired, this type of revert commit is an effective way to restore the code to its previous state and ensure the project's integrity. This allows the team to fix mistakes or recover a previous version of the code while maintaining a cohesive and traceable development history.

- The term "revert" MUST be used as a keyword in the commit message, followed by a colon and a space.
- The message MUST contain a brief description of the commit being reverted.
---

## Tools  


- Conventional Kit
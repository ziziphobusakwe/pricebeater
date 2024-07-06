### Feature branching: 
  - Create a new branch for each new feature & only merge to main once feature implementation, testing & reviews are done
    - Keeps existing solution stable by isolating changes
        - Reduces risk of breaking changes 
        - Easier rollback & bug tracking 
        - Better management of releases 
    - Improves efficiency by enabling development of features in parallel 
    - Improves quality by simplifying code reviews

## Branching & workflow strategy 
 - Main branch: 
   - Production-ready branch. 
   - Only thoroughly tested and stable code (from Int branch) should be merged here.
 - Int branch: 
   - Integration branch. 
   - Only thoroughly tested and reviewed code (from feature branches) should be merged here. 
   - Facilitates integrating features and ensuring they work well together before pushing to the main branch.
 
 
## Branch naming guidelines 
 - feature/short-description
 - bugfix/short-description
 - hotfix/short-description
 - improvement/short-description
 - refactor/short-description
 - experiment/short-description
 - docs/short-description

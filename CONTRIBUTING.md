#Pull Request Pre-Checklist

### Formatting & Syntax

- [ ] Did you use Prettier while in development? 
- [ ] Were eslint rules used in development? 
- [ ] Does the code under review pass linting with no errors? 
> Prettier is the preferred tool for code formatting. https://github.com/prettier/prettier
> The eslint rules for self show are encouraged to be used, and found here: https://github.com/colonyamerican/portico/blob/develop/applications/self-show/.eslintrc

### Documentation 
- [ ] Is the code under reivew clear in what action(s) it performs?
> Code under review should be structured so that it is clear in what action(s) it performs. Compacted, obsfucated, or shorthanded code should be first submitted in a easily read state when under review.
>
> If this is a new repo/project/product on boarding documentation is expected to be completed prior to on boarding new developers. 
> If this is an API documentation is required.

### Coding Style
- [ ] If this code has shared functionality, has it been moved to a common/lib? 
> If a method must be used outside the original file more than once, it should be included in a common/lib folder. 

### React Component Guidleines 
- [ ] If the code under review is a React component, does it comply with each of the items below?
> New components must extend React.Component. 
>
> Proptypes should be imported separately, as they have been moved in React 16. Introduced in React v15.5.0 https://reactjs.org/blog/2017/04/07/react-v15.5.0.html
>
> Use of stores in pre-existing components is permissible. 
>
> Use of stores in new components is discouraged. 
>
> Use of Flux in new components is discouraged.

### Test coverage 
- [ ] Does the test coverage of the code under review meet or exceed previous levels of coverage?
> Coverage should not dip below the threshold prior to your pull request. 
> The iterative long term goal of test coverage is 80-90% Coverage. 

### Dependencies
- [ ] Are any environment changes or dependencies required for the code under review to execute properly? 
> Environment variable changes, removal/addition of npm packages, or any such change(s) required for the code under review to execute should be made clear in the pull request. 

### What is the Pull Request/Peer Review Process? 
Click [Here](PULL_REQUEST_PROCESS.md)


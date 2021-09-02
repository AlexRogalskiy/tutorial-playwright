# Applitools Tutorial - Playwright

Get started with Applitools Eyes visual testing with these examples of using the [Playwright](https://playwright.dev/) and the [Eyes Playwright SDK](https://www.npmjs.com/package/@applitools/eyes-playwright).


## Getting Started

### Installing Dependencies
```
npm install
```

### Running Tests
```
npm test
```

## What's inside?

### Test Examples

This repository includes a variety of examples on how you can use Applitools Eyes with your Playwright project.

- Basic: running the Eyes SDK without a manually configured runner
- Classic: running the Eyes SDK with the Classic runner (locally)
- Ultrafast: running the Eyes SDK with the Applitools Ultrafast Grid (cloud)

### GitHub Action Workflows

Also included are two separate GitHub Actions.

- tests.yml: runs the suite of tests whenever changes are pushed to the main branch or whenever a pull request is targeted to the main branch
- updates.yml: runs daily via cron schedule updating all project dependencies

Note: updates.yml is intended to be a tool for Applitools to maintain this tutorial with it's limited depdencies and scope. It's not recommended to automatically upgrade all dependencies without process and proper review.

## Add Applitools Eyes with your Playwright project

Learn more about how to install and integrate the Eyes SDK with our [Playwright tutorial](https://applitools.com/tutorials/playwright.html)!

<https://applitools.com/tutorials/playwright.html>

## More Information

Learn more about Applitools [Eyes](https://info.applitools.com/ucY77) and the [Ultrafast Test Cloud](https://info.applitools.com/ucY78) at [applitools.com](https://info.applitools.com/ucY76).

More about the Eyes Cypress SDK:
* https://www.npmjs.com/package/@applitools/eyes-playwright
* https://applitools.com/docs/api/eyes-sdk/index-gen/classindex-playwright-javascript.html

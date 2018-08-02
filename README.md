# Proxycrawl.com Node JS engineering test

Welcome to the test.  
This test is created to show your skills using javascript and Node.  
Please avoid using any dependency unless strictly necessary.

## Instructions

1. Create a free account in [proxycrawl.com](https://proxycrawl.com)
1. Fork the repository
1. Solve the problem (see below)
1. Commit to your fork `master` branch
1. Submit your forked repository solution with your CV to: jobs [at] proxycrawl [dot] com

If your solution fits our code quality requirements, we will reply to your email with the next steps.

Make sure to have fun while doing it!

## Problem to solve

Please avoid using any dependency unless strictly necessary.

Using the [ProxyCrawl API](https://proxycrawl.com/dashboard/docs) load any url from the internet (you are free to choose), parse the contents and extract 3 relevant things. Return those things as a JSON.

Here is an example for crawling the following Amazon url: [https://www.amazon.com/gp/product/B00004TZY8/](https://www.amazon.com/gp/product/B00004TZY8/). Once the node script is executed, it should print back something like the following:

```json
{
  "title": "Mattel Games UNO Card Game",
  "price": 4.99,
  "reviews":  2225
}
```

The data you display is up to you and not relevant for the test result as soon as it's accurate to the page.

### Things we evaluate

- Approach taken
- Coding style
- Coding length
- Dependencies (if any)
- Tests (if any)

---

ProxyCrawl

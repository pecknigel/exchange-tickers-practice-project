# Suggested Tasks

***This document is a work in progress - November 2024.***

Suggested tasks to complete.

This project is provided for learning and practice. Use it as you see fit - however works for your learning.

If you prefer more structure, the tasks below can provide that.

Ongoing support and guided learning is available from Nigel via the [main website](https://prescriptionfree.academy/).

## Essentials

The following tasks are considered essential. They set up the basic functionality of the tickers.

### Step 1: Generate Random Prices

Set up a routine that generates random prices for a set of symbols. The symbols should each be three capital letters.

### Step 2: Output Data to STDOUT

Now that you have data, make it available by outputting it to the STDOUT (standard out) stream.

*Implementation Considerations*

Use `process.stdout.write` to print to STDOUT (standard out).

Consider putting this new code that makes the call to generate the data and output it in a separate file to the code for doing all the work (often called a module).

That way you can reuse your module in other ways. It’s not tied to the way that it’s used.

It’s also just good practice to organise your code in this way, so it’s separate and each piece has a particular responsibility.

Since this is a way to call your program, add a script to your `package.json` such as:

```
“start”: “node dist/index.js”
```

### Step 3: Persist the Prices and Adjust Them Over Time

[More to come…]

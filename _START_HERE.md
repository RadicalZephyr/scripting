# The philosophy of scripting

Scripting is a way to quickly and easily automate tasks.

I've generally seen it used for two main goals.

- Automate big processes with many pieces that go together (yes definitely do this. . . but bash is likely not the "best in class" tool for it).
- Script your work as you do it.

## Story time from my consulting days

I'd like to share a quick story from my work as a consultant. Pretty much everything about it has been changed but hopefully the essence remains.

I was tasked with generating a whole bunch of certificates for the many different environments that we were using with my client.

I hadn't done that before so my first step was exploratory. Mostly just figure out how to use the library to generate public keys, etc.

Now we had 6 environments. . . and after I figure out the commands to write I think the fastest path would have been to keep a quick list. . . and do them one at a time.

At maybe 5 minutes each it would be like 30 minutes and then I'd be done with the task.

I didn't do it that way.

Instead, I took an hour figuring out how to script it.

Why did I do it this way (when it was obviously slower)?

A few reasons:

- Accuracy. Humans make mistakes when doing repetitive tasks.
- Discoverability. I put the script that I had written into our shared developer drive so that if folks needed to understand an issue later. . . they could literally read what I had done.
- Repeatability. . . let's talk more about that one.

It turns out. . . I noticed a mistake I had made in my script the next morning after reading a bit more about it (turns out programming is hard).

I made the change in my script. . . and re-ran it.

Cool. So now with the first two advantages (which in my opinion are already #worth), now we are even on the cost function too.

But it gets better. . .

Someone from a different department called me all frantic because the certs weren't working. . . it turns out that they needed them generated in a slightly different way.
The person on the other end of the line sounded so miserable telling me that I would need to redo this work.

I told him it was all good because I had scripted it.

3 minutes later I was done, having made the change that he requested.

So think about that accuracy again. . . if I had just manually done it, what are the odds the first batch were all correct?

I'd say, pretty high. I'm generally pretty careful with code. But the third batch? IDK. . .

Anyways. . . theirs a 4th reason.

- Scripting is a skill that you can practice and improve.

What if in the future you are as fast as scripting it as if you had done it manually?

What if you are faster?

+++
date = '2025-01-02T10:23:21+01:00'
title = 'Alignment or why we need to think about AI safety'
+++

I want to begin this blog with an outline of the problem with AI and why we need to pay attention to AI safety.

Recently, I caught up with a friend who countered my interest in AI safety by claiming that this focus was “so German”—always overly cautious, regulating everything too much, and thereby slowing down innovation and blocking AI’s potential. While his argument has some merit, I believe there’s a deeper dimension to how AI could go wrong—one that goes beyond misuse, which was essentially his concern. This dimension is referred to as the alignment problem, and it’s what we’ll explore today.

### Machines these days

Let’s start with a simple example: an old-fashioned machine like a cash machine. Cash machines today often have digital displays, but their behavior is fairly straightforward. The machine reads the user’s card, asks for a PIN and the desired withdrawal amount, and then dispenses cash. Of course, there are additional steps involved, and errors can occur, but the machine’s behavior is generally unambiguous. If it’s programmed correctly, it will always do what we expect—dispense the correct amount of cash. If it makes a mistake, the problem lies in the program, and we can fix it by correcting the code.

Now, consider a different kind of machine: the spam detector in your email inbox. What do you expect it to do? It should distinguish between spam and non-spam emails. But how does it decide what is spam? The detector has to learn this distinction.

We train the spam detector by providing examples of emails that are spam and others that are not. Without going into technical details, you can imagine how you might judge an email as spam—certain features like generic greetings (“Dear User…”) or offers to buy something might signal spam. The detector learns these features and uses them to classify new emails.

But as you’ve probably experienced, the spam detector isn’t perfect. Sometimes, it flags an important email as spam—a mistake. This happens because the detector didn’t learn correctly how to distinguish between spam and non-spam emails. Unlike the cash machine, where you can fix the problem by changing a line of code, the spam detector’s behavior depends on what it learned from the examples.

### When the behavior gets more complex

As we have seen with the spam detector, when machines learn behavior, there is always the risk that they will learn something different from what we intended. This misalignment becomes even more challenging when the desired behavior involves human values or norms. How do you teach a machine values when humans themselves struggle to define and agree on them?

This is the essence of the alignment problem. You might think, “If my spam detector gets it wrong, it’s annoying but not a big deal.” But the stakes are much higher with advanced AI systems.

Take ChatGPT, for example. It also learns behavior—in this case, generating text based on your messages. But unlike the spam detector, its behavior is even less defined. You could ask it a factual question with a clear answer, or you could ask for advice, where the response depends heavily on *your* values or norms the model might not fully understand.

Now imagine AI systems far more capable than ChatGPT and might surpass human intelligence in certain areas. If such systems are not aligned with human values, they could pursue goals in ways that harm us, even unintentionally. For instance, an AI system tasked with solving a global problem might take actions we didn’t foresee, causing more harm than good.

### Why alignment matters

As we’ve seen, machines that learn behavior can misalign with what we expect them to do. The challenge is that this behavior often relies on human values, which are notoriously difficult to teach a machine. The alignment problem lies at the heart of AI safety research because misaligned AI could lead to unintended and potentially harmful outcomes.

While a misclassified email is a small annoyance, misaligned AI systems operating in high-stakes areas like healthcare, justice, or governance could have far-reaching consequences.


In the following posts, we will dive deeper into the risks of misaligned AI and examine how realistic these risks are. For now, it is enough to understand that AI safety isn’t only about preventing misuse. It’s about ensuring that AI does what we want it to do, in particular not causing (unintenionally) harm.
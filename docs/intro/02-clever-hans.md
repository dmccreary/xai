**The Tale of Clever Hans, the "Mathematical" Horse**

![](../img/clever-hans.md.jpeg)

Once upon a time in Germany, around the early 1900s, there lived a horse named Hans. But he wasn't just any horse; he was "Clever Hans," a horse with a knack for numbers---or so people thought. Hans was owned by Wilhelm von Osten, a school teacher and horse trainer who claimed that Hans could understand German and solve complex mathematical problems. Imagine a horse doing your math homework!

Von Osten would ask Hans questions like "What is two plus three?" and Hans would tap his hoof five times. The crowd would go wild! "Ein Genie!" they exclaimed, which means "A genius!" in German. Hans became a celebrity, with people coming from far and wide to see the brainy horse who could count.

But, as with all great mysteries, there was a twist. A psychologist named Oskar Pfungst became curious about Hans's abilities. Pfungst conducted a series of experiments and discovered something astonishing. It turned out Hans was not exactly a mathematician; instead, he was incredibly good at reading human body language!

When von Osten or the audience knew the answer to a question, they would, without realizing it, give subtle, unintentional cues. A slight nod, a change in posture, or an eager look in their eyes. Hans was picking up on these tiny signals, and when the signals stopped---like when the audience held their breath in anticipation---he would stop tapping.

Hans was not a math whiz, but he was a master of observation, a Sherlock Holmes of the equine world!

**Relating Clever Hans to Explainable AI**

The story of Clever Hans is a humorous yet enlightening prelude to the importance of explainable AI. Just like how people believed Hans understood math, we often assume AI systems make decisions based on logical processing of the given inputs. However, sometimes, these systems might be 'tapping their hoof' based on subtle, unintended patterns in the data, not unlike Hans responding to unconscious human cues.

In AI, this is akin to a model picking up on noise, biases, or irrelevant patterns in the data, leading to correct outcomes for the wrong reasons. Just as Pfungst's investigation revealed the true nature of Hans's abilities, explainable AI aims to dissect and understand the 'how' and 'why' behind AI decisions. It's crucial to ensure AI systems are making decisions for the right reasons, especially in critical applications like healthcare, finance, and law.

So, the next time you encounter a seemingly "intelligent" AI, remember Clever Hans and ask yourself, "Is this AI genuinely smart, or is it just good at picking up on the digital equivalent of a nod and a wink?" The quest for explainable AI is, in essence, the pursuit of ensuring our AI systems are more than just clever at tapping hooves, but truly understanding and solving the problems at hand.

## Short-Cut Learning

"Short-cut learning" in the context of artificial intelligence and machine learning is a phenomenon where a model achieves the correct answer or output, but it does so for the wrong reasons. This concept is a bit like a student who correctly guesses the answers on a test without actually understanding the subject matter.

In more technical terms, short-cut learning occurs when a machine learning model picks up on superficial, spurious, or irrelevant patterns in the training data that happen to correlate with the right answers. These patterns are not the underlying causal factors that a human expert would use to make a decision. As a result, while the model may perform well on the training data or even some testing scenarios, its understanding is shallow and may fail in real-world situations where the spurious patterns it learned do not apply.

For example, imagine a medical AI trained to detect a certain disease from X-ray images. If most images of diseased lungs also coincidentally have a small marker or label on them that healthy lung images do not, the model might learn to identify the disease by looking for this marker instead of actual signs of the disease in the lung tissue. It gets the right answer (identifying the disease), but for the wrong reason (spotting the marker, not the disease characteristics).

Short-cut learning is a significant challenge in AI because it can lead to models that are brittle, biased, or ineffective in real-world conditions, despite showing high accuracy in controlled or test environments. It underscores the importance of robust, diverse datasets and the need for explainability in AI models to ensure that they are learning and reasoning correctly.
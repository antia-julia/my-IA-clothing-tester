<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# CLOTHING TESTER

Final project for the Building AI course

## Summary

I would like to develop an AI capable of identifying clothing dimensions. Imagine a mirror with a camera at the top, allowing us to see ourselves and analyze the garment we show, whether it's pants or a shirt.

This camera will detect the product and take its measurements (product length, sleeve length, back width, waist width, hip width). Once these measurements are obtained, we will ask the customer if they can provide their own measurements, either verbally or through the same camera.

Finally, the AI will compare the measurements and tell us what our perfect size would be. If the customer wants the garment to be looser or tighter, it will suggest taking one size up or, if possible, one size down.


## Background

In our daily lives, we encounter various everyday problems, whether they are time issues, indecision, or even visual problems (people with low vision, no vision, or color blindness). This AI would solve all these problems at once.

In my case, since the COVID lockdown, I don't like crowds and whenever I can, I try to avoid them or spend as little time as possible among them. How many times has it happened to us to go to a clothing store and not have time or help from a sales assistant, as fewer and fewer people are being hired for customer service? Well, with this technology, it would be like having a virtual assistant.


## How is it used?

This idea would be implemented mainly in clothing stores, fitting rooms, or in a column in the middle of the store so that the customer can use it without needing to enter the fitting room or if they are occupied.

How to use it

1. Activation: The customer arrives and stands in front of the mirror. The user can activate the AI with a command, for example, "Hello Zara". The camera or AI will activate.

2. Initial Interaction: The AI will ask if the customer needs help analyzing a product. The customer responds yes.

3. Product Analysis: The AI proceeds to analyze the product, identifying it with its corresponding ID or SKU. For example, it might say: "This is the Logo t-shirt, black color, size S. Regular fit."

4. Size Inquiry: The AI asks if the customer needs to know if that is the correct size for them. If the customer responds yes, the AI will ask for permission to obtain their measurements.

5. Obtaining Measurements: The customer can provide their measurements orally or the AI can calculate them using its own camera.

6. Size Recommendation: Once the measurements are obtained, the AI will say: "Your ideal size is S, but if you like looser clothing, we recommend one size up. If you prefer fitted clothing, you could try one size down, but it might be tight on the back (since the AI knows your back width is 1 cm larger than the t-shirt, although this can also depend on the type of fabric if it is stretchy)."

![image](https://github.com/user-attachments/assets/6880cc49-c219-4983-a9c8-2f0f50624737)


## Challenges

There are things that this AI could not answer:

1. Products from other companies: It cannot measure products that are not from the company itself.
2. Personal preferences: It cannot tell you if the red dress or the pink dress suits you better.
3. One-size-fits-all products: For one-size-fits-all products, like hats, it could measure the circumference of your head or the hat, but it either fits or it doesn't. Asking this to an AI wouldn't make much sense.

Regarding vulnerability issues, the following situations could arise:

1. Activation without consent: The AI could activate without the customer's consent due to a problem with voice recognition, ambient noise, or because something similar to "Hello Zara" was said.
2. Accidental activation: The AI could accidentally activate while cleaning the mirror if it is touched by hand.

## What next?

I suppose that with knowledge, time, personnel, and money, anything is possible.


## Acknowledgments

Thanks to https://www.elementsofai.com/ for providing me with AI knowledge.

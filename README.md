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

If you need to resize images, you have to use an HTML tag, like this:
<img src="src="https://www.shutterstock.com/image-photo/full-length-profile-shot-young-260nw-2201187189.jpg" width="300">

![image](https://github.com/user-attachments/assets/6880cc49-c219-4983-a9c8-2f0f50624737)



This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc

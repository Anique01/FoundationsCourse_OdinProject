# Chaining Selectors

In this exercise, I focused on understanding how to chain different selectors to apply unique styles to elements that share one or more class names. The goal was to style two images, each with two class names, using chained selectors to ensure they had distinct styles despite sharing a common class. This exercise helped me reinforce the concept of chaining selectors to target specific elements in a more refined way.

### What I Did  
I was given two images, each with a shared class name, and I needed to apply unique styles to them based on their specific class combinations. I chained the class selectors for each image to ensure that the styles applied only when both classes were present:  
- For the element with both the `avatar` and `proportioned` classes, I set the width to 300 pixels and ensured the height automatically adjusted to maintain the original square proportions (using a percentage or a similar responsive approach).  
- For the element with both the `avatar` and `distorted` classes, I set the width to 200 pixels and manually adjusted the height to 400 pixels, making it twice as tall as the width (hardcoding the pixel value for height).

### What I Learned  
This exercise taught me how to chain class selectors effectively, allowing me to target specific elements with more precision even if they share a class name. I learned how to apply styles in a way that respected both shared and unique properties, such as using width and height values to control the proportions of images without hardcoding unnecessary values.

By working with chained selectors, I became more comfortable with writing more specific rules in CSS, targeting combinations of classes rather than just individual classes. This approach helped me fine-tune the styling of elements that had multiple shared and unique characteristics, ensuring they displayed exactly as intended.

Additionally, I reinforced my understanding of maintaining element proportions dynamically (without hardcoding) and the impact of hardcoding values when necessary (like the height for the distorted image).
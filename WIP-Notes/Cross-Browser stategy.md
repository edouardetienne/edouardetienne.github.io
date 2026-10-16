# Cross-browser strategy
## Device/browser compatibility matrix
planning document
clear and organised list of which device and browser combinations will be used to test the product
=> risk-based decision of what to test and what not to test
Includes
- device type
- browser
- screen size

for each feature, a mark is made in the column of the configuration that will be used for testing

## Using web analytics to prioritise testing
Answer 3 questions
- which browser did most visitors use?
- what type of device were they on? (Windos, Mac, iPhone, Android phone...)
- How large was the screen?

## Defining tiers of support
=> define priority levels:
- **Tier 1** - Full checking: the most popular configurations. 80-90% of the audience. Check every features in every release.
- **Tier 2** - Basic checking: used by a smaller, but meaningful portion of the audience. 5-10%. Make sure the core features work.
- **Tier 3** - Not supporred. Very old browsers or rare configurations. Less tahn 1% of user. Deliberate decision not to test.


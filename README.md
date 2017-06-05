This project is created in Eclipse IDE as Maven project.
It contains a cucumber feature file and its implementation for the following use case:
Feature: Search for "Nikon" @ http://www.amazon.com, sort by price : highest  to lowest and then open second item from search results.
Scenario: User can find right "Nikon" product
Given Amazon home page is open
When User searches for Nikon
And Sorts results by price : high to low
And Opens the second item
Then Product title of opened item contains Nikon D3X


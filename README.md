# Artificial Intelligence in financial risk management
	

	Final project for the Building AI course
	

	## Summary
	

	This project's goal is to provide a tool, that would allow for easier and better assessment of the financial risk. AI-based tool to help people that are investing on a 	stock markets assess the risk is the main target of this project.
	

	

	## Background
	

	When it comes to risk management, people (or in this case investors, to be more precise) often tend to (for example) overestimate possible events with very big impact on the price of asset, yet with very low probability of happening. At the same time they often underestimate possible events with small impact on the price of asset, yet with very high probability of happening and/or possible multiple occurance, effectively affecting an asset the same amout as the low probability event. That problem could be solved by an AI 'advisor' able to analyse the data and calculate the real risk and eventually advise whether or not sell/buy an asset. Also, with the AI solution we could resign from traditional methods of risk valuation and try to develop a new one, based on a real data (with possibility to use past data to train the model - we can take the data from past to train the model, where our expected result would be let's say today's price of an asset).
	

	

	## How is it used?
	

	Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
	

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
	

	Data gathering, building a simple model for first tests and looking where it goes!
	

	

	## Acknowledgments
	

	*  The [Elements of AI](https://www.elementsofai.com/) Team for giving an inspiration to think about this project
	*  The rest will come with the project's progress :)

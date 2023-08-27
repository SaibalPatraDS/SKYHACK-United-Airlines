# SKYHACK United Airlines

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/fde01eee-1d2c-42af-b272-34445b3d53f2)

As an analyst, you are required to leverage data to help in identifying opportunity areas in United’s current Food &amp;Beverage(F&amp;B) service and make recommendations which can help in increasing F&amp;B (Food &amp;Beverage) service satisfaction rate by identifying pain points for our customers and challenges in our current inventory planning


## About the DataSets

`Table  - Inflight Satisfaction Score`

This dataset captures valuable insights into passenger satisfaction levels on United Airlines flights. Highlighted rows in unison serve as the primary key, facilitating precise data correlation.

- **Flight Details:** Includes flight number, origin, and destination station codes, record locator (unique booking ID), scheduled departure date, departure gate, arrival gate, international/domestic indicator, number of legs in the trip, and mileage-related metrics (actual flown miles and haul type).

- **Satisfaction Scores:** Provides satisfaction-related data, such as survey question text, customer response scores ranging from 0 to 5, and satisfaction type (ranging from 0-3 for Dissatisfied and 4-5 for Satisfied).

- **Inflight Service Attributes:** Comprises sub-categories within the food & beverage domain, cabin code description, cabin name (economy/economy plus), entity (Latin/domestic/Atlantic), seat factor band (groups based on seat factor percentage), loyalty program level (Mileage Plus Program level), customer generation (Silent/GenX), fleet type description (aircraft type), fleet usage (mainline/express), equipment type code, UA/UAX indicator, and Wi-Fi provider.

- **Arrival Delay Information:** Contains data about arrival delay, including arrival delay minutes and delay time group.

- **Hub-and-Spoke Model:** Indicates whether the station is a hub or spoke in United Airlines' network.


`Table 2 - Customer Comments/Feedback`

This dataset contains a wealth of customer feedback and comments related to various aspects of airline services. The dataset is structured as follows:

- **Flight Information**: It includes essential flight details such as flight number, origin/departure station code, destination/arrival station code, scheduled departure date, arrival delay group (categorization of arrival delay time), and departure delay group (categorization of departure delay time).

- **Service Entity**: This column specifies whether the flight belongs to the Latin, Domestic, or Atlantic service entity.

- **Customer Comments**: The 'verbatim_text' column contains the actual comments provided by customers, offering insights into their experiences and opinions.

- **Seat Factor Information**: This dataset also classifies flights into seat factor bands, which group flights based on the percentage of seats filled by revenue passengers. This information is recorded in the 'seat_factor_band' column.

- **Survey Question**: The 'ques_verbatim_text' column provides context for the customer comments by indicating the survey question or topic related to the feedback.

- **Loyalty Program Level**: It includes details about the Mileage Plus Program level of the customers providing feedback.

- **Aircraft and Fleet Details**: The 'fleet_type_description' column specifies the type of aircraft used for the flight, such as B737-900 or B777-200. Additionally, the 'fleet_usage' column categorizes flights as either Mainline or Express.

- **Customer Response Group**: The 'response_group' column differentiates between members and non-members providing feedback.

`Table 3 - Inflight Service: Inventory Data (Business/First Class - J)`

This dataset provides essential information related to inflight service inventory for United Airlines' Business and First Class (J) passengers. Key details include flight-specific data such as flight number, departure and arrival station codes, scheduled departure date, and the entrée product's description and code. Additionally, the dataset contains valuable inventory-related data, such as planned and consumed entrée quantities. Notably, the highlighted rows represent the primary key for this dataset, enabling precise data tracking and analysis. This dataset serves as a foundational resource for optimizing inflight service planning, ensuring passenger satisfaction, and efficiently managing inventory levels

`Table 4 - Inflight Service: Pre-order Data (All Cabins - J/Y)`

This dataset provides comprehensive information about pre-ordered inflight meals across all cabin classes, including Business (J) and Economy (Y). It encompasses essential flight details such as flight number, departure and arrival station codes, scheduled departure date, and a unique booking ID known as the record locator.

Additionally, the dataset features meal-related information, such as meal short descriptions, meal groups (e.g., Entrée Hot/Cold, Sandwich, Liquor), meal categories (e.g., Breakfast, Snack, Dinner, Liquor), the carrier code (UA), cabin code (Business - J, Economy - Y), and full meal descriptions. There's also an indicator for whether a meal is an entrée (Y/N) and the quantity of pre-ordered meals.



## Solving the Problem -

1. In file_0001.ipynb, I have performed some basics plots and have tried to visualize the data, so to get an basic understanding of the data.
   
![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/5ec458c0-b783-4500-9e36-90043fa9c203)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/64aedacf-315f-4328-bc88-7cece3298deb)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/815280e6-2d78-4283-8071-b89c88ecea49)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/e03106a3-5bb7-4297-828f-3ef039e34557)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/6e1f1875-39b2-4b43-8cdd-4e0893242cc0)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/495f8718-357c-4fd9-bbb5-3ad84b8838bb)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/73338a7a-cf32-45b2-888d-acee4045d8a1)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/3afce06c-fffb-43b0-abf2-1f5a76b41174)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------


2. In file_0002.ipynb, I have tried to merge customer_comments data with satisfactory_score to data have some idea of the reviews.

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/2dfa62e7-9856-4ec2-8d73-f84b547ca543)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------


![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/881fbea8-3ce2-4e07-a1f8-eb09397a279f)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/368c7e47-e90d-4b49-bce7-be9d14904b0b)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------


![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/72e871ef-0bc6-4367-a3a5-ada7359d0042)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

3. In file_0003.ipynb, I have worked with comments data and I have processed the data.
   
   3.1. **Importing Libraries:**
   - `nltk`: The Natural Language Toolkit is a powerful library for working with human language data.
   - `stopwords`: This module provides a list of common English stopwords, which are words like "the," "and," "is," etc. that are often removed from text data during preprocessing.
   - `word_tokenize`: This function tokenizes (splits) a sentence into individual words.
   - `PorterStemmer`: This is an instance of the Porter stemming algorithm, which reduces words to their root form. For example, "jumping" becomes "jump," and "cats" becomes "cat."

   3.2. **Downloading NLTK Resources:**
   - The code begins by downloading required NLTK resources, specifically the list of English stopwords and the punkt tokenizer models.

   3.3. **Function Definition: `process_sentence`**
   - This function takes a single sentence (a string of text) as input and processes it.
   - It tokenizes the sentence into individual words using the `word_tokenize` function.
   - It defines two sets: `stop_words` (common English stopwords) and `punctuation` (common punctuation marks).

   3.4. **Text Processing within the Function:**
   - The function then iterates through each word in the tokenized sentence:
     - It checks if the lowercase version of the word is in the `stop_words` set, which contains common stopwords. If the word is a stopword, it's skipped.
     - It also checks if the word is in the `punctuation` set, which contains common punctuation marks. If it's punctuation, it's also skipped.
     - For the remaining words, it applies stemming using the `PorterStemmer` to reduce them to their root form.
   - The filtered words are collected in the `filtered_words` list.

  3.5. **Joining Filtered Words:**
   - The filtered words are then joined back together into a single string, forming the `filtered_sentence`.

  3.6. **Processing Text Data:**
   - The code snippet demonstrates how to process a collection of sentences. For each sentence in the collection (presumably stored in a DataFrame column called `verbatim_text`), the `process_sentence` function is applied.

 3.7. **Appending to `filtered_sentence`:**
   - There's a comment in the code that suggests you might want to append the filtered sentences to a list. However, there's a mistake in the code for doing this. You should use a list to store the filtered sentences and append each `filtered_sentence` to the list.



![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/69afc1a4-f4cc-4a51-b603-b8831c42208b)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

Adding the new column to the data

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/1519a5cf-12fa-4fb8-a07b-81af4b703136)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------
Using `rake_nltk` library, I have tried to find out the keywords from the comments. 

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/3c6c53b7-dd8e-4077-8be4-a2dfe6b29291)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

I have tried plotting `WordCloud` as well, 

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/a3975f54-84d8-42f5-8002-94990722c778)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/cf7b7840-daac-440f-bce8-b200ffb367c5)

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/7e40578b-b437-4b95-b6f0-5353f5eb5a15)
Satisfied Word Cloud

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/201ad9ed-02d5-4837-a7c1-a4664fa9d3f7)
Dissatisfied Word Cloud

------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

4. In file_0004.ipynb I have gone thorugh the customer comments and tried to find insights are pattern in the data.

   ![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/913c7354-5bc0-4d92-a7ea-3a2e615dd04b)
----------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------


Finally save the data to csv file further use.



 5. In file_0005.ipynb I have worked with previously save data,

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/d84e1540-6b93-4a88-849c-80152628c44e)

-----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------


![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/3123884f-ca7c-44b6-bd24-25f6c6f1fea8)

-----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------



### Conclusions :

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/8d3b6ba7-14a2-4b95-86f9-b173085bbcca)

-----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------



**For Business/First Class**

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/ea4ab95c-2383-4696-a624-93cd397330ba)

-----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------



![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/3be1d2db-fdae-4b56-afa6-fa50db36e618)


-----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------


**out of top 50 dishes finding those dishes where the perct_consumption ratio is less than mean of overall data**

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/c8e8571e-c037-49c2-b265-ef0fe61cf79c)

-----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------




![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/a2dfc1f6-15f0-4b41-b1f1-d417b4d93b68)
**Target for UA**




**Best meal description for both Business/First Class as well as for the Pre-Order(Economy class)**

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/da0be0aa-b8bc-435d-a45c-f57e69bd4de3)


-------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------

**Finding the best meal and its consumption ratio and no of times it was ordered**

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/190190aa-45ea-42eb-ab0d-f602db28d082)

-------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------

### Final Conclusion 

![image](https://github.com/SaibalPatraDS/SKYHACK-United-Airlines/assets/102281722/21a1b6a2-e8ba-4b97-a6ad-4cfbdb80c6fe)

-------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------




## Methodology: Thinking Outside the Box for Traveler Satisfaction

In the quest to understand traveler preferences, it's clear that not all food options are created equal. Travelers aren't universally dissatisfied; they're seeking something specific. The trend toward health-conscious choices is evident, as passengers look for healthier and tastier alternatives to traditional snacks. United Airlines has faced criticism for serving late or minimal snacks on long-haul flights, leaving passengers hungry for quality options.

**How Did I Uncover These Insights?**
I began by identifying the most frequently pre-ordered and consumed products in both business and economy class. If passengers are consistently choosing these items, there must be compelling reasons behind their choices. To uncover these reasons, I delved into customer comments for top-rated products.

Additionally, I analyzed feedback from dissatisfied passengers to pinpoint their grievances and proposed potential solutions.


Our solution aims to address the following key areas of improvement:

Healthier Snacking Options: We will introduce a range of healthier snack choices that cater to passengers' increasing concern for well-being. This includes low-calorie, nutritious, and flavorful options.
Enhanced Long-Haul Food Service: Passengers on long-haul flights can expect an improved dining experience. We will ensure that meal options are not only satisfying but also timed appropriately to prevent hunger during the journey.
Vegetarian and Varied Choices: The menu will see an expansion in vegetarian and diverse meal selections to cater to a wider range of preferences.
Quality Over Quantity: Our focus will be on delivering high-quality food items that passengers genuinely enjoy, reducing waste and improving overall satisfaction.
Customer Feedback Integration: We will establish a system for actively gathering and incorporating customer feedback to continually refine our offerings.
Marketing Initiatives: Launch marketing campaigns highlighting meal combos and enticing options to boost pre-orders.
By addressing these areas, our solution aims to elevate the overall in-flight dining experience and boost passenger satisfaction.































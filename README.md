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






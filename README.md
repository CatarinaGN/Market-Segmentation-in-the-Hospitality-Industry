# Assignment: Business Cases With Data Science

"Like most hotels, hotel H, a hotel located in Lisbon, Portugal, a member of the independent hotel chain C, uses a hospitality standard market segmentation based on the origin of the customer. However, A, the new marketing manager of hotel H, recognized that this type of segmentation, as is today well-known (3, 4), is not useful for the hotel marketing department. The name of the individual and the company name is anonymized to protect confidentiality. The referenced data are real.

Until 2015 hotel chain C operated 4 hotels, however, with the acquisition of new hotels, the hotel chain board decided to invest more in marketing. However, it was not until 2018 that the hotel chain created a marketing department and hired a new marketing manager, A. A realized that the current customer segmentation was not adequate, as it only reflected one only customer characteristic, its sales origin. It did not reflect geographic characteristics, such as the country of origin, demographic characteristics, such as age, or behavioral characteristics, such as the number of stays.

Without proper customer segmentation, it is difficult for A to define a strategy to reach new customers and to continue to captivate the current customers. Taking into consideration the multiple distribution channels that hotels operate nowadays (travel agencies, travel operators, online travel agencies – OTA, brand websites, meta searchers websites, among others). For example, corporate customers tend to make reservations very near the arrival date, book directly with the hotel, and be willing to pay more for a better-equipped room, while a customer on holiday tends to make reservations more distant from the arrival date, book with a travel operator or OTA, and to look for better price opportunities. 

Explore the data and identify the variables that should be used to segment customers
2. Use K-Means clustering to identify customers segments
1. Justify your selection of K (taking into consideration the business use)
2. Use PCA to reduce dimensionality and speed-up model development
3. Suggest business applications for the findings

Domain knowledge is essential in any analytical field, especially in data mining, business analytics, and machine learning [4,5]. Therefore, a few considerations are presented to help use the dataset, particularly in the critical data understanding and data preparation phases [6].
  1. Hotels do not create a customer record for every guest. Usually, hotels only create a profile for the booking holder. However, some hotels have a policy of creating a profile for each guest companion (adult or children) only in particular cases. In Europe, a hotel can only create a profile if the customer gives express authorization.
  2. Typically, a customer profile is created in one of three moments: at the customer’s first checked-out at the hotel, at the customer first cancelation, or the customer’s first no-show.
  3. Due to PMS application malfunctions, user errors, customers providing different identification documents or use other names (e.g., first plus last name or full name), sometimes hotels have more than one profile for the same customer.
  4. Usually, only one personal information is necessary to make a booking at a hotel: the booking holder’s name.
  5. Only after a customer’s first stay can hotels confirm the guest’s personal details, such as nationality, identification card number, and birthdate, among others.
"

By Professor Nuno António, Nova Information Management School

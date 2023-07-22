## Question sets & related prompts from Learning to Ask Questions for Zero-shot Dialogue State Tracking

[Paper Link (short@sigir2023)](https://dl.acm.org/doi/pdf/10.1145/3539618.3592010)

## Prompts Used (text-davinci-003, temperature of 1)


### LLM:
Given the set of slot slot keys (hotel-pricerange, restaurant-pricerange, hotel-type, attraction-type, hotel-book day, restaurant-book day, hotel-book people, train-book people, restaurant-book people, hotel-area, restaurant-area, attraction-area, hotel-name, attraction-name, restaurant-name, train-destination, taxi-destination, taxi-departure, train-departure, train-arriveby, taxi-arriveby, train-leaveat, taxi-leaveat, restaurant-food, restaurant-book time, hotel-book stay, hotel-parking, hotel-stars, hotel-internet, train-day), write one natural language question relating to each slot. The questions must pertain to every slot. Semantically similar slots should have similar questions. 


- What is the price range of the hotel?
- What is the price range of the restaurant?
- What type of hotel are you looking for?
- What type of attraction are you interested in?
- On what day do you want to book the hotel?
- On what day do you want to book the restaurant?
- How many people are you booking the hotel for?
- How many people are you booking the train for?
- How many people are you booking the restaurant for?
- What area is the hotel located in?
- What area is the restaurant located in?
- What area is the attraction located in?
- What is the name of the hotel?
- What is the name of the attraction?
- What is the name of the restaurant?
- What is the destination of the train?
- What is the destination of the taxi?
- What is the departure point of the taxi?
- What is the departure point of the train?
- What time do you need to arrive by on the train?
- What time do you need to arrive by in the taxi?
- What time do you need to leave at on the train?
- What time do you need to leave at in the taxi?
- What type of food does the restaurant serve?
- What time do you want to book the restaurant for?
- How long do you want to stay at the hotel?
- Does the hotel have parking?
- How many stars does the hotel have?
- Does the hotel have internet access?
- On what day do you want to book the train?


### Pronouns:
Given the set of slot slot keys (hotel-pricerange, restaurant-pricerange, hotel-type, attraction-type, hotel-book day, restaurant-book day, hotel-book people, train-book people, restaurant-book people, hotel-area, restaurant-area, attraction-area, hotel-name, attraction-name, restaurant-name, train-destination, taxi-destination, taxi-departure, train-departure, train-arriveby, taxi-arriveby, train-leaveat, taxi-leaveat, restaurant-food, restaurant-book time, hotel-book stay, hotel-parking, hotel-stars, hotel-internet, train-day), write a natural language question relating to each slot, so as to maximize performance of a question-answering system. The questions must be generic and pertain to every slot. Sementically similar slots should have similar questions. Be consistent in the pronouns, use the third person. If needed, use "the user".


1. What is the price range of the hotel?
2. What is the price range of the restaurant?
3. What type of hotel is the user looking for?
4. What type of attraction is the user looking for?
5. On what day does the user want to book a hotel?
6. On what day does the user want to book a restaurant?
7. How many people does the user want to book a hotel for?
8. How many people does the user want to book a train for?
9. How many people does the user want to book a restaurant for?
10. What area is the hotel located in?
11. What area is the restaurant located in?
12. What area is the attraction located in?
13. What is the name of the hotel?
14. What is the name of the attraction?
15. What is the name of the restaurant?
16. What is the destination of the train?
17. What is the destination of the taxi?
18. What is the departure point for the taxi?
19. What is the departure point for the train?
20. What time does the user need to arrive by for the train?
21. What time does the user need to arrive by for the taxi?
22. What time does the user need to leave at for the train?
23. What time does the user need to leave at for the taxi?
24. What type of food does the user want at the restaurant?
25. What time does the user want to book the restaurant for?
26. How long does the user want to book the hotel for?
27. Does the hotel have parking?
28. How many stars does the hotel have?
29. Does the hotel have internet access?
30. On what day does the user want to book the train?

![](https://github.com/ja-rivera94/soft-one/images/conceptual_model.jpeg)
| Concept | Description | comments |
|---|---|---|
| Activity | Represents the different kinds of activities that are registered in the system ||
| Expense | Represents the expenses of an activity |
| Traveler | Represents the person who participates in an activity
| Activity - expense | It relates the expenses associated with an activity, the activity can have several expenses but an expense belongs only to the activity |
| Activity - Traveler | It relates travelers than are part of an Activity, an activity could have 0 o multiple travelers, and a traveler could be in 0 or multiple activities
| Expense - Traveler | It relates an expense to a traveler, an expense is made by a traveler | 
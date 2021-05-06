# Vityasa Internship
### Question 1
POST https://vityasa.herokuapp.com/items

[1, 4, -1, "hello", "world", 0, 10, 7]

{
  "valid_entries": 4,
  "invalid_entries": 4,
  "min": 1,
  "max": 10,
  "average": 5.5
}

<img src="1.png">

POST https://vityasa.herokuapp.com/booking
{
  "slot": 1, "name": "John"
}

{"status":"confirmed booking for John in slot 1"}

<img src="2.png">

GET https://vityasa.herokuapp.com/booking

{'slot': 1, 'name': ['John', 'Diana']}

<img src="3.png">

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"location": "delhi"}
	- slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Mumbai"}
    - slot{"location": "Mumbai"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Mexican"}
    - slot{"cuisine": "Mexican"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"location": "Mumbai"}
	- slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - utter_goodbye
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"location": "bangalore"}
	- slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"location": "delhi"}
	- slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"location": "bangalore"}
	- slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"location": "nagpur"}
	- slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"location": "nagpur"}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"location": "nagpur"}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": false}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"location": "nagpur"}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": false}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
	- action_check_location
	- slot{"location_valid": true}
	- slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "ahmedabad"}
    - slot{"location": "ahmedabad"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "surajbhala11@gmail.com"}
    - slot{"email": "surajbhala11@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "malkapur"}
    - slot{"location": "malkapur"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "malkapur"}
    - slot{"location": "malkapur"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "sangvi"}
    - slot{"location": "sangvi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "bhosari"}
    - slot{"location": "bhosari"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* restaurant_search{"location": "Pune"}
    - slot{"location": "Pune"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye
* greet
    - utter_greet
* restaurant_search{"location": "chennai"}
    - slot{"location": "chennai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "hyderabad"}
    - slot{"location": "hyderabad"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* incorrect_email{"email_incorrect": "abc_xyz"}
    - utter_incorrect_email

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "jodhpur"}
    - slot{"location": "jodhpur"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye
* goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Kolkata"}
    - slot{"location": "Kolkata"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* incorrect_email{"location": "abc"}
    - slot{"location": "abc"}
    - utter_incorrect_email
* send_email{"email": "abc@xyz.com"}
    - slot{"email": "abc@xyz.com"}

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* incorrect_email{"email": "abc"}
    - slot{"email": "abc"}
    - utter_incorrect_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* incorrect_email{"email": "abc"}
    - slot{"email": "abc"}
    - utter_incorrect_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* incorrect_email{"email": "rww"}
    - slot{"email": "rww"}
    - utter_incorrect_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye
	
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye
	
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye
	
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye
	
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye
	
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "mumbai"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye

# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "mumbai"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye
	
# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "mumbai"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye
	
# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "mumbai"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_goodbye
	
# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "mumbai"}
    - slot{"cuisine": "italian"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye
## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
	
## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "bengaluru"}
    - slot{"location": "bangalore"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "khamkhed"}
    - slot{"location": "khamkhed"}
    - action_check_location
    - slot{"location_valid": false}
    - slot{"location_operational": false}
    - utter_no_operations
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
	- action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
	
## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "malkapur"}
    - slot{"location": "malkapur"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
	- action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "bodwad"}
    - slot{"location": "bodwad"}
    - action_check_location
    - slot{"location_valid": false}
    - slot{"location_operational": false}
    - utter_no_operations
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
	- action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "jimmydasani@gmail.com"}
    - slot{"email": "jimmydasani@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* restaurant_search{"cuisine": "north indian", "location": "vasai-virarcity"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "vasai-virarcity"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* incorrect_email{"incorrect_email": "sirajbhala"}
    - utter_incorrect_email
* send_email{"email": "sbhala@avaya.com"}
    - slot{"email": "sbhala@avaya.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "location": "Pune"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "Pune"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye
* goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "vellore"}
    - slot{"location": "vellore"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* affirm
    - utter_goodbye
* goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "location": "delhi"}
    - slot{"cuisine": "american"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email
    - utter_ask_email
* send_email{"email": "surajbhala11@gmail.com"}
    - slot{"email": "surajbhala11@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
* goodbye

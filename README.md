# Memori App 

## Description
The goal was to develop a web platform that enables learning by [Spaced Repetition](https://en.wikipedia.org/wiki/Spaced_repetition) and [Active Recall](https://en.wikipedia.org/wiki/Testing_effect).

The platform enables users to create decks containing cards with questions and answers. Users study them by first viewing the question side of the card, attempting to answer it themselves, and then clicking to flip the card and check the correct answer. They are also required to rate their own response.

A "smart" algorithm determines the sequence of cards based on how well the user answered, prioritizing cards that need more practice and removing those that have been successfully learned (according to the algorithm's criteria). Learning is considered complete when all cards are successfully learned for the current time interval. After some time, the deck becomes active again for review, with the cards sequenced based on previous learning performance.

![quesion answer (2)](https://github.com/user-attachments/assets/fcf4b013-722e-45aa-b77e-513b59b1e94f)

<img width="841" alt="my decks" src="https://github.com/user-attachments/assets/db2bf074-9cd5-4c24-a27d-ce2ba4159bd4" />

<img width="935" alt="question" src="https://github.com/user-attachments/assets/afcc83b4-f1c2-4152-8c81-af9190ec860c" />

<img width="931" alt="answer" src="https://github.com/user-attachments/assets/11df1d18-cf24-4e2d-b852-51c6df20938d" />

After creating a deck, the user can add, delete, and edit learning cards.

![editing cards](https://github.com/user-attachments/assets/c93f7459-7f46-4af9-b752-e6c0b0d7dba9)

![deck](https://github.com/user-attachments/assets/497a5ad2-c426-4e74-8bf8-ffc5c1ec14c2)

The platform supports three types of user roles. A regular user can create and study decks. An admin has additional privileges, including managing other users and their decks, and can switch between student mode—for personal learning—and admin mode for performing administrative tasks. The highest level, super admin, has full control over the system, including the ability to manage admins.

![student-admin mode (1)](https://github.com/user-attachments/assets/3b3f2c2d-860b-4b1e-918f-f4d5fd5c8a4c)

<img width="848" alt="adminm3" src="https://github.com/user-attachments/assets/b6d7eebe-7b05-49a1-b1f5-85ed526eeca8" />

<img width="841" alt="admin4" src="https://github.com/user-attachments/assets/7406f0f9-61ce-4160-9e8e-737613a0b66f" />


## Usage
Run the project using `mvn spring-boot:run` 

## Sample Users for different Roles
| Role(s)        	 | Username 	        | Password 	  |
|------------------|-------------------|-------------|
| ADMIN          	 | _superAdmin_    	 | _passwd_   	 |
| STUDENT        	 | _user1_    	      | _passwd_   	 |
| ADMIN, STUDENT 	 | _admin_    	      | _passwd_   	 |

## Authors
* Elizaveta Terente

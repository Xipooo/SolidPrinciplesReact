# Refactor and Extension Exercise

This is the starter project for the refactor and extension exercise. You and your team will need to implement the user stories provided below while using the listed practices and principles to refactor and build your code. You and your team will need to story point and prioritize the user stories (they are not currently listed in any particular order) then proceed through each story according to their priority. Your team should work with ONE single repository shared between all developers.

## Practices & Principles

Use the following practices and principles during this exercise.

- Iteration Planning
- Automated Testing
- Test Driven Development
    - Red, Green, Refactor
    - 3 Laws Of TDD
    - N-ZOMBIES
- DRY (Rule of 3)
- SOLID
- Clean Code
- YAGNI
- Stateful and Stateless components
- Architect the solution into appropriate layers
- Paired Programming (Optional)
- Feature foldering (optional)

## Architectural Guidelines (Optional)

Use the following optional architectural guidelines while refactoring and implementing user stories:

- Use a centralized git repository (GitHub, GitLab, BitBucket, etc...)
- Use a CI/CD pipeline for your builds
- Use a RESTful API for business rules and storing to a persistence layer
- Organize your application into appropriate domains and slice it into micro services
- Use message queues, events, and services buses to pass information between services
- Run your services in Docker containers
- Deploy the master branch of your application to a cloud host

## User Stories

Story point, prioritize, then complete these user stories:

#### Customer User Stories

- As a customer I want to see a message that tells me why a car is not valid so that I know why my submission is being rejected.
- As a customer I want to be able to see information about the company I am submitting the car information to so that I know it is a legitimate business.
- As a customer I want to be able to send the business owner a message so that I can ask a follow up question if my car is accepted or rejected.
- As a customer I want to see a history of the cars I have submitted to the form so that I don't submit a vehicle a second time.
- As a customer I want to be able to access the website from my phone so I can submit a vehicle while I'm away from home.
- As a customer I want my choices of vehicle makes, models, and years to be automatically populated so that I can easily pick my vehicle.

#### Business Owner User Stories

- As the business owner I want to be able to accept specific models of vehicles along with their year and make so that I can accept a wider range of vehicles.
- As the business owner I want to be able to know the colors of the vehicles being submitted to the form so that I can make better decisions about my inventory.
- As the business owner I want to be able to create new acceptance rules so that I can accept more types of vehicles.
- As the busienss owner I want to be able to remove acceptance rules so that I can stop accepting vehicles that are already in my inventory.
- As the business owner I want to be able to see a list of email addresses of customers who use the website so that I can send them a newsletter.
- As the business owner I want to be able to see a picture of the vehicle submitted by the customer so that I can manually reject a vehicle if it has damage.

## Helpful Resources

- [NHTSA Vehicle API](https://vpic.nhtsa.dot.gov/api/)
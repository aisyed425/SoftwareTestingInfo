# SoftwareTestingInfo
Short software developer testing notes to help me with jobs focused on Software Development Testing

## Notes/Course takeawayas
I have recently gotten an interview for Testing and I have decided to keep my notes on my GitHub as I check it very frequently and update it regularly.

- ###Testing Pyramid
--3 levels Unit Tests, Integration Tests, E2E Tests
    - Unit tests are quick and focused. They check components in isolation
    - Integration tests verify that different parts of the system work together properly
    - End to end tests check your entire application from a user perspective.
 -- A pyramid is used because it shows how much/quantity of each test
    - At the bottom of the pyramid is the unit tests, it is the largest section so it should have the most test.
    - some integration tests, and even fewer e2e tests

### Unit Tests
- Test a single "unit" of code such as a function, method or class in **complete isolation**
- They are fast (can run thousands in seconds), Reliable (With no external dependencies), and precise.

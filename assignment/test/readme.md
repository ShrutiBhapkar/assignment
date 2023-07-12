# TestApp Unit Tests

This repository contains unit tests for a Flask application using the pytest framework. The tests ensure the functionality of the `/` and `/timeout` routes in the application.

## Prerequisites

- Python (version X.X.X)
- pytest (version X.X.X)
- Flask (version X.X.X)

## Installation

1. Clone the repository:

$ git clone https://github.com/your-repo/your-project.git
$ cd your-project

markdown
Copy code

2. Install the required dependencies:

$ pip install -r requirements.txt

markdown
Copy code

## Running the Tests

1. Run the tests:

$ pytest

markdown
Copy code

## Test Cases

### `test_index`

- Description: Tests the `/` route of the Flask application.
- Method: GET
- Assertions:
  - The response status code should be 200.
  - The response text should be "Hello welcome to myassignment".

### `test_timeout`

- Description: Tests the `/timeout` route of the Flask application.
- Method: GET
- Assertions:
  - The response status code should be 200.

## Mocking

The `mock_sleep` fixture is used to mock the `sleep()` function in order to simulate the delay in the `/timeout` route.

## Notes

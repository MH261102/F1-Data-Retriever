# F1-Data-Retriever
This Python script allows users to fetch various types of Formula 1 data from the OpenF1 API based on user input. The script supports multiple endpoints and can retrieve information such as car data, driver details, intervals, laps, pit stops, and more.

## Features

- Fetch session key based on year, country, and session name
- Retrieve detailed information about car data, drivers, intervals, laps, and other F1 data
- User-friendly prompts to collect necessary parameters

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/OpenF1-Data-Retriever.git
    cd OpenF1-Data-Retriever
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required packages:
    ```bash
    pip install requests pprint
    ```

## Usage

1. Run the script:
    ```bash
    python openf1_data_retriever.py
    ```

2. Follow the prompts to select the type of data you want to retrieve and provide the necessary parameters.

### Example

To get the pit information for car 44 in the Abu Dhabi Race of 2021:

- When prompted, select the type of data (`pit` in this case).
- Enter the year (`2021`), country name (`Abu Dhabi`), and session name (`Race`).
- Enter the driver number (`44`).

The script will fetch the session key based on the provided meeting information and then retrieve the requested pit data.

## Supported Data Types

1. `car_data`
2. `drivers`
3. `intervals`
4. `laps`
5. `location`
6. `meetings`
7. `pit`
8. `position`
9. `race_control`
10. `sessions`
11. `stints`
12. `team_radio`
13. `weather`

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the existing coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the creators of the OpenF1 API for providing such a comprehensive and open-source platform for Formula 1 data.

## Contact

For any questions or issues, please open an issue on the GitHub repository or contact me directly.

---

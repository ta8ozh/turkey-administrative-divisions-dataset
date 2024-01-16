# Turkey Administrative Divisions Dataset

## Overview

This repository contains a dataset representing the administrative divisions of Turkey, including provinces, districts, and neighborhoods. The dataset is structured in JSON format, making it easily accessible and manipulable for various applications such as geographical analysis, mapping, and local governance studies.

## Data Structure

The dataset is organized in a hierarchical JSON format, as follows:

- **Province**: The top-level element representing a province in Turkey.
  - `province`: The name of the province (e.g., "Adana").
- **Districts**: A list of districts within the province.
  - `district`: The name of the district (e.g., "Aladağ").
- **Neighborhoods**: A list of neighborhoods within the district.
  - Each item in the list is a string representing the name of a neighborhood (e.g., "Akören").

### Example Entry

```json
[
  {
    "province": "Adana",
    "districts": [
      {
        "district": "Aladağ",
        "neighborhoods": [
          "Akören"
        ]
      }
    ]
  }
]
```

## Usage

This dataset can be used for a variety of purposes including, but not limited to, academic research, geographical information systems (GIS), urban planning, and data visualization projects.

## Contributing

Contributions to expand or enhance this dataset are welcome. Please feel free to submit a pull request or open an issue to discuss potential additions or changes.

## License

This dataset is provided under the [MIT License](LICENSE).
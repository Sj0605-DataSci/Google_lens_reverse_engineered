# Shoppin: Google Lens Reverse Engineered

## Overview
Used pretrain models for benchmarking like ResNet, Tripletnetwork, Siamese, Clip, Autoencoder, LSH, EfficientNET

## Report Link
https://docs.google.com/document/d/1C39xits3xOIPl4goo9EdJAbqAY68y-teyrsL1aq61wI/edit?usp=sharing

## Project Structure
```
├── sampled_fashion_dataset/
├── app.py
├── detailed_metrics_[timestamp].csv
├── model_comparison_results_[timestamp].csv
├── query_results_[timestamp].csv
├── requirements.txt
└── search.ipynb
```

## Features
- Model comparison and evaluation
- Detailed metrics tracking and reporting
- Query processing and results generation (retrieved)
- Interactive Jupyter notebook for search functionality

## Installation

1. Clone the repository:
```bash
git clone https://github.com/[username]/Shoppin.git
cd Shoppin
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Running the Application
```bash
python app.py
```

### Using the Search Notebook
1. Start Jupyter Notebook:
```bash
jupyter notebook
```
2. Open `search.ipynb` and follow the instructions within the notebook.

## Data Files
- `detailed_metrics_[timestamp].csv`: Contains detailed performance metrics and analysis results
- `model_comparison_results_[timestamp].csv`: Stores comparison data between different models
- `query_results_[timestamp].csv`: Saves query processing results

## Requirements
See `requirements.txt` for a complete list of dependencies.

## Development
- The project uses Python 3.x
- Virtual environment is recommended for development
- Code follows PEP 8 style guidelines

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Project Link: https://github.com/sj0605-datasci/Shoppin

## Acknowledgments
- Thanks to contributors who have participated in this project
- Inspired by modern shopping data analysis needs
- Built with Python and Jupyter Notebook

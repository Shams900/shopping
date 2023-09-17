# shopping
# Shopping Predictions

This repository contains code for training and evaluating a k-nearest neighbor model to predict online shopping behavior. The model uses various features as evidence to classify whether a visitor will make a purchase or not (revenue).

## Dataset

The dataset used for training and evaluation is stored in a CSV file. The file contains the following features:

- Administrative: Number of pages visited by the user in the "Administrative" category.
- Administrative Duration: Total time spent by the user on the "Administrative" pages.
- Informational: Number of pages visited by the user in the "Informational" category.
- Informational Duration: Total time spent by the user on the "Informational" pages.
- ProductRelated: Number of pages visited by the user in the "ProductRelated" category.
- ProductRelated Duration: Total time spent by the user on the "ProductRelated" pages.
- BounceRates: Bounce rate of the website.
- ExitRates: Exit rate of the website.
- PageValues: Average page value of the website.
- SpecialDay: Special day indicator (e.g., Mother's Day, Valentine's Day).
- Month: Month of the visit (0-11, January to December).
- OperatingSystems: Operating system used by the visitor.
- Browser: Browser used by the visitor.
- Region: Geographic region of the user.
- TrafficType: Type of traffic source.
- VisitorType: Visitor type (returning or not returning).
- Weekend: Indicator of whether the visit occurred on a weekend.

The corresponding labels indicate whether revenue was generated from the visit (1) or not (0).

## Usage

1. Ensure you have Python installed.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Prepare your data in a CSV file with the same format as the provided dataset.
4. Run the script `shopping.py` and provide the path to your data file as a command-line argument.

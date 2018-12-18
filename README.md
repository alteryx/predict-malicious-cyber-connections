# Predicting Malicious Cyber Connections
<p style="margin:30px">
    <img style="display:inline; margin-right:50px" width=50% src="https://www.featuretools.com/wp-content/uploads/2017/12/FeatureLabs-Logo-Tangerine-800.png" alt="Featuretools" />
</p>

**The general setup for the problem is a common one: we have a single table of log lines recording Internet traffic between various sources. Traffic between a source and destination is labeled as malicious or clean in the dataset, and we'd like to be able to predict ahead of time if a future connection between a source and a destination will be malicious.**

We'll demonstrate an end-to-end workflow using a [Cybersecurity Dataset](https://s3.amazonaws.com/featuretools-static/CyberFLTenDays.csv) derived from [data](https://csr.lanl.gov/data/cyber1/) from the Los Alamos National Laboratory. This notebook demonstrates a rapid way to predict whether a connection (defined in several ways) is malicious.

1. [Generate features for several types of connections](Create%20Feature%20Matrices%20from%20LL%20Cyber%20Data.ipynb)
2. [Make predictions for source name/destination name pairs with Machine Learning](Predicting%20Malicious%20Cyber%20Connections%20with%20Featuretools.ipynb)

## Highlights
* Automatically generate 2000 features
* Learn how to write your own primitive to be applied to the data

## Running the tutorial
1. Clone the repo

    ```
    git clone https://github.com/Featuretools/predict-malicious-cyber-connections.git
    ```

2. Install the requirements

    ```
    pip install featuretools
    ```

3. Download the [data](https://s3.amazonaws.com/featuretools-static/CyberFLTenDays.csv)

4. Run the Tutorials:
    - [Generate features for several types of connections](Create%20Feature%20Matrices%20from%20LL%20Cyber%20Data.ipynb)
    - [Make predictions for source name/destination name pairs with Machine Learning](Predicting%20Malicious%20Cyber%20Connections%20with%20Featuretools.ipynb)


## Feature Labs
<a href="https://www.featurelabs.com/">
    <img src="http://www.featurelabs.com/wp-content/uploads/2017/12/logo.png" alt="Featuretools" />
</a>

Featuretools is an open source project created by [Feature Labs](https://www.featurelabs.com/). To see the other open source projects we're working on visit Feature Labs [Open Source](https://www.featurelabs.com/open). If building impactful data science pipelines is important to you or your business, please [get in touch](https://www.featurelabs.com/contact.html).

### Contact

Any questions can be directed to help@featurelabs.com

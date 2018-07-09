# Apparel-Recommendation

Extracts apparel details from amazon api and recommends similar products using nltk and keras

![](images/recommendation.jpg)

## DOMAIN BACKGROUND

Personalized product recommendations are the alternative way of navigating through the online shop. More people find products they need. Even if they didn’t think of them. Build a recommendation engine which suggests similar products to the given product in any e-commerce websites ex. Amazon.com, myntra.com etc.

In this project we are extracting the json file for over 180,000 apparels images and recommend similar apparels using content based search.

## PROBLEM STATEMENT

Given a json file for extracting the 180k apparel images from amazon.com we need to recommend the similar apparel based on the document id i.e product id and number of apparels to be recommended at a time.
Each of those images will be recommended based on following fields:
```
1. asin  ( Amazon standard identification number)

2. brand ( brand to which the product belongs to )

3. color ( Color information of apparel, it can contain many colors as   a value ex: red and black stripes ) 

4. product_type_name (type of the apperal, ex: SHIRT/TSHIRT )

5. medium_image_url  ( url of the image )

6. title (title of the product.)

7. formatted_price (price of the product)
```
We are going to use a total of `seven approaches` for recommending the apparel as following.

```
1.Bag of words model

2.tf-idf model

3.idf model

4.word2vec model

5.idf weighted word2vec model

6.weighted similarity using brand and color

7.visual features based using convolution neural networks
```

3.DATASETS AND INPUTS

1. [tops_fashion.json](https://drive.google.com/file/d/11ch_27I3oqGlu-VhYyWJmEk6nLO3wdRE/view?usp=sharing)

2. [16k_apparel_preprocessed pickle file](https://drive.google.com/open?id=1yDZDY2Y-4VvPSxJeCyPhqhxfNtAW9e6j)

3. [Trained Word2Vec Model](https://drive.google.com/file/d/1FByX9HSM8KhNL0rdp3jWD_xpmbVt8Dy0/view?usp=sharing)

4.


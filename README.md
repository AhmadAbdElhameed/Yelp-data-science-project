### Yelp-data-science-project
#### Yelp reviews data analysis and sentiment analysis

#### About Yelp :
- Yelp is a which publish crowd-sourced reviews about local businesses, as well as the online reservation service Yelp Reservations. The company also trains small businesses in how to respond to reviews, hosts social events for reviewers, and provides data about businesses, including health inspection scores.

- Yelp was founded in 2004 by former PayPal employees. By 2010 it had $30 million in revenues and the website had published more than 4.5 million crowd-sourced reviews.


#### Business Objects:


Business objects contain basic information about local businesses.
The 'business_id' field can be used with the Yelp API to fetch even more information for visualizations,
but note that you'll still need to comply with the API TOS. The fields are as follows:

{
  'type': 'business',

  'business_id': (a unique identifier for this business),

  'name': (the full business name),

  'neighborhoods': (a list of neighborhood names, might be empty),

  'full_address': (localized address),

  'city': (city),

  'state': (state),

  'latitude': (latitude),

  'longitude': (longitude),

  'stars': (star rating, rounded to half-stars),

  'review_count': (review count),

  'photo_url': (photo url),

  'categories': [(localized category names)]

  'open': (is the business still open for business?),

  'schools': (nearby universities),

  'url': (yelp url)

}


**Attribues of review dataset are as following :**

- review_id: ID of the review
- user_id: ID of the user
- business_id: ID of the business
- stars: ratings of the business
- date: review date
- text: review from the user
- useful: number of users who vote a review as usefull
- funny: number of users who vote a review as funny
- cool: number of users who vote a review as cool

**Attributes of business dataset are as following:**

- business_id: ID of the business
- name: name of the business
- address: address of the business
- city: city of the business
- state: state of the business
- postal_code: postal code of the business
- latitude: latitude of the business
- longitude: longitude of the business
- stars: average rating of the business
- review_count: number of reviews received
- is_open: 1 if the business is open, 0 therwise
- categories: multiple categories of the business

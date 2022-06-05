## `Collaborative Filtering Recommender System`

**Objective**
This projects tries to implement collaborative filtering using memory based technique of distance proximity using
cosine distance and nearest neighbors on a data set with 4 attributes/features with over 2MB data, we will try to recommend 3-5 products to clients who visit a beauty online store.

**Approach**

- `Data Description`
- `Exploratory Data Analysis`
  - Remove duplicates
  - Check Missing Record/Remove them since ratings are subjective
- `Visualizations`
  - Creating visuals with plotly
  - Creating new columns and Further visuals for more insight
- `Preprocessing`
  - Encoding UserId and ProductId
- `Application of centered cosine similarity`
  - Mean ratings for each user
  - Normalizing features
  - User-item matrix creation
  - Identifying top 3, 5 similar users
  - Recommend products to top 3, 5 users

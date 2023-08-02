#  Federated Search with Typesense

This is an app that showcases Typesense's Federated or Multi-Search feature.


## Dataset

There are two datasets used in this app

1. Dataset containing Books.

2. Dataset containing Indian Foods.

## Tech Stack

This search experience is powered by Typesense which is a fast, open source typo-tolerant search-engine. It is an open source alternative to Algolia and an easier-to-use alternative to ElasticSearch.

The app was built using the [Typesense Adapter for InstantSearch.js](https://github.com/typesense/typesense-instantsearch-adapter)

The search backend is powered by a single node.

## Development

1. Create a `.env` file using `.env.example` as reference.

2. Generate and index data
  ```shell
  yarn indexData
  ```

4. Install dependencies and run the local server:

```shell
yarn
yarn start
```

Open http://localhost:3000 to see the app.

## Authors

- [@tejassrivastava](https://www.github.com/tejassrivastava)
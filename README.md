# Manipulate Data with Javascript and NodeJS

## 🌟 Goal

> Learning Javascript basics by manipulating arrays, objects, functions etc...

## 👷 Prerequisites

1. Have a Github account properly setup with your local Git
   > You should use ssh authentication between your local git and
   Github. **[How to set it up](https://help.github.com/articles/connecting-to-github-with-ssh)**
2. **Fork** the repository

   ![fork button](img/fork.png)

3. **Clone** your fork locally
    ```shell
    cd /path/to/workspace 
    git clone git@github.com:YOUR_USERNAME/secure-web-dev-workshop1.git
    ```
4. Run the `index.js` file with node
    ```shell
    node index.js
    ```
5. Check the result, it should display `🚀 It Works!`

## 🗒 What to do

There are multiple `TODO` instructions inside the `index.js` file. You have to do the task associated with each one
of them.

Commit your changes after resolving each `TODO`

```shell
git commit -m "feat(feat-name): Explain commit"
```

## 📦 Data structure

We will work on a public dataset (OpenData) given by French gov and the city of Paris, named "[Lieux de tournage à Paris](https://opendata.paris.fr/explore/dataset/lieux-de-tournage-a-paris/information)"

This dataset represents a list of locations for outdoor scene shooting in Paris since 2016. It does not include data of
the current year.

Here is an element extracted from the dataset, to show the data structure:

```json
{
  "datasetid": "lieux-de-tournage-a-paris",
  "recordid": "737d97372281f1d51fe3294aae21179ca00e2e05",
  "fields": {
    "coord_y": 48.83566,
    "type_tournage": "Long m\u00e9trage",
    "nom_producteur": "MANDARIN PRODUCTION",
    "date_fin": "2020-08-21",
    "geo_point_2d": [
      48.83566000015182,
      2.348314535961912
    ],
    "nom_tournage": "TOUT S'EST BIEN PASSE",
    "ardt_lieu": "75013",
    "geo_shape": {
      "coordinates": [
        2.348314535961912,
        48.83566000015182
      ],
      "type": "Point"
    },
    "id_lieu": "2020-404",
    "nom_realisateur": "Francois OZON",
    "adresse_lieu": "rue pascal, 75013 paris",
    "date_debut": "2020-08-20",
    "annee_tournage": "2020",
    "coord_x": 2.34831454
  },
  "geometry": {
    "type": "Point",
    "coordinates": [
      2.348314535961912,
      48.83566000015182
    ]
  },
  "record_timestamp": "2022-02-21T12:01:17.756+01:00"
}
```

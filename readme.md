## Database

Create Database

```
use song_db

```

## Collection/Table
Create Collection

```
db.createCollection("songs")

```
```
db.createCollection("artists")

```


```
db.createCollection("popular_songs")

```

## Document
Insert Document

```
db.songs.insertMany([
  {
    title:'Sahabat Sejati',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Dan',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Melompat Lebih Tinggi',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Sahabat Sejati',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Hari Bersamanya',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Seberapa Pantas',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Kita',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Sephia',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Sebuah Kisah Klasik',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  },
  {
    title:'Berhenti Berharap',
    artists:[
      "Sheila On 7"
    ],
    album:"Sahabat"

  }
])
```
```
db.songs.insertMany([
  {
    name:'Sheila On 7',
    date_of_birth:"17 Juli 1989",
    genres: [
      "pop"
    ]
  },
   {
    name:'Tulus',
    date_of_birth:"20 Agustus 1987",
    genres: [
      "pop"
    ]
  },
   {
    name:'Ariel Noah',
    date_of_birth:"19 September 1981",
    genres: [
      "pop"
    ]
  },
   {
    name:'Geisha',
    date_of_birth:"7 Juni 1986",
    genres: [
      "pop"
    ]
  },
   {
    name:'Mawar Eva',
    date_of_birth:"26 September 2001",
    genres: [
      "pop"
    ]
  },
   {
    name:'Agnes Monica',
    date_of_birth:"1 Juli 1986",
    genres: [
      "pop"
    ]
  },
   {
    name:'Cinta Laura',
    date_of_birth:"17 agustus 1993",
    genres: [
      "pop"
    ]
  },
   {
    name:'Rizky Febian',
    date_of_birth:"25 Februari 1998",
    genres: [
      "pop"
    ]
  },
   {
    name:'Mahalini',
    date_of_birth:"4 Maret 2000",
    genres: [
      "pop"
    ]
  },
  {
    name:'Putri Delina',
    date_of_birth:"29 Agustus 2001",
    genres: [
      "pop"
    ]
  }
])
```
```

db.popular_songs.insertMany([
   {
    title:'Sahabat Sejati',
    played_count:1000,
    period_of_time:"29 Juli 2016"

  },
  {
    title:'Dan',
    played_count:13000,
    period_of_time:"2 Agustus 2016"

  },
  {
    title:'Melompat Lebih Tinggi',
   played_count:400,
    period_of_time:"28 April 2016"

  },
  {
    title:'Sahabat Sejati',
    played_count:300,
    period_of_time:"18 April 2021"

  },
  {
    title:'Hari Bersamanya',
    played_count:100,
    period_of_time:"23 Mei 2015"

  },
  {
    title:'Seberapa Pantas',
   played_count:1000,
    period_of_time:"01 Mei 2001"

  },
  {
    title:'Kita',
   played_count:1000,
    period_of_time:"10 Oktober 2019"

  },
  {
    title:'Sephia',
    played_count:400,
    period_of_time:"09 September 2014"

  },
  {
    title:'Sebuah Kisah Klasik',
    played_count:500,
    period_of_time:"12 Februari 2020"

  },
  {
    title:'Berhenti Berharap',
 played_count:1900,
    period_of_time:"18 Februari 2001"

  }
])
```
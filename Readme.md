<h1>Soal nomor 1 Profile Skiljek</h1>

```js
{
"_id": "ObjectId('ABC')",
"full_name": "Muhammad Ikhwan Fathulloh",
"email": "muhammadikhwanfathulloh17@gmail.com",
"phone_number": 0858********
}
```

<h1>Soal nomor 2 Profile Skilshop</h1>
<h2>Relasi one to many</h2>

```js
{
    "_id": "ObjectId('CBA')",
    "full_name": "Muhammad Ikhwan Fathulloh",
    "phone_mumber": 0858********
    "address": [
        "ObjectId('XYZ')",
        "ObjectId('LMN')",
    ]
}
```

<h1>Soal nomor 3</h1>
<h2>Relasi one to one</h2>

```js
{
    "_id": "ObjectId('ABA')",
    "product_name": "Origami",
    "brand_name": "SkilShirt",
    "variant": [{
        "_id": "ObjectId('BAB')",
        "variant_name_1": "Origami Garuda",
        "color": "Hitam",
        "quantity": 12,
        "price": "Rp 130.000",
    },{
         "_id": "ObjectId('CAC')",
        "variant_name_2": "Origami Hanoman",
        "color": "Navy",
        "quantity": 10,
        "price": "Rp 150.000",
    }]
}
```

<h1>Soal nomor 4</h1>
<h2>Relasi one to many</h2>

```js
[
    {
    "_id": "ObjectId('SKV')",
    "cinema_name": "Monsta",
    "film": [
        "ObjectId('Boboiboy The Movie')",
        "ObjectId('Boboiboy The Movie 2')"
    ],
    "location": "Bandung"
    },
    {
    "_id": "ObjectId('VKS')",
    "cinema_name": "Cinema 31",
    "film": [
        "ObjectId('Red Cliff')",
        "ObjectId('Admiral Roaring Current')"
    ],
     "location": "Bandung"
    }
]
```

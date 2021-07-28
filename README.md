# Javascript test

Implement function `mergePeopleWithAnimals`, which should fetch list of people and list of animals, and merge them by animalId. Result should be:

```json
 [
    {
        name: "John",
        id: 1,
        animal: {
            name: "Piggy",
            id: 3,
            sound: "qui",
        },
    },
    ...
  ]
```



## List of people
[https://private-anon-d1351ae69b-giboork.apiary-mock.com/people](https://private-anon-d1351ae69b-giboork.apiary-mock.com/people)

```json
[
  {
    "name": "John",
    "id": 1,
    "animalId": 3
  },
  {
    "name": "Albert",
    "id": 2,
    "animalId": 9
  },
  {
    "name": "john",
    "id": 3,
    "animalId": 6
  }
]
```

## List of animals
[https://private-anon-d1351ae69b-giboork.apiary-mock.com/animals](https://private-anon-d1351ae69b-giboork.apiary-mock.com/animals)
```json
[
  {
    "name": "Piggy",
    "id": 3,
    "sound": "qui"
  },
  {
    "name": "Tiggy",
    "id": 6,
    "sound": "rawr"
  },
  {
    "name": "Froggy",
    "id": 9,
    "sound": "quack"
  }
]
```
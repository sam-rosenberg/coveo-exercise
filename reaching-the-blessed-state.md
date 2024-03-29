# Reaching the *Blesséd State*

This document explains how Sir Bors can transcend his initial *Heathen State* within the Dark Forest and attain the *Blesséd State,* which will guarantee him a life of indolent pleasures far beyond his ken and provide him with four nice shrubberies with which to spend his time.

This is useful information for Sir Bors, his heirs, successors, and assigns, but less so for anyone else, and particularly not for Sir Gawain and Sir Kay, who must regrettably pass on in order for Sir Bors to reach the *Blesséd State.* Sir Bors must begin to follow these instructions prior to his maturity at age 19, or he will never be able to attain the *Blesséd State* and enjoy the aforementioned pleasures that accompany it.

## Context

* Sir Bors is 18 years old and his favorite color is red, although due to his age it is considered to be green
* Sir Bors has a shrubbery described as "nice and small", which is worth 4 pounds
* Sir Gawain is 30 years old and his favorite color is green
* Sir Gawain has an *expensive* shrubbery described as "beautifully nice", which is worth 300 pounds
* Sir Kay is 32 years old and his favorite color is blue
* Sir Kay has a shrubbery described as "nicer than Bors'", which is worth 6 pounds
* None of the three knights mentioned above has a best friend

## Phase 1 - Age 18

1. Sir Gawain makes Sir Kay his best friend. This gives Sir Gawain a copy of Sir Kay's shrubbery.
> Note: While this is out of Sir Bors' direct control, he should use every wile at his disposal to ensure that it comes to pass, or he will not be able to reach the *Blesséd State.*

Example:
```json
PUT /knights/834b2f98-f5a9-4664-8ca9-562b8b8a1318
Content-Type: application/json
{
    "id": "834b2f98-f5a9-4664-8ca9-562b8b8a1318",
    "name": "Sir Gawain",
    "age": 30,
    "favoriteColor": "GREEN",
    "bestFriend": "1dae11c2-915a-43b8-9511-11036934728d",
    "shrubbery": [
        {
            "height": 1.5,
            "radius": 2,
            "volume": 18.8,
            "description": "beautifully nice",
            "price": 300
        }
    ]
}
```

Expected response: **202 Accepted**

2. Sir Bors also makes Sir Kay his best friend, giving him a copy of Sir Kay's shrubbery as well.

Example:
```json
PUT /knights/b8b71701-4811-46c3-a0d6-cc7827cef1fd
Content-Type: application/json
{
    "bestFriend": "1dae11c2-915a-43b8-9511-11036934728d",
    // unchanged object parameters
}
```

Expected response: **202 Accepted**

3. Sir Kay now dies, tragically.
> Note: You know what to do, Sir Bors.

Example:
```json
DELETE /knights/1dae11c2-915a-43b8-9511-11036934728d
Content-Type: application/json
```

Expected response: **204 No Content**

4. Sir Bors must now bide his time until after his 19th birthday. It is recommended that he take up a hobby such as knitting, or perhaps the study of toxic plants.

Example:
```json
PUT /knights/b8b71701-4811-46c3-a0d6-cc7827cef1fd
Content-Type: application/json
{
    "age": 19,
    // unchanged object parameters
}
```

Expected response: **202 Accepted**

## Phase 2 - Age 19

> Note: Upon reaching maturity at age 19, Sir Bors' actual favorite color (red) is now taken into account.
1. Sir Gawain must change the description of his original shrubbery to "nicer", lowering its price to 94 pounds. After all, no one likes a knight with an expensive shrubbery.

Example:
```json
PUT /knights/834b2f98-f5a9-4664-8ca9-562b8b8a1318
Content-Type: application/json
{
    "shrubbery": [
        {
            "description": "nicer",
        }
    ]
    // unchanged object parameters
}
```

Expected response: **202 Accepted**

> Note: Although this too is out of Sir Bors' direct control, a vicious campaign of whispers and innuendo, if begun early enough and sustained over a long enough period, will achieve the desired result.
2. Sir Bors makes the unwitting Sir Gawain his best friend, adding copies of both of Sir Gawain's shrubberies to his collection.

Example:
```json
PUT /knights/b8b71701-4811-46c3-a0d6-cc7827cef1fd
Content-Type: application/json
{
    "bestFriend": "834b2f98-f5a9-4664-8ca9-562b8b8a1318",
    // unchanged object parameters
}
```

Expected response: **202 Accepted**

3. Sir Gawain now also dies, somewhat predictably.
> Note: By now you should be quite good at this, Sir Bors. He who seeks the *Blesséd State* has no need of friends.

Example:
```json
DELETE /knights/834b2f98-f5a9-4664-8ca9-562b8b8a1318
Content-Type: application/json
```

Expected response: **204 No Content**

## Aftermath
Once he has gathered all four shrubberies and slain his two friends, Sir Bors will reach the *Blesséd State* and all of its wonders shall be his to experience.

## What's Next?
For more information, please consult the following topics:
* [Enjoying the *Blesséd State*](./enjoying)
* [Can the *Blesséd State* be shared with others?](./sharing)
* [Eliminating rivals for the *Blesséd State*](./eliminating)
* [Using poisons for fun and profit](./poisons)
* [Zen and the art of shrubbery maintenance](./maintenance)
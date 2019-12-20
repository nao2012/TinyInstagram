# TinyInstagram
Tiny Instagram Project M1 ATAL

YASSIN Mathis
MAZARI Naïma

# Modèle de la base de donnée 

type Post {
    id - integer
    caption - text
    url - text
    created_at - timestamp with time zone
    user_id - text
}
 
type User {
    name - text
    last_seen - timestamp with time zne
    avatar - text
    email - text
    id - text, primary key
}

type Like {
    id - integer
    user_id - text
    post_id - integer
}

type Follow {
    id - integer
     follower_id - text
    following_id - text
}


#Benchmark

## Test 1: How much time it takes to post of message if followed by 10, 100 and 500 followers? (average on 30 measures)




## Test 2: How much time it takes to retrieve the last 10, 100 and 500 last messages ? (average of 30 measures)



## Test 3: How much “likes” can you do per second ?? (average on 30 measures)

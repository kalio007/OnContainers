json
{
"keyValue": [value array]
}

can be yaml or yml

---

we dont have to use quote
also we dont have to use curly braces but idnetation to represnet hierarchy
also no commas to sepreate name value pairs
funthermore we dont use quote for key value pairs

---

keyvalue: value
keyvalue:
objectkeyvalue: value

we use hypen to represent arrays

tags:

- software
- devops

we mostly use yaml files for configuration while json for information exchange between computers like client and servers

docker compose
$docker compose build
to run all the dockerfiles in our directory

$docker compose ps
to view the aviable docker images

$docker compose up -d

$docker compose down
to take down the contianers

docker networks
$

to ping the api from a difffrent continaer ti test our networks

$docker exec -it (imageID) sh
$ping api(container)

logining in as root user in the continer's shell
$docker exec -it -u root (contianer id) sh

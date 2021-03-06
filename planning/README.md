## USER STORIES

* As a user, I can see a list of maps, because I want to see a list of maps other users have created!

* As a user, I can view a map, because I want to see interesting things in my area!

* As an authenticated user, I can create maps, because I want to personalize my maps!

* An an authenticated user, I can modify maps, because I want to add, edit, or remove points in the map!

* As a user, I can favorite a map, because I want to see my favorite maps easily!

* As a user, I can have a profile, because I want to be able to indicate my favorite maps, and the maps I have contributed to!

## MAPS

* a map can contain many points

* each point can have: a title, description, and image

## E.R.D.

!["WIKI-MAP-ERD"](https://github.com/davemgj84/Midterm-LHL/blob/master/planning/Wiki-map-ERD.jpg?raw=true)

## ROUTES
* Mockup Login?
* GET /maps - DONE
* GET /maps/:id - DONE
* GET /users/:id - DONE
* GET /users/:id/favorites - DONE
* GET /maps/new - DONE (need redirect location)
* POST /maps (creates a new map) - DONE
* POST /maps/:id/locations (updating location data) - DONE
* PATCH /maps/:id/edit - DONE
* DELETE /maps/:id/delete - DONE

## MVP GOALS
* Populate forms with existing data when editing locations - users can then edit what they want and re-submit

## STRETCH GOALS
* GET /login
* POST /login (mockup page)
* Allow user maps to be public or private?

## Initial Mockup 

!["WIKI-MAP-MOCKUP"](https://github.com/davemgj84/Midterm-LHL/blob/routes/planning/Mockup%20-%20Wiki-map.png?raw=true)

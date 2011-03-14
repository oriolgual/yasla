# YASLA (The name sucks, I know)

YASLA is a simple web app to manage shopping lists collaboratively.

# TODO

## Global

* Login with Google Account (Powered by Omniauth, only Google Accounts currently)
* Login with invitation
* Share a shopping list by email (will receive invitation)
* Switch editing / shopping mode

### Editing mode

#### Lists (RESTful)
* Split list total cost with people sharing it
* Check people as payed (only owner)

#### Items (RESTful)
* Add items to a shopping list
* Add itmes by autodiscover (most commonn items bought on past lists)
* Add item amount
* Assign item to category

#### Categories (RESTful)
* Set default custom order for all categories

#### Locations (RESTful)
* Order categories scoped to location


### Shopping mode

#### Lists
* Select current list 
* View current total spent (if price added)
* Store total spent (if it can't be autocalculated)

####  Items
* Sorted alphabetically
* Grouped by category/ungrouped
* Check items as bought
* Add metadata to a bought item: price, amount, unit (gr, lbs, litres)

#### Categories
* Sort alphabetically
* Sort by custom order (supermarkets change the products from time to time)
* Sort by custom order scoped to location (each supermaket may have its own ordering)

#### Location
* Store location coordinates
* Store location name

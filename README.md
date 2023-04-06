 # Team Ditto - Table 8

 #### We are working on the "Internship track-1 : Visibility of professional opportunities" problem statement. Our Idea involves using an algorithm which employs distance to create different views for each user availing services. Currently every user availing a service sees a similar view. To test this our team opened fiverr accounts and used the same filters. We all got the same view for our search.This only caters to the top service providers while alienating multiple new or old with low review accunts. We think our solution of using distance will help fix this issue.

## Insights from Tinder

#### Tinder, the popular dating app, uses a distance algorithm to determine which potential matches to display to its users. This algorithm takes into account the user's location, as well as their preferred search radius, to show them potential matches within a certain distance. The algorithm uses a combination of GPS coordinates and triangulation to determine the user's location accurately. Once the user's location is established, the algorithm searches for potential matches within the user's preferred search radius. This helps to ensure that users are shown matches that are reasonably close by, which can increase the likelihood of them actually meeting up in person. Additionally, the distance algorithm is continually updated to account for changes in the user's location or search radius, ensuring that the matches displayed remain relevant and up-to-date. Overall, the distance algorithm plays a critical role in providing Tinder users with an efficient and effective way to find potential matches in their area.
#### We think using an upgraded version of the same or similar algorithm will help us. 

## Insights from Swiggy

#### An approach to making the address capture more accurate is inspired by Swiggy’s address capture system. Users can input multiple addresses and based on where the application is opened Swiggy will automatically set the delivery address to nearest saved location. We can implement this in our system so that users who are travelling around can use this system to be able to view talent from their current location. This will also reduce load on the server since it does not have to keep a track on the users location at all times and constantly refresh the list of talent around them.

## Approaches Considered

### BFS graph parsing based on device location
### GeoPY - Using Coordinates to generate view

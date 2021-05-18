## Rotten Potatos

Pages
-  Home Page
-  Login
-  Signup
-  Profile Page
   -  Edit Profile
   -  Edit Password
   -  Edit Picture
   -  List of reviews done
   -  List of movies that you want to see (and review)
-  Logout (Feature)
-  Delete Account

-  Simple Search
-  Movies List Page
-  Single Movie
   - See reviews
   - Add a review (is logged in)

-  Add Movie (add image as well)
-  Edit Movie

-  Add Review (with not only text, but also them potatos)
-  Edit Review


## Users
_id: ID
email:String (required, unique)
username String (required, unique)
password String (required)
profilePic: String
wishlist: [Movies]
role: String [Either Admin, or Regular]
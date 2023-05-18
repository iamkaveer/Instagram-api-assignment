
# Instagram-api-assignment

Its a simple Instagram api project made by using Spring boot to do simple CRUD operations.




## Technologies Used

**Java**

**Spring Boot**

**Hibernate**

**MySQL**

**Maven**


## API Documentation
### Admin Controller
- Toggle Blue Tick: PUT /admin/user/{id}/{blueTick}
- Toggles the blue tick status of a user.
### Comment Controller
- Add Comment: POST /comment
- Adds a comment to a post.
### Post Controller
- Add Post: POST /post?email={email}&token={token}
- Adds a new post.
- Get All Posts: GET /post?email={email}&token={token}
- Retrieves all posts.
- Get Likes for Post: GET /post/{postId}/likeCount
- Retrieves the number of likes for a post.

### User Controller
- Sign Up: POST /user/signup
- Creates a new user account.
- Sign In: POST /user/signin
- Authenticates user and generates a token.
- Sign Out: DELETE /user/signout?email={email}&token={token}
- Logs out a user and invalidates the token.
- Update User: PUT /user?email={email}&token={token}
- Updates user information.
- Follow User: POST /user/follow/{myId}/{otherId}
- Follows another user.
- Like Post: POST /user/like
- Likes a post.



## Run Locally


```bash
 http://localhost:8080
```


## Data Models
The InstagramProject API uses the following data models:
- Admin
- AuthenticationToken
- InstagramComment
- InstagramFollower
- InstagramFollowing
- Post
- PostLike
- User

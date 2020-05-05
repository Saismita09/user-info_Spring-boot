# user-info_Spring-boot

1. Creating a "/signup" api and a user model so take user information while signup.
2. Creating a "/login" api to let the user login using email and password.
3. This system would be having session management so create another api "/dummy" which is accessible only if user is logged in.
   and if user is logged in then by going on this api, the user session should also be extended.
4. Create a "/logout" api which will invalifdate the session of the user.
5. For fast testing purpose use 1 min as max age of the session

   Note: We would be using H2 database for storage.

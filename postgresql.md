# permissions

- Together with authentication and throttling, permissions determine whether a request should be granted or denied access.

- Permission checks are always run at the very start of the view, before any other code is allowed to proceed. Permission checks will typically use the authentication information in the request.user and request.auth properties to determine if the incoming request should be permitted.

- The simplest style of permission would be to allow access to any authenticated user, and deny access to any unauthenticated user. This corresponds to the IsAuthenticated class in REST framework.

- Permissions in REST framework are always defined as a list of permission classes.

- The AllowAny permission class will allow unrestricted access, regardless of if the request was authenticated or unauthenticated.

- The IsAuthenticated permission class will deny permission to any unauthenticated user, and allow permission otherwise.

- The IsAdminUser permission class will deny permission to any user, unless user.is_staff is True in which case permission will be allowed.

- The IsAuthenticatedOrReadOnly will allow authenticated users to perform any request. Requests for unauthorised users will only be permitted if the request method is one of the "safe" methods; GET, HEAD or OPTIONS.
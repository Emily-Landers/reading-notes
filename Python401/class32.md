# Permissions & Postgresql

- Permissions in `REST` framework are always defined as a list of permission classes.
- Before running the main body of the view each permission in the list is checked. If any permission check fails, an `exceptions.PermissionDenied` or `exceptions.NotAuthenticated` exception will be raised, and the main body of the view will not run.
- `REST` framework permissions also support object-level permissioning. Object level permissions are used to determine if a user should be allowed to act on a particular object, which will typically be a model instance.
- The default permission policy may be set globally, using the `DEFAULT_PERMISSION_CLASSES` setting.
- The `AllowAny` permission class will allow unrestricted access, regardless of if the request was authenticated or unauthenticated.
- The `IsAuthenticated` permission class will deny permission to any unauthenticated user, and allow permission otherwise.
- The `IsAdminUse`r permission class will deny permission to any user, unless user.is_staff is True in which case permission will be allowed.
- The `IsAuthenticatedOrReadOnly` will allow authenticated users to perform any request. Requests for unauthorized users will only be permitted if the request method is one of the "safe" methods; `GET`, `HEAD` or `OPTIONS`.

## Resources 

- https://www.django-rest-framework.org/api-guide/permissions/ 

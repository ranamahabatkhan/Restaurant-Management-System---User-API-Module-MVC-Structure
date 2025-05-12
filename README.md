# Restaurant Management System - User Module
## MVC Structure

This is a Node.js/Express-based backend system for a Restaurant Management application, specifically focusing on the user management module. The system provides functionality for user registration, authentication, and role-based access control.

### Key Features:

1. User Management:
   - Registration with full name, email, username, and password
   - Login functionality with credential verification
   - Password update with current password verification
   - Role management (admin, customer, salesman)

2. Security:
   - Password hashing using bcrypt
   - Basic admin authorization checks (via headers)
   - Prepared structure for JWT/session authentication (to be implemented)

3. API Endpoints:
   - Public routes for registration and login
   - Protected routes for admin operations (user list, role update, deletion)
   - User-specific routes (password update)

4. Response Formats:
   - JSON responses for API clients
   - HTML responses for browser requests (user list)

## Files Structure

```
server.js          - Main application entry point
userRoutes.js      - Routes for user-related endpoints
userController.js  - Business logic for user operations
userModel.js       - Mongoose schema and model for users
authMiddleware.js  - Placeholder for authentication middleware
```


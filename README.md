# 🔐 Enterprise OAuth2 Authentication System - MERN Stack By Rohit Kumar Gupta.

A complete, production-ready OAuth2 social authentication system with advanced security features, role-based access control, audit logging, and enterprise-level observability.

## 🌟 Overview

This is a comprehensive authentication system featuring Google and Facebook OAuth using Authorization Code Flow with PKCE, JWT-based sessions, role-based access control, account linking, profile management, audit logging, and a complete admin panel.

## ✨ Key Features

### Authentication & OAuth
- ✅ **Google & Facebook OAuth** - Authorization Code Flow with PKCE
- ✅ **Email/Password Auth** - Traditional signup and login
- ✅ **Account Linking** - Link multiple OAuth providers to one account
- ✅ **Nonce-based Replay Protection** - Prevents token replay attacks
- ✅ **State Parameter Validation** - CSRF protection for OAuth flows
- ✅ **Redirect-back Support** - Returns to original destination after auth

### Session & Token Management
- ✅ **Short-lived JWT Access Tokens** - 15 minutes, httpOnly cookies
- ✅ **Refresh Token Strategy** - 7-day refresh tokens with rotation
- ✅ **Server-side Token Blacklist** - Invalidate tokens on logout
- ✅ **Logout All Devices** - Revoke all user sessions
- ✅ **Secure Cookies** - httpOnly, SameSite, secure in production

### Security Hardening
- ✅ **CSRF Protection** - Single-use CSRF tokens
- ✅ **Rate Limiting** - Per-endpoint limits with sliding window
- ✅ **Input Validation** - Email, password, URL validation with XSS sanitization
- ✅ **Strict CORS** - Environment-based origin validation
- ✅ **Password Hashing** - Bcrypt with 10 salt rounds
- ✅ **Secrets Management** - Environment-based configuration

### Roles & Permissions
- ✅ **Role-Based Access Control** - User, Moderator, Admin roles
- ✅ **Claim-based Permissions** - Fine-grained access control
- ✅ **Role Assignment on Signup** - Default user role
- ✅ **Admin Upgrades** - Admin-only role management
- ✅ **UI Gating** - Role-based navigation and features

### User Management
- ✅ **Profile Management** - Edit name, bio, location, website
- ✅ **Profile Sync** - Pull name/avatar from OAuth with consent
- ✅ **Consent Management** - Profile sync, data processing, marketing preferences
- ✅ **Account Deletion** - GDPR-compliant data removal
- ✅ **Editable Profile Fields** - Character limits and validation

### Admin Panel
- ✅ **User Management** - List, search, filter users
- ✅ **Role Management** - Update user roles and claims
- ✅ **Account Status Control** - Activate/deactivate users
- ✅ **System Statistics** - Users by role, provider, activity
- ✅ **Audit Log Viewer** - View system-wide audit logs

### Auditing & Observability
- ✅ **Structured Logging** - JSON-formatted logs with severity levels
- ✅ **Correlation IDs** - UUID-based request tracing
- ✅ **Per-user Audit Logs** - Last 100 actions with IP and user agent
- ✅ **Security Event Logging** - Track suspicious activities
- ✅ **Success/Failure Metrics** - Authentication analytics
- ✅ **Admin Analytics** - System health and usage metrics

### Developer Experience
- ✅ **Mock OAuth Provider** - Test without real OAuth credentials
- ✅ **Database Seeding** - Instant test data with multiple roles
- ✅ **Environment Validation** - Catch configuration errors early
- ✅ **Health Check Endpoint** - Monitor system status
- ✅ **Configuration Endpoint** - Debug settings (dev only)

## 🛠️ Tech Stack

**Backend:**
- Node.js & Express.js
- MongoDB & Mongoose
- JWT (jsonwebtoken)
- bcryptjs
- OAuth2 with PKCE
- Axios

**Frontend:**
- React 18
- Vite
- React Router v6
- Axios
- Context API

**Security:**
- CSRF Protection
- Rate Limiting (Sliding Window)
- Input Validation & Sanitization
- Token Blacklist
- Correlation IDs


**Screenshots of Output:**

1. Login Page:

   
![Fs 1](https://github.com/user-attachments/assets/10501844-19d2-4aef-b2f5-b50d9a157afb)


2. Admin Panel: 


![Picture2](https://github.com/user-attachments/assets/d549e1a9-4033-43ad-9325-a69632b583b4)


3. Settings Interface:

   
![Picture3](https://github.com/user-attachments/assets/d31254cd-86da-4e6b-98bf-004dd1a4d51f)


4. Admin Panel Statistics: 


![Picture4](https://github.com/user-attachments/assets/bc47abc9-df61-4460-a46f-fe65afbb35c4)


5. Admin Panel Audit Logs: 


![Picture6](https://github.com/user-attachments/assets/ff7c487d-ba1f-4176-8e25-cdd22fbc6155)





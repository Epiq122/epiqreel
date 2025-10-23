# Let's Go Further - Progress Tracker

**Book:** "Let's Go Further" by Alex Edwards
**Project:** EpiqReel API
**Started:** October 15, 2025

## 📊 Overall Progress

- **Chapters Completed:** 7/21
- **Current Focus:** CRUD Operations
- **Next Milestone:** Complete Database Integration & CRUD

---

## 📚 Chapter Progress

### Part 1: Foundation

- ✅ **Chapter 1:** Introduction
- ✅ **Chapter 2:** Getting Started
  - ✅ 2.1 Project setup and skeleton structure
  - ✅ 2.2 A basic HTTP server
  - ✅ 2.3 API endpoints and RESTful routing

### Part 2: Core API Development

- ✅ **Chapter 3:** Sending JSON Responses

  - ✅ 3.1 Fixed-format JSON
  - ✅ 3.2 JSON encoding
  - ✅ 3.3 Encoding structs
  - ✅ 3.4 Formatting and enveloping responses
  - ✅ 3.5 Advanced JSON customization
  - ✅ 3.6 Sending error messages

- ✅ **Chapter 4:** Parsing JSON Requests

  - ✅ 4.1 JSON decoding
  - ✅ 4.2 Managing bad requests
  - ✅ 4.3 Restricting inputs
  - ✅ 4.4 Custom JSON decoding
  - ✅ 4.5 Validating JSON input

- ✅ **Chapter 5:** Database Setup and Configuration

  - ✅ 5.1 Setting up PostgreSQL
  - ✅ 5.2 Connecting to PostgreSQL
  - ✅ 5.3 Configuring the database connection pool

- ✅ **Chapter 6:** SQL Migrations

  - ✅ 6.1 An overview of SQL migrations
  - ✅ 6.2 Working with SQL migrations

- ⬜ **Chapter 7:** CRUD Operations

  - ⬜ 7.1 Setting up the movie model
  - ⬜ 7.2 Creating a new movie
  - ⬜ 7.3 Fetching a movie
  - ⬜ 7.4 Updating a movie
  - ⬜ 7.5 Deleting a movie

- ⬜ **Chapter 8:** Advanced CRUD Operations

  - ⬜ 8.1 Handling partial updates
  - ⬜ 8.2 Optimistic concurrency control
  - ⬜ 8.3 Managing SQL query timeouts

- ⬜ **Chapter 9:** Filtering, Sorting, and Pagination
  - ⬜ 9.1 Parsing query string parameters
  - ⬜ 9.2 Validating query string parameters
  - ⬜ 9.3 Listing data
  - ⬜ 9.4 Filtering lists
  - ⬜ 9.5 Full-text search
  - ⬜ 9.6 Sorting lists
  - ⬜ 9.7 Paginating lists
  - ⬜ 9.8 Returning pagination metadata

### Part 3: Advanced Features

- ⬜ **Chapter 10:** Rate Limiting

  - ⬜ 10.1 Global rate limiting
  - ⬜ 10.2 IP-based rate limiting
  - ⬜ 10.3 Configuring the rate limiters

- ⬜ **Chapter 11:** Graceful Shutdown

  - ⬜ 11.1 Sending shutdown signals
  - ⬜ 11.2 Intercepting shutdown signals
  - ⬜ 11.3 Executing the shutdown

- ⬜ **Chapter 12:** User Model Setup and Registration

  - ⬜ 12.1 Setting up the users database table
  - ⬜ 12.2 Setting up the users model
  - ⬜ 12.3 Registering a user

- ⬜ **Chapter 13:** Sending Emails

  - ⬜ 13.1 SMTP server setup
  - ⬜ 13.2 Creating email templates
  - ⬜ 13.3 Sending a welcome email
  - ⬜ 13.4 Sending background emails
  - ⬜ 13.5 Graceful shutdown of background tasks

- ⬜ **Chapter 14:** User Activation

  - ⬜ 14.1 Setting up the tokens database table
  - ⬜ 14.2 Creating secure activation tokens
  - ⬜ 14.3 Sending activation tokens
  - ⬜ 14.4 Activating a user

- ⬜ **Chapter 15:** Authentication

  - ⬜ 15.1 Authentication options
  - ⬜ 15.2 Generating authentication tokens
  - ⬜ 15.3 Authenticating requests

- ⬜ **Chapter 16:** Permission-based Authorization

  - ⬜ 16.1 Requiring user activation
  - ⬜ 16.2 Setting up the permissions database table
  - ⬜ 16.3 Setting up the permissions model
  - ⬜ 16.4 Checking permissions
  - ⬜ 16.5 Granting permissions

- ⬜ **Chapter 17:** Cross-origin Requests
  - ⬜ 17.1 An overview of CORS
  - ⬜ 17.2 Demonstrating the same-origin policy
  - ⬜ 17.3 Simple CORS requests
  - ⬜ 17.4 Preflight CORS requests

### Part 4: Production & Deployment

- ⬜ **Chapter 18:** Metrics

  - ⬜ 18.1 Exposing metrics with expvar
  - ⬜ 18.2 Creating custom metrics
  - ⬜ 18.3 Request-level metrics
  - ⬜ 18.4 Recording HTTP status codes

- ⬜ **Chapter 19:** Building, Versioning and Quality Control

  - ⬜ 19.1 Creating and using makefiles
  - ⬜ 19.2 Managing environment variables
  - ⬜ 19.3 Quality-controlling code
  - ⬜ 19.4 Module proxies and vendoring
  - ⬜ 19.5 Building binaries
  - ⬜ 19.6 Managing and automating version numbers

- ⬜ **Chapter 20:** Deployment and Hosting

  - ⬜ 20.1 Creating a DigitalOcean droplet
  - ⬜ 20.2 Server configuration and installing software
  - ⬜ 20.3 Deployment and executing migrations
  - ⬜ 20.4 Running the API as a background service
  - ⬜ 20.5 Using Caddy as a reverse proxy

- ⬜ **Chapter 21:** Appendices
  - ⬜ 21.1 Managing password resets
  - ⬜ 21.2 Creating additional activation tokens
  - ⬜ 21.3 Authentication with JSON Web Tokens
  - ⬜ 21.4 JSON encoding nuances
  - ⬜ 21.5 JSON decoding nuances
  - ⬜ 21.6 Request context timeouts

---

## 🗓️ Weekly Progress Log

### Week of October 15, 2025

**Goal:** Complete Part 1 and start API endpoints

**Accomplished:**

- ✅ Set up initial project structure
- ✅ Created basic HTTP server with application struct
- ✅ Implemented healthcheck endpoint
- ✅ Added RESTful routing foundation
- ✅ Configured structured logging with slog
- ✅ Set up command-line flags for configuration
- ✅ Implemented JSON response encoding with envelope pattern
- ✅ Created Movie model with custom JSON marshaling
- ✅ Built comprehensive error handling system
- ✅ Added panic recovery middleware
- ✅ Implemented custom 404 and 405 handlers
- ✅ Implemented JSON request parsing with readJSON helper
- ✅ Created comprehensive validator package
- ✅ Added movie validation with business rules
- ✅ Implemented custom JSON unmarshaling for Runtime type
- ✅ Built request size limiting and input restrictions
- ✅ Created detailed error responses for all JSON parsing issues
- ✅ Set up PostgreSQL database connection with lib/pq driver
- ✅ Implemented connection pooling with configurable parameters
- ✅ Added environment variable support for DSN configuration
- ✅ Created openDB helper with timeout and ping verification
- ✅ Installed and configured golang-migrate CLI tool
- ✅ Created initial migration for movies table
- ✅ Added check constraints migration for data validation
- ✅ Resolved PostgreSQL schema permissions for user

**Challenges:**

- ✅ Initially had typo in `MarshalJSON` method name (wrote `MarshaJSON`)
- ✅ Learned about new Go 1.24+ `omitzero` struct tag
- ✅ Understanding the difference between `json.Decoder` and `json.Unmarshal`
- ✅ Implementing comprehensive error handling for various JSON edge cases
- ✅ DSN format confusion - needed `postgres://` scheme, not custom scheme
- ✅ Understanding connection pool parameters and their impact
- ✅ PostgreSQL permission denied for schema public - needed to grant privileges

**Key Learnings:**

- ✅ Application structure patterns and dependency injection
- ✅ Configuration management with command-line flags
- ✅ Structured logging with slog package
- ✅ HTTP server configuration and timeouts
- ✅ RESTful API design principles
- ✅ Go project organization best practices
- ✅ JSON encoding and custom marshaling with `MarshalJSON` interface
- ✅ Envelope pattern for consistent API responses
- ✅ Custom type marshaling (Runtime type to "102 mins" format)
- ✅ Struct tags: `json:"-"`, `omitzero` for zero value omission
- ✅ Error response patterns and centralized error handling
- ✅ Middleware pattern for panic recovery
- ✅ Custom router error handlers (NotFound, MethodNotAllowed)
- ✅ JSON decoding with `json.Decoder` for streaming
- ✅ Custom UnmarshalJSON implementation for type validation
- ✅ Request body size limiting with `http.MaxBytesReader`
- ✅ Disallowing unknown fields with `DisallowUnknownFields()`
- ✅ Detecting multiple JSON values in request body
- ✅ Type-safe error handling with `errors.As()` and `errors.Is()`
- ✅ Validator pattern for reusable validation logic
- ✅ Generic functions in Go (Unique, PermittedValue)
- ✅ Regular expressions for email validation
- ✅ Comprehensive business rule validation (year ranges, genre counts, etc.)
- ✅ PostgreSQL driver import with blank identifier (\_ "github.com/lib/pq")
- ✅ Database connection pooling concepts (max open, max idle, idle timeout)
- ✅ Context-based timeouts with context.WithTimeout()
- ✅ Database health checking with PingContext()
- ✅ Deferred resource cleanup (defer db.Close())
- ✅ Environment variable configuration with os.Getenv()
- ✅ DSN format: postgres://username:password@host/database
- ✅ Connection pool tuning for production workloads
- ✅ SQL migrations concept - versioned, repeatable database changes
- ✅ Migration naming: timestamp_description.up.sql and .down.sql
- ✅ Check constraints for data integrity at database level
- ✅ PostgreSQL array_length() function for validating array sizes
- ✅ date_part() function for extracting year from timestamps
- ✅ Schema permissions: GRANT ALL ON SCHEMA public TO user
- ✅ Tracking migrations with schema_migrations table

**Questions:**

- ✅ Why wasn't custom JSON marshaling working? → Method name typo!
- ✅ How to handle malformed JSON gracefully? → Use type assertions with errors.As()
- ✅ How to prevent clients from sending extra fields? → Use DisallowUnknownFields()
- ✅ What's the correct PostgreSQL DSN format? → postgres://user:pass@host/db
- ✅ How to configure connection pooling? → SetMaxOpenConns, SetMaxIdleConns, SetConnMaxIdleTime
- ✅ Permission denied for schema public? → GRANT ALL ON SCHEMA public TO user

---

## 🎯 Current Status

**Working on:** Chapter 7 - CRUD Operations
**Last completed:** Chapter 6.2 - Working with SQL migrations
**Next up:** Chapter 7.1 - Setting up the movie model

---

## 📝 Notes & References

- **Repository:** https://github.com/Epiq122/epiqreel
- **Book GitHub:** https://github.com/let-s-go-further/greenlight
- **Go version:** Check with `go version`

---

## 🏆 Milestones

- ✅ **Milestone 1:** Foundation & JSON API (Chapters 1-4)
- [ ] **Milestone 2:** Database Integration & CRUD (Chapters 5-9)
- [ ] **Milestone 3:** Advanced Features & Rate Limiting (Chapters 10-11)
- [ ] **Milestone 4:** User Authentication System (Chapters 12-16)
- [ ] **Milestone 5:** CORS & Metrics (Chapters 17-18)
- [ ] **Milestone 6:** Production Deployment (Chapters 19-21)

---

_Last updated: October 22, 2025_

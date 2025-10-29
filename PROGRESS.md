# Let's Go Further - Progress Tracker

**Book:** "Let's Go Further" by Alex Edwards
**Project:** EpiqReel API
**Started:** October 15, 2025

## 📊 Overall Progress

- **Chapters Completed:** 14/21
- **Current Focus:** Authentication
- **Next Milestone:** Complete User Authentication System

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

- ✅ **Chapter 7:** CRUD Operations

  - ✅ 7.1 Setting up the movie model
  - ✅ 7.2 Creating a new movie
  - ✅ 7.3 Fetching a movie
  - ✅ 7.4 Updating a movie
  - ✅ 7.5 Deleting a movie

- ✅ **Chapter 8:** Advanced CRUD Operations

  - ✅ 8.1 Handling partial updates
  - ✅ 8.2 Optimistic concurrency control
  - ✅ 8.3 Managing SQL query timeouts

- ✅ **Chapter 9:** Filtering, Sorting, and Pagination
  - ✅ 9.1 Parsing query string parameters
  - ✅ 9.2 Validating query string parameters
  - ✅ 9.3 Listing data
  - ✅ 9.4 Filtering lists
  - ✅ 9.5 Full-text search
  - ✅ 9.6 Sorting lists
  - ✅ 9.7 Paginating lists
  - ✅ 9.8 Returning pagination metadata

### Part 3: Advanced Features

- ✅ **Chapter 10:** Rate Limiting

  - ✅ 10.1 Global rate limiting
  - ✅ 10.2 IP-based rate limiting
  - ✅ 10.3 Configuring the rate limiters

- ✅ **Chapter 11:** Graceful Shutdown

  - ✅ 11.1 Sending shutdown signals
  - ✅ 11.2 Intercepting shutdown signals
  - ✅ 11.3 Executing the shutdown

- ✅ **Chapter 12:** User Model Setup and Registration

  - ✅ 12.1 Setting up the users database table
  - ✅ 12.2 Setting up the users model
  - ✅ 12.3 Registering a user

- ✅ **Chapter 13:** Sending Emails

  - ✅ 13.1 SMTP server setup
  - ✅ 13.2 Creating email templates
  - ✅ 13.3 Sending a welcome email
  - ✅ 13.4 Sending background emails
  - ✅ 13.5 Graceful shutdown of background tasks

- ✅ **Chapter 14:** User Activation

  - ✅ 14.1 Setting up the tokens database table
  - ✅ 14.2 Creating secure activation tokens
  - ✅ 14.3 Sending activation tokens
  - ✅ 14.4 Activating a user

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
- ✅ Created MovieModel struct with all CRUD operations
- ✅ Implemented Insert method with RETURNING clause
- ✅ Implemented Get method with error handling for missing records
- ✅ Implemented Update method with version incrementing
- ✅ Implemented Delete method with RowsAffected check
- ✅ Created Models wrapper struct for dependency injection
- ✅ Integrated database models into application handlers
- ✅ Added Location header for created resources
- ✅ Implemented partial update support with pointer fields
- ✅ Added optimistic concurrency control with version checking
- ✅ Implemented ErrEditConflict for race condition detection
- ✅ Added context timeouts to all database operations (3 seconds)
- ✅ Created editConflictResponse for 409 Conflict errors
- ✅ Implemented query string parameter parsing helpers (readString, readCSV, readInt)
- ✅ Created Filters struct for pagination and sorting
- ✅ Added GIN indexes on genres array and title tsvector for performance
- ✅ Implemented GetAll method with full-text search using to_tsvector
- ✅ Added genre filtering with PostgreSQL array containment operator (@>)
- ✅ Implemented dynamic sorting with sort safelist validation
- ✅ Added pagination with LIMIT and OFFSET
- ✅ Implemented count(\*) OVER() window function for total records
- ✅ Created calculateMetadata helper for pagination metadata
- ✅ Integrated filtering, sorting, and pagination into listMoviesHandler
- ✅ Installed golang.org/x/time/rate for token bucket rate limiting
- ✅ Installed github.com/tomasen/realip for client IP extraction
- ✅ Implemented rateLimit middleware with IP-based rate limiting
- ✅ Created map[string]\*client to track limiters per IP address
- ✅ Added background goroutine to clean up stale clients every minute
- ✅ Added limiter configuration flags (rps, burst, enabled)
- ✅ Integrated rate limiting middleware into routes chain
- ✅ Created rateLimitExceededResponse for 429 status code
- ✅ Extracted server setup into serve() method
- ✅ Created shutdownError channel for graceful shutdown coordination
- ✅ Implemented signal handler goroutine for SIGINT and SIGTERM
- ✅ Added 30-second timeout for graceful shutdown with context.WithTimeout
- ✅ Called srv.Shutdown(ctx) to gracefully stop accepting new requests
- ✅ Used errors.Is() to distinguish between normal and abnormal shutdown
- ✅ Created users database table with citext extension for case-insensitive emails
- ✅ Implemented User model with password struct and bcrypt hashing
- ✅ Built registerUserHandler for POST /v1/users endpoint
- ✅ Added password validation (8-72 characters) and email format validation
- ✅ Implemented Insert, GetByEmail, and Update methods on UserModel
- ✅ Added ErrDuplicateEmail for handling unique constraint violations
- ✅ Integrated Users into Models struct

**Challenges:**

- ✅ Initially had typo in `MarshalJSON` method name (wrote `MarshaJSON`)
- ✅ Learned about new Go 1.24+ `omitzero` struct tag
- ✅ Understanding the difference between `json.Decoder` and `json.Unmarshal`
- ✅ Implementing comprehensive error handling for various JSON edge cases
- ✅ DSN format confusion - needed `postgres://` scheme, not custom scheme
- ✅ Understanding connection pool parameters and their impact
- ✅ PostgreSQL permission denied for schema public - needed to grant privileges
- ✅ SQL placeholder typo - used `1$` instead of `$1` causing Update to fail
- ✅ Understanding RETURNING clause for getting auto-generated values
- ✅ Understanding when nil pointers indicate "no update" vs actual nil values
- ✅ Testing concurrent updates to verify optimistic locking works correctly
- ✅ Understanding CSV parsing for multi-value query parameters
- ✅ Building dynamic SQL safely with safelists to prevent injection
- ✅ PostgreSQL full-text search concepts (tsvector, tsquery)
- ✅ Window functions (count(\*) OVER()) for efficient total counting
- ✅ GIN index usage for arrays and full-text search performance
- ✅ Flag redefinition errors - flag names must be unique
- ✅ Understanding rate limiting with token bucket algorithm
- ✅ Cleaning up old map entries to prevent memory leaks
- ✅ Understanding graceful shutdown vs abrupt termination
- ✅ Coordinating goroutines with channels for shutdown signaling
- ✅ Using http.ErrServerClosed to detect normal shutdown
- ✅ citext extension not being enabled - needed CREATE EXTENSION in migration
- ✅ Understanding bcrypt cost factor selection (12 for strong security)
- ✅ Handling duplicate email errors from unique constraint violations
- ✅ Password field exclusion from JSON with json:"-" tag
- ✅ Missing //go:embed directive causing template parsing failures
- ✅ Email sender format requires space: "Name <email@domain.com>"
- ✅ Mailtrap SMTP port 2525 vs default port 25
- ✅ Fixing duplicate email constraint error string (missing closing quote)
- ✅ Understanding background goroutines for non-blocking operations
- ✅ sync.WaitGroup for tracking background task completion during shutdown
- ✅ PostgreSQL permission denied for tokens table - needed GRANT ALL
- ✅ Missing closing quote in JSON struct tag causing field unmarshal failure
- ✅ Understanding crypto/rand for secure token generation
- ✅ SHA-256 hashing for storing tokens securely in database

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
- ✅ RETURNING clause to get auto-generated values (INSERT RETURNING)
- ✅ Repository pattern for database operations
- ✅ Dependency injection with Models struct
- ✅ Error handling with errors.Is() for type checking
- ✅ Location header for created resources (RFC 7231)
- ✅ SQL placeholders for preventing SQL injection
- ✅ Scanning query results into struct fields
- ✅ RowsAffected for verifying DELETE/UPDATE operations
- ✅ Partial updates using pointer fields to detect "not provided"
- ✅ Optimistic concurrency control (OCC) with version field
- ✅ Version incrementing with SET version = version + 1
- ✅ WHERE clause conditions for preventing lost updates
- ✅ ErrEditConflict custom error for race conditions
- ✅ 409 Conflict status code for concurrent update failures
- ✅ Query string parameter parsing with url.Values
- ✅ Helper functions: readString, readCSV, readInt
- ✅ Default values for optional query parameters
- ✅ CSV parsing for multi-value parameters (genres=action,comedy)
- ✅ Integer validation with strconv.Atoi
- ✅ Filters struct for pagination and sorting logic
- ✅ Embedding Filters in input structs
- ✅ Sort safelist for preventing SQL injection in ORDER BY
- ✅ Dynamic SQL query building with fmt.Sprintf
- ✅ Full-text search with PostgreSQL to_tsvector and plainto_tsquery
- ✅ Array containment with @> operator for genre filtering
- ✅ LIMIT and OFFSET for pagination
- ✅ count(\*) OVER() window function for total record count
- ✅ Calculating pagination metadata (current page, total pages, etc.)
- ✅ GIN indexes on arrays for performance (genres)
- ✅ GIN indexes on tsvector for full-text search performance
- ✅ Metadata struct with first_page, last_page, current_page, page_size, total_records
- ✅ Token bucket algorithm for rate limiting (golang.org/x/time/rate)
- ✅ rate.Limiter with configurable requests per second and burst
- ✅ IP-based rate limiting using map[string]\*client
- ✅ Extracting client IP with realip.FromRequest (handles X-Forwarded-For, X-Real-IP)
- ✅ Mutex (sync.Mutex) for protecting shared map access
- ✅ Background goroutine for periodic cleanup of stale entries
- ✅ time.Since() for tracking client last seen time
- ✅ Conditional middleware with config.limiter.enabled flag
- ✅ 429 Too Many Requests status code for rate limit violations
- ✅ Middleware chaining pattern (recoverPanic -> rateLimit -> router)
- ✅ Graceful shutdown with srv.Shutdown() and context timeout
- ✅ Signal handling with os/signal package (SIGINT, SIGTERM)
- ✅ Channel-based communication between goroutines (shutdownError chan)
- ✅ Buffered channels (make(chan os.Signal, 1)) for signal handling
- ✅ signal.Notify() for registering signal handlers
- ✅ Distinguishing http.ErrServerClosed from actual errors
- ✅ Context with deadline for shutdown timeout (30 seconds)
- ✅ Extracting server logic into serve() method for better organization
- ✅ PostgreSQL citext extension for case-insensitive text type
- ✅ CREATE EXTENSION IF NOT EXISTS for enabling PostgreSQL extensions
- ✅ bytea type for storing binary data (password hashes)
- ✅ bcrypt.GenerateFromPassword() with cost factor 12
- ✅ bcrypt.CompareHashAndPassword() for constant-time password verification
- ✅ Password struct with plaintext and hash fields
- ✅ Set() method for hashing passwords before storage
- ✅ Matches() method for verifying passwords against stored hash
- ✅ json:"-" struct tag to exclude sensitive fields from JSON
- ✅ Email validation with regex pattern (EmailRX)
- ✅ Password length constraints (8-72 bytes for bcrypt)
- ✅ UNIQUE constraint on email column with citext for case-insensitive uniqueness
- ✅ Detecting duplicate key violations with pq error checking
- ✅ ErrDuplicateEmail custom error for application-level handling
- ✅ GetByEmail() method for user lookup by email address
- ✅ Update() method with version checking for users
- ✅ //go:embed directive for embedding template files in binary
- ✅ embed.FS for embedded file system access
- ✅ text/template and html/template for dual-format emails
- ✅ Parsing templates from embedded FS with ParseFS()
- ✅ ExecuteTemplate() with named templates (subject, plainBody, htmlBody)
- ✅ bytes.Buffer for building email content
- ✅ mail.NewMsg() for creating email messages
- ✅ mail.TypeTextPlain and mail.TypeTextHTML for content types
- ✅ AddAlternativeString() for multi-part emails (plain + HTML)
- ✅ DialAndSend() for connecting to SMTP and sending email
- ✅ SMTP configuration flags (host, port, username, password, sender)
- ✅ Mailtrap for testing email delivery in development
- ✅ SMTP port 2525 for Mailtrap (not 25)
- ✅ Email sender format: "Name <email@example.com>" with space
- ✅ Background goroutines with app.background() helper
- ✅ sync.WaitGroup for tracking background tasks
- ✅ defer recover() in background tasks to prevent panics crashing server
- ✅ Logging errors from background tasks instead of returning them
- ✅ 202 Accepted status code for asynchronous operations
- ✅ Waiting for background tasks during graceful shutdown
- ✅ app.wg.Wait() before completing shutdown
- ✅ crypto/rand package for cryptographically secure random tokens
- ✅ rand.Text() for generating URL-safe base32 tokens (26 bytes)
- ✅ SHA-256 hashing tokens before database storage
- ✅ Storing token hash (not plaintext) in database for security
- ✅ bytea PRIMARY KEY for token hash in PostgreSQL
- ✅ Foreign key with ON DELETE CASCADE for automatic cleanup
- ✅ Token expiry with timestamp comparison (expiry > NOW())
- ✅ Token scope for different token types (activation, authentication, etc.)
- ✅ One-time use tokens by deleting after successful use
- ✅ INNER JOIN to query users by token hash and scope
- ✅ GetForToken() method combining users and tokens tables
- ✅ DeleteAllForUser() for invalidating all user tokens of a scope
- ✅ Token validation (26 bytes long, not empty)
- ✅ Time-to-live (TTL) for token expiration (3 days for activation)
- ✅ Updating email templates with activation token instructions
- ✅ map[string]any for passing multiple template data values
- ✅ 200 OK status for successful activation vs 202 Accepted for registration
- ✅ Repository pattern with model structs for database operations
- ✅ RETURNING clause to get auto-generated IDs, timestamps, and versions
- ✅ QueryRow() vs Exec() - when to use each for different operations
- ✅ Scan() method for mapping database rows to Go structs
- ✅ pq.Array() for PostgreSQL array handling in both directions
- ✅ sql.ErrNoRows for detecting missing records
- ✅ ErrRecordNotFound custom error for application-level handling
- ✅ RowsAffected() to verify DELETE operations succeeded
- ✅ Version incrementing with `version = version + 1` in UPDATE
- ✅ Location header (RFC 7231) for newly created resources
- ✅ Models struct wrapper for dependency injection pattern
- ✅ Pointer receivers for database models to avoid copying
- ✅ Partial updates using pointer fields (*string, *int32, \*Runtime)
- ✅ Nil pointer check pattern for detecting which fields to update
- ✅ Optimistic concurrency control (OCC) for preventing lost updates
- ✅ Version field as optimistic lock for concurrent modifications
- ✅ WHERE clause with version check: AND version = $6
- ✅ ErrEditConflict for detecting race conditions
- ✅ HTTP 409 Conflict for edit conflict scenarios
- ✅ Context timeouts with context.WithTimeout()
- ✅ QueryRowContext() and ExecContext() for timeout-aware queries
- ✅ defer cancel() pattern for context cleanup
- ✅ 3-second timeout for database operations
- ✅ Race condition testing with concurrent requests (xargs -P8)

**Questions:**

- ✅ Why wasn't custom JSON marshaling working? → Method name typo!
- ✅ How to handle malformed JSON gracefully? → Use type assertions with errors.As()
- ✅ How to prevent clients from sending extra fields? → Use DisallowUnknownFields()
- ✅ What's the correct PostgreSQL DSN format? → postgres://user:pass@host/db
- ✅ How to configure connection pooling? → SetMaxOpenConns, SetMaxIdleConns, SetConnMaxIdleTime
- ✅ Permission denied for schema public? → GRANT ALL ON SCHEMA public TO user
- ✅ Why isn't version incrementing on update? → SQL placeholder typo ($1 not 1$)
- ✅ How to get auto-generated values after INSERT? → Use RETURNING clause
- ✅ How to handle partial updates? → Use pointer fields, only update non-nil values
- ✅ How to prevent lost updates in concurrent scenarios? → Optimistic locking with version
- ✅ Why are concurrent updates getting edit conflicts? → That's correct! OCC working as designed

---

## 🎯 Current Status

**Working on:** Chapter 15 - Authentication
**Last completed:** Chapter 14.4 - Activating a user
**Next up:** Chapter 15.1 - Authentication options

---

## 📝 Notes & References

- **Repository:** https://github.com/Epiq122/epiqreel
- **Book GitHub:** https://github.com/let-s-go-further/greenlight
- **Go version:** Check with `go version`

---

## 🏆 Milestones

- ✅ **Milestone 1:** Foundation & JSON API (Chapters 1-4)
- ✅ **Milestone 2:** Database Integration & CRUD (Chapters 5-9)
- ✅ **Milestone 3:** Advanced Features & Rate Limiting (Chapters 10-11)
- [ ] **Milestone 4:** User Authentication System (Chapters 12-16)
- [ ] **Milestone 5:** CORS & Metrics (Chapters 17-18)
- [ ] **Milestone 6:** Production Deployment (Chapters 19-21)

---

_Last updated: October 28, 2025_

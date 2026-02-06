# Gddit Backend

Java backend API for the Gddit Reddit-like forum application.

## 🚀 Features

- RESTful API endpoints
- Post and comment management
- User authentication
- Subreddit management
- Upvote/downvote system

## 🛠️ Tech Stack

- **Language:** Java
- **Framework:** Spring Boot
- **Build Tool:** Maven/Gradle
- **Database:** (Add your DB info here)

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/gmuller-dev/gddit-backend.git
cd gddit-backend

# Build the project
./mvnw clean install
# or
./gradlew build

# Run the application
./mvnw spring-boot:run
# or
./gradlew bootRun
```

## 📡 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/posts` | GET | Get all posts |
| `/api/posts/{id}` | GET | Get post by ID |
| `/api/subreddits` | GET | Get all subreddits |

*(Expand with your actual endpoints)*

## 🏗️ Project Structure

```
src/
├── main/
│   ├── java/com/example/gddit/
│   │   ├── controller/    # REST controllers
│   │   ├── service/       # Business logic
│   │   ├── repository/    # Data access
│   │   └── model/         # Entity classes
│   └── resources/
│       └── application.properties
└── test/                  # Unit tests
```

## 📝 Configuration

Update `src/main/resources/application.properties` with your database configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/gddit
spring.datasource.username=your_username
spring.datasource.password=your_password
```

## 🤝 Frontend

Pair this backend with the [angular-gddit](https://github.com/gmuller-dev/angular-gddit) frontend for a complete application.

---
*Backend for Gddit forum*

# A Small Rest Server In Go

Golang Gin boilerplate with MongoDB.

## Installation

1. `gin-gonic` for writing REST api interface.
```bash
import "github.com/gin-gonic/gin"
```

2. `net/http` for using constants such as `http.StatusOK`.
```bash
import "net/http"
```

3. `godotenv` for working with environment variables. 
```bash
import "github.com/joho/godotenv"
```

4. `mongo-driver` for working with *MongoDB*.
```
import (
    "go.mongodb.org/mongo-driver/bson"
    "go.mongodb.org/mongo-driver/mongo"
    "go.mongodb.org/mongo-driver/mongo/options"
)
```
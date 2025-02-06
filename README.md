# .NET Web API Sample Project

A simple RESTful API built with .NET 7.0

## Prerequisites
- .NET 7.0 SDK
- Docker (optional)

## Running the Application

### Local Development
1. Clone the repository
2. Navigate to the project directory
3. Run `dotnet restore`
4. Run `dotnet run`

### Using Docker
1. Build the image: `docker build -t myapp .`
2. Run the container: `docker run -p 8080:80 myapp`

## API Endpoints
- GET /api/product - Get all products
- GET /api/product/{id} - Get product by ID
- POST /api/product - Create new product
#   E C S _ . N E T A P P  
 
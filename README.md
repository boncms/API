
# Porn API – Quick Start Guide 🚀

**Porn API** is a powerful **adult video API** with over **1 million Full HD 1080p videos**, perfect for building fast, reliable adult websites and apps.

---

## 🔗 Base URL
https://api.porn-api.com/api


## 📦 Response Format
All endpoints return data in **JSON** format.

## 🔒 Authentication & Rate Limits
- Currently, no API key or authentication token is required for basic access.  
- API rate limits may apply to ensure service stability.

## 📌 Main Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET /movies` | Retrieve or search movies | Supports filters and pagination |
| `GET /movies/{slug}` | Get detailed movie info by slug | Includes embed URL and metadata |
| `GET /genres` | Get all genres | Returns available categories |
| `GET /actors` | Get all actors | Returns list of performers |
| `GET /countries` | Get all countries | Returns list of countries |

## ⚡ Example Requests

**Get the first page of movies:**

> curl -X GET "https://api.porn-api.com/api/movies?page=1"

**Get the page 1 to page 10:**

> curl -X GET "https://api.porn-api.com/api/movies?page=1&limit=10"

**Get the page 1 to page 10 with keyword:**

> curl -X GET "https://api.porn-api.com/api/movies?page=1&limit=10&sortBy=createdAt&sortOrder=DESC&keyword=anal"

**Get Movie by Slug**

> curl -X GET "https://api.porn-api.com/api/movies/yui-hatano-bound-teacher-s-forbidden-desire"

**Get All Genres**

> curl -X GET "https://api.porn-api.com/api/categories"

**Get All Actors**

> curl -X GET "https://api.porn-api.com/api/actors"

**Get All Countries**

> curl -X GET "https://api.porn-api.com/api/countries"

## 🛠️ Best Practices

-   **Respect rate limits**: To prevent service disruptions, avoid making too many requests in a short period.
    
-   **Handle errors**: Always check for errors (HTTP status codes and error messages).
    
-   **Cache data**: Consider caching results for better performance and reduced load on the API.
    
-   **Legal Compliance**: Ensure your application complies with local laws regarding adult content.
    

----------

## 💬 Support

If you have any questions or issues with the API, you can refer to the [official documentation](https://porn-api.com/api-docs?utm_source=github.com) or contact the support team.

## 📝 Notes

-   **API Version**: Always check the version you're using, as the API may evolve.
    
-   **Data Accuracy**: The API may update its content regularly, so make sure you handle any changes in data formats or available information.
    

----------

## 📚 References

-   Official documentation: [Porn API Docs](https://porn-api.com/api-docs?utm_source=github.com)
-   Telegram Support: [@b0b0b3b3](https://t.me/b0b0b3b3)

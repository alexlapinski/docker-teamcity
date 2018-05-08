# TeamCity Docker Stack

## Getting Started
### Setting Secrets
 * Create the postgres password
 ```
 echo "your-password" | docker secret create teamcity_postgres_password -
 ```

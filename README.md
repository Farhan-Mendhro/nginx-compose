 How to Run
1.Clone the repository:

```Bash

git clone <your-repo-link>
cd <repo-folder>

```

2.Start the application:

```bash

docker compose up -d

```

3.View the site: Open your browser and go to: http://localhost:8080


🛠️ Project Structure
index.html: The static frontend file.

docker-compose.yml: The blueprint that maps the HTML file into the Nginx container.


Docker Commands Used

```bash

Start: docker compose up -d
Stop:	docker compose down
Check Logs:	docker compose logs -f

```

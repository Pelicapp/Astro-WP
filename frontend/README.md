# Astro-WP

Simply run this command to start local Wordpress:

```
docker-compose up -d
```

Access your WordPress at http://localhost:8000.
Then install your Wordpress and add the WPGraphQL plugin.
**Don't use default permalink as recommended by WPGraphQL.**

Go to /frontend and run 
```
npm run dev
```
Go to your Astro website and view the fetched WordPress articles.